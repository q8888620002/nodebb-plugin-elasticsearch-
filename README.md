# Elasticsearch Search for NodeBB

## Motivation

Since the current nodebb search engine does not support Chinese-text search, I decided to use elasticsearch as the search engine not the db engine. So it's important that you have to import t your data from the mongodb/redis to build index for elasticsearch by any plugin. 

For this plugin, I am assuming that your are using mongo-connector(https://github.com/mongodb-labs/mongo-connector) as me.

This is a updated plugin from joe1chen(https://github.com/joe1chen/nodebb-plugin-search-elasticsearch)  NodeBB to utilise an installation of Elasticsearch as a search backend which supports Madarin text

## Contributors

joe1chen(https://github.com/joe1chen/nodebb-plugin-search-elasticsearch)


## Configuration

1. Install this plugin via npm: `npm install nodebb-plugin-elasticsearch`
1. Activate it in the Plugins page
1. Restart NodeBB
1. Check that the plugin has successfully connected to the search engine. If not, adjust as necessary.

## Installation

    npm install nodebb-plugin-elasticsearch
    
##TODO

fixed the topic search issue 