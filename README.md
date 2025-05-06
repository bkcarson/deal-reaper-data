# Deal Reaper Data

This repository hosts the CSV data used by the **Deal Reaper Chrome Extension**, which displays NFT floor prices and ranks for collections on Magic Eden and OpenSea.

## Purpose
The `collections.csv` file contains data about NFT collections, including their URLs, floor prices, and ranks. The Deal Reaper extension fetches this file to provide real-time information when users browse supported NFT marketplaces.

## File Structure
The CSV file (`collections.csv`) has the following structure:

```csv
url,floor_price,rank
https://magiceden.io/marketplace/collection1,3.2 SOL,5
https://opensea.io/collection/collection2,0.08 ETH,10
