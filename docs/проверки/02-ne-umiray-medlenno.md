# Запись верификации источников: раздел 2

Дата верификации: 2026-09-07. Метод: для каждого источника открывался Europe PMC REST (`<https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:"…"&resultType=core&format=json>`, отдельные — через `TITLE:` или `EXT_ID:<pmid> AND SRC:MED`). Запись содержит название, авторов, журнал, год, DOI, PMID и полную аннотацию; все приводимые ниже цифры взяты из аннотации. Сайт PubMed для WebFetch отдаёт страницу с cookie-перехватом, doi.org возвращает 302 на страницу издательства (NEJM), которая возвращает 403, поэтому за основу взят Europe PMC. DOI указаны по записям Europe PMC. (Среди проверенных статей Aune 2016 по орехам DOI на самом деле `10.1186/s12916-016-0730-3`; мой первоначальный `-0730-5` был неверным, эта статья в итоге не вошла в основной текст.)

## Пункт 1. Бросить курить
- <https://doi.org/10.1056/NEJMsa1211128> — подтверждено: Jha P и др., NEJM 2013, PMID 23343063. Оригинал аннотации: «Life expectancy was shortened by more than 10 years among the current smokers»; «Adults who had quit smoking at 25 to 34, 35 to 44, or 45 to 54 years of age gained about 10, 9, and 6 years of life, respectively»; «Cessation before the age of 40 years reduces the risk of death associated with continued smoking by about 90%.»
- <https://doi.org/10.1016/S0140-6736(15)00340-2> — подтверждено: Chen Z и др., Lancet 2015, PMID 26466050. Оригинал: городские мужчины «RR 1·32 [95% CI 1·24-1·41] vs 1·65 [1·53-1·79]» (1990-е против 2010-х), сельские мужчины «RR 1·13 [1·09-1·17] vs 1·22 [1·16-1·29]»; «Ex-smokers who had stopped by choice…had little smoking-attributed risk more than 10 years after stopping.»
- <https://doi.org/10.1016/S0140-6736(10)61388-8> — подтверждено: Oberg M и др., Lancet 2011, PMID 21112082. Оригинал: «603,000 deaths were attributable to second-hand smoke in 2004, which was about 1·0% of worldwide mortality.»

## Пункт 2. Сахаросодержащие напитки
- <https://doi.org/10.1161/CIRCULATIONAHA.118.037401> — подтверждено: Malik VS и др., Circulation 2019, PMID 30882235. Оригинал: категории «(<1/mo, 1-4/mo, 2-6/week, 1-<2/d, and ≥2/d) were 1.00 (reference), 1.01 (0.98, 1.04), 1.06 (1.03, 1.09), 1.14 (1.09, 1.19), and 1.21 (1.13, 1.28)»; 37 716 мужчин и 80 647 женщин, «36 436 deaths». Аннотация не даёт HR на каждую порцию в день, в основной текст не пошло.
- <https://doi.org/10.1001/jamainternmed.2019.2478> — подтверждено: Mullee A и др., JAMA Intern Med 2019. Оригинал: total soft drinks «HR, 1.17; 95% CI, 1.11-1.22»; sugar-sweetened «HR, 1.08; 95% CI, 1.01-1.16»; artificially sweetened «HR, 1.26; 95% CI, 1.16-1.35»; 451 743 участника.

## Пункт 3. Соль с пониженным содержанием натрия
- <https://doi.org/10.1056/NEJMoa2105675> — подтверждено: Neal B и др., NEJM 2021, PMID 34459569. Оригинал: 20 995 участников, среднее наблюдение 4,74 года; инсульт «rate ratio, 0.86»; основные сердечно-сосудистые события «rate ratio, 0.87»; смерть «39.28 events vs. 44.61 events per 1000 person-years; rate ratio, 0.88»; отношение рисков гиперкалиемии 1,04, без значимой разницы.
- <https://doi.org/10.1056/NEJMoa1311889> — подтверждено: O'Donnell M и др., NEJM 2014, PMID 25119607. Оригинал: «≥ 7.00 g per day…odds ratio, 1.15; 95% CI, 1.02 to 1.30»; «below 3.00 g per day…odds ratio, 1.27; 95% CI, 1.12 to 1.44».

