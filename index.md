# Introduction
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
AREA_ID                  |	AreaID
AREA_TYPE				         |	AreaType
AREA_DESC_CODE           |	AreaDescCode
PRODUCT_TYPE             |	ProductType
OPEN_BALANCE             |	OpenBalance
OPEN_BALANCE_OUOM        |	OpenBalanceOUOM
CURRENT_BALANCE          |	CurrentBalance
CURRENT_BALANCE_OUOM     |	CurrentBalanceOUOM
ORIGINAL_FILE_NAME       |	OriginalFileName
DECRYPT_KEY              |	DecryptKey
DECRYPTION_TYPE          |	DecryptionType
DIGITAL_SIZE             |	DigitalSize
DIGITAL_SIZE_UOM         |	DigitalSizeUOM
MEDIA_TYPE               |	MediaType
REMARK                   |	Remark
SIZE_TYPE                |	SizeTypeOffshore
SIZE_TYPE                |	SizeTypeOnshore


### QUERY `geo_location`

### QUERY `geo_centroid`
