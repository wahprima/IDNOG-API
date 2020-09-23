# Introduction IDOG-API
Initial (Draft) guidance of Indonesia Oil &amp; Gas API for data exchange.

All standards in this document are based on [**Permen No 7 Tahun 2019**](https://jdih.esdm.go.id/peraturan/Permen%20ESDM%20Nomor%207%20Tahun%202019.pdf) which comply to the international open standard data model [**PPDM 3.9**](https://docs.ppdm.org/). Any subject related to metadata is also followed guidelines from **SK KAPUSDATIN KESDM Rev 4.2**, a standard oil and gas metadata catalogue in Indonesia.



## QUERY
```
GET /api/search/
{

}

```

### QUERY `fulltext`

### QUERY `metadata`
This guidelines tries to map metadata standard from **SK KAPUSDATIN KESDM Rev 4.2** to the standard usage in the form of API.

#### `basin`

SK Rev 4.2 | API
----------- | -----------
AREA_ID | areaID
AREA_TYPE				| areaType
AREA_DESC_CODE          | areaDescCode
PRODUCT_TYPE            | productType
OPEN_BALANCE            | openBalance
OPEN_BALANCE_OUOM       | openBalanceOUOM
CURRENT_BALANCE         | currentBalance
CURRENT_BALANCE_OUOM    | currentBalanceOUOM
ORIGINAL_FILE_NAME      | originalFileName
DECRYPT_KEY             | decrtyptKey
DECRYPTION_TYPE         | decryptionType
DIGITAL_SIZE            | digitalSize
DIGITAL_SIZE_UOM        | digitalSizeUOM
MEDIA_TYPE              | mediaType
REMARK                  | remark
SIZE_TYPE               | sizeTypeOffshore
SIZE_TYPE               | sizeTypeOnshore


### QUERY `geo_location`

### QUERY `geo_centroid`
