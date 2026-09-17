# Запись верификации источников: раздел 6

Пояснение по методу проверки: doi.org всегда возвращает 302; страницы издательств JAMA/NEJM/Elsevier/Wiley/ACP/RSNA/Nature для WebFetch возвращают 403, страницы PubMed отдают только cookie. Поэтому аннотации единообразно проверены через официальный REST Europe PMC (`<https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:<doi>&resultType=core&format=json>`, возвращает те же данные, что и PubMed, включая abstractText); в отдельных случаях использован NCBI E-utilities efetch. Ниже «фактически открытый URL» — это адрес, по которому WebFetch успешно вернул содержимое. Все DOI в записях Europe PMC совпадают с заголовками/авторами/годом.

## Пункт 1. Мультивитамины

- Источник A: Sesso HD et al. 2012 JAMA, DOI 10.1001/jama.2012.14805
  - Фактически открыт: Europe PMC REST (поиск по DOI). Заголовок совпал: «Multivitamins in the prevention of cardiovascular disease in men: the Physicians' Health Study II randomized controlled trial», 2012, JAMA. Подтверждено.
  - Цифры (аннотация): «14,641 male US physicians»; «median follow-up 11.2 years»; «major cardiovascular events … HR, 1.01; 95% CI, 0.91-1.10; P = .91»; «total mortality … HR, 0.94; 95% CI, 0.88-1.02; P = .13»
- Источник B: USPSTF 2022 JAMA, DOI 10.1001/jama.2022.8970
  - Фактически открыт: <https://jamanetwork.com/journals/jama/fullarticle/2793446> (цель редиректа doi.org, прямое извлечение успешно). Заголовок совпал: «Vitamin, Mineral, and Multivitamin Supplementation to Prevent Cardiovascular Disease and Cancer: US Preventive Services Task Force Recommendation Statement», 2022, JAMA 327(23). Подтверждено.
  - Цифры: «Multivitamin trials reviewed: 9 RCTs involving 51,550 participants showed no association between multivitamin supplementation and all-cause mortality»; для мультивитаминов оценка I; для бета-каротина и витамина E — оценка D («recommends against the use of beta carotene or vitamin E supplements for the prevention of cardiovascular disease or cancer»); бета-каротин «Increased lung cancer risk (RR 1.18) in smokers/asbestos-exposed workers» (цифра 1.18 напрямую в пункт не вошла).
- Контраргумент в примечании: Gaziano JM et al. 2012 JAMA, DOI 10.1001/jama.2012.14641
  - Фактически открыт: <https://pubmed.ncbi.nlm.nih.gov/?term=10.1001%2Fjama.2012.14641> (в этом запуске PubMed успешно вернул аннотацию). Заголовок совпал: «Multivitamins in the prevention of cancer in men: the Physicians' Health Study II randomized controlled trial». Подтверждено.
  - Цифры: «hazard ratio [HR], 0.92; 95% CI, 0.86-0.998; P=.04»; «HR, 0.88; 95% CI, 0.77-1.01; P=.07»

## Пункт 2. Рыбий жир

- Manson JE et al. 2019 NEJM, DOI 10.1056/NEJMoa1811403
  - Фактически открыт: Europe PMC REST (поиск по DOI). Заголовок совпал: «Marine n-3 Fatty Acids and Prevention of Cardiovascular Disease and Cancer», 2019, NEJM. Подтверждено.
  - Цифры: «25,871 participants»; «1 g/day»; «median follow-up of 5.3 years»; «major cardiovascular events … hazard ratio, 0.92; 95% CI, 0.80 to 1.06; P=0.24»; «Death from any cause … hazard ratio was 1.02 (95% CI, 0.90 to 1.15)»
