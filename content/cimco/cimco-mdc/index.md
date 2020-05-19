---
title: CIMCO MDC-MAX
summary: Here we describe CIMCO MDC-MAX.
date: "2018-06-28T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---
{{< figure library="true" src="dnc.png" title="" lightbox="true" >}}
**CIMCO MDC-Max** jest zintegrowanym systemem gromadzenia i raportowania danych produkcyjnych parku maszynowego. Umożliwia zarówno bieżące raportowanie wartości charakterystycznych dla wydajności maszyny lub grupy maszyn, jak również raportowanie wielkości historycznych, takich jak: bilans pracy maszyny, min/max/średni czas cyklu, współczynniki OEE i inne.
{{< figure library="true" src="cimco-mdc-2.jpg" title="" lightbox="true" >}}

**Podstawowe cechy CIMCO MDC-Max**
* Automatyczne i bezobsługowe gromadzenie danych na podstawie sygnałów wewnątrz urządzenia monitorowanego
* Automatyczne i bezobsługowe gromadzenie danych na podstawie komunikatów wysyłanych przez maszynę przez port transmisji danych w trakcie pracy maszyny
* Dodatkowe dane gromadzone za pomocą czytników kodów kreskowych i/lub paneli operatorskich na stanowisku pracy
* Podgląd bieżących danych produkcyjnych maszyny (tryb pracy, czas cyklu, ilość sztuk od rozpoczęcia zmiany, itp.)
* Elastyczna konfiguracja historycznych raportów ilościowych, jakościowych i wydajnościowych maszyny
* Otwarta baza danych SQL umożliwiająca integrację z innymi systemami w przedsiębiorstwie

**CIMCO MDC-Max - monitorowanie poprzez Ethernet**
System umożliwia monitorowanie poprzez sieć Ethernet maszyn ze sterowaniem:
* FANUC
* HAAS
* HEIDENHAIN
* BROTHER
* maszyny wyposażone w protokół MT Connect
* Sinumerik

**Zalety rozwiązania**

* Bieżące informacje na temat wykorzystania parku maszynowego
* Raporty danych historycznych do wykorzystania przez służby utrzymania ruchu i planowania
* Powiadomienia SMS/e-mail w przypadku krytycznych zdarzeń
* Elastyczna architektura systemu umożliwiająca dowolną modyfikację czy rozbudowę w przyszłości
{{< figure library="true" src="monitor-shopfloor.png" title="" lightbox="true" >}}

**Metody zbierania statusów pracy w CIMCO MDC-Max**

1. automatyczne, oparte na sygnałach pochodzących ze sterowań maszyn
{{< figure library="true" src="cimco-mdc-sie.jpg" title="Podłączenie maszyn w sieć - rozwiązanie oparte na sieci LAN" lightbox="true" >}}
2. manualne, oparte na wprowadzaniu statusów pracy maszyn, operatorów za pomocą paneli operatorskich
{{< figure library="true" src="cimco-mdc-panel-operatorski.jpg" title="Przykładowy panel operatorski" lightbox="true" >}}
3. manualne, oparte na wprowadzaniu statusów pracy maszyn, operatorów za pomocą kodów kreskowych
{{< figure library="true" src="cimco-mdc-skaner.jpg" title="Przykładowe kody kreskowe" lightbox="true" >}}
