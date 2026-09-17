# Запись верификации: раздел 13

Пояснение: все «открытые» URL — это ссылки, по которым WebFetch действительно открыл страницу и в возвращённом оригинале нашёл соответствующее предложение. Квота WebSearch в этой сессии (200/200) была исчерпана к началу работы над разделом, поэтому использовался только WebFetch; Bing / DuckDuckGo / Sogou / Baidu при запросе китайских запросов почти все возвращают нерелевантные результаты или капчу, китайские официальные страницы удавалось открывать только по заранее известным URL или путём обхода каталогов. Журнальные публикации единообразно проверены через Europe PMC REST (по DOI) — для подтверждения названия, авторов, журнала, года и цифр в аннотации; страницы издательств (LWW, Ovid, AHA, SAGE) для скрейпинга возвращают 402/403.

## Журнальные публикации

### Sasson 2010 (пункт 1)
- DOI: 10.1161/CIRCOUTCOMES.109.889576 (doi.org 302 → ahajournals.org 403)
- Открыто: PubMed 20123673 и интерфейс Europe PMC, аннотация согласована.
- Оригинал: «79 studies involving 142,740 patients»; «pooled survival to hospital discharge was 7.6%»; «witnessed by a bystander (6.4% to 13.5%) … who received bystander CPR (3.9% to 16.1%)»; «Although 53% (95% CI, 45.0% to 59.9%) of events were witnessed by a bystander, only 32% (95% CI, 26.7% to 37.8%) received bystander CPR».

### Zheng 2023 BASIC-OHCA (пункт 1)
- В Europe PMC найдено по заголовку: Zheng J, Lv C, Zheng W и др. Incidence, process of care, and outcomes of out-of-hospital cardiac arrest in China: a prospective study of the BASIC-OHCA registry. The Lancet Public Health, 2023. DOI 10.1016/S2468-2667(23)00173-1
- Оригинал: «7121 (20.3%) received bystander cardiopulmonary resuscitation»; «441 (1.2%) of 38,227 survived» (выписка или 30 дней).
- Одновременно попалось Xie X и др. 2023 Circ Cardiovasc Qual Outcomes (DOI 10.1161/circoutcomes.121.008856): выживаемость при выезде скорой 1,15%, в основной текст не вошло.

### Teixeira 2018 (пункт 2)
- DOI 10.1016/j.jamcollsurg.2017.12.016, указанный в задании, в Europe PMC даёт другую статью (Woo Y и др. о раке желудка) — отброшено.
- Поиском по заголовку в Europe PMC найден правильный DOI: 10.1016/j.jamcollsurg.2018.01.047. Teixeira PGR, Brown CVR, Emigh B и др., Texas Tourniquet Study Group. Civilian Prehospital Tourniquet Use Is Associated with Improved Survival in Patients with Peripheral Vascular Injury. J Am Coll Surg 2018.
- Оригинал: «11 Level I trauma centers (January 2011 through December 2016)»; «During 6 years, 1 026 patients with peripheral vascular injuries were admitted»; «Prehospital tourniquets were used in 181 (17.6%) patients»; «Mortality was 5.2% in the non-tourniquet group compared with 3.9% in the tourniquet group»; «the use of tourniquets was found to be independently associated with survival (adjusted odds ratio 5.86; 95% CI 1.41 to 24.47; adjusted p = 0.015)». В черновике по памяти было указано 3,4% против 8,9%, после второй сверки аннотации исправлено.

### Kragh 2009 (пункт 2)
- DOI: 10.1097/SLA.0b013e31818842ba (doi.org 302 → ovid.com 402)
- Открыто через Europe PMC: Kragh JF Jr и др. Survival with emergency tourniquet use to stop bleeding in major limb trauma. Ann Surg 2009.
- Оригинал: 232 пациента, 309 конечностей; «Tourniquet use when shock was absent was strongly associated with survival (90% vs. 10%; P < 0.001)»; догоспитальные 194 человека — летальность 11%, наложенные в приёмном покое 38 — 24%; 5 нуждавшихся, но не получивших жгут — выживаемость 0%, получившие — 87%; «no amputations resulted from tourniquet use alone», кратковременный парез нерва у 4.