- ASCEND Study Collaborative Group 2018 NEJM, DOI 10.1056/NEJMoa1804989
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Effects of n-3 Fatty Acid Supplements in Diabetes Mellitus», 2018, NEJM. Подтверждено.
  - Цифры: «15,480 patients with diabetes without atherosclerotic cardiovascular disease»; «1-gram capsules daily»; «Mean 7.4 years»; «rate ratio, 0.97; 95% CI, 0.87 to 1.08; P=0.55»; «All-cause mortality: rate ratio, 0.95; 95% CI, 0.86 to 1.05»
- Контраргумент: Bhatt DL et al. 2019 NEJM, DOI 10.1056/NEJMoa1812792
  - Фактически открыт: <https://eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=pubmed&id=30415628&rettype=abstract&retmode=text> (у Europe PMC для этой записи нет abstractText, поэтому использован NCBI efetch). Заголовок совпал: «Cardiovascular Risk Reduction with Icosapent Ethyl for Hypertriglyceridemia», REDUCE-IT Investigators, NEJM 2019 (PMID 30415628). Подтверждено.
  - Цифры: «hazard ratio was 0.75 (95% CI, 0.68–0.83; P<0.001)»; «17.2% of the icosapent ethyl group versus 22.0% of the placebo group»; «2 g of icosapent ethyl twice daily (total daily dose, 4 g)»; «established cardiovascular disease or diabetes … statin therapy, fasting triglycerides of 135–499 mg/dL»; «8,179 patients»

## Пункт 3. Витамин D

- Manson JE et al. 2019 NEJM, DOI 10.1056/NEJMoa1809944
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Vitamin D Supplements and Prevention of Cancer and Cardiovascular Disease», 2019, NEJM. Подтверждено.
  - Цифры: «2000 IU daily»; «25,871»; «Median 5.3 years»; «Invasive cancer: hazard ratio, 0.96; 95% CI, 0.88 to 1.06; P=0.47»; «Major cardiovascular events: hazard ratio, 0.97; 95% CI, 0.85 to 1.12; P=0.69»; «Death from any cause: hazard ratio was 0.99 (95% CI, 0.87 to 1.12)»
- Neale RE et al. 2022 Lancet Diabetes Endocrinol, DOI 10.1016/S2213-8587(21)00345-4
  - Фактически открыт: Europe PMC REST (поиск по DOI вернул пусто; поиск по TITLE:"D-Health Trial" AND AUTH:Neale — в возвращённой записи поле DOI = 10.1016/S2213-8587(21)00345-4, совпадает). Заголовок совпал: «The D-Health Trial: a randomised controlled trial of the effect of vitamin D on mortality», 2022. Подтверждено.
  - Цифры: «21 315 participants, including 10 662 to the vitamin D group and 10 653 to the placebo group»; «60 000 IU per month for 5 years»; «1100 deaths were recorded (placebo 538 [5·1%]; vitamin D 562 [5·3%])»; «HR … 1.04 [95% CI 0·93 to 1·18]; p=0·47»; «median follow-up 5·7 years»; «Australians 60 years or older who were recruited across the country via the Commonwealth electoral roll» (подтверждено при повторном извлечении; в основном тексте написано «старше 60 лет», без указания верхнего предела).

## Пункт 4. Антиоксидантные добавки

- Bjelakovic G et al. 2012 Cochrane, DOI 10.1002/14651858.CD007176.pub2
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Antioxidant supplements for prevention of mortality in healthy participants and patients with various diseases», 2012, Cochrane Database Syst Rev. Подтверждено.
  - Цифры: «78 trials, 296,707 participants»; «RR 1.02, 95% CI 0.98 to 1.05 (random-effects)»; «Low risk of bias trials (56 trials, 244,056 participants): RR 1.04, 95% CI 1.01 to 1.07»; «Beta-carotene: RR 1.05, 95% CI 1.01 to 1.09»; «Vitamin E: RR 1.03, 95% CI 1.00 to 1.05»
