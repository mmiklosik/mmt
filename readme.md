# ui-components

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

## Etalony
### etalon adries
sluzba
```
.../etalons/address?q=zochova (q = query zadavane do vyhladavacieho policka)
```
pre query `zochova` je prilozeny response (GET.address.invalid.json) => adresy nie su validne, chyba referenceNumber (Orientacne cislo)
pre query `zochova 5` je prilozeny response (GET.address.json) => adresy su uz validna
### etalon firiem
sluzba
```
.../etalons/legal-subject?q=habita (q = query zadavane do vyhladavacieho policka)
```
pre query `habita` je prilozeny JSON response (GET.legalSubject.json)
treba ratat s tym, ze adresy vratene zo sluzby mozu byt nevalidne (napr. chyba referenceNumber)

## Zoznam formularovych komponentov a ich selektory
```
text (.field .text)
currency (.field .currency)
email (.field .email)
iban (.field .iban)
id-card (.field .id-card)
number (.field .number)
password (.fiedl .password)
personal-number (.field .personal-number)
phone (.field .phone)
zipCode (.field .zip-code)

search (.field .selector .choice .search)
select (.field .selector .choice .select)

check (.field .selection .check)
radio (.field .selection .radio)
radio-group (.field .group .radio-group)

date (.field .selector .datetime)
time (.field .selector .datetime)
month (.field .selector .datetime)
year (.field .selector .datetime)
```
