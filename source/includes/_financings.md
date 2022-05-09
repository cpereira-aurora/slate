# Financings

Represent financings taken by a buyer on a Solar project.
Financings are related to a Design, and a Project.

## Get a specific Financing

```shell
curl "http://aurorasolar.com/api/financings/a36d5c61-cba4-48ac-ba46-6f043c94335a" \
  -H 'x-auth-token: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpZCI6Ijg2N2JkMjdhLWFjNzktNGFiMC04OGI0LTJjNmUyMzVjNTY1ZCIsImVtYWlsIjoiY3BlcmVpcmFAYXVyb3Jhc29sYXIuY29tIiwiZXhwIjoxNjUxODE2MTcxLCJqdGkiOiJmZmQ2NWI4Yy00ZDRjLTQ5MjQtODk0MS0xN2VlMWRiNGJmYzUifQ.FC79et6Kp3z2VDx33VVzQkFNqe5zoI3Yrn9OvKwRGe8'
```

This endpoint returns a Financing.

### HTTP Request

`GET http://aurorsolar.com/api/financings/<ID>`

### URL Parameters

| Parameter | Description                            |
|-----------|----------------------------------------|
|  ID       | The ID of the financing to be returned |