- ATBC Study Group 1994 NEJM, DOI 10.1056/NEJM199404143301501
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «The effect of vitamin E and beta carotene on the incidence of lung cancer and other cancers in male smokers», 1994, NEJM. Подтверждено.
  - Цифры: «29,133 male smokers»; «20 mg per day»; «change in incidence, 18 percent; 95 percent confidence interval, 3 to 36 percent»; «8 percent higher (95 percent confidence interval, 1 to 16 percent)»
- Omenn GS et al. 1996 NEJM, DOI 10.1056/NEJM199605023341802
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Effects of a combination of beta carotene and vitamin A on lung cancer and cardiovascular disease», 1996, NEJM. Подтверждено.
  - Цифры: «18,314 smokers, former smokers, and asbestos-exposed workers»; «relative risk of lung cancer of 1.28 (95 percent confidence interval, 1.04 to 1.57; P=0.02)»; «relative risk of death from any cause was 1.17 (95 percent confidence interval, 1.03 to 1.33)»
- Уровень D по USPSTF в примечании — то же, что источник B пункта 1, подтверждено.

## Пункт 5. Глюкозамин/хондроитин

- Clegg DO et al. 2006 NEJM, DOI 10.1056/NEJMoa052771
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Glucosamine, chondroitin sulfate, and the two in combination for painful knee osteoarthritis», 2006, NEJM. Подтверждено.
  - Цифры: «1,583 patients»; «placebo (60.1%)»; «Glucosamine: 3.9 percentage points higher (P=0.30)»; «Chondroitin sulfate: 5.3 percentage points higher (P=0.17)»; «Combined treatment: 6.5 percentage points higher (P=0.09)»; «Celecoxib: 10.0 percentage points higher (P=0.008)»; «moderate-to-severe pain at baseline … 79.2 percent vs. 54.3 percent, P=0.002»; при повторном извлечении подтверждены «… or placebo for 24 weeks» и «Exploratory analyses suggest that the combination of glucosamine and chondroitin sulfate may be effective in the subgroup of patients with moderate-to-severe knee pain».

## Пункт 6. Витамин C

- Hemilä H, Chalker E 2013 Cochrane, DOI 10.1002/14651858.CD000980.pub4
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Vitamin C for preventing and treating the common cold», 2013. Подтверждено.
  - Цифры: «pooled RR was 0.97 (95% confidence interval (CI) 0.94 to 1.00)»; «29 trial comparisons with 11,306 participants»; «In adults, colds shortened by 8% (3% to 12%); in children by 14% (7% to 21%)»; «No consistent effect of vitamin C was seen on the duration or severity of colds in the therapeutic trials». Цифра по группе экстремальной физической нагрузки — из второго извлечения: «Five trials involving a total of 598 marathon runners, skiers and soldiers on subarctic exercises yielded a pooled RR of 0.48 (95% CI 0.35 to 0.64)».

## Пункт 7. Полное ПЭТ-КТ / онкомаркеры

- USPSTF 2018 JAMA, DOI 10.1001/jama.2017.21926
  - Фактически открыт: <https://pubmed.ncbi.nlm.nih.gov/29450531/> (в этом запуске успешно вернулось). Заголовок совпал: «Screening for Ovarian Cancer: US Preventive Services Task Force Recommendation Statement», 2018, JAMA, DOI 10.1001/jama.2017.21926. Подтверждено. (Изначально по памяти был указан DOI 10.1001/jama.2018.0938 — неверен; через WebSearch найден корректный DOI и проверен.)
  - Фактически открыт: <https://www.uspreventiveservicestaskforce.org/uspstf/recommendation/ovarian-cancer-screening>. Подтверждено.
  - Цифры (дословно с официальной страницы): «No difference was found in ovarian cancer mortality … with 0.34% in the screening group and 0.29% in the usual care group (relative risk, 1.18 [95% CI, 0.82 to 1.71])»; «Surgery to investigate positive screening test results among women who ultimately did not have ovarian cancer occurred in 0.2% of participants in the UK Pilot CA-125 group, 0.97% … 3.25% of participants in the UKCTOCS ultrasound group, and 3.17% of participants in the PLCO CA-125 plus ultrasound group»; «Up to 15% of these women had major surgical complications»
