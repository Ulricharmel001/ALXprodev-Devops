# Advance Shell Scripting Exercise
## Api Automation
Script to automate an API request to a public API and handle the response.
This script fetches data from the PokeAPI for a specific Pokémon and saves the response to a file.
if the request fails, it logs the error to a separate file.

## Data Extraction  Automation 

Added a script that Extract information from the json file
created from the previous exercise, it extract specific field 
using `awk, sed, echo and jq` 

## Auto extract multiple data , Batch processing 

Objective: Automate the retrieval of data for multiple Pokémon and store it in separate files.

### Instructions:
Create a script that loops through a list of Pokémon [Bulbasaur, Ivysaur, Venusaur, Charmander, Charmeleon]

For each Pokémon, retrieve its data from the API and save it to a separate file named after the Pokémon (e.g., pikachu.json, bulbasaur.json…).  

Handle any potential rate-limiting issues by adding a delay between requests.