## Пункт 4. Шаги
- <https://doi.org/10.1016/S2468-2667(21)00302-9> — подтверждено: Paluch AE и др., Lancet Public Health 2022, PMID 35247352. Оригинал: «47 471 adults, among whom there were 3013 deaths»; «Quartile median steps per day were 3553 for quartile 1, 5801 for quartile 2, 7842 for quartile 3, and 10 901 for quartile 4»; «adjusted HR for all-cause mortality was 0·60 (95% CI 0·51-0·71) for quartile 2, 0·55 (0·49-0·62) for quartile 3, and 0·47 (0·39-0·57) for quartile 4»; ≥60 лет — «6000-8000 steps per day», <60 лет — «8000-10 000 steps per day».
- <https://doi.org/10.1093/eurjpc/zwad229> — подтверждено: Banach M и др., Eur J Prev Cardiol 2023, PMID 37555441. Оригинал: «A 1000-step increment was associated with a 15% decreased risk of all-cause mortality»; «the cut-off point of 3867 steps/day for all-cause mortality».

## Пункт 5. Приверженность к гипотензивной и гиполипидемической терапии
- <https://doi.org/10.1016/S0140-6736(15)01225-8> — подтверждено: Ettehad D и др., Lancet 2016, PMID 26724178. Оригинал: основные сердечно-сосудистые события «RR 0·80, 95% CI 0·77-0·83»; инсульт «0·73, 0·68-0·77»; сердечная недостаточность «0·72, 0·67-0·78»; «13% reduction in all-cause mortality (0·87, 0·84-0·91)».
- <https://doi.org/10.1016/S0140-6736(10)61350-5> — подтверждено: CTT Collaboration, Lancet 2010, PMID 21067804. Оригинал: основные сосудистые события «rate ratio [RR] 0·78, 95% CI 0·76–0·80»; «all-cause mortality was reduced by 10% per 1·0 mmol/L LDL reduction (RR 0·90, 95% CI 0·87–0·93)».
- <https://doi.org/10.1093/eurheartj/eht295> — подтверждено: Chowdhury R и др., Eur Heart J 2013, PMID 23907142. Оригинал: «Corresponding RRs of all-cause mortality were 0.55 (0.46-0.67) and 0.71 (0.64-0.78) for good adherence to statins and antihypertensive agents»; хорошая приверженность против плохой (<80%).

## Пункт 6. Сон
- <https://doi.org/10.1093/sleep/33.5.585> — подтверждено: Cappuccio FP и др., Sleep 2010, PMID 20469800. Оригинал: «16 studies…1,382,999 male and female participants…112,566 deaths»; короткий сон «RR: 1.12; 95% CI 1.06 to 1.18»; длинный «1.30; [1.22 to 1.38]». Аннотация не приводит определения «короткого» и «длинного» сна в часах, поэтому в основном тексте конкретные часовые пороги не указаны.
- <https://doi.org/10.1161/JAHA.117.005947> — подтверждено: Yin J и др., JAHA 2017, PMID 28889101. Оригинал: <7 ч «RR was 1.06 (95% CI, 1.04-1.07) per 1-hour reduction»; >7 ч «RR was 1.13 (95% CI, 1.11-1.15) per 1-hour increment».
- <https://doi.org/10.1093/sleep/zsad253> — подтверждено: Windred DP и др., Sleep 2024, PMID 37738616. Оригинал: «60 977 UK Biobank participants»; «1859» deaths; «Higher sleep regularity was associated with a 20%-48% lower risk of all-cause mortality» (верхние четыре квинтили SRI против наименее регулярного); «Sleep regularity was a stronger predictor of all-cause mortality than sleep duration».

## Пункт 7. Умеренная физическая активность
- <https://doi.org/10.1001/jamainternmed.2015.0533> — подтверждено: Arem H и др., JAMA Intern Med 2015, PMID 25844730. Оригинал: менее 7,5 MET-ч/нед «HR, 0.80 [95% CI, 0.78-0.82]»; 1-2 раза «HR, 0.69 [95% CI, 0.67-0.70]»; 2-3 раза «HR, 0.63»; 3-5 раз «HR, 0.61 [95% CI, 0.59-0.62]»; 10 и более раз «HR, 0.69 [95% CI, 0.59-0.78]».
- <https://doi.org/10.1136/bmj.l4570> — подтверждено: Ekelund U и др., BMJ 2019, PMID 31434697. Оригинал: HR по квартилям MVPA «1.00, 0.64 (0.55–0.74), 0.55 (0.40–0.74), and 0.52 (0.43–0.61)»; верхний квартиль total PA «0.27 (0.23 to 0.32)».

## Пункт 8. Силовые упражнения
- <https://doi.org/10.1136/bjsports-2021-105061> — подтверждено: Momma H и др., Br J Sports Med 2022, PMID 35228201. Оригинал: «Muscle-strengthening activities were associated with a 10-17% lower risk of all-cause mortality»; «J-shaped associations with the maximum risk reduction (approximately 10-20%) at approximately 30-60 min/week»; «Combined muscle-strengthening and aerobic activities (versus none) were associated with a lower risk of all-cause…mortality».