- Furtado CD et al. 2005 Radiology, DOI 10.1148/radiol.2372041741
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Whole-body CT screening: spectrum of findings and recommendations in 1192 patients», 2005, Radiology. Подтверждено.
  - Цифры: «1030 (86%) of 1192 subjects had at least one abnormal finding»; «Four hundred forty-five (37%) patients received at least one recommendation for additional evaluation»; «most findings were benign by description and required no further evaluation»

## Пункт 8. Фитнес-браслеты

- Jakicic JM et al. 2016 JAMA, DOI 10.1001/jama.2016.12858
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Effect of Wearable Technology Combined With a Lifestyle Intervention on Long-term Weight Loss: The IDEA Randomized Clinical Trial», 2016, JAMA. Подтверждено.
  - Цифры: «estimated mean weight loss, 3.5 kg [95% CI, 2.6-4.5] in the enhanced intervention group and 5.9 kg [95% CI, 5.0-6.8] in the standard intervention group; difference, 2.4 kg [95% CI, 1.0-3.7]; P = .002»; «471 randomized participants»

## Пункт 9. Органические продукты

- Smith-Spangler C et al. 2012 Ann Intern Med, DOI 10.7326/0003-4819-157-5-201209040-00007
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Are organic foods safer or healthier than conventional alternatives?: a systematic review», 2012, Annals of Internal Medicine. Подтверждено.
  - Цифры: «17 studies in humans and 223 studies of nutrient and contaminant levels in foods met inclusion criteria»; «The published literature lacks strong strong evidence that organic foods are significantly more nutritious than conventional foods»; «risk difference, 30%» (остаточные пестициды); «Only 3 human studies examined clinical outcomes, finding no significant differences … for allergic outcomes or symptomatic infection». В аннотации также есть «antibiotic-resistant … risk difference, 33%» — в пункт не вошло. «Обнаружение не равно превышению нормы» — моя формулировка; оригинал говорит о разнице рисков обнаружения остатков, без указания процента превышения норм.

## Пункт 10. БАДы

- Страница пресс-конференции Главного государственного управления по регулированию рынка КНР
  - Фактически открыт: <https://www.samr.gov.cn/tssps/sjdt/tpxw/art/2023/art_4b658b824b1b4b0ba57c09a56cc93aad.html>. Заголовок страницы — «Главное управление рынка проводит тематическую пресс-конференцию о „Руководстве по маркировке предупреждающих надписей на БАД“ и „Положении об управлении каталогом сырья и функций БАД“», пресс-конференция от 20 августа 2019 года, официальный сайт samr.gov.cn. Подтверждено.
  - Оригинал: «保健食品不是药物，不能代替药物治疗疾病»; «警示区面积不少于其所在版面的20%»; «补充膳食营养物质、维持改善机体健康状态或者降低疾病发生风险因素»
  - Не подтверждено: страница самого объявления <https://gkml.samr.gov.cn/nsjg/tssps/201908/t20190820_306116.html> — четыре попытки WebFetch подряд вернули «Socket is closed», страница-перепечатка на gov.cn — 404; в источнике указана только успешно открытая страница пресс-конференции samr.gov.cn.

## Пункт 11. Пробиотики

- Khalesi S et al. 2019 Eur J Clin Nutr, DOI 10.1038/s41430-018-0135-9
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «A review of probiotic supplementation in healthy adults: helpful or hype?», 2019, European Journal of Clinical Nutrition. Подтверждено.
  - Оригинал: «45» исследований; «this review failed to support the ability of probiotics to cause persistent changes in gut microbiota, or improve lipid profile in healthy adults»; изменения микрофлоры — «transient»; показатели с небольшим улучшением — «stool consistency, bowel movement, and vaginal lactobacilli concentration»