### Dow 2019 — руководство Wilderness Medical Society по переохлаждению (пункт 11)
- DOI: 10.1016/j.wem.2019.10.002 (doi.org 302 → sagepub 403; wemjournal.org 301 → sagepub; sciencedirect 403)
- Europe PMC подтвердил заголовок, авторов (Dow J, Giesbrecht GG, Danzl DF и др.), журнал Wilderness & Environmental Medicine, 2019, PMID 31740369, не открытый доступ. Проверена только аннотация, конкретные рекомендации открыть не удалось, в примечании пункта это отмечено.

### Lipman 2019 — руководство Wilderness Medical Society по тепловым заболеваниям (пункт 6)
- DOI: 10.1016/j.wem.2018.10.004 (аналогично 403)
- Europe PMC подтвердил заголовок, авторов (Lipman GS, Gaudio FG, Eifling KP и др.), журнал, 2019, PMID 31221601, не открытый доступ. Проверена только аннотация.

## Китайские официальные документы

### Порядок профилактики и лечения при контакте с возбудителем бешенства (редакция 2023) (пункты 3, 14)
- URL: <https://www.ndcpa.gov.cn/jbkzzx/c100014/common/content/content_1706569159854649344.html>
- Открыт. Издатели: Общий отдел Государственного управления по контролю заболеваний, Канцелярия Национальной комиссии здравоохранения, 2023-09-13.
- Оригинал: «接触或者喂饲动物，或者完好的皮肤被舔舐为 I 级暴露。裸露的皮肤被轻咬……为 Ⅱ 级暴露。单处或者多处贯穿性皮肤咬伤……为 Ⅲ 级暴露»; «用肥皂水（或者其他弱碱性清洁剂）和一定压力的流动清水交替彻底冲洗所有咬伤和抓伤处约 15 分钟»; «判定为 Ⅲ 级暴露者，应处置伤口并注射狂犬病被动免疫制剂和接种狂犬病疫苗»; «狂犬病病死率几乎达 100%，暴露后狂犬病疫苗接种无禁忌症»
- PDF на chinacdc.cn/…/P020240906525421817465.pdf скачивается, но без инструмента OCR не разбирается, не цитируется.

### Гражданский кодекс (пункты 1, 5)
- URL: <https://www.spp.gov.cn/spp/fl/202006/t20200602_463888.shtml> (база законодательства ВНП, тот же, что в разделе 8)
- Открыт, заголовок страницы «Гражданский кодекс КНР».
- Статья 184: «因自愿实施紧急救助行为造成受助人损害的，救助人不承担民事责任。»
- Статья 1032: «自然人享有隐私权。任何组织或者个人不得以刺探、侵扰、泄露、公开等方式侵害他人的隐私权。»
- Статья 1033 (страницы court.gov.cn/zixun/xiangqing/233181.html и tjca.miit.gov.cn сверены): «除法律另有规定或者权利人明确同意外，任何组织或者个人不得实施下列行为：（一）以电话、短信、即时通讯工具、电子邮件、传单等方式侵扰他人的私人生活安宁……»
- Статья 1195: spp, court.gov.cn, miit — возвращённый текст обрывается до этой статьи (ограничение длины); cac.gov.cn с пагинацией _6/_7 — 404; gov.cn content_5516649 — 404; zqdzfy PDF — 404. **Не подтверждено**, в основном тексте отмечено TODO.

