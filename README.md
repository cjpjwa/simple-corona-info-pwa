# simple-corona-info-pwa
Simple Corona Info is a progressive web app (PWA) showing information about new cases in Germany compared to the previous day
and 7 day incidence for German counties (Landkreise). You can save the 7 day inicidence (cases in the last 7 days/100000 PE) for 10 counties.
Typing on the county name shows additional data (cases, population ...). This PWA idea was inspired by the [COVID-19 Inzidenz-Widget für iOS](https://gist.github.com/malakka/0576bb922e7b81b95137a06b619bba1b)

Working sample of the PWA can be found here: https://cinfo.cjpj.de

![Screenshot sample app](https://github.com/cjpjwa/simple-corona-info-pwa/blob/06f690e9b300cfa247ff4f0e9facba8270cad231/screenshot/screenshot_02.png?raw=true)

## Data Saving
The county ID is saved via localstorage. 

## Data Scource (Quellenvermerk)
Quellenvermerk: Robert Koch-Institut (RKI), dl-de/by-2-0

Die Daten sind die "Fallzahlen in Deutschland" des [Robert Koch-Institut (RKI)](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Fallzahlen.html)
und stehen unter der [Open Data Datenlizenz Deutschland - Namensnennung - Version 2.0](https://www.govdata.de/dl-de/by-2-0) zur Verfügung.

## License
simple-corona-info-pwa is licensed under [The MIT License](https://github.com/cjpjwa/simple-corona-info-pwa/blob/master/LICENSE)

## Used Libs 
- [simple-app-Shell](https://github.com/cjpjwa/simple-app-shell) under [The MIT License](https://github.com/cjpjwa/simple-app-shell/blob/master/LICENSE)
