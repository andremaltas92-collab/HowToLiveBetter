# Запись верификации источников: раздел 1

Дата верификации 2026-09-07. Большинство сайтов издательств (NEJM, Elsevier, Wiley, BMJ, AHA) возвращают WebFetch код 403, поэтому для этих источников использовался Europe PMC REST (`<https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:"…"&resultType=core&format=json>`), который по тому же DOI отдаёт название, авторов, журнал, год и полный текст аннотации; doi.org сам по себе резолвит (302 на издательство). Все приводимые ниже «оригиналы» — это фразы, вытащенные из аннотации/полного текста.

## 1. Ремень безопасности
- <https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813573> — открыт (PDF переведён в текст через pdftotext). Заголовок «Occupant Protection in Passenger Vehicles: 2022 Data, DOT HS 813 573, May 2024» совпал.
  - Оригинал: «Fifty percent of passenger vehicle occupants killed in traffic crashes in 2022 were unrestrained (based on known restraint use).»
  - Оригинал: «lap/shoulder seat belts, when used, reduce the risk of: fatal injury to front-seat passenger car occupants by 45 percent; … fatal injury to front-seat light-truck occupants by 60 percent»
  - Оригинал: «60 percent of those in the second row were unrestrained.»
- <https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries> — открыт. Оригинал: «Wearing a seat-belt can reduce the risk of death among vehicle occupants by up to 50%.»
- <https://ghoapi.azureedge.net/api/RS_196?$filter=SpatialDim%20eq%20%27CHN%27> — открыт (WHO GHO API). Китай, 2021: 248 099 (95% CI 233 685–262 513). RS_198 тем же способом: 17,4/100 000 за 2021 год.
  - Примечание: интерфейс GHO вернул RS_196 как абсолютное число, а RS_198 как коэффициент — порядок оказался обратным ожидаемому; сами цифры взяты из возвращённого JSON.

## 2. Шлем
- <https://doi.org/10.1002/14651858.CD004333.pub3> — doi.org резолвит в Wiley (403), через Europe PMC запись подтверждена: Liu BC, 2008, «Helmets for preventing injury in motorcycle riders».
  - Оригинал: «helmets were estimated to reduce the risk of death by 42% (OR 0.58, 95% CI 0.50 to 0.68)»; «reduce the risk of head injury by 69% (OR 0.31, 95% CI 0.25 to 0.38)»

## 3. Пожарный извещатель / угарный газ
- <https://doi.org/10.1001/jama.279.20.1633> — через Europe PMC запись подтверждена: Marshall SW, Runyan CW и др., JAMA 1998, «Fatal residential fires: who dies and who survives?».
  - Оригинал: «Overall, a functioning smoke detector lowered the risk of death (OR, 0.39; 95% CI, 0.18-0.83).»
- <https://www.usfa.fema.gov/downloads/pdf/statistics/v22i2.pdf> — открыт (PDF в текст). Заголовок «Fatal Fires in Residential Buildings (2018-2020), Topical Fire Report Series June 2022 Vol 22 Issue 2» совпал.
  - Оригинал: «Smoke alarms were not present in 24% of fatal fires in occupied residential buildings.»; «The leading human factor contributing to the ignition of fatal fires in residential buildings was being 'asleep' (41%).»
- <https://doi.org/10.46234/ccdcw2020.008> — doi.org резолвит в weekly.chinacdc.cn (только метаданные), полный текст получен через Europe PMC PMC8392909 fullTextXML. Авторы You J, Liu J, Zhou M, China CDC Weekly 2020.
  - Оригинал: «In 2018, there were 11,523 deaths caused by carbon monoxide poisoning reported in China»; «highest proportions occurring in December (72.59%), January (67.42%), and February (66.48%)»
- Не использовано: страница NFPA «Smoke Alarms in US Home Fires» отдала только заголовок, PDF отчёта вернул 500, проверить не удалось, поэтому цифра NFPA «смертность на 55% ниже» в текст не пошла.

## 4. Артериальное давление
- <https://doi.org/10.1016/S0140-6736(15)01225-8> — страница Elsevier показала только «Redirecting»; через Europe PMC запись подтверждена: Ettehad D, Lancet 2016.
  - Оригинал: «relative risk [RR] 0·80, 95% CI 0·77-0·83» (основные сердечно-сосудистые события); «stroke (0·73, 0·68-0·77)»; «heart failure (0·72, 0·67-0·78)»; «a significant 13% reduction in all-cause mortality (0·87, 0·84-0·91)»
  - Оригинал: «We identified 123 studies with 613,815 participants for the tabular meta-analysis.»
- <https://doi.org/10.1016/S0140-6736(17)32478-9> — через Europe PMC запись подтверждена: Lu J, Lancet 2017, China PEACE Million Persons Project.
  - Оригинал: «44·7% (95% CI 44·6-44·8) of the sample had hypertension, of whom 44·7% (44·6-44·8) were aware of their diagnosis, 30·1% (30·0-30·2) were taking prescribed antihypertensive medications, and 7·2% (7·1-7·2) had achieved control»

## 5. Не превышать скорость и не садиться за руль пьяным
- <https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries> — открыт.
  - Оригинал: «Every 1% increase in mean speed produces a 4% increase in the fatal crash risk.»; «The risk of a road traffic crash starts at low levels of blood alcohol concentration (BAC).»

## 6. Детское автокресло
- NHTSA 813573 (тот же, что и в пункте 1). Оригинал: «NHTSA has estimated that car seats reduce the risk of fatal injury by 71 percent for infants (younger than 1 year old) and by 54 percent for toddlers (1 to 4 years old) in passenger cars.»
- WHO fact sheet по дорожному движению (тот же). Оригинал: «The use of child restraints can lead to a 71% reduction in deaths among infants.»

## 7. Утопление
- <https://doi.org/10.1136/ip.2010.028688> — doi.org резолвит в injuryprevention.bmj.com (403); через Europe PMC запись подтверждена: Cummings P, Mueller BA, Quan L. Injury Prevention 2011;17(3):156-159, PMID 20889519.
  - Оригинал: «The adjusted RR was 0.51 (95% CI 0.35 to 0.74).»
  - Примечание: первоначально записанный мной DOI (...028381) был неверным — doi.org возвращал 404, заменён на ...028688, выданный Europe PMC.
- <https://doi.org/10.46234/ccdcw2023.198> — резолвит в weekly.chinacdc.cn; полный текст получен через Europe PMC PMC10689961. Li Z, China CDC Weekly 2023.
  - Оригинал: «the national drowning mortality rate from 6.60 per 100,000 in 2013 down to 3.28 per 100,000 in 2021»; «rural areas exhibited roughly double the mortality rate found in urban areas»; «in China, it is deemed the primary cause of death for children between the ages of 1 and 14»; «peaking at 3.95 per 100,000 in the 15–19 year age group»
- <https://doi.org/10.46234/ccdcw2024.057> — резолвит в weekly.chinacdc.cn; аннотация получена через Europe PMC. Zhou J, China CDC Weekly 2024.
  - Оригинал: «In 2021, drowning and road traffic crashes were the top two causes of child injury deaths, explaining 31.1% and 27.9% of total injury deaths, respectively.»
- Не использовано: страница Китайского CDC chinacdc.cn/.../t20210809_233793.html вернула 404.