### Уголовный кодекс (пункты 5, 15)
- URL: <https://jtgl.beijing.gov.cn/jgj/jgxx/flfg/fl/11033925/index.html> (перепечатка Пекинского управления полиции общественной безопасности, интегрированный текст «по поправке (XI)», тот же, что в разделе 9)
- Открыт.
- Статья 20: «为了使国家、公共利益、本人或者他人的人身、财产和其他权利免受正在进行的不法侵害，而采取的制止不法侵害的行为，对不法侵害人造成损害的，属于正当防卫，不负刑事责任。»
- Статья 263: «以暴力、胁迫或者其他方法抢劫公私财物的，处三年以上十年以下有期徒刑，并处罚金», отягчающие обстоятельства — от десяти лет до смертной казни (по аннотации страницы).
- Статья 274: «敲诈勒索公私财物，数额较大或者多次敲诈勒索的，处三年以下有期徒刑、拘役或者管制，并处或者单处罚金», при крупной сумме — от трёх до десяти лет.

### Закон о противодействии телефонному и интернет-мошенничеству (пункт 4)
- URL: <https://www.spp.gov.cn/spp/fl/202209/t20220902_575631.shtml>
- Открыт, принят 2022-09-02, вступил в силу 2022-12-01.
- Статья 8: «各级人民政府和有关部门应当加强反电信网络诈骗宣传，普及相关法律和知识，提高公众对各类电信网络诈骗方式的防骗意识和识骗能力。»
- Статьи 20, 34 — те же, что в разделе 8.

### Раздел «Приёмы распознавания мошенничества» Управления общественной безопасности провинции Фуцзянь (пункты 4, 5)
- Каталог <http://gat.fujian.gov.cn/ztzl/fjjffpzxrx/spjq/> открыт, каждая статья открыта по списку.
- Мошенничество с «заданиями» (2023-07-03) <http://gat.fujian.gov.cn/ztzl/fjjffpzxrx/spjq/202307/t20230703_6196881.htm>: «以低投入、高回报骗取受害人信任»; «以『任务单未完成』为由拒绝退还本金»; «喊你一起赚钱的大概率是想赚你的钱。如遇到诈骗，请及时拨打 110 报警，手机可下载并注册国家反诈中心 APP»
- Инвестиции и управление капиталом (2023-12-20) …/202312/t20231220_6362145.htm: «犯罪分子组织『水军』在群里扮演投资者，晒出收益误导受害人»; «给予小额返利让受害人尝到甜头，不断诱导加大投资额度»; «不轻信『专家指导』『稳赚不赔』等噱头»
- Кредит (2023-12-07) …/202312/t20231207_6326741.htm: «缴纳一定的保证金，否则不放款，一旦你把钱打过去，对方立即就会把你拉黑»; «贷款并不需要交保证金、做银行流水账，一旦遇上了，一定是假的»
- Подмена под «службу поддержки» (2023-10-20) …/202310/t20231020_6279505.htm: три шага «自报家门，取得初步信任», «制造恐慌，提出解决办法» (влияние на кредитную историю), «催促付款，实施诈骗»
- Подмена под «прокуратуру/полицию» (2023-09-13) …/202309/t20230913_6255863.htm: «公检法机关不存在所谓的『安全账户』，凡是通过电话、QQ、微信、网络等办案、做笔录的『公检法机关』，都是诈骗。» Не соглашаться на «трансляцию экрана».
- «Забой свиньи» (онлайн-романтическое мошенничество) (2023-08-18) …/202308/t20230818_6232030.htm: «对于从未见过面，只见到照片或者视频的『恋人』，不可轻信»
- Замаскированное под «клубнику» задание (2024-03-07) …/202403/t20240307_6410612.htm: «任何时候，不管对方以什么理由借口，让你刷单返现、做任务、做数据的都是骗子»; «一定要保存好证据，及时拨打 110，切勿继续转账»
- 96110 (2023, URL-дата 2023-03-06, дата в аннотации страницы не совпадает с этим; указан только год) …/202303/t20230306_6126156.htm: «来电不轻信，信息不透露，链接不点击，转账多核实»
- «Буква «секс» как красная тряпка» (2026-01-16, …/202601/t20260116_7081388.htm): страница открыта, заголовок и ведомство видны, но текст основной части встроен как base64-картинка, два считывания текста не дали, **не цитируется**.