## Пункт 12. Холодный душ

- Buijze GA et al. 2016 PLOS ONE, DOI 10.1371/journal.pone.0161749
  - Фактически открыт: <https://journals.plos.org/plosone/doi?id=10.1371/journal.pone.0161749>. Заголовок совпал: «The Effect of Cold Showering on Health and Work: A Randomized Controlled Trial», 2016. Подтверждено.
  - Цифры: «3,018 individuals»; «30, 60, or 90 seconds»; «29% reduction … (IRR: 0.71, P = 0.003)»; «For illness days there was no significant group effect»; «no clinically relevant differences in quality of life, work productivity, anxiety»
- Cain T et al. 2025 PLOS ONE, DOI 10.1371/journal.pone.0317615
  - Фактически открыт: <https://journals.plos.org/plosone/doi?id=10.1371/journal.pone.0317615>. Заголовок совпал: «Effects of cold-water immersion on health and wellbeing: A systematic review and meta-analysis», 2025. Подтверждено.
  - Оригинал: «Eleven randomized controlled trials encompassing 3,177 total participants»; «significant increases in inflammation immediately…and 1 hour post CWI»; «no meaningful immediate or delayed immune changes»; «a significant reduction in stress…12 hours post-CWI»; «current evidence base is constrained by few RCTs, small sample sizes»

## Пункт 13. Детокс / щёлочи

- Klein AV, Kiat H 2015 J Hum Nutr Diet, DOI 10.1111/jhn.12286
  - Фактически открыт: Europe PMC REST. Заголовок совпал: «Detox diets for toxin elimination and weight management: a critical review of the evidence», 2015. Подтверждено.
  - Оригинал: «Although the detox industry is booming, there is very little clinical evidence to support the use of these diets»; «no randomised controlled trials have been conducted to assess the effectiveness of commercial detox diets in humans»
- Fenton TR, Huang T 2016 BMJ Open, DOI 10.1136/bmjopen-2015-010438
  - Фактически открыт: Europe PMC REST (поиск по DOI). Заголовок совпал: «Systematic review of the association between dietary acid load, alkaline water and cancer», 2016, BMJ Open. Подтверждено. (Изначально по памяти был указан DOI 10.1136/bmjopen-2016-010438 — doi.org возвращал 404; WebSearch и Europe PMC дают 2015-010438, исправлено.)
  - Оригинал: «8278 citations were identified, and 252 abstracts were reviewed; 1 study met the inclusion criteria»; «no association between the diet acid load with bladder cancer (OR=1.15: 95% CI 0.86 to 1.55, p=0.36)»; «Promotion of alkaline diet and alkaline water to the public for cancer prevention or treatment is not justified»

## Пункт 14. Восемь стаканов воды в день

- Valtin H 2002 Am J Physiol Regul Integr Comp Physiol, DOI 10.1152/ajpregu.00365.2002
  - Фактически открыт: Europe PMC REST (страница journals.physiology.org вернула 403). Заголовок совпал: «"Drink at least eight glasses of water a day." Really? Is there scientific evidence for "8 x 8"?», Heinz Valtin, 2002. Подтверждено.
  - Оригинал: «No scientific studies were found in support of 8 x 8. Rather, surveys of food and fluid intake on thousands of adults…strongly suggest that such large amounts are not needed»

## Рассмотренные, но не вошедшие кандидаты

- Пероральный коллаген: существующие мета-анализы — малые выборки и часто спонсируются производителями, с тенденцией к положительным результатам; не соответствует критерию раздела «есть данные о неэффективности», не вошло.
- Очистители воздуха/воды: проверка не проводилась, доказательств по жёстким конечным точкам не найдено, не вошло.
- Сам по себе ранний подъём: плохо отделяется от регулярности сна, прямых контролируемых доказательств не найдено, не вошло.
- Многозадачность/«помидор»: прямых доказательств нет, по требованию не вошло.
