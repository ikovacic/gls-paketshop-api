# GLS PaketShop API

API endpoint koji u JSON formatu vraća sve GLS PaketShop lokacije na kojima je moguće preuzeti pakete unutar Hrvatske (https://www.paket.hr/paketshop).

Podaci se ažuriraju svakih 15 minuta.

## Endpoint

Endpoint je dostupan na adresi https://api.applause.hr/gls/get-locations i prihvaća GET requestove.

## Parametri

* limit - integer
* offset - integer
* id - integer
* zip_code - integer
* search - bilo koji string
* type - “formatted”


## Primjeri poziva

* https://api.applause.hr/gls/get-locations?limit=10
* https://api.applause.hr/gls/get-locations?limit=10&offset=10
* https://api.applause.hr/gls/get-locations?id=11
* https://api.applause.hr/gls/get-locations?zip_code=10255
* https://api.applause.hr/gls/get-locations?search=appla
* https://api.applause.hr/gls/get-locations?search=zagr+100
* https://api.applause.hr/gls/get-locations?type=formatted