## Пункт 9. Долгое сидение
- <https://doi.org/10.7326/M17-0212> — подтверждено: Diaz KM и др., Ann Intern Med 2017, PMID 28892811. Оригинал: верхний против нижнего квартиля по общему сидению «HR, 2.63 [CI, 1.60 to 4.30]»; по длительности непрерывного сидения «HR, 1.96 [CI, 1.31 to 2.93]»; «both the total volume of sedentary time and its accrual in prolonged, uninterrupted bouts are associated with all-cause mortality». В аннотации не указан 30-минутный порог, поэтому в заголовке пункта конкретное число минут не написано.
- <https://doi.org/10.1016/S0140-6736(16)30370-1> — подтверждено: Ekelund U и др., Lancet 2016, PMID 27475271. Оригинал: референс «those sitting <4 h/day and in the most active quartile [>35·5 MET-h per week]»; нижний квартиль активности + сидение >8 ч/день «HR=1·59, 1·52-1·66»; самые активные + >8 ч «HR=1·04; 95% CI 0·99-1·10»; «about 60-75 min per day…seem to eliminate the increased risk of death associated with high sitting time»; ТВ ≥5 ч у самых активных «HR=1·16, 1·05-1·28».

## Пункт 10. Переработанное мясо
- <https://doi.org/10.1093/aje/kwt261> — подтверждено: Larsson SC, Orsini N, Am J Epidemiol 2014, PMID 24148709. Оригинал (верхняя против нижней категории): необработанное красное мясо «1.10 (95% CI: 0.98, 1.22)»; переработанное мясо «1.23 (95% CI: 1.17, 1.28)»; красное мясо в целом «1.29 (95% CI: 1.24, 1.35)».
- <https://doi.org/10.3945/ajcn.117.153148> — подтверждено: Schwingshackl L и др., Am J Clin Nutr 2017, PMID 28446499. Оригинал (на порцию в день): цельнозерновые «RR: 0.92; 95% CI: 0.89, 0.95»; красное мясо «RR: 1.10; 95% CI: 1.04, 1.18»; переработанное мясо «RR: 1.23; 95% CI: 1.12, 1.36».
- <https://doi.org/10.7326/M19-1621> — подтверждено: Johnston BC и др., Ann Intern Med 2019, PMID 31569235. Оригинал: «continue current unprocessed red meat consumption (weak recommendation, low-certainty evidence)»; «continue current processed meat consumption (weak recommendation, low-certainty evidence)».

## Пункт 11. Алкоголь
- <https://doi.org/10.1016/S0140-6736(18)30134-X> — подтверждено: Wood AM и др., Lancet 2018, PMID 29676281. Оригинал: «the minimum mortality risk around or below 100 g per week»; ожидаемая продолжительность жизни в 40 лет: >100–≤200 г/нед «approximately 6 months», >200–≤350 г/нед «1–2 years», >350 г/нед «4–5 years».
- <https://doi.org/10.1016/S0140-6736(18)31310-2> — подтверждено: GBD 2016 Alcohol Collaborators, Lancet 2018. Оригинал: «The level of alcohol consumption that minimised harm across health outcomes was zero (95% UI 0·0-0·8) standard drinks per week.»
- <https://doi.org/10.1001/jamanetworkopen.2023.6185> — подтверждено: Zhao J и др., JAMA Netw Open 2023, PMID 37000449. Оригинал: «low-volume drinkers (1.3-24.0 g per day; RR, 0.93; P = .07) compared with lifetime nondrinkers»; «45 to 64 and 65 or more grams per day (RR, 1.19 and 1.35; P < .001)».
- <https://doi.org/10.1001/archinte.166.22.2437> — подтверждено: Di Castelnuovo A и др., Arch Intern Med 2006, PMID 17159008. Оригинал: «maximum protection being 18% in women (99% confidence interval, 13%-22%) and 17% in men»; «up to 4 drinks per day in men and 2 drinks per day in women, was inversely associated with total mortality».

## Пункт 12. Цельные зёрна
- <https://doi.org/10.1136/bmj.i2716> — подтверждено: Aune D и др., BMJ 2016, PMID 27301975. Оригинал: на 90 г/день «0.83 (0.77 to 0.90; I(2)=83%, n=11) for all causes»; «Reductions in risk were observed up to an intake of 210-225 g/day».
- Schwingshackl 2017 — то же, что в пункте 10 (whole grains RR 0.92).