### Управление по контролю заболеваний провинции Юньнань — материалы о тепловом ударе (пункт 6)
- URL: <https://ynsjkj.yn.gov.cn/html/2026/jikongkepu_0719/2606.html>
- Открыт, заголовок «Появились эти симптомы — возможно, у вас тепловой удар! В тяжёлых случаях может быть смертельно», 2026-07-19.
- Оригинал: «立即将其转移到阴凉通风处»; холодное влажное полотенце; при сохранном сознании — подсоленная вода; «如果症状严重或持续不缓解，应立即拨打急救电话»; летальность теплового удара «极高».

## ВОЗ

### Бешенство (пункт 3)
- <https://www.who.int/zh/news-room/fact-sheets/detail/rabies> (одновременно открыта английская версия)
- Оригинал: «全世界每年估计有 5.9 万人死于狂狂狂病»; «在高达 99% 的人类狂狂狂病病例中，狗是病毒传播的罪魁祸首»; «暴露后立即使用水和肥皂彻底清洗伤口至少 15 分钟»; «清洗伤口，立即接种疫苗，并注射狂狂免疫球蛋白/单克隆抗体» (III степень)

### Укусы животных (пункт 12)
- <https://www.who.int/zh/news-room/fact-sheets/detail/animal-bites> (одновременно открыта английская версия)
- Оригинал: «立即完全固定被咬的身体部位，并迅速送到最近的医疗机构就医»; «避免使用止血带，并避免切割伤口»; «用针对当地蛇种的适当抗蛇毒血清进行治疗»; при укусе собаки «用肥皂和自来水冲洗和清洁伤口 15 分钟»

### Отравление при укусе змеи (пункт 12)
- <https://www.who.int/zh/news-room/fact-sheets/detail/snakebite-envenoming> (английская версия, 2023-09-12)
- Оригинал: «每年约有 81 410 至 137 880 人死于蛇咬伤», ампутации и стойкая инвалидность — около 3-кратного числа погибших; «高质量抗蛇毒血清是防止 или逆转大部分毒蛇咬伤毒性作用的最有效治疗方法»

### Утопление (пункт 8)
- <https://www.who.int/zh/news-room/fact-sheets/detail/drowning> (одновременно открыта английская версия)
- Оригинал: «世界各地每年溺水死亡总数估计为 30 万例»; «92% 的溺水死亡发生在低收入和中等收入国家»; английская версия «fourth leading cause of death for children aged 1–4 years and the third leading cause of death for children aged 5–14 years»; «safe rescue and resuscitation training»

## Официальные страницы федеральных ведомств США (как замена, где китайские страницы не открылись)

### FEMA Ready.gov Home Fires (пункт 7)
- <https://www.ready.gov/home-fires> открыт.
- Оригинал: «Drop down to the floor and crawl low, under any smoke to your exit»; «Before opening a door, feel the doorknob and door. If either is hot, or if there is smoke coming around the door, leave the door closed and use your second way out»; «If you open a door, open it slowly. Be ready to shut it quickly if heavy smoke or fire is present»; «stop, drop and roll»; «If you can't get out, close the door and cover vents and cracks around doors with cloth or tape to keep smoke out. Call 9-1-1»
- Формулировок «не пользоваться лифтом» и «не возвращаться» в оригинале страницы нет — в пункте 7 они даны как общая практика.

### FEMA Ready.gov Earthquakes (пункт 13)
- <https://www.ready.gov/earthquakes> открыт.
- Оригинал: «Drop where you are onto hands and knees»; «Cover your head and neck with one arm and hand»; «Hold until the shaking stops»; «Turn face down and cover your head and neck with a pillow»; «Stay there. Move to an open area away from buildings, trees, streetlights and power lines»; «Pull over and stop. Set your parking brake»; «If you are inside, stay and do not run outside; avoid doorways»; «Expect aftershocks»; «Send a text or bang on a pipe or wall. Cover your mouth with your shirt for protection and instead of shouting, use a whistle»; не пользоваться лифтами в повреждённом здании, не заходить в повреждённые здания.

### NWS Heat Related Illnesses (пункт 6)
- <https://www.weather.gov/safety/heat-illness> открыт.
- Оригинал: тепловой удар — «body temperature above 103°F»; «Call 911 or get the victim to a hospital immediately. Heat stroke is a severe medical emergency», в прохладное место, холодные влажные компрессы; «Do not provide fluids»; тепловое истощение — «Loosen clothing. Apply cool, wet cloths or have person sit in a cool bath», маленькие глотки воды; «Seek immediate medical attention if the person vomits, symptoms worsen or last longer than 1 hour»

### NWS During Extreme Cold (пункт 11)
- <https://www.weather.gov/safety/cold-during> открыт (/safety/cold-hypothermia — 404)
- Оригинал: «If your temperature is 95°F or less, you feel cold and sluggish, or you are having trouble thinking clearly, see a doctor immediately»; «Get medical attention immediately. Move the victim inside to a heated location and begin warming the center of the body first»; «If the person is unconscious, administer CPR»; тёплое питьё, алкоголь «reduces shivering»; обморожение — «Do not use hot water or radiant heat such as a fireplace»

### MedlinePlus Choking (пункт 9)
- <https://medlineplus.gov/ency/article/000047.htm> открыт.
- Оригинал: «Are you choking? Can you speak?»; при сохранном кашле и способности говорить — не вмешиваться; «repeated cycles of 5 back blows followed by 5 abdominal thrusts, until the object comes out or the person becomes unconscious»; при потере сознания — начать СЛР; вызвать 911; для беременных и полных людей — грудные толчки.

### NPS Staying Safe Around Bears (пункт 14)
- <https://www.nps.gov/subjects/bears/safety.htm> открыт.
- Оригинал: «Do NOT run, but if the bear follows, stop and hold your ground. Bears can run as fast as a racehorse both uphill and down»; «Stay calm and remember that most bears do not want to attack you; they usually just want to be left alone»; «Continue to talk to the bear in low tones»; «If the bear is stationary, move away slowly and sideways»; «Make yourselves look as large as possible»; «Do NOT climb a tree. Both grizzlies and black bears can climb trees»; при нападении гризли — «PLAY DEAD. Lay flat on your stomach with your hands clasped behind your neck. Spread your legs»; при нападении чёрного медведя — «DO NOT PLAY DEAD … try to fight back using any object available»

### NPS Mojave / Death Valley Safety (пункт 10)
- <https://www.nps.gov/moja/planyourvisit/safety.htm> открыт: «a minimum of one gallon of water per person, per day; hikers and cyclists should carry two gallons per person, per day»; «Let someone know your trip route, destination, and return date, vehicle make and license plate. Cell phone coverage is sporadic»; «Avoid strenuous activity during times of extreme heat»
- <https://www.nps.gov/deva/planyourvisit/safety.htm> открыт: «DRINK plenty of water, at least one gallon a day»; «DO NOT hike in the valley/lower elevations when it is hot!»; «limited to no cell phone service», рекомендуется спутниковый телефон.
- Формулировки «если машина сломалась — оставайтесь рядом с машиной» ни в одной из страниц нет (страница Joshua Tree — 404), поэтому пункт отнесён к уровню C.

## Не открыто или не извлечено, не цитировано
- Министерство общественной безопасности mps.gov.cn, m.mps.gov.cn: всю сессию HTTP 521; доля видов мошенничества отмечена TODO.
- Управление пожарно-спасательной службы 119.gov.cn: 405/412; qmxfkp подкаталог 412.
- Национальная комиссия здравоохранения nhc.gov.cn — страница «高温中暑预防知识要点» (/wjw/jbyfykz/201007/1edb19b7dd4e4bdf8da5ea45f4a64e23.shtml) — 412 (http и https).
- Китайский сейсмологический центр <https://www.cea.gov.cn/cea/dzpd/dzcs/5758823/index.html> (о самоспасении при землетрясении, 2024-05-10, Хайнаньское землетрясение) и …/5758835/index.html (Бэйцзинский сейсмологический центр): страницы открыты, заголовок и дата видны, но текст рендерится скриптом — извлечь не удалось.
- Министерство по чрезвычайным ситуациям mem.gov.cn/kp: разделы бытовой безопасности и стихийных бедствий открываются, но каждая ссылка указывает на mp.weixin.qq.com (аккаунт в WeChat) — по правилам не цитируется; отдельных страниц по газу, поражению током, заблудиться нет.
- Китайский Красный Крест redcross.org.cn: главная открыта, раздел первой помощи содержит только новости об обучении — нет страниц по остановке кровотечения, утоплению, приёму Хеймлиха.
- Китайский CDC chinacdc.cn: страницы тем здоровья открываются, разделы хронических болезней и травматизма возвращают пустые страницы.
- Официальный сайт BeiDou beidou.gov.cn/xt/xtjs/: Socket is closed.
- ВОЗ heat-and-health и first-aid Q&A по змеиным укусам: 404.
- CDC extreme-cold, heat-health, drowning — 404 или без подходящего оригинала по спасению.
- Поисковый интерфейс gov.cn (sousuo.www.gov.cn/search-gov/data): `t=zhengce` отдаёт, но по запросам раздела 13 нет результатов; `t=xinwen` / `govall` — «没有找到相关结果».
- Кандидаты «поражение током» и «утечка газа»: ни одного открываемого официального оригинала не найдено — **не вошли**.
- Минимальная комплектация аптечки: включена в стоимость пунктов 2 и 11, отдельным пунктом не выносится.

## 2026-09-07, дополнительная проверка: переписан пункт о землетрясениях (пункт 13 раздела 13)

Переписан по результатам читательского отзыва: «лечь, найти укрытие, держаться — не выбегать» не подходит для внезапных сильных толчков с возможным обрушением; есть случаи, когда быстро выбежавшие выживали.

Открытые и проверенные оригиналы:

1. Europe PMC запись MED/1600585, <https://europepmc.org/article/MED/1600585>
   Armenian HK, Noji EK, Oganesian AP (1992). A case-control study of injuries arising from the earthquake in Armenia, 1988. Bulletin of the World Health Organization, 70(2), 251-257.
   Оригинал аннотации дословно: «A total of 189 such individuals were identified through neighbourhood polyclinics in the city of Leninakan and 159 noninjured controls were selected from the same neighbourhoods.» / «98% of persons who were hospitalized with injuries were inside a building at the time of the earthquake, compared with 83% of the controls (odds ratio = 12.20, 95% confidence interval (CI) = 3.62-63.79).» / «The odds ratio of injuries for individuals who were in a building that had five or more floors, compared with those in lower buildings, was 3.65 (95% CI = 2.12-6.33).» / «Leaving buildings after the first shock of the earthquake was a protective behaviour. The odds ratio for those staying indoors compared with those who ran out was 4.40 (95% CI = 2.24-8.71).»
   Подтверждено: заголовок, авторы, журнал, год, том-страницы, три отношения шансов с доверительными интервалами.
   Ограничения (отмечены в примечании пункта): контрольная группа — не пострадавшие из того же квартала, погибшие не включены; в аннотации не сказано, была ли поправка на этажность.

2. Mahue-Giangreco M, Mack W, Seligson H, Bourque LB (2001). Annals of Epidemiology, 11(5), 347-357. <https://doi.org/10.1016/s1047-2797(01)00220-4> (PMID 11399450)
   В аннотации упомянуто, что «the current recommendation of 'duck, cover, and hold'» ночью и в постели не обязательно оптимально, и что «reaching for or catching objects, bracing, or holding onto perceived stable objects may increase risk for more serious injury». Подтверждены заголовок, авторы, журнал, том-страницы, DOI.

