# Expense Tracker

### Setup

#### To run locally without docker

`npm install` and than `npm start`

#### To run with docker

```
docker build -t financewise/web-app:v1.0.0 .
```

```
docker run -d -p 3000:3000 financewise/web-app:v1.0.0
```

### Expense POJO

```json
{
    "id":"",
    "description":"",
    "companyName":"",
    "address":"",
    "amount":"",
    "participants": [
        {
            "username":"",
            "password":"",
            "fullName":"",
            "profilePicture":""
        }
    ],
    "currency":"",
    "categories": [
        {
            "name":"",
            "description":""
        }
    ],
    "tags":[
        {
            "name":"",
            "description":""
        }
    ]
}
```