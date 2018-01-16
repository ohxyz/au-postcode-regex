# Australian Postcode Regular Expression - AU Postcode Regex

`/0[8-9][0-9][0-9]|[1-9][0-9][0-9][0-9]/`

Source: https://auspost.com.au/business/marketing-and-communications/access-data-and-insights/address-data/postcode-data

## Postcodes by state

    0800 ... 0999, 1000 ... 2599, 2600 ... 2619, 2620 ... 2899, 2900 ... 2920, 2921 ... 2999,
     |         |    |         |    |         |    |         |    |         |    |         |    
     +-- ACT --+    +-- NSW --+    +-- ACT --+    +-- NSW --+    +-- ACT --+    +-- NSW --+
    
    
    3000 ... 3999, 4000 ... 4999, 5000 ... 5999, 6000 ... 6999, 7000 ... 7999, 
     |         |    |         |    |         |    |         |    |         |    
     +-- Vic --+    +-- Qld --+    +-- SA ---+    +-- WA ---+    +-- Tas --+
    
    
    8000 ... 8999, 9000 ... 9999
     |         |    |         |
     +-- Vic --+    +-- Qld --+

## So, the regex is

`/0[8-9][0-9][0-9]|[1-9][0-9][0-9][0-9]/`