3. US FEMA Ready.gov. Earthquakes. <https://www.ready.gov/earthquakes>
   2026-09-07 повторная проверка, оригинал раздела «During»: «Drop where you are onto hands and knees.» / «Cover your head and neck with one arm and hand.» / «Hold until the shaking stops.» / «If you are inside, stay and do not run outside; avoid doorways.»
   Страница не делает исключения для зданий без антисейсмической защиты, кирпичных или саманных построек.

Не получены: страницы Китайского сейсмологического центра с научно-популярным текстом (рендеринг скриптом, текст не извлекается), TODO остаётся.
Не принято: анализ с коротких видеоплатформ (не отвечает правилам цитирования); упомянутые читателем «конкретные случаи, когда почти все выжили потому, что быстро выбежали» — официальный или журнальный источник найти не удалось, в пункт не вошло.

### 2026-09-07, повторная проверка: получен оригинал Китайского сейсмологического центра (расшифровка субтитров видео), TODO снят

Причины двух предыдущих неудач стали понятны: в статьях раздела «地震科普» Китайского сейсмологического центра основной текст не текстовый, а встроенный mp4. В сыром HTML у элемента `id="news_content"` есть только `<video src="...mp4">`, поэтому в браузере страница тоже отображается пустой.

Изменённый путь: извлечение кадров и чтение субтитров:
- страница <https://www.cea.gov.cn/cea/dzpd/dzcs/5537260/index.html> (заголовок «При землетрясении — прятаться или бежать?», титр «Сейсмологическое управление провинции Аньхой», раздел сейсмологической популяризации Китайского сейсмологического центра)
- видео <https://www.cea.gov.cn/cea/dzpd/dzcs/5537260/2020051215493612585.mp4>, длительность 2 мин 33 с, 1920×1080
- ffmpeg с шагом 1,5–3 секунды на кадр, кадры со склейкой субтитров, покадровое чтение

Расшифрованные оригинальные субтитры (по порядку появления, дословно):
«今天我们就来聊一聊» «既要因地制宜» «也要因人而异» «综合考虑建筑物的抗震能力» «人员所处位置、体能、室外环境» «具体情况具体分析»
«地震时 如果在户外» «应该第一时间疏散到空旷的地方避震» «避开容易倒塌的高大建筑物» «注意远离高架桥、电线杆、玻璃幕墙» «广告牌以及其他高空悬挂物» «还要注意远离化工厂、危险品仓库等»
«这里指的是在符合抗震设防要求的建筑内»
карточка-заголовок: «震时就近躲避» «震后迅速撤离»
«地震发生时» «建筑物整体垮塌的可能性较小» «即使在大地震中彻底垮塌的建筑物也是少数»
«绝大多数的建筑物只是遭受不同程度的破坏» «坠落的建筑构件及装饰物品» «才是对生命安全最大的威胁»
«震时无保护措施的盲目乱跑» «反而容易被坠落的天花板、吊灯（扇）等物品砸伤»
«躲也要讲究科学» «的避震口诀要时刻牢记» «用手或者其他软物保护好头颈部» «并牢牢地抓住桌腿»
«这样才能保证在晃动过程中» «从而达到遮蔽保护的效果»
«则应迅速贴紧承重墙蹲伏» «同时保护好头部» «注意避开外墙、窗户、阳台等等»

Ключевой момент: официальная формула «при землетрясении — спрятаться на месте, после — быстро покинуть» имеет прямые условия — «в здании, отвечающем требованиям антисейсмической защиты», и в начале указано «действовать по обстановке» / «с учётом конкретного человека» / «учитывая антисейсмическую способность здания». Это согласуется с подходом пункта — разбирать землетрясение по типу здания, поэтому пункт переписан с указанием этого ролика как основного источника, отметка TODO (ожидается проверка: оригинал Китайского сейсмологического центра) снята.
Ролик отдельно не рассматривает одноэтажные дома и здания без антисейсмической защиты, поэтому в пункте формулировка «в старом доме — выбежать» опирается на армянское исследование и помечена как спорная.