## Пункт 13. Фрукты и овощи
- <https://doi.org/10.1093/ije/dyw319> — подтверждено: Aune D и др., Int J Epidemiol 2017, PMID 28338764. Оригинал: «the summary RR per 200 g/day was…0.90 (95% CI: 0.87-0.93…for all-cause mortality»; «Reductions in risk were observed up to 800 g/day for all outcomes except cancer (600 g/day)».
- <https://doi.org/10.1161/CIRCULATIONAHA.120.048996> — подтверждено: Wang DD и др., Circulation 2021, PMID 33641343. Оригинал: «daily intake of 5 servings of fruit and vegetables was associated with hazard ratios (95% CI) of 0.87 (0.85-0.90) for total mortality» (референс — 2 порции/день); «≈5 servings per day of fruit and vegetables, or 2 servings of fruit and 3 servings of vegetables, was associated with the lowest mortality».

## Пункт 14. Сверхпереработанные продукты
- <https://doi.org/10.1136/bmj-2023-077310> — подтверждено: Lane MM и др., BMJ 2024, PMID 38418082. Оригинал: «all cause mortality (risk ratio 1.21, 1.15 to 1.27; low)» — класс II, highly suggestive; «cardiovascular disease related mortality (risk ratio 1.50, 95% confidence interval 1.37 to 1.63; GRADE=very low)» — класс I, convincing.

## Пункт 15. Горение в помещении / PM2.5
- <https://doi.org/10.1001/jama.2018.2151> — подтверждено: Yu K и др., JAMA 2018, PMID 29614179. Оригинал: 271 217 взрослых; приготовление пищи на твёрдом топливе — общая смертность «HR, 1.11 [95% CI, 1.03-1.20]»; отопление — «HR, 1.14 [95% CI, 1.03-1.26]»; перешедшие (готовка) «HR, 0.87 [95% CI, 0.79-0.95]»; перешедшие (отопление) «HR, 0.67 [95% CI, 0.57-0.79]».
- <https://doi.org/10.1016/j.envint.2020.105974> — подтверждено: Chen J, Hoek G, Environ Int 2020, PMID 32703584. Оригинал: «The combined Risk Ratio (RR) for PM₂.₅ and natural-cause mortality was 1.08 (95%CI 1.06, 1.09) per 10 µg/m³», 104 когортных исследования.

## Пункт 16. Вес
- <https://doi.org/10.1016/S0140-6736(16)30175-1> — подтверждено: Global BMI Mortality Collaboration, Lancet 2016, PMID 27423262. Оригинал: «All-cause mortality was minimal at 20·0-25·0 kg/m(2)»; 25.0-27.5 — «1·07, 1·07-1·08»; 27.5-30.0 — «1·20, 1·18-1·22»; 30.0-35.0 — «1·45, 95% CI 1·41-1·48»; 35.0-40.0 — «1·94, 1·87-2·01»; 40.0-60.0 — «2·76, 2·60-2·92»; Восточная Азия на 5 кг/м² — «1·39 (1·34-1·44)»; анализ ограничен «never-smokers without chronic diseases at recruitment who survived 5 years».
- <https://doi.org/10.1001/jama.2012.113905> — подтверждено: Flegal KM и др., JAMA 2013, PMID 23280227. Оригинал: «The summary HRs were 0.94 (95% CI, 0.91-0.96) for overweight, 1.18 (95% CI, 1.12-1.25) for obesity (all grades combined), 0.95 (95% CI, 0.88-1.01) for grade 1 obesity, and 1.29 (95% CI, 1.18-1.41) for grades 2 and 3 obesity.»

## Проверено, но не вошло в основной текст
- Aune D и др. (2016) по орехам, BMC Medicine, <https://doi.org/10.1186/s12916-016-0730-3>, PMID 27916000: на 28 г/день ACM «0.78 (95% CI: 0.72-0.84)». Эффект мог быть усилен вмешивающимися факторами, а каждый день стоит денег — для соблюдения лимита в 16 пунктов не вошло.
- Sofi F и др. (2010) средиземноморская диета, Am J Clin Nutr, <https://doi.org/10.3945/ajcn.2010.29673>, PMID 20810976: увеличение на 2 балла «RR = 0.92; 95% CI: 0.90, 0.94». Пересекается с пунктами 10, 12, 13, поэтому не вошло.
- Holt-Lunstad J и др. (2010) PLoS Med, <https://doi.org/10.1371/journal.pmed.1000316>, PMID 20668659: «OR = 1.50 (95% CI 1.42 to 1.59)»; Holt-Lunstad J и др. (2015) Perspect Psychol Sci, <https://doi.org/10.1177/1745691614568352>, PMID 25910392: «social isolation odds ratio (OR) = 1.29, loneliness OR = 1.26, and living alone OR = 1.32». Эффект социальной изоляции велик, но обратная причинность выражена, доказательств вмешательства нет — для соблюдения лимита пунктов не вошло; при необходимости можно добавить как пункт 17.

## Не подтверждено
- Ничего. Все числа в основном тексте взяты из открытых выше записей. Колонка «стоимость» (деньги, время) — авторская оценка, на литературу не ссылается.
