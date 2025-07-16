# country capital api
An API that returns the name of a country if the capital city is provided


It is built using 
- Flask
- Python

> **Example**   
> https://example.com/country-capital/Delhi  
> this will return India  

## How to run in your system
1.Clone the repo 
```bash
git clone https://github.com/repo
```
2.Move to the working directory
```bash
cd country-capital-api
```
3.Install the dependencies
```bash
pip install -r requirements.txt
```
4.Start the api
```bash
uvicorn app:app --reload
```
5.Use it 
```bash
GET request:
http://127.0.0.1:8000/country-capital/London
```

The result should be `UK`


