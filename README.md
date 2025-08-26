# Interview


## API Endpoint

### Airports Endpoint
```bash
curl https://my-json-server.typicode.com/tnguyen-avelo/interview/airports
```

### Available Data
The API provides airport information including:
- id
- airportCode  
- country

### Example Response
```json
{
    "airports": [
        {
            "id": 1,
            "name": "New Haven, CT",
            "airportCode": "HVN",
            "country": "USA"
        },
        {
            "id": 2,
            "name": "New York, NY",
            "airportCode": "JFK",
            "country": "USA"
        },
        
        {
            "id": 3,
            "name": "Orlando, FL",  
            "airportCode": "MCO",
            "country": "USA"
        }
    ]
}
```
