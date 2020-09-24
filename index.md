# INTRODUCTION
Initial (Draft) guidance of Indonesia Oil &amp; Gas API for data exchange.

All standards in this document are based on [**Permen No 7 Tahun 2019**](https://jdih.esdm.go.id/peraturan/Permen%20ESDM%20Nomor%207%20Tahun%202019.pdf) which comply to the international open standard data model [**PPDM 3.9**](https://docs.ppdm.org/). Detail explanation regarding metadata standard catalogue are documented in **SK KAPUSDATIN KESDM Rev 4.2**.

# NAMING CONVENTION
It is recommended to use camel case for request and response body and query parameter names.

Example :
```
//camelCaseSentence
{
 "areaID" : "12345"
}
```

# QUERY
```
GET /api/search/
{

}

```

## QUERY `fulltext`



## QUERY `metadata`


This guidelines tries to map metadata standard from **SK KAPUSDATIN KESDM Rev 4.2** to the standard usage in the API format.

List of tables and the formatting guidelines are documented as follow :

### [1. Basin - `basin`](basin.md)

### [2. Working Area - `workingArea`](workingArea.md)


## QUERY `geo_location`



## QUERY `geo_centroid`

