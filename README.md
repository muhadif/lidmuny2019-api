# LIDMUNY2019-API
## Usage

| Route | HTTP Verb | Description | Required Parameter | Optional Parameter |
|---|---|---|---|---|
| `/jsonapi/node/announcement` | `GET` | Get all announcemet |  | 
| `/jsonapi/node/announcement/{id}` | `GET` | Get spesific annoucement | `id` | 
| `/jsonapi/node/article/` | `GET` | Get all article or news |  |
| `/jsonapi/node/article/{id}` | `GET` | Get spesific article or news | `id` |

#EXAMPLE
##Get ALL ANNOUNCEMENT
1. request 
  `/jsonapi/node/announcement`
2. response
'''json
{
"jsonapi": {
"version": "1.0",
"meta": {
"links": {
"self": {
"href": "http://jsonapi.org/format/1.0/"
}
}
}
},
"data": [],
"links": {
"self": {
"href": "http://lidm2019.uny.ac.id/jsonapi/node/Article"
}
}
}
'''

