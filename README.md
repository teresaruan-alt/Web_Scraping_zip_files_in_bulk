## Extract multiple zip files using web scraping with Python Beautiful Soup 

```
Process:
```
#### Step 1) Inspect URL using Chrome DevTools in DOM 

1.0: Inspect url where information reside 

     Initial URL= 'https://s3.amazonaws.com/tripdata/index.html'
     tripdata_url='https://s3.amazonaws.com/tripdata/'
     

1.1: Loop through tripdata_url to obtain information
      - Extract filenames into a list 
      - Output file counts

1.2: Remove potential duplicated files

1.3: Write a loop to 
      - standardized all file names 
      - unzip each file
      - save all csv files in local drive




#### Step 2) WIP- import all into SQL Server for further analysis


