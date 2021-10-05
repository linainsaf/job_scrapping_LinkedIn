# job_scrapping_LinkedIn
Using linkedin-jobs-scraper --> https://github.com/spinlud/linkedin-jobs-scraper library to scrapp jobs from LinkedIn


# How to use it : 

- Install requirements.txt :
```shell
pip install -r requirements.txt 
```
- In main function, change to desired queries. Example :

 queries = [{"query": 'Software engineer', "location": 'United States', "limit": 3},
            {"query": 'Data scientist', "location": 'United States', "limit": 3}]
        
 query : Title of the job 
 location : Location of the job wanted
 limit : number of the jobs that we want to scrapp for this query.
 
 
 PS : - queries is a list, so we can multiple queries at once. 
      - go see https://github.com/spinlud/linkedin-jobs-scraper  for more options and filters. 
      
 
 - To begin scrapping we use : jobs=scrap_linkedin(queries)
 
