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
In the data folder, there are nodes.csv and edges.csv files, containing the aforementioned DataFrames' contents. The graph contains 30k nodes and 60k+ edges of linked articles from English Wikipedia. In the node metadata, we have included the title and summaries (couple sentences) as well as the Estonian equivalent title of each article, given that it exists.

TODO: Probably (?) should also scrape the Estonian Wikipedia. Dunno.

# Analytics
TODO

# Link to Report
TODO