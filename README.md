# google-image-download
Download images using the Google Custom Search API

## Use Case 
Download image using the Google Custom Search Engine

## Getting Startedd 
### Get your API Key and CX ID
Get your API Key from [here](https://developers.google.com/custom-search/v1/overview)

### After getting the api key, create a custom search engine.
Create a custom search engine from [here](https://cse.google.com/cse/all)
I suggest that you read the [guide](https://developers.google.com/custom-search/docs/tutorial/creatingcse) provided by Google for better understanding. Anyway : 

* Enable Image Search
* Enable Global Search (optional, but if you want maximum results)

### Using the module

Install Google API Client
```
pip install --upgrade google-api-python-client
```
Install PIL 
```
pip install pillow
```
### Running the code 
#### Do not forget to replace the API Key and CXID with your own!

To use the module - simply import the module and call the function. If you want to test, browse to the cloned directory : 

```
python run.py
```

## Regards
