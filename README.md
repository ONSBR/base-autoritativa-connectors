# base-autoritativa-connectors
Wrapper for queries on Mapa da Informação system, based on Neo4J

##Needs a config.js at dist directoty
```
{
    "port": 3000,
    "bodyLimit": "100kb",
    "corsHeaders": ["Link"],
    "authentication":"<<hash>>",
    "mapaInformacaoBaseUrl":"<<mapainformacaourl>>",
    "wikiBaseUrl":"<<wiki url>>",
    "statements":{
    }
}
```
