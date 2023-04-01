# Custom-Search-Engine

## Project Overview:

This project aims to create a search engine that is capable of filtering and reordering search results based on predefined filters. To achieve this, we will use the Google API to fetch search results, store them and then rank them based on the filters we define. To create and run the code, we will be using VSCode, other IDE such as pycharm can also be used. The project ends with a basic search page and a results list.

## Tools and Technologies Used:

- Python 3.9
- VsCode IDE
- Flask web framework
- Google Custom Search API

## Project Steps:

- Set up a Programmable Search Engine Custom Search API by creating an engine and obtaining an API key.
- Create a module to search using the API and retrieve search results.
- Create a Flask application to search and render results.
- Implement filters to re-rank results before displaying them.
- Store the results in a database using storage.py.
- Download a list of ad and tracker URLs and save it as blacklist.txt.
- Install Python 3.9 and the required Python packages listed in requirements.txt.
- Run the project using Flask.

## Project Files:

- app.py: The main file that contains the web interface.
- filter.py: The file that contains the code to filter search results.
- search.py: The file that contains the code to retrieve search results.
- settings.py: The file that contains the settings required by other files.
- storage.py: The file that contains the code to save search results to a database.

## Local Setup:

To run this project locally, you will need to follow these steps:

- Install Python 3.9 or a later version.
- Install the required Python packages by running "pip install -r requirements.txt".
- Create a Programmable Search Engine Custom Search API and obtain an API key.
- Download the list of ad and tracker URLs and save it as blacklist.txt.
- Copy the storage.py file into your project directory.
- Run the project using Flask by running "flask --debug run --port 5001" in the terminal.


## Other files:
We will also need to download a list of ad and tracker urls from [here](https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt), which will be used to filter out undesirable domains. Please save this list as blacklist.txt in your project directory. I would also suggest copying the storage.py file to your directory before starting the project.

## Run:
Finally, to run the project, you need to execute pip install -r requirements.txt followed by flask --debug run --port 5001.
