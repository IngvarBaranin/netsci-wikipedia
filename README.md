# netsci-wikipedia
A Network Science project about exploring the graph structures of Wikipedia in multiple languages

# Setup
``````bash
conda create -n netsci python=3.7.12 -c conda-forge
conda activate netsci
pip install -r requirements.txt
``````

# Scraping Wikipedia data
Hint: Not necessary! Initial data has already been scraped. See Data section.

In order to scrape data from Wikipedia, resulting in a DataFrame of graph edges and a DataFrame of nodes with their metadata, run notebooks/data_creation_pywikibot_api_batched.ipynb

# Data
In the data folder, there are nodes_<language>.csv and edges_<language>.csv files, containing the aforementioned DataFrames' contents. The English Wikipedia network contains 30k nodes and 60k+ edges of linked articles. Similarly, the Estonian Wikipedia network contains ~7k nodes and ~12k edges between linked articles. Additionally in the node metadata, we have included the title and summaries (all sentences that fit in the first 500 characters of an article) as well as the interlanguage equivalent title of each article, if it exists.

# Analytics
For our analysis findings and link prediction results, see the report, which can be found [here](data/Network_Science_Project.pdf)
