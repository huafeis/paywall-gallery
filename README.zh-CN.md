# Open Paywall Gallery

## 语言版本

- [English](README.md)
- [简体中文](README.zh-CN.md)

由 <a href="https://www.paywallpro.app/?utm_source=github&utm_medium=open_dataset&utm_campaign=paywall_gallery" target="_blank" rel="noopener noreferrer">PaywallPro</a> 发布的开放、精选 iOS App 付费墙与 Onboarding 案例数据集。

你可以通过这个仓库研究头部 iOS App 如何设计付费墙、设置价格、使用免费试用、展示订阅权益、设计 Onboarding 流程，并在不同品类中实现订阅变现。

如果你希望我们持续开放更多付费墙和 Onboarding 案例，欢迎 Star 这个仓库。

---

## 什么是 PaywallPro？

PaywallPro 是一个面向 App 开发者、产品经理、增长团队和设计师的订阅智能分析平台。

它帮助团队研究真实 iOS App 的付费墙、Onboarding 流程、定价模型、历史版本变化和变现数据信号。

PaywallPro 目前追踪：

- 46,000+ iOS 付费墙截图
- 2,000+ Onboarding 流程
- 付费墙历史版本
- 定价与试用变化
- MRR、RPD、ARPU 和订阅基准等收入信号

---

## 为什么我们做这个仓库？

订阅 App 正在快速增长，但很多团队在做付费墙和定价决策时，依然主要依赖经验、审美判断，或者孤立的 A/B 测试。

Open Paywall Gallery 希望帮助开发者在设计、开发或测试之前，先研究真实的付费墙案例。

你可以用它理解：

- 头部 App 如何呈现订阅价值
- 不同价格档位如何组织
- 免费试用如何被包装和强调
- Onboarding 如何为购买转化做铺垫
- 月付与年付方案如何建立价格锚点
- 不同品类的付费墙模式有什么差异
- 真实 App 中可以观察到哪些变现信号

---

## 关于这个仓库

`paywall-gallery` 是一个开放的 iOS App 付费墙与 Onboarding 预览数据集，以机器可读的 Markdown 文件形式发布。

它是 PaywallPro 数据库中的精选子集，设计目标是：

- 免费访问，无需注册
- 机器可读，使用结构化 frontmatter，方便程序化读取
- 易于浏览，包含人工可读的摘要和预览截图
- 适合产品研究、定价研究、UX 参考和增长分析

当前评审版本：500 个 App。目标公开版本：Top 500 iOS 订阅 App，并持续扩展。

---

## 这个仓库包含什么？

- 代表性的付费墙截图
- 可用时提供 Onboarding 预览
- 简洁的 App 案例页面
- 定价模型摘要
- 付费墙模式分类
- 部分公开的变现数据信号
- 品类索引
- 跳转到 PaywallPro 查看更多信息的链接

---

## 哪些内容保留在 PaywallPro 中？

这个仓库提供每个 App 的精选公开预览。

完整的 PaywallPro 产品包含：

- 完整付费墙截图集
- 完整 Onboarding 流程
- 所有历史付费墙版本
- 逐版本变化记录
- 改版前后的付费墙对比
- 历史定价实验
- A/B 对比参考
- 收入、MRR、RPD、ARPU 和排名信号
- 按品类、地区、定价模型和 App 类型筛选的高级能力

查看完整数据库：

<a href="https://www.paywallpro.app/?utm_source=github&utm_medium=open_dataset&utm_campaign=paywall_gallery" target="_blank" rel="noopener noreferrer">https://www.paywallpro.app</a>

---

## 数据格式

每个 App 条目位于：

```txt
apps/{app-name}-{app_id}.md
```

字段说明请查看 [Data Dictionary](docs/data-dictionary.md)。

---

## 代表性 App

| App | 品类 | 预估 MRR | 付费墙模式 | 页面 |
|---|---|---:|---|---|
| Snapchat | Photo & Video | $7.83M | No Free Trial - Soft Paywall | [打开](apps/snapchat-447188370.md) |
| Life360: Stay Connected & Safe | Social Networking | $4.50M | Free Trial - Soft Paywall | [打开](apps/life360-stay-connected-and-safe-384830320.md) |
| Grindr - Gay Dating & Chat | Social Networking | $3.10M | No Free Trial - Soft Paywall | [打开](apps/grindr-gay-dating-and-chat-319881193.md) |
| YouTube | Photo & Video | $3.07M | No Free Trial - Soft Paywall | [打开](apps/youtube-544007664.md) |
| Google Photos: Backup & Edit | Photo & Video | $2.77M | No Free Trial - Soft Paywall | [打开](apps/google-photos-backup-and-edit-962194608.md) |
| Amazon Music: Songs & Podcasts | Music | $2.58M | Free Trial - Soft Paywall | [打开](apps/amazon-music-songs-and-podcasts-510855668.md) |
| Bumble Dating App: Meet & Date | Lifestyle | $2.57M | Credit Paywall | [打开](apps/bumble-dating-app-meet-and-date-930441707.md) |
| GameChanger | Sports | $2.54M | Free Trial - Soft Paywall | [打开](apps/gamechanger-1308415878.md) |
| X | News | $2.48M | No Free Trial - Soft Paywall | [打开](apps/x-333903271.md) |
| Telegram Messenger | Social Networking | $2.13M | No Free Trial - Soft Paywall | [打开](apps/telegram-messenger-686449807.md) |
| Dropbox: Cloud Storage Backup | Productivity | $2.09M | Free Trial - Soft Paywall | [打开](apps/dropbox-cloud-storage-backup-327630330.md) |
| NFL | Sports | $2.04M | No Free Trial - Soft Paywall | [打开](apps/nfl-389781154.md) |
| SoundCloud: The Music You Love | Music | $1.71M | No Free Trial - Soft Paywall | [打开](apps/soundcloud-the-music-you-love-336353151.md) |
| BIGO LIVE-Live Stream, Go Live | Social Networking | $1.65M | No Free Trial - Soft Paywall | [打开](apps/bigo-live-live-stream-go-live-1077137248.md) |
| Adobe Acrobat Reader: Edit PDF | Business | $1.61M | Free Trial - Soft Paywall | [打开](apps/adobe-acrobat-reader-edit-pdf-469337564.md) |
| NYTimes: US and Global News | News | $1.48M | No Free Trial - Soft Paywall | [打开](apps/nytimes-us-and-global-news-284862083.md) |
| FaceApp: Perfect Face Editor | Photo & Video | $1.45M | Free Trial - Soft Paywall | [打开](apps/faceapp-perfect-face-editor-1180884341.md) |
| Wyze - Never Wonder | Lifestyle | $1.45M | Free Trial - Soft Paywall | [打开](apps/wyze-never-wonder-1288415553.md) |
| MileIQ: Mileage Tracker & Log | Finance | $1.26M | Free Trial - Soft Paywall | [打开](apps/mileiq-mileage-tracker-and-log-578830929.md) |
| Lingokids: Games & Shows | Education | $1.16M | No Free Trial - Soft Paywall | [打开](apps/lingokids-games-and-shows-1002043426.md) |
| Quizlet: More than Flashcards | Education | $1.16M | Free Trial - Soft Paywall | [打开](apps/quizlet-more-than-flashcards-546473125.md) |
| TIDAL Music: HiFi Sound | Music | $1.03M | Free Trial - Soft Paywall | [打开](apps/tidal-music-hifi-sound-913943275.md) |
| Peloton: Fitness & Workouts | Health & Fitness | $1.01M | No Free Trial - Soft Paywall | [打开](apps/peloton-fitness-and-workouts-792750948.md) |
| Lightroom: AI Photo Editor | Photo & Video | $1.01M | Free Trial - Soft Paywall | [打开](apps/lightroom-ai-photo-editor-878783582.md) |
| Hily Dating App: Meet. Date. | Lifestyle | $999.74K | No Free Trial - Soft Paywall | [打开](apps/hily-dating-app-meet-date-1250946975.md) |
| PictureThis - Plant Identifier | Education | $983.15K | Free Trial - Soft Paywall | [打开](apps/picturethis-plant-identifier-1252497129.md) |
| iScanner: PDF Document Scanner | Business | $976.93K | Free Trial - Soft Paywall | [打开](apps/iscanner-pdf-document-scanner-1040093707.md) |
| Tinder Dating App: Date & Chat | Lifestyle | $921.50K | No Free Trial - Soft Paywall | [打开](apps/tinder-dating-app-date-and-chat-547702041.md) |
| epocrates: Drug Info & Pill ID | Medical | $908.38K | Free Trial - Soft Paywall | [打开](apps/epocrates-drug-info-and-pill-id-281935788.md) |
| MLB | Sports | $870.76K | No Free Trial - Soft Paywall | [打开](apps/mlb-493619333.md) |
| Splice - Video Editor & Maker | Photo & Video | $853.22K | Free Trial - Soft Paywall | [打开](apps/splice-video-editor-and-maker-409838725.md) |
| Simply Piano: Learn Piano Fast | Education | $852.93K | Free Trial - Soft Paywall | [打开](apps/simply-piano-learn-piano-fast-1019442026.md) |
| NordVPN: VPN Fast & Secure | Utilities | $845.33K | No Free Trial - Soft Paywall | [打开](apps/nordvpn-vpn-fast-and-secure-905953485.md) |
| Intuit QuickBooks for Business | Business | $835.84K | Free Trial - Soft Paywall | [打开](apps/intuit-quickbooks-for-business-584606479.md) |
| Yubo: Chat Meet & Make Friends | Social Networking | $807.31K | No Free Trial - Soft Paywall | [打开](apps/yubo-chat-meet-and-make-friends-1038653883.md) |
| Ultimate Guitar: Chords & Tabs | Music | $766.57K | Free Trial - Soft Paywall | [打开](apps/ultimate-guitar-chords-and-tabs-357828853.md) |
| Paramount+ | Entertainment | $756.00K | No Free Trial - Soft Paywall | [打开](apps/paramount-530168168.md) |
| PURE: Open-Minded Dating App | Lifestyle | $752.12K | No Free Trial - Soft Paywall | [打开](apps/pure-open-minded-dating-app-690661663.md) |
| Suno - AI Songs & Music | Music | $743.32K | No Free Trial - Soft Paywall | [打开](apps/suno-ai-songs-and-music-6480136315.md) |
| Text Me - Phone Call + Texting | Social Networking | $727.67K | No Free Trial - Soft Paywall | [打开](apps/text-me-phone-call-texting-514485964.md) |
| Fambase: Live & Group Chat | Utilities | $726.99K | No Free Trial - Soft Paywall | [打开](apps/fambase-live-and-group-chat-1580059320.md) |
| ClassDojo | Education | $722.02K | Free Trial - Soft Paywall | [打开](apps/classdojo-552602056.md) |
| Flighty – Live Flight Tracker | Travel | $718.66K | No Free Trial - Soft Paywall | [打开](apps/flighty-live-flight-tracker-1358823008.md) |
| Hallow: Prayer & Meditation | Reference | $672.17K | Free Trial - Soft Paywall | [打开](apps/hallow-prayer-and-meditation-1405323394.md) |
| Taimi: LGBTQ+ Dating & Meet Up | Social Networking | $653.64K | No Free Trial - Soft Paywall | [打开](apps/taimi-lgbtq-dating-and-meet-up-1282966364.md) |
| Zoom Workplace | Business | $644.96K | Free Trial - Soft Paywall | [打开](apps/zoom-workplace-546505307.md) |
| Joi - Live Stream | Social Networking | $640.86K | Free Trial - Soft Paywall | [打开](apps/joi-live-stream-1497699883.md) |
| Arlo Secure: Home Security | Lifestyle | $639.79K | No Free Trial - Soft Paywall | [打开](apps/arlo-secure-home-security-1459289784.md) |
| Speak: Language Learning | Education | $597.05K | Free Trial - Soft Paywall | [打开](apps/speak-language-learning-1286609883.md) |
| Peacock TV: Stream TV & Movies | Entertainment | $591.92K | No Free Trial - Soft Paywall | [打开](apps/peacock-tv-stream-tv-and-movies-1508186374.md) |
| The League: Intelligent Dating | Lifestyle | $589.13K | No Free Trial - Soft Paywall | [打开](apps/the-league-intelligent-dating-893653132.md) |
| Text Free: Second Phone Number | Social Networking | $586.73K | No Free Trial - Soft Paywall | [打开](apps/text-free-second-phone-number-399355755.md) |
| Gauth: AI Study Companion | Education | $582.84K | Free Trial - Soft Paywall | [打开](apps/gauth-ai-study-companion-1542571008.md) |
| Copilot: Track & Budget Money | Finance | $581.53K | Free Trial - Soft Paywall | [打开](apps/copilot-track-and-budget-money-1447330651.md) |
| YouTube Music | Music | $576.01K | No Free Trial - Soft Paywall | [打开](apps/youtube-music-1017492454.md) |
| Norton 360 Security & VPN | Utilities | $572.85K | Free Trial - Soft Paywall | [打开](apps/norton-360-security-and-vpn-1278474169.md) |
| Grammarly: AI Keyboard & Notes | Productivity | $564.58K | Free Trial - Soft Paywall | [打开](apps/grammarly-ai-keyboard-and-notes-1158877342.md) |
| Pimsleur \| Language Learning | Education | $564.34K | No Free Trial - Soft Paywall | [打开](apps/pimsleur-language-learning-1405735469.md) |
| FAX from iPhone: Send Doc App | Business | $559.61K | No Free Trial - Soft Paywall | [打开](apps/fax-from-iphone-send-doc-app-978931264.md) |
| SiriusXM: Music, Sports & News | Music | $525.95K | Free Trial - Soft Paywall | [打开](apps/siriusxm-music-sports-and-news-317951436.md) |
| Retake AI Face & Selfie Editor | Photo & Video | $506.20K | Free Trial - Soft Paywall | [打开](apps/retake-ai-face-and-selfie-editor-6466298983.md) |
| HBO Max: Stream Movies & TV | Entertainment | $474.78K | No Free Trial - Soft Paywall | [打开](apps/hbo-max-stream-movies-and-tv-1666653815.md) |
| 18Birdies: Golf GPS Tracker | Sports | $459.84K | Free Trial - Soft Paywall | [打开](apps/18birdies-golf-gps-tracker-892700751.md) |
| MacroFactor - Macro Tracker | Health & Fitness | $448.73K | No Free Trial - Soft Paywall | [打开](apps/macrofactor-macro-tracker-1553503471.md) |
| Elevate - Brain Training Games | Education | $437.34K | Free Trial - Soft Paywall | [打开](apps/elevate-brain-training-games-875063456.md) |
| Kiddopia: Kids Learning Games | Education | $432.37K | No Free Trial - Soft Paywall | [打开](apps/kiddopia-kids-learning-games-1223397201.md) |
| Citizen: Safety & Live Video | News | $416.35K | Free Trial - Soft Paywall | [打开](apps/citizen-safety-and-live-video-1039889567.md) |
| iHeart: Radio, Music, Podcasts | Music | $408.71K | Free Trial - Soft Paywall | [打开](apps/iheart-radio-music-podcasts-290638154.md) |
| Finch: Self-Care Pet | Health & Fitness | $398.93K | Free Trial - Soft Paywall | [打开](apps/finch-self-care-pet-1528595748.md) |
| TP-Link Tapo | Lifestyle | $397.31K | No Free Trial - Soft Paywall | [打开](apps/tp-link-tapo-1472718009.md) |
| ReciMe: Recipes & Meal Planner | Food & Drink | $383.01K | Free Trial - Soft Paywall | [打开](apps/recime-recipes-and-meal-planner-1593779280.md) |
| VSCO: Photo & Video Editor | Photo & Video | $378.78K | Free Trial - Soft Paywall | [打开](apps/vsco-photo-and-video-editor-588013838.md) |
| Huckleberry: Baby & Child | Medical | $377.92K | No Free Trial - Soft Paywall | [打开](apps/huckleberry-baby-and-child-1169136078.md) |
| Headspace: Sleep & Meditation | Health & Fitness | $373.54K | Free Trial - Soft Paywall | [打开](apps/headspace-sleep-and-meditation-493145008.md) |
| Invoice Maker - Invoice Fly | Business | $372.36K | Free Trial - Soft Paywall | [打开](apps/invoice-maker-invoice-fly-1606911248.md) |
| Blinkist: Book Summaries Daily | Education | $370.73K | No Free Trial - Soft Paywall | [打开](apps/blinkist-book-summaries-daily-568839295.md) |
| Flightradar24 \| Flight Tracker | Travel | $350.32K | No Free Trial - Soft Paywall | [打开](apps/flightradar24-flight-tracker-382233851.md) |
| Early Learning Academy | Education | $347.58K | Free Trial - Soft Paywall | [打开](apps/early-learning-academy-586328581.md) |
| Solid Starts: Baby First Foods | Education | $336.88K | Free Trial - Soft Paywall | [打开](apps/solid-starts-baby-first-foods-1564189151.md) |
| BandLab – Music Maker & Beats | Music | $336.62K | Free Trial - Soft Paywall | [打开](apps/bandlab-music-maker-and-beats-968585775.md) |
| Invoice Simple: Invoice Maker | Business | $336.09K | No Free Trial - Soft Paywall | [打开](apps/invoice-simple-invoice-maker-694831622.md) |
| CARFAX - New & Used Cars | Shopping | $331.68K | No Free Trial - Soft Paywall | [打开](apps/carfax-new-and-used-cars-479267592.md) |
| Insight Timer: Meditate, Sleep | Health & Fitness | $325.16K | Free Trial - Soft Paywall | [打开](apps/insight-timer-meditate-sleep-337472899.md) |
| Marco Polo - Video Messenger | Social Networking | $321.44K | Free Trial - Soft Paywall | [打开](apps/marco-polo-video-messenger-912561374.md) |
| Bloomberg: Business News Daily | News | $320.84K | No Free Trial - Soft Paywall | [打开](apps/bloomberg-business-news-daily-281941097.md) |
| Crunchyroll | Entertainment | $315.45K | No Free Trial - Soft Paywall | [打开](apps/crunchyroll-329913454.md) |
| Ancestry: Family History & DNA | Reference | $308.26K | Free Trial - Soft Paywall | [打开](apps/ancestry-family-history-and-dna-349554263.md) |
| Tezza: Aesthetic Photo Editor | Photo & Video | $305.86K | Free Trial - Soft Paywall | [打开](apps/tezza-aesthetic-photo-editor-1393061654.md) |
| PlantIn: Plant Identifier・Care | Education | $305.67K | Free Trial - Soft Paywall | [打开](apps/plantin-plant-identifier-care-1527399597.md) |
| Slopes: Ski & Snowboard | Sports | $304.82K | Free Trial - Soft Paywall | [打开](apps/slopes-ski-and-snowboard-643351983.md) |
| Fishbrain - Fishing App | Sports | $303.73K | Free Trial - Soft Paywall | [打开](apps/fishbrain-fishing-app-477967747.md) |
| GoPro Quik | Photo & Video | $301.04K | No Free Trial - Soft Paywall | [打开](apps/gopro-quik-561350520.md) |
| TuneIn Radio: Music & Sports | Music | $300.60K | Free Trial - Soft Paywall | [打开](apps/tunein-radio-music-and-sports-418987775.md) |
| Willow - Watch Live Cricket | Sports | $300.55K | No Free Trial - Soft Paywall | [打开](apps/willow-watch-live-cricket-370916083.md) |
| Epic - Kids' Books & Reading | Education | $300.28K | Free Trial - Soft Paywall | [打开](apps/epic-kids-books-and-reading-719219382.md) |
| Keiki Learning games for Kids | Education | $298.82K | Free Trial - Soft Paywall | [打开](apps/keiki-learning-games-for-kids-1508098273.md) |
| Plenty of Fish : Dating App | Social Networking | $291.24K | No Free Trial - Soft Paywall | [打开](apps/plenty-of-fish-dating-app-389638243.md) |
| CoinSnap: Coin Identifier | Reference | $280.63K | Free Trial - Soft Paywall | [打开](apps/coinsnap-coin-identifier-1634551626.md) |
| Goodnotes: AI Notes, Docs, PDF | Productivity | $279.75K | Free Trial - Soft Paywall | [打开](apps/goodnotes-ai-notes-docs-pdf-1444383602.md) |
| Gaze: Live Video Chat App | Social Networking | $279.35K | No Free Trial - Soft Paywall | [打开](apps/gaze-live-video-chat-app-1506577189.md) |
| Simply Guitar - Learn Guitar | Education | $268.66K | Free Trial - Soft Paywall | [打开](apps/simply-guitar-learn-guitar-1476695335.md) |
| Vocabulary - Learn words daily | Education | $268.37K | Free Trial - Soft Paywall | [打开](apps/vocabulary-learn-words-daily-1084540807.md) |
| Cronometer: Calorie Counter | Health & Fitness | $264.83K | No Free Trial - Soft Paywall | [打开](apps/cronometer-calorie-counter-1145935738.md) |
| Adobe Scan: PDF & OCR Scanner | Business | $264.07K | Free Trial - Soft Paywall | [打开](apps/adobe-scan-pdf-and-ocr-scanner-1199564834.md) |
| PicCollage: Magic Photo Editor | Photo & Video | $260.58K | Free Trial - Soft Paywall | [打开](apps/piccollage-magic-photo-editor-448639966.md) |
| IMVU: Fun 3D Avatar Chat Game | Social Networking | $258.66K | No Free Trial - Soft Paywall | [打开](apps/imvu-fun-3d-avatar-chat-game-919745844.md) |
| Paperless Post: Invitations | Lifestyle | $255.41K | Currency Paywall | [打开](apps/paperless-post-invitations-489940389.md) |
| Sweat: Fitness App For Women | Health & Fitness | $254.50K | Free Trial - Soft Paywall | [打开](apps/sweat-fitness-app-for-women-1049234587.md) |
| GuitarTuna: Tune & Play Guitar | Music | $253.03K | Free Trial - Soft Paywall | [打开](apps/guitartuna-tune-and-play-guitar-527588389.md) |
| InPulse - Heart Rate Monitor | Health & Fitness | $248.57K | Free Trial - Soft Paywall | [打开](apps/inpulse-heart-rate-monitor-1489944782.md) |
| Calorie Counter & Food Tracker | Health & Fitness | $246.63K | No Free Trial - Soft Paywall | [打开](apps/calorie-counter-and-food-tracker-6474290049.md) |
| Natural Cycles Fertility App | Health & Fitness | $243.99K | No Free Trial - Soft Paywall | [打开](apps/natural-cycles-fertility-app-765535549.md) |
| Solvely - AI Study Tools | Education | $243.61K | Free Trial - Soft Paywall | [打开](apps/solvely-ai-study-tools-6446930976.md) |
| Zwift: Indoor Cycling Fitness | Health & Fitness | $242.38K | Free Trial - Soft Paywall | [打开](apps/zwift-indoor-cycling-fitness-1134655040.md) |
| Burner: Second Phone Number | Utilities | $242.13K | Free Trial - Hard Paywall | [打开](apps/burner-second-phone-number-505800761.md) |
| Audible: Audiobooks & Podcasts | Books | $241.79K | No Free Trial - Soft Paywall | [打开](apps/audible-audiobooks-and-podcasts-379693831.md) |
| OkCupid Dating: Date Singles | Lifestyle | $241.74K | No Free Trial - Soft Paywall | [打开](apps/okcupid-dating-date-singles-338701294.md) |
| Motivation - Daily quotes | Health & Fitness | $239.89K | Free Trial - Soft Paywall | [打开](apps/motivation-daily-quotes-876080126.md) |
| CapCut: Photo & Video Editor | Photo & Video | $239.84K | Free Trial - Soft Paywall | [打开](apps/capcut-photo-and-video-editor-1500855883.md) |
| Co–Star Personalized Astrology | Lifestyle | $238.23K | No Free Trial - Soft Paywall | [打开](apps/co-star-personalized-astrology-1264782561.md) |
| Washington Post | News | $236.94K | No Free Trial - Soft Paywall | [打开](apps/washington-post-352509417.md) |
| KICK - Live Streaming | Photo & Video | $236.25K | Currency Paywall | [打开](apps/kick-live-streaming-6446202561.md) |
| Smule: Sing & Duet | Music | $232.62K | Free Trial - Soft Paywall | [打开](apps/smule-sing-and-duet-509993510.md) |
| Package Tracker - pkge Mobile | Business | $232.35K | Free Trial - Soft Paywall | [打开](apps/package-tracker-pkge-mobile-1397865865.md) |
| iFIT Workouts | Health & Fitness | $232.07K | No Free Trial - Soft Paywall | [打开](apps/ifit-workouts-1274601042.md) |
| Hulu: Stream TV shows & movies | Entertainment | $231.37K | No Free Trial - Soft Paywall | [打开](apps/hulu-stream-tv-shows-and-movies-376510438.md) |
| YNAB | Finance | $227.83K | Free Trial - Soft Paywall | [打开](apps/ynab-1010865877.md) |
| LazyFit: Workout For Beginners | Health & Fitness | $224.82K | Free Trial - Soft Paywall | [打开](apps/lazyfit-workout-for-beginners-1669413773.md) |
| Instories: AI Photo & Video | Photo & Video | $224.69K | Free Trial - Soft Paywall | [打开](apps/instories-ai-photo-and-video-1454762989.md) |
| VPN - Super Unlimited Proxy | Productivity | $223.73K | Free Trial - Soft Paywall | [打开](apps/vpn-super-unlimited-proxy-1370293473.md) |
| Zutobi: Permit & Driving Prep | Education | $222.87K | Free Trial - Soft Paywall | [打开](apps/zutobi-permit-and-driving-prep-1394069110.md) |
| Photomath | Education | $221.34K | Free Trial - Soft Paywall | [打开](apps/photomath-919087726.md) |
| SnoreLab : Record Your Snoring | Medical | $220.45K | Free Trial - Soft Paywall | [打开](apps/snorelab-record-your-snoring-529443604.md) |
| ExpressVPN · Secure & Fast VPN | Utilities | $219.57K | Free Trial - Soft Paywall | [打开](apps/expressvpn-secure-and-fast-vpn-886492891.md) |
| Gmail - Email by Google | Productivity | $219.55K | No Free Trial - Soft Paywall | [打开](apps/gmail-email-by-google-422689480.md) |
| Microsoft OneDrive | Productivity | $217.81K | No Free Trial - Soft Paywall | [打开](apps/microsoft-onedrive-477537958.md) |
| Speech Blubs: Language Therapy | Education | $214.43K | Free Trial - Soft Paywall | [打开](apps/speech-blubs-language-therapy-1239522573.md) |
| Canva: AI Video & Photo Editor | Photo & Video | $206.30K | Free Trial - Soft Paywall | [打开](apps/canva-ai-video-and-photo-editor-897446215.md) |
| Invoice Maker ▸ Estimate App | Business | $202.53K | Free Trial - Soft Paywall | [打开](apps/invoice-maker-estimate-app-1314873764.md) |
| TradingView: Track All Markets | Finance | $201.09K | Free Trial - Soft Paywall | [打开](apps/tradingview-track-all-markets-1205990992.md) |
| Video Up! Video Editor & Maker | Photo & Video | $197.26K | No Free Trial - Soft Paywall | [打开](apps/video-up-video-editor-and-maker-1585824635.md) |
| Chispa: Dating App for Latinos | Social Networking | $196.60K | No Free Trial - Soft Paywall | [打开](apps/chispa-dating-app-for-latinos-1289684085.md) |
| Photoshop Express Photo Editor | Photo & Video | $194.39K | Free Trial - Soft Paywall | [打开](apps/photoshop-express-photo-editor-331975235.md) |
| Otter Transcribe Voice Notes | Productivity | $192.95K | No Free Trial - Soft Paywall | [打开](apps/otter-transcribe-voice-notes-1276437113.md) |
| nugs: Live Music Lives Here | Music | $192.31K | No Free Trial - Soft Paywall | [打开](apps/nugs-live-music-lives-here-1032794422.md) |
| Amazon Prime Video | Entertainment | $191.66K | Free Trial - Soft Paywall | [打开](apps/amazon-prime-video-545519333.md) |
| Toonapp: AI Photo & Video Art | Photo & Video | $190.42K | Free Trial - Soft Paywall | [打开](apps/toonapp-ai-photo-and-video-art-1540719743.md) |
| ChatBox AI - Chatbot Assistant | Productivity | $189.37K | Free Trial - Soft Paywall | [打开](apps/chatbox-ai-chatbot-assistant-6447763703.md) |
| Duolingo: Language Lessons | Education | $189.36K | No Free Trial - Soft Paywall | [打开](apps/duolingo-language-lessons-570060128.md) |
| B1G+: Watch College Sports | Sports | $186.92K | No Free Trial - Soft Paywall | [打开](apps/b1g-watch-college-sports-474679690.md) |
| Keeper Password Manager | Productivity | $185.04K | No Free Trial - Soft Paywall | [打开](apps/keeper-password-manager-287170072.md) |
| Azar: Chat, Meet Friends | Social Networking | $184.65K | No Free Trial - Soft Paywall | [打开](apps/azar-chat-meet-friends-972558973.md) |
| Lingvano - Learn Sign Language | Education | $184.17K | Free Trial - Soft Paywall | [打开](apps/lingvano-learn-sign-language-1547252782.md) |
| Wanderlog - Travel Planner | Travel | $182.38K | Free Trial - Soft Paywall | [打开](apps/wanderlog-travel-planner-1476732439.md) |
| Google Drive | Productivity | $181.32K | No Free Trial - Soft Paywall | [打开](apps/google-drive-507874739.md) |
| Waking Up: Meditation & Wisdom | Health & Fitness | $180.03K | Free Trial - Soft Paywall | [打开](apps/waking-up-meditation-and-wisdom-1307736395.md) |
| BODi Home Fitness & Workouts | Health & Fitness | $177.70K | Free Trial - Soft Paywall | [打开](apps/bodi-home-fitness-and-workouts-1031660123.md) |
| Kismia - Dating App & Chat | Lifestyle | $176.64K | Free Trial - Soft Paywall | [打开](apps/kismia-dating-app-and-chat-1571274697.md) |
| The Athletic: All Sports News | Sports | $173.62K | Free Trial - Soft Paywall | [打开](apps/the-athletic-all-sports-news-1135216317.md) |
| Toca Boca Jr: Fun Kids Games | Education | $173.49K | No Free Trial - Soft Paywall | [打开](apps/toca-boca-jr-fun-kids-games-943869618.md) |
| Tagged Dating: Chat & Go Live! | Social Networking | $172.26K | No Free Trial - Soft Paywall | [打开](apps/tagged-dating-chat-and-go-live-358899126.md) |
| Nibble: Your Bite of Knowledge | Education | $172.03K | Free Trial - Soft Paywall | [打开](apps/nibble-your-bite-of-knowledge-6444046612.md) |
| CNBC: Stock Market & Business | News | $171.72K | No Free Trial - Soft Paywall | [打开](apps/cnbc-stock-market-and-business-398018310.md) |
| Badoo Dating: Meet New People | Lifestyle | $171.58K | Currency Paywall | [打开](apps/badoo-dating-meet-new-people-351331194.md) |
| MyTunes : AI Music Generator | Music | $168.89K | No Free Trial - Soft Paywall | [打开](apps/mytunes-ai-music-generator-6447001239.md) |
| AI Song Generator: Mozart | Music | $167.30K | No Free Trial - Soft Paywall | [打开](apps/ai-song-generator-mozart-6502656704.md) |
| MeetMe: Go Live & Meet People | Social Networking | $166.21K | No Free Trial - Soft Paywall | [打开](apps/meetme-go-live-and-meet-people-372648912.md) |
| Pok Pok \| Montessori Preschool | Education | $165.71K | Free Trial - Soft Paywall | [打开](apps/pok-pok-montessori-preschool-1550204730.md) |
| BeautyPlus-Selfie Photo Editor | Photo & Video | $162.91K | Free Trial - Soft Paywall | [打开](apps/beautyplus-selfie-photo-editor-622434129.md) |
| DIRTVision | Sports | $162.16K | No Free Trial - Soft Paywall | [打开](apps/dirtvision-1514512179.md) |
| Smart Printer App & Scan | Business | $160.81K | Free Trial - Soft Paywall | [打开](apps/smart-printer-app-and-scan-1597439129.md) |
| Cleaner Kit - Clean Up Storage | Utilities | $159.77K | Free Trial - Soft Paywall | [打开](apps/cleaner-kit-clean-up-storage-1194582243.md) |
| Photo Collage Maker PicJointer | Photo & Video | $159.77K | Free Trial - Soft Paywall | [打开](apps/photo-collage-maker-picjointer-509987785.md) |
| Outlier: Betting Data & Tools | Sports | $158.50K | Free Trial - Soft Paywall | [打开](apps/outlier-betting-data-and-tools-6443885102.md) |
| ReelShort - Stream Drama & TV | Entertainment | $157.47K | No Free Trial - Soft Paywall | [打开](apps/reelshort-stream-drama-and-tv-1636235979.md) |
| Rumble: Livestreams & Videos | Photo & Video | $157.24K | No Free Trial - Soft Paywall | [打开](apps/rumble-livestreams-and-videos-1518427877.md) |
| Photo Scan App by Photomyne | Photo & Video | $154.32K | Free Trial - Soft Paywall | [打开](apps/photo-scan-app-by-photomyne-1037784828.md) |
| Simply Sing: My Singing App | Music | $154.29K | Free Trial - Soft Paywall | [打开](apps/simply-sing-my-singing-app-1592900217.md) |
| Private Photo Vault - Pic Safe | Photo & Video | $154.16K | Free Trial - Soft Paywall | [打开](apps/private-photo-vault-pic-safe-417571834.md) |
| The Zeus Network | Entertainment | $151.04K | No Free Trial - Soft Paywall | [打开](apps/the-zeus-network-1399446592.md) |
| ‎My Package Delivery Tracker | Shopping | $150.58K | Free Trial - Soft Paywall | [打开](apps/my-package-delivery-tracker-6447516226.md) |
| McAfee: Stay Secure & Private | Utilities | $150.40K | No Free Trial - Soft Paywall | [打开](apps/mcafee-stay-secure-and-private-724596345.md) |
| DistroKid | Music | $150.11K | No Free Trial - Soft Paywall | [打开](apps/distrokid-1548832265.md) |
| Sago Mini World: Kids Games | Education | $148.12K | No Free Trial - Soft Paywall | [打开](apps/sago-mini-world-kids-games-874425722.md) |
| FaxFree: Send Fax From iPhone | Business | $147.82K | No Free Trial - Soft Paywall | [打开](apps/faxfree-send-fax-from-iphone-1151406354.md) |
| Dil Mil: South Asian Dating | Lifestyle | $147.79K | No Free Trial - Soft Paywall | [打开](apps/dil-mil-south-asian-dating-879383901.md) |
| NASCAR MOBILE | Sports | $147.03K | No Free Trial - Soft Paywall | [打开](apps/nascar-mobile-552764013.md) |
| onX Hunt: GPS Hunting Maps | Navigation | $146.07K | Free Trial - Soft Paywall | [打开](apps/onx-hunt-gps-hunting-maps-672902340.md) |
| DateMyAge™ - Mature Dating 40+ | Lifestyle | $145.25K | No Free Trial - Soft Paywall | [打开](apps/datemyage-mature-dating-40-1270059501.md) |
| JustFit: Lazy Workout & Fit | Health & Fitness | $144.73K | No Free Trial - Soft Paywall | [打开](apps/justfit-lazy-workout-and-fit-1574460221.md) |
| Chat AI: Ask Agent Anything | Productivity | $144.43K | Free Trial - Soft Paywall | [打开](apps/chat-ai-ask-agent-anything-1668787639.md) |
| DramaBox - Stream Drama Shorts | Entertainment | $142.68K | No Free Trial - Soft Paywall | [打开](apps/dramabox-stream-drama-shorts-6445905219.md) |
| Nebula: Spiritual Guidance | Lifestyle | $142.51K | Free Trial - Soft Paywall | [打开](apps/nebula-spiritual-guidance-1459969523.md) |
| NYT Cooking: Quick Tasty Meals | Food & Drink | $141.44K | Free Trial - Soft Paywall | [打开](apps/nyt-cooking-quick-tasty-meals-911422904.md) |
| Planner 5D: AI Home Design | Lifestyle | $141.03K | No Free Trial - Soft Paywall | [打开](apps/planner-5d-ai-home-design-606173978.md) |
| MasterClass: Online Classes | Education | $140.97K | No Free Trial - Soft Paywall | [打开](apps/masterclass-online-classes-1273867416.md) |
| Lively - Period Tracker, Cycle | Health & Fitness | $139.92K | No Free Trial - Soft Paywall | [打开](apps/lively-period-tracker-cycle-6447674634.md) |
| Alarmy - Loud alarm clock | Lifestyle | $139.22K | Free Trial - Soft Paywall | [打开](apps/alarmy-loud-alarm-clock-1163786766.md) |
| DMV Practice Test 2026 myDMV | Education | $138.38K | Free Trial - Soft Paywall | [打开](apps/dmv-practice-test-2026-mydmv-1625234008.md) |
| Waplog - Dating & Video Call | Social Networking | $137.30K | No Free Trial - Soft Paywall | [打开](apps/waplog-dating-and-video-call-557997762.md) |
| The Pattern: Astrology | Lifestyle | $136.65K | No Free Trial - Soft Paywall | [打开](apps/the-pattern-astrology-1071085727.md) |
| Joist: Estimate Invoice Maker | Business | $134.85K | No Free Trial - Soft Paywall | [打开](apps/joist-estimate-invoice-maker-592163563.md) |
| Secret Photo Vault: Keepsafe | Photo & Video | $134.14K | Free Trial - Soft Paywall | [打开](apps/secret-photo-vault-keepsafe-510873505.md) |
| Bumpy – International Dating | Social Networking | $133.94K | No Free Trial - Soft Paywall | [打开](apps/bumpy-international-dating-1455336523.md) |
| Deepsearch AI Search Assistant | Lifestyle | $133.93K | No Free Trial - Soft Paywall | [打开](apps/deepsearch-ai-search-assistant-6741062364.md) |
| Udemy Online Video Courses | Education | $133.05K | No Free Trial - Soft Paywall | [打开](apps/udemy-online-video-courses-562413829.md) |
| Ground News | News | $132.01K | No Free Trial - Soft Paywall | [打开](apps/ground-news-1324203419.md) |
| Moises: The Musician's App | Music | $131.06K | No Free Trial - Soft Paywall | [打开](apps/moises-the-musician-s-app-1515796612.md) |
| Welltory: Health, Heart Rate | Health & Fitness | $130.95K | No Free Trial - Soft Paywall | [打开](apps/welltory-health-heart-rate-1074367771.md) |
| Facetune: Photo & Video Editor | Photo & Video | $128.41K | Free Trial - Soft Paywall | [打开](apps/facetune-photo-and-video-editor-1149994032.md) |
| Audiomack - Play Music Offline | Music | $128.05K | Free Trial - Soft Paywall | [打开](apps/audiomack-play-music-offline-921765888.md) |
| Discord - Talk, Play, Hang Out | Social Networking | $127.98K | No Free Trial - Soft Paywall | [打开](apps/discord-talk-play-hang-out-985746746.md) |
| InstaSize: AI Photo Editor | Photo & Video | $126.74K | Free Trial - Soft Paywall | [打开](apps/instasize-ai-photo-editor-576649830.md) |
| Wellmy - Heart Rate Monitor | Health & Fitness | $124.06K | Free Trial - Soft Paywall | [打开](apps/wellmy-heart-rate-monitor-6463719381.md) |
| AI Music, Song Generator・Shoom | Music | $122.84K | No Free Trial - Hard Paywall | [打开](apps/ai-music-song-generator-shoom-6499126830.md) |
| Strong Workout Tracker Gym Log | Health & Fitness | $121.93K | No Free Trial - Soft Paywall | [打开](apps/strong-workout-tracker-gym-log-464254577.md) |
| Once: Perfect Match Dating App | Lifestyle | $121.78K | No Free Trial - Soft Paywall | [打开](apps/once-perfect-match-dating-app-1489440748.md) |
| Adult Coloring Book - Pigment | Lifestyle | $119.83K | Free Trial - Soft Paywall | [打开](apps/adult-coloring-book-pigment-1062006344.md) |
| Repost+ for Instagram . | Social Networking | $119.11K | Free Trial - Soft Paywall | [打开](apps/repost-for-instagram-1477820240.md) |
| Luxy - Selective Dating App | Social Networking | $118.59K | No Free Trial - Soft Paywall | [打开](apps/luxy-selective-dating-app-873518909.md) |
| djay - DJ App & AI Mixer | Music | $116.98K | Free Trial - Soft Paywall | [打开](apps/djay-dj-app-and-ai-mixer-450527929.md) |
| TV Remote & Universal Control™ | Utilities | $115.98K | Free Trial - Soft Paywall | [打开](apps/tv-remote-and-universal-control-6458692724.md) |
| Woofz - Puppy and Dog Training | Lifestyle | $115.19K | Free Trial - Hard Paywall | [打开](apps/woofz-puppy-and-dog-training-1532020050.md) |
| HelloTalk - Language Learning | Education | $114.90K | Currency Paywall | [打开](apps/hellotalk-language-learning-557130558.md) |
| ScanGuru: PDF & Photo Scanner | Business | $114.88K | Free Trial - Soft Paywall | [打开](apps/scanguru-pdf-and-photo-scanner-1040149161.md) |
| InShot - Video Editor | Photo & Video | $114.76K | Free Trial - Soft Paywall | [打开](apps/inshot-video-editor-997362197.md) |
| MuseScore－Sheet Music & Chords | Music | $114.72K | Free Trial - Soft Paywall | [打开](apps/musescore-sheet-music-and-chords-835731296.md) |
| Shots: AI Photo Video Creator | Photo & Video | $114.38K | No Free Trial - Soft Paywall | [打开](apps/shots-ai-photo-video-creator-6745820631.md) |
| Meitu AI Photo & Video Editor | Photo & Video | $113.53K | Free Trial - Soft Paywall | [打开](apps/meitu-ai-photo-and-video-editor-416048305.md) |
| Coloring Games for Kids 2-6! | Education | $111.97K | Free Trial - Soft Paywall | [打开](apps/coloring-games-for-kids-2-6-451719402.md) |
| Tiny Scanner - PDF Scanner App | Business | $110.70K | Free Trial - Soft Paywall | [打开](apps/tiny-scanner-pdf-scanner-app-595563753.md) |
| Seeking Alpha: News & Analysis | Finance | $109.80K | No Free Trial - Soft Paywall | [打开](apps/seeking-alpha-news-and-analysis-552799694.md) |
| Flight Tracker + | Travel | $109.35K | Free Trial - Soft Paywall | [打开](apps/flight-tracker-533365777.md) |
| Captions: AI Edits Your Video | Photo & Video | $109.21K | No Free Trial - Soft Paywall | [打开](apps/captions-ai-edits-your-video-1541407007.md) |
| Rosetta Stone Classic (2024) | Education | $107.27K | Free Trial - Soft Paywall | [打开](apps/rosetta-stone-classic-2024-435588892.md) |
| Malwarebytes - Mobile Security | Utilities | $107.16K | Free Trial - Soft Paywall | [打开](apps/malwarebytes-mobile-security-1327105431.md) |
| Yoga-Go: Tai Chi & Pilates | Health & Fitness | $106.58K | No Free Trial - Soft Paywall | [打开](apps/yoga-go-tai-chi-and-pilates-1361619409.md) |
| Visify: AI Photo Generator | Photo & Video | $106.03K | Free Trial - Soft Paywall | [打开](apps/visify-ai-photo-generator-6472172759.md) |
| Coco -Live Stream & Video Chat | Social Networking | $105.72K | No Free Trial - Soft Paywall | [打开](apps/coco-live-stream-and-video-chat-1435758172.md) |
| FORM: Strength, Pilates, Gym | Health & Fitness | $105.64K | Free Trial - Soft Paywall | [打开](apps/form-strength-pilates-gym-1578636146.md) |
| SplashLearn: Kids Learning App | Education | $104.94K | Free Trial - Hard Paywall | [打开](apps/splashlearn-kids-learning-app-672658828.md) |
| Facelab: Face & Body Editor | Photo & Video | $103.50K | Free Trial - Soft Paywall | [打开](apps/facelab-face-and-body-editor-1361012099.md) |
| Sereal+ Short Drama, TV Series | Entertainment | $102.19K | No Free Trial - Soft Paywall | [打开](apps/sereal-short-drama-tv-series-6473688138.md) |
| UnitedMasters: Release Music | Music | $101.89K | No Free Trial - Soft Paywall | [打开](apps/unitedmasters-release-music-1442118788.md) |
| ZEPETO: Avatar, Connect & Live | Social Networking | $101.38K | Currency Paywall | [打开](apps/zepeto-avatar-connect-and-live-1350301428.md) |
| Praktika – AI Language Tutor | Education | $101.13K | Free Trial - Soft Paywall | [打开](apps/praktika-ai-language-tutor-1624701477.md) |
| Polycam 3D Scans & Floor Plans | Photo & Video | $99.76K | Free Trial - Soft Paywall | [打开](apps/polycam-3d-scans-and-floor-plans-1532482376.md) |
| AccuWeather: Weather Forecast | Weather | $99.48K | Free Trial - Soft Paywall | [打开](apps/accuweather-weather-forecast-300048137.md) |
| 1Password: Password Manager | Productivity | $99.08K | No Free Trial - Soft Paywall | [打开](apps/1password-password-manager-1511601750.md) |
| Find Air - My Device Tracker | Utilities | $98.98K | Free Trial - Soft Paywall | [打开](apps/find-air-my-device-tracker-1507917112.md) |
| Rock Identifier: Stone ID | Education | $98.95K | Free Trial - Soft Paywall | [打开](apps/rock-identifier-stone-id-1546796934.md) |
| Edjing Mix - DJ Music Mixer | Music | $98.87K | Free Trial - Soft Paywall | [打开](apps/edjing-mix-dj-music-mixer-493226494.md) |
| The Guardian - US & World News | News | $98.82K | No Free Trial - Soft Paywall | [打开](apps/the-guardian-us-and-world-news-409128287.md) |
| Scanner App. JPG, Photo to PDF | Business | $98.71K | Free Trial - Soft Paywall | [打开](apps/scanner-app-jpg-photo-to-pdf-1425891150.md) |
| Premom Ovulation Tracker & BBT | Health & Fitness | $98.44K | No Free Trial - Soft Paywall | [打开](apps/premom-ovulation-tracker-and-bbt-1279295922.md) |
| STARZ | Entertainment | $98.36K | No Free Trial - Soft Paywall | [打开](apps/starz-550221096.md) |
| SleepWatch - Top Sleep Tracker | Health & Fitness | $98.17K | Free Trial - Soft Paywall | [打开](apps/sleepwatch-top-sleep-tracker-1138066420.md) |
| Micro Learning - SmartyMe | Education | $97.63K | No Free Trial - Soft Paywall | [打开](apps/micro-learning-smartyme-6736654449.md) |
| Vids AI - Reels Video Editor | Photo & Video | $97.60K | Free Trial - Soft Paywall | [打开](apps/vids-ai-reels-video-editor-1634361180.md) |
| Moongate: Binaural Beats | Music | $97.25K | Free Trial - Soft Paywall | [打开](apps/moongate-binaural-beats-6471041035.md) |
| IQ Masters: Brain Games, Tests | Education | $96.64K | Free Trial - Soft Paywall | [打开](apps/iq-masters-brain-games-tests-6475717895.md) |
| ViX: TV, Sports and News | Entertainment | $94.84K | No Free Trial - Soft Paywall | [打开](apps/vix-tv-sports-and-news-1531467766.md) |
| Scan to PDF－Document Scanner | Business | $94.59K | Free Trial - Soft Paywall | [打开](apps/scan-to-pdf-document-scanner-1575194801.md) |
| YouCam Makeup: Face Editor | Photo & Video | $94.35K | Free Trial - Soft Paywall | [打开](apps/youcam-makeup-face-editor-863844475.md) |
| Gibson: Learn to Play Guitar | Education | $94.27K | Free Trial - Soft Paywall | [打开](apps/gibson-learn-to-play-guitar-1116032929.md) |
| AI Photo Video Editor, Enhance | Photo & Video | $93.71K | No Free Trial - Soft Paywall | [打开](apps/ai-photo-video-editor-enhance-6447604690.md) |
| GoodShort - Short Dramas Hub | Entertainment | $93.61K | No Free Trial - Soft Paywall | [打开](apps/goodshort-short-dramas-hub-6448176203.md) |
| Motivation: daily Peptalk | Health & Fitness | $93.54K | No Free Trial - Soft Paywall | [打开](apps/motivation-daily-peptalk-976885594.md) |
| Birdbuddy: ID & Collect Birds | Education | $93.49K | Free Trial - Soft Paywall | [打开](apps/birdbuddy-id-and-collect-birds-1622355240.md) |
| Proton VPN: Fast & Secure | Utilities | $93.26K | No Free Trial - Soft Paywall | [打开](apps/proton-vpn-fast-and-secure-1437005085.md) |
| Plant Parent: Plant Care Guide | Lifestyle | $92.96K | Free Trial - Soft Paywall | [打开](apps/plant-parent-plant-care-guide-1612792132.md) |
| Hooked on Phonics Learning | Education | $92.81K | Free Trial - Soft Paywall | [打开](apps/hooked-on-phonics-learning-588868907.md) |
| PhotoGrid: Video Collage Maker | Photo & Video | $92.70K | Free Trial - Soft Paywall | [打开](apps/photogrid-video-collage-maker-543577420.md) |
| Surfshark VPN: Fast VPN App | Productivity | $91.38K | No Free Trial - Soft Paywall | [打开](apps/surfshark-vpn-fast-vpn-app-1391782046.md) |
| LumaBooth Event Photo Booth | Photo & Video | $91.31K | No Free Trial - Soft Paywall | [打开](apps/lumabooth-event-photo-booth-1162206015.md) |
| DailyWire+ | News | $91.06K | No Free Trial - Soft Paywall | [打开](apps/dailywire-1477317200.md) |
| Talkatone: WiFi Text & Calls | Social Networking | $90.70K | No Free Trial - Soft Paywall | [打开](apps/talkatone-wifi-text-and-calls-397648381.md) |
| Beat Maker Pro: Music drum Pad | Music | $90.64K | No Free Trial - Soft Paywall | [打开](apps/beat-maker-pro-music-drum-pad-1362013798.md) |
| Deezer: Music Player, Podcast | Music | $89.92K | Free Trial - Soft Paywall | [打开](apps/deezer-music-player-podcast-292738169.md) |
| YouCam Perfect:AI Photo Editor | Photo & Video | $89.66K | Free Trial - Soft Paywall | [打开](apps/youcam-perfect-ai-photo-editor-768469908.md) |
| Qobuz: Music & Editorial | Music | $89.55K | Free Trial - Soft Paywall | [打开](apps/qobuz-music-and-editorial-946429340.md) |
| Muzz: Where Muslims Marry | Lifestyle | $89.50K | No Free Trial - Soft Paywall | [打开](apps/muzz-where-muslims-marry-969997496.md) |
| Printer App: Smart Print | Business | $88.96K | Free Trial - Soft Paywall | [打开](apps/printer-app-smart-print-1585148293.md) |
| EveryDollar: Budget Management | Finance | $88.82K | Free Trial - Soft Paywall | [打开](apps/everydollar-budget-management-942571931.md) |
| Photo Collage - Collageable | Photo & Video | $88.56K | Free Trial - Soft Paywall | [打开](apps/photo-collage-collageable-1085652055.md) |
| Cleanup: Phone Storage Cleaner | Utilities | $86.63K | Free Trial - Soft Paywall | [打开](apps/cleanup-phone-storage-cleaner-1510944943.md) |
| Monarch: Budget & Track Money | Finance | $86.22K | Free Trial - Soft Paywall | [打开](apps/monarch-budget-and-track-money-1459319842.md) |
| SellRaze: List, sell, earn | Shopping | $85.98K | Free Trial - Soft Paywall | [打开](apps/sellraze-list-sell-earn-6455042085.md) |
| Action Network: Sports Betting | Sports | $85.80K | No Free Trial - Soft Paywall | [打开](apps/action-network-sports-betting-1083677479.md) |
| Alight Motion | Photo & Video | $85.63K | No Free Trial - Soft Paywall | [打开](apps/alight-motion-1459833443.md) |
| Planta: AI Plant & Garden Care | Lifestyle | $85.26K | No Free Trial - Soft Paywall | [打开](apps/planta-ai-plant-and-garden-care-1410126781.md) |
| Pray.com: Bible & Daily Prayer | Health & Fitness | $84.89K | Free Trial - Soft Paywall | [打开](apps/pray-com-bible-and-daily-prayer-1161035371.md) |
| Monkey Run - Make New Friends | Social Networking | $84.80K | Free Trial - Soft Paywall | [打开](apps/monkey-run-make-new-friends-1549926278.md) |
| Settlemate: Financial Savings | Finance | $84.25K | No Free Trial - Hard Paywall | [打开](apps/settlemate-financial-savings-6737785495.md) |
| The Wonder Weeks - Baby leaps | Health & Fitness | $83.45K | No Free Trial - Soft Paywall | [打开](apps/the-wonder-weeks-baby-leaps-529815782.md) |
| Second Phone Number - 2Number | Utilities | $83.30K | Free Trial - Soft Paywall | [打开](apps/second-phone-number-2number-1216135390.md) |
| Free VPN by Free VPN .org™ | Utilities | $82.52K | Free Trial - Soft Paywall | [打开](apps/free-vpn-by-free-vpn-org-1050171910.md) |
| Cosmo: AI Editor, Hair Filters | Photo & Video | $82.28K | No Free Trial - Soft Paywall | [打开](apps/cosmo-ai-editor-hair-filters-6444848535.md) |
| Norton VPN – Fast & Secure | Productivity | $82.12K | Free Trial - Soft Paywall | [打开](apps/norton-vpn-fast-and-secure-1095519285.md) |
| Cricut Design Space | Graphics & Design | $81.69K | No Free Trial - Soft Paywall | [打开](apps/cricut-design-space-749471884.md) |
| Golfshot Golf GPS Range Finder | Sports | $80.89K | Free Trial - Soft Paywall | [打开](apps/golfshot-golf-gps-range-finder-622851626.md) |
| Reframe: Drink Less & Thrive | Health & Fitness | $80.77K | Free Trial - Soft Paywall | [打开](apps/reframe-drink-less-and-thrive-1485756576.md) |
| Plant Identifier & Care App | Education | $80.75K | Free Trial - Soft Paywall | [打开](apps/plant-identifier-and-care-app-1557446434.md) |
| flowkey – Learn to Play Piano | Education | $80.68K | Free Trial - Soft Paywall | [打开](apps/flowkey-learn-to-play-piano-1020357408.md) |
| Sanford Guide Antimicrobial | Medical | $80.58K | Free Trial - Soft Paywall | [打开](apps/sanford-guide-antimicrobial-863196620.md) |
| Esti: Aesthetic Photo Editor | Photo & Video | $80.50K | Free Trial - Soft Paywall | [打开](apps/esti-aesthetic-photo-editor-6457366208.md) |
| SlideShow Maker Photo to Video | Photo & Video | $80.21K | Free Trial - Soft Paywall | [打开](apps/slideshow-maker-photo-to-video-924826256.md) |
| StepsApp Pedometer | Health & Fitness | $79.27K | No Free Trial - Soft Paywall | [打开](apps/stepsapp-pedometer-1037595083.md) |
| Dating.com: Global Chat & Date | Social Networking | $79.14K | No Free Trial - Soft Paywall | [打开](apps/dating-com-global-chat-and-date-945614824.md) |
| Reports+ for Followers Tracker | Social Networking | $78.91K | No Free Trial - Soft Paywall | [打开](apps/reports-for-followers-tracker-1485509764.md) |
| Bark - Parental Controls | Productivity | $78.71K | No Free Trial - Soft Paywall | [打开](apps/bark-parental-controls-1477619146.md) |
| DramaWave - Dramas & Reels | Entertainment | $78.68K | No Free Trial - Soft Paywall | [打开](apps/dramawave-dramas-and-reels-6670430706.md) |
| Unfollow Tracker: MyFollowers | Utilities | $78.66K | Free Trial - Soft Paywall | [打开](apps/unfollow-tracker-myfollowers-1666254795.md) |
| Kahoot! Play & Create Quizzes | Education | $78.14K | Free Trial - Soft Paywall | [打开](apps/kahoot-play-and-create-quizzes-1131203560.md) |
| Financial Times: Business News | News | $78.12K | No Free Trial - Soft Paywall | [打开](apps/financial-times-business-news-1200842933.md) |
| Yuno - General knowledge | Education | $77.90K | Free Trial - Soft Paywall | [打开](apps/yuno-general-knowledge-1500143611.md) |
| Astra - Life Advice | Lifestyle | $77.77K | Free Trial - Hard Paywall | [打开](apps/astra-life-advice-6473748536.md) |
| The New Yorker | News | $76.92K | Free Trial - Soft Paywall | [打开](apps/the-new-yorker-1081530898.md) |
| Davis's Drug Guide - Nurses | Medical | $76.83K | Free Trial - Soft Paywall | [打开](apps/davis-s-drug-guide-nurses-301427093.md) |
| Jumpspeak \| Language Learning | Education | $76.75K | No Free Trial - Soft Paywall | [打开](apps/jumpspeak-language-learning-1514709368.md) |
| Linktree: Link in Bio Creator | Social Networking | $75.67K | Free Trial - Soft Paywall | [打开](apps/linktree-link-in-bio-creator-1593515263.md) |
| Yousician: Learn & Play Guitar | Education | $75.48K | Free Trial - Soft Paywall | [打开](apps/yousician-learn-and-play-guitar-959883039.md) |
| discovery+ \| Stream TV Shows | Entertainment | $75.39K | Free Trial - Soft Paywall | [打开](apps/discovery-stream-tv-shows-1498327873.md) |
| MacrosFirst - Macro Tracker | Health & Fitness | $75.38K | Free Trial - Soft Paywall | [打开](apps/macrosfirst-macro-tracker-1253012487.md) |
| Songsterr Tabs & Chords | Music | $75.37K | No Free Trial - Soft Paywall | [打开](apps/songsterr-tabs-and-chords-399211291.md) |
| Cozi Family Organizer | Productivity | $75.27K | No Free Trial - Soft Paywall | [打开](apps/cozi-family-organizer-407108860.md) |
| Minutes: AI Meeting Note Taker | Productivity | $74.71K | Free Trial - Soft Paywall | [打开](apps/minutes-ai-meeting-note-taker-6504206467.md) |
| Breethe: Sleep & Meditation | Health & Fitness | $74.04K | Free Trial - Soft Paywall | [打开](apps/breethe-sleep-and-meditation-920161006.md) |
| AI Photo Generator - Collart | Graphics & Design | $74.04K | No Free Trial - Soft Paywall | [打开](apps/ai-photo-generator-collart-1561940699.md) |
| Lowins - Live Video Streaming | Social Networking | $73.65K | Currency Paywall | [打开](apps/lowins-live-video-streaming-1540625368.md) |
| TapeACall: Call Recorder | Business | $73.61K | Free Trial - Soft Paywall | [打开](apps/tapeacall-call-recorder-573751328.md) |
| Carb Manager: Keto & Macro Log | Health & Fitness | $73.27K | No Free Trial - Soft Paywall | [打开](apps/carb-manager-keto-and-macro-log-410089731.md) |
| QUITTR - Break Free Now | Health & Fitness | $73.03K | No Free Trial - Soft Paywall | [打开](apps/quittr-break-free-now-6532588521.md) |
| Coursera: Grow your career | Education | $73.00K | No Free Trial - Soft Paywall | [打开](apps/coursera-grow-your-career-736535961.md) |
| Donna AI Song & Music Maker | Music | $72.76K | No Free Trial - Soft Paywall | [打开](apps/donna-ai-song-and-music-maker-6482289804.md) |
| VPN Hotspot Shield: Secure VPN | Productivity | $72.41K | Free Trial - Soft Paywall | [打开](apps/vpn-hotspot-shield-secure-vpn-443369807.md) |
| FaceAi: Face Swap Any Video | Photo & Video | $72.25K | No Free Trial - Soft Paywall | [打开](apps/faceai-face-swap-any-video-6470990632.md) |
| Splash Jr: PreK & Kindergarten | Education | $72.24K | Free Trial - Soft Paywall | [打开](apps/splash-jr-prek-and-kindergarten-610303073.md) |
| Universal Remote TV Control · | Utilities | $72.22K | Free Trial - Soft Paywall | [打开](apps/universal-remote-tv-control-1581765635.md) |
| TeamSnap | Sports | $71.42K | Free Trial - Soft Paywall | [打开](apps/teamsnap-393048976.md) |
| Pic+ - AI Video Generator | Photo & Video | $71.26K | No Free Trial - Soft Paywall | [打开](apps/pic-ai-video-generator-6476751797.md) |
| RunwayML | Photo & Video | $70.70K | No Free Trial - Soft Paywall | [打开](apps/runwayml-1665024375.md) |
| iScape: Landscape Design | Lifestyle | $70.47K | Free Trial - Soft Paywall | [打开](apps/iscape-landscape-design-439688430.md) |
| Universal TV Remote Control・ | Utilities | $69.77K | Free Trial - Soft Paywall | [打开](apps/universal-tv-remote-control-6443877058.md) |
| Alive by Whitney Simmons | Health & Fitness | $69.52K | Free Trial - Soft Paywall | [打开](apps/alive-by-whitney-simmons-1488020055.md) |
| FaceLab: Face Age, Hair Filter | Photo & Video | $69.33K | Free Trial - Soft Paywall | [打开](apps/facelab-face-age-hair-filter-1530776865.md) |
| Jobber Field Service Software | Business | $69.27K | Free Trial - Soft Paywall | [打开](apps/jobber-field-service-software-1014146758.md) |
| HitMeal Calorie & Food Tracker | Health & Fitness | $69.25K | Free Trial - Soft Paywall | [打开](apps/hitmeal-calorie-and-food-tracker-1544461026.md) |
| Blinq: Digital Business Card | Business | $69.23K | Free Trial - Soft Paywall | [打开](apps/blinq-digital-business-card-1324102258.md) |
| Skylight App | Photo & Video | $69.16K | No Free Trial - Soft Paywall | [打开](apps/skylight-app-1438779037.md) |
| FitOn Workouts & Fitness Plans | Health & Fitness | $69.05K | No Free Trial - Soft Paywall | [打开](apps/fiton-workouts-and-fitness-plans-1442473191.md) |
| SHRED: Gym & Home Workouts | Health & Fitness | $68.57K | Free Trial - Soft Paywall | [打开](apps/shred-gym-and-home-workouts-1439828095.md) |
| Smart Cleaner: Free Up Storage | Utilities | $68.42K | Free Trial - Soft Paywall | [打开](apps/smart-cleaner-free-up-storage-6448222268.md) |
| AI Chatbot: Pixi | Productivity | $68.39K | Free Trial - Soft Paywall | [打开](apps/ai-chatbot-pixi-6499593159.md) |
| Socratic AI - Homework Helper | Education | $68.36K | Free Trial - Soft Paywall | [打开](apps/socratic-ai-homework-helper-1605965391.md) |
| White Noise Deep Sleep Sounds | Health & Fitness | $68.31K | Free Trial - Soft Paywall | [打开](apps/white-noise-deep-sleep-sounds-1083248251.md) |
| Vivino: Drink The Right Wine | Food & Drink | $68.15K | No Free Trial - Soft Paywall | [打开](apps/vivino-drink-the-right-wine-414461255.md) |
| Boo — Dating. Friends. Chat. | Social Networking | $67.76K | No Free Trial - Soft Paywall | [打开](apps/boo-dating-friends-chat-1498407272.md) |
| Balance: Meditation & Sleep | Health & Fitness | $67.69K | Free Trial - Soft Paywall | [打开](apps/balance-meditation-and-sleep-1361356590.md) |
| X-VPN: VPN Fast & Secure | Productivity | $67.38K | Free Trial - Hard Paywall | [打开](apps/x-vpn-vpn-fast-and-secure-1250312807.md) |
| Persona: AI Beauty Editor | Photo & Video | $67.35K | No Free Trial - Soft Paywall | [打开](apps/persona-ai-beauty-editor-1561622206.md) |
| Photoleap: AI Photo Generator | Photo & Video | $67.12K | Free Trial - Soft Paywall | [打开](apps/photoleap-ai-photo-generator-1191337894.md) |
| Body Tune - Face Photo Editor | Photo & Video | $66.69K | Free Trial - Soft Paywall | [打开](apps/body-tune-face-photo-editor-1222515036.md) |
| Planner & Journal - Zinnia | Lifestyle | $66.54K | Free Trial - Soft Paywall | [打开](apps/planner-and-journal-zinnia-1485310935.md) |
| Paired: Couples & Relationship | Lifestyle | $66.54K | Free Trial - Soft Paywall | [打开](apps/paired-couples-and-relationship-1469609343.md) |
| Cardi Mate: Heart Rate Monitor | Health & Fitness | $66.47K | Free Trial - Soft Paywall | [打开](apps/cardi-mate-heart-rate-monitor-1570842053.md) |
| BET+ | Entertainment | $66.30K | No Free Trial - Hard Paywall | [打开](apps/bet-1456618978.md) |
| Petlibro | Lifestyle | $66.23K | Free Trial - Soft Paywall | [打开](apps/petlibro-1586120661.md) |
| MadMuscles: Workouts & Diet | Health & Fitness | $65.99K | No Free Trial - Soft Paywall | [打开](apps/madmuscles-workouts-and-diet-1526814298.md) |
| Coconote - AI Note Taker | Education | $65.96K | Free Trial - Soft Paywall | [打开](apps/coconote-ai-note-taker-6479320349.md) |
| Universal TV Remote · | Utilities | $65.96K | Free Trial - Soft Paywall | [打开](apps/universal-tv-remote-1439422220.md) |
| MICO: Make Friends, Go Live | Social Networking | $65.83K | No Free Trial - Soft Paywall | [打开](apps/mico-make-friends-go-live-908023218.md) |
| Planes Live - Flight Tracker | Travel | $65.78K | Free Trial - Soft Paywall | [打开](apps/planes-live-flight-tracker-1097815000.md) |
| Chibi Dolls - Games for Girls | Education | $65.76K | Free Trial - Soft Paywall | [打开](apps/chibi-dolls-games-for-girls-6472036852.md) |
| GoodNovel - Booktok, Stories | Books | $65.60K | Currency Paywall | [打开](apps/goodnovel-booktok-stories-1503128132.md) |
| Replika - AI Friend | Health & Fitness | $65.26K | No Free Trial - Soft Paywall | [打开](apps/replika-ai-friend-1158555867.md) |
| Cleaner Guru: Clean Up Storage | Utilities | $65.16K | Free Trial - Soft Paywall | [打开](apps/cleaner-guru-clean-up-storage-1476380919.md) |
| Ringtones for iphone: Ringtune | Music | $64.72K | Free Trial - Soft Paywall | [打开](apps/ringtones-for-iphone-ringtune-1036141497.md) |
| Reels Maker for Instagram BEAT | Photo & Video | $64.58K | No Free Trial - Soft Paywall | [打开](apps/reels-maker-for-instagram-beat-6443517019.md) |
| Powerful Cleaner-Clean Storage | Lifestyle | $64.41K | Free Trial - Soft Paywall | [打开](apps/powerful-cleaner-clean-storage-1618902724.md) |
| Letterboxd | Social Networking | $64.17K | No Free Trial - Soft Paywall | [打开](apps/letterboxd-1054271011.md) |
| Call Santa Claus with PNP | Entertainment | $63.95K | No Free Trial - Soft Paywall | [打开](apps/call-santa-claus-with-pnp-902026228.md) |
| Picsart AI Photo Editor, Video | Photo & Video | $63.85K | Free Trial - Soft Paywall | [打开](apps/picsart-ai-photo-editor-video-587366035.md) |
| Speak & Learn English: Learna | Education | $63.70K | Free Trial - Soft Paywall | [打开](apps/speak-and-learn-english-learna-6478287397.md) |
| invideo AI: AI Video Generator | Photo & Video | $63.47K | No Free Trial - Soft Paywall | [打开](apps/invideo-ai-ai-video-generator-6471394316.md) |
| Universal TV Remote Control＊ | Utilities | $63.16K | Free Trial - Soft Paywall | [打开](apps/universal-tv-remote-control-6477382010.md) |
| Video Star | Photo & Video | $63.13K | Free Trial - Soft Paywall | [打开](apps/video-star-438596432.md) |
| Clip Studio Paint | Graphics & Design | $63.07K | No Free Trial - Soft Paywall | [打开](apps/clip-studio-paint-1262985592.md) |
| Minichat – video chat, texting | Social Networking | $63.05K | Free Trial - Soft Paywall | [打开](apps/minichat-video-chat-texting-1506912979.md) |
| iRomance-Step Into Stories | Games | $62.83K | Currency Paywall | [打开](apps/iromance-step-into-stories-1643862208.md) |
| Coverstar - Positive Social | Social Networking | $62.62K | Currency Paywall | [打开](apps/coverstar-positive-social-1219890480.md) |
| Lifesum: AI Calorie Counter | Health & Fitness | $61.88K | No Free Trial - Soft Paywall | [打开](apps/lifesum-ai-calorie-counter-286906691.md) |
| AI Song Generator - Zona | Music | $61.85K | No Free Trial - Soft Paywall | [打开](apps/ai-song-generator-zona-6499261254.md) |
| Cowboy+ | Sports | $61.83K | No Free Trial - Soft Paywall | [打开](apps/cowboy-1494157233.md) |
| LastPass Password Manager | Productivity | $61.77K | No Free Trial - Soft Paywall | [打开](apps/lastpass-password-manager-324613447.md) |
| Voice Recorder — Audio Memos | Business | $61.55K | Free Trial - Hard Paywall | [打开](apps/voice-recorder-audio-memos-1639516366.md) |
| Piano - Keyboard Lesson & Game | Music | $61.35K | Free Trial - Soft Paywall | [打开](apps/piano-keyboard-lesson-and-game-1360309966.md) |
| Mileage Tracker by Everlance | Finance | $61.27K | Free Trial - Soft Paywall | [打开](apps/mileage-tracker-by-everlance-985378916.md) |
| Police Scanner Radio & Fire | News | $61.22K | Free Trial - Soft Paywall | [打开](apps/police-scanner-radio-and-fire-498405045.md) |
| QR Code Reader，Barcode Scanner | Utilities | $60.61K | Free Trial - Soft Paywall | [打开](apps/qr-code-reader-barcode-scanner-1226650677.md) |
| Perplexity - AI Search & Chat | Productivity | $60.38K | No Free Trial - Soft Paywall | [打开](apps/perplexity-ai-search-and-chat-1668000334.md) |
| Lensa AI: Photo Editor | Photo & Video | $60.37K | Free Trial - Soft Paywall | [打开](apps/lensa-ai-photo-editor-1436732536.md) |
| Documents: File Manager & Docs | Productivity | $60.27K | Free Trial - Soft Paywall | [打开](apps/documents-file-manager-and-docs-364901807.md) |
| Quizard AI: Homework Helper | Education | $60.02K | Free Trial - Soft Paywall | [打开](apps/quizard-ai-homework-helper-1667996582.md) |
| Rithmm: AI Sports Betting | Sports | $59.89K | Free Trial - Soft Paywall | [打开](apps/rithmm-ai-sports-betting-1641010681.md) |
| Yoga \| Down Dog | Health & Fitness | $59.83K | No Free Trial - Soft Paywall | [打开](apps/yoga-down-dog-983693694.md) |
| Reading Eggs - Learn to Read | Education | $59.42K | Free Trial - Soft Paywall | [打开](apps/reading-eggs-learn-to-read-726696040.md) |
| Blood Pressure Tracker SmartBP | Medical | $58.78K | No Free Trial - Soft Paywall | [打开](apps/blood-pressure-tracker-smartbp-519076558.md) |
| Aura: Security & Protection | Finance | $58.76K | Free Trial - Soft Paywall | [打开](apps/aura-security-and-protection-1547735089.md) |
| Health Planner & Tracker | Health & Fitness | $58.75K | Free Trial - Soft Paywall | [打开](apps/health-planner-and-tracker-6471674773.md) |
| MobiOffice・Word Docs・Excel・PDF | Business | $58.45K | Free Trial - Soft Paywall | [打开](apps/mobioffice-word-docs-excel-pdf-924005506.md) |
| AI Photo Video Generator: AURA | Photo & Video | $58.00K | No Free Trial - Soft Paywall | [打开](apps/ai-photo-video-generator-aura-6743614509.md) |
| Boards.com | Business | $57.77K | Free Trial - Soft Paywall | [打开](apps/boards-com-1507677341.md) |
| Muscle Monster Workout Planner | Health & Fitness | $57.74K | No Free Trial - Soft Paywall | [打开](apps/muscle-monster-workout-planner-6471547318.md) |
| Imprint: Visual Micro Learning | Education | $57.39K | Free Trial - Soft Paywall | [打开](apps/imprint-visual-micro-learning-1482780647.md) |
| Call Recorder for iPhone. | Business | $57.28K | Free Trial - Soft Paywall | [打开](apps/call-recorder-for-iphone-1503665233.md) |
| CardiaLink-Heart rate&Health | Health & Fitness | $56.91K | No Free Trial - Soft Paywall | [打开](apps/cardialink-heart-rate-and-health-6746929680.md) |
| LEGO® DUPLO® MARVEL | Education | $56.86K | No Free Trial - Soft Paywall | [打开](apps/lego-duplo-marvel-1573101225.md) |
| Muse: Reels Video Editor | Photo & Video | $56.80K | Free Trial - Soft Paywall | [打开](apps/muse-reels-video-editor-1638320348.md) |
| Phomemo | Education | $56.77K | No Free Trial - Soft Paywall | [打开](apps/phomemo-1456102145.md) |
| Glowify - AI Hairstyle Try On | Photo & Video | $56.42K | Free Trial - Soft Paywall | [打开](apps/glowify-ai-hairstyle-try-on-6751491972.md) |
| StudyFetch: Make Learning Easy | Education | $56.30K | No Free Trial - Soft Paywall | [打开](apps/studyfetch-make-learning-easy-6663574866.md) |
| Quiz AI: AI Homework Helper | Education | $56.02K | Free Trial - Soft Paywall | [打开](apps/quiz-ai-ai-homework-helper-6444201819.md) |
| Land id® | Productivity | $55.95K | Free Trial - Soft Paywall | [打开](apps/land-id-1173937731.md) |
| Aveola: 1-on-1 Live Video Chat | Entertainment | $55.29K | Currency Paywall | [打开](apps/aveola-1-on-1-live-video-chat-1622015258.md) |
| GrowIt: Garden Planner | Lifestyle | $54.44K | Free Trial - Soft Paywall | [打开](apps/growit-garden-planner-6443580320.md) |
| Angel: Stream TV & Movies | Entertainment | $54.34K | No Free Trial - Soft Paywall | [打开](apps/angel-stream-tv-and-movies-1473663873.md) |
| WeMoms - Pregnancy & Baby App | Medical | $54.21K | Free Trial - Soft Paywall | [打开](apps/wemoms-pregnancy-and-baby-app-938845147.md) |
| Turbo AI - Notetaker | Education | $53.95K | Free Trial - Soft Paywall | [打开](apps/turbo-ai-notetaker-6502794561.md) |
| SignNow: e-Signature app | Productivity | $53.83K | Free Trial - Soft Paywall | [打开](apps/signnow-e-signature-app-489262811.md) |
| Dr. Kegel: For Men’s Health | Health & Fitness | $53.67K | Free Trial - Soft Paywall | [打开](apps/dr-kegel-for-men-s-health-1470065487.md) |
| Globoplay: Novelas, séries e + | Entertainment | $53.41K | No Free Trial - Soft Paywall | [打开](apps/globoplay-novelas-s-ries-e-536321738.md) |
| AI Video Photo Generator Videa | Photo & Video | $53.38K | No Free Trial - Soft Paywall | [打开](apps/ai-video-photo-generator-videa-6738990592.md) |
| iMemories | Photo & Video | $53.00K | No Free Trial - Soft Paywall | [打开](apps/imemories-528388477.md) |
| Popl: AI Lead Capture | Business | $52.92K | Free Trial - Soft Paywall | [打开](apps/popl-ai-lead-capture-1503939262.md) |
| AI ChatBot Assistant: AskEasy | Productivity | $52.76K | Free Trial - Soft Paywall | [打开](apps/ai-chatbot-assistant-askeasy-6447290444.md) |
| America's Test Kitchen | Food & Drink | $52.72K | Free Trial - Soft Paywall | [打开](apps/america-s-test-kitchen-1365223384.md) |
| Mooze - Relaxing & Antistress | Lifestyle | $52.37K | Free Trial - Soft Paywall | [打开](apps/mooze-relaxing-and-antistress-6447049042.md) |
| Home Planner AI：Room Design 3D | Lifestyle | $52.20K | No Free Trial - Soft Paywall | [打开](apps/home-planner-ai-room-design-3d-1076159017.md) |
| MyFitnessPal: Calorie Counter | Health & Fitness | $52.15K | Free Trial - Soft Paywall | [打开](apps/myfitnesspal-calorie-counter-341232718.md) |
| Tennis Channel | Sports | $52.06K | No Free Trial - Soft Paywall | [打开](apps/tennis-channel-651092377.md) |
| Language Learning - Ling | Education | $52.00K | Free Trial - Soft Paywall | [打开](apps/language-learning-ling-1403783779.md) |
| LifeLock Identity | Finance | $51.97K | No Free Trial - Soft Paywall | [打开](apps/lifelock-identity-1422875903.md) |
| Flipped:Chat with AI Character | Entertainment | $51.86K | No Free Trial - Soft Paywall | [打开](apps/flipped-chat-with-ai-character-6445969623.md) |
| Scanner – Scan PDF & Document | Business | $51.76K | Free Trial - Soft Paywall | [打开](apps/scanner-scan-pdf-and-document-1291962681.md) |
| VPN Lumos: Open & Connect USA | Utilities | $51.71K | Free Trial - Soft Paywall | [打开](apps/vpn-lumos-open-and-connect-usa-1373844471.md) |
| memory OS: Brain Training | Education | $51.64K | No Free Trial - Soft Paywall | [打开](apps/memory-os-brain-training-1553283646.md) |
| The Sculpt Society | Health & Fitness | $51.39K | Free Trial - Soft Paywall | [打开](apps/the-sculpt-society-1481275761.md) |
| BoldVoice: Accent Training | Education | $51.34K | Free Trial - Soft Paywall | [打开](apps/boldvoice-accent-training-1567841142.md) |
| Budge World: Learning & Fun | Education | $51.12K | No Free Trial - Soft Paywall | [打开](apps/budge-world-learning-and-fun-1051902027.md) |
| AllConvert Kit - Image & Video | Utilities | $51.09K | Free Trial - Soft Paywall | [打开](apps/allconvert-kit-image-and-video-6456411698.md) |
| QR Code Reader＊Barcode Scanner | Utilities | $50.79K | No Free Trial - Soft Paywall | [打开](apps/qr-code-reader-barcode-scanner-1584764976.md) |
| Super Simple - Kids Songs | Education | $50.75K | Free Trial - Soft Paywall | [打开](apps/super-simple-kids-songs-1458640095.md) |
| Gronda: Recipes for Chefs | Food & Drink | $50.66K | Free Trial - Soft Paywall | [打开](apps/gronda-recipes-for-chefs-1164423781.md) |
| Forms for Google Docs | Productivity | $50.60K | Free Trial - Soft Paywall | [打开](apps/forms-for-google-docs-1619382448.md) |
| Trucker Path: Truck GPS & Fuel | Navigation | $50.58K | Free Trial - Soft Paywall | [打开](apps/trucker-path-truck-gps-and-fuel-782746890.md) |
| Workout for Women: Home & Gym | Health & Fitness | $50.53K | Free Trial - Soft Paywall | [打开](apps/workout-for-women-home-and-gym-839285684.md) |
| Eato®: Calorie Tracker | Health & Fitness | $49.93K | Free Trial - Soft Paywall | [打开](apps/eato-calorie-tracker-6478076952.md) |
| NGL: ask me anything | Lifestyle | $49.91K | No Free Trial - Soft Paywall | [打开](apps/ngl-ask-me-anything-1596550932.md) |
| Celebs - Celebrity Look Alike | Photo & Video | $49.78K | Free Trial - Soft Paywall | [打开](apps/celebs-celebrity-look-alike-1488127870.md) |
| Deepstash: Smarter Every Day! | Education | $49.66K | No Free Trial - Soft Paywall | [打开](apps/deepstash-smarter-every-day-1445023295.md) |
| AI Catch: AI Video Generator | Photo & Video | $49.54K | No Free Trial - Soft Paywall | [打开](apps/ai-catch-ai-video-generator-6739276631.md) |
| The Wall Street Journal. News | News | $49.24K | No Free Trial - Soft Paywall | [打开](apps/the-wall-street-journal-news-364387007.md) |
| RIZZ | Lifestyle | $49.11K | Free Trial - Soft Paywall | [打开](apps/rizz-1663430725.md) |
| DaVinci - Image Generator AI | Photo & Video | $49.06K | Free Trial - Soft Paywall | [打开](apps/davinci-image-generator-ai-1630366866.md) |
| Calculator₊ | Utilities | $48.80K | Free Trial - Soft Paywall | [打开](apps/calculator-398129933.md) |
| AI Calorie Counter - Appediet | Health & Fitness | $48.77K | Free Trial - Soft Paywall | [打开](apps/ai-calorie-counter-appediet-6450329545.md) |
| Rap Fame - Rap Music Studio | Music | $48.42K | Free Trial - Soft Paywall | [打开](apps/rap-fame-rap-music-studio-1476399789.md) |
| Clean Manager: Storage Cleaner | Utilities | $48.28K | Free Trial - Soft Paywall | [打开](apps/clean-manager-storage-cleaner-1579881271.md) |
| Halo AI: Photo & Video Editor | Photo & Video | $48.17K | Free Trial - Hard Paywall | [打开](apps/halo-ai-photo-and-video-editor-6740445587.md) |
| Full Code Medical Simulation | Medical | $48.07K | No Free Trial - Soft Paywall | [打开](apps/full-code-medical-simulation-1207424206.md) |
| KidloLand Kids Toddler Games | Education | $48.03K | Free Trial - Soft Paywall | [打开](apps/kidloland-kids-toddler-games-533412119.md) |
| Fachat: Chat & Community | Social Networking | $47.95K | Currency Paywall | [打开](apps/fachat-chat-and-community-1475875470.md) |
| Fitness AI Gym Workout Planner | Health & Fitness | $47.79K | No Free Trial - Soft Paywall | [打开](apps/fitness-ai-gym-workout-planner-1446224156.md) |
| HuntStand: GPS Maps & Tools | Sports | $47.77K | No Free Trial - Soft Paywall | [打开](apps/huntstand-gps-maps-and-tools-778772892.md) |
| Unfold: Reels & Story Maker | Photo & Video | $47.60K | No Free Trial - Soft Paywall | [打开](apps/unfold-reels-and-story-maker-1247275033.md) |
| Pillow: Sleep Tracker | Health & Fitness | $47.57K | Free Trial - Soft Paywall | [打开](apps/pillow-sleep-tracker-878691772.md) |
| Justin Guitar Lessons & Songs | Education | $47.55K | Free Trial - Soft Paywall | [打开](apps/justin-guitar-lessons-and-songs-1176125504.md) |
| Perfect365 Makeup Photo Editor | Lifestyle | $47.50K | Free Trial - Soft Paywall | [打开](apps/perfect365-makeup-photo-editor-475976577.md) |
| Precious - Baby Photo Art | Lifestyle | $47.24K | Free Trial - Soft Paywall | [打开](apps/precious-baby-photo-art-1103530261.md) |
| MBC Shahid | Entertainment | $47.17K | No Free Trial - Soft Paywall | [打开](apps/mbc-shahid-879915134.md) |
| Podcast App | News | $47.03K | Free Trial - Soft Paywall | [打开](apps/podcast-app-1199070742.md) |
| Livly Island - Adopt Cute Pets | Social Networking | $46.97K | No Free Trial - Soft Paywall | [打开](apps/livly-island-adopt-cute-pets-1553045339.md) |
| pdfFiller: edit PDF documents | Business | $46.91K | Free Trial - Soft Paywall | [打开](apps/pdffiller-edit-pdf-documents-571613512.md) |
| The Atlantic Magazine | News | $46.89K | Free Trial - Soft Paywall | [打开](apps/the-atlantic-magazine-397599894.md) |
| Epoch Times: Live & Breaking | News | $46.82K | No Free Trial - Soft Paywall | [打开](apps/epoch-times-live-and-breaking-670443321.md) |
| I Am Sober | Lifestyle | $46.78K | Free Trial - Soft Paywall | [打开](apps/i-am-sober-672904239.md) |
| QR Reader for iPhone | Utilities | $46.78K | Free Trial - Soft Paywall | [打开](apps/qr-reader-for-iphone-368494609.md) |
| Retouch Me: Face, Body Editor | Photo & Video | $46.65K | Free Trial - Soft Paywall | [打开](apps/retouch-me-face-body-editor-830286763.md) |
| Dino Fun - Games for kids | Education | $46.60K | Free Trial - Soft Paywall | [打开](apps/dino-fun-games-for-kids-549750492.md) |
| Brainly: Your Personal Tutor | Education | $46.40K | No Free Trial - Soft Paywall | [打开](apps/brainly-your-personal-tutor-745089947.md) |
| DreameShort - Drama TV | Entertainment | $46.22K | No Free Trial - Soft Paywall | [打开](apps/dreameshort-drama-tv-6462846884.md) |
| LUDEX Sports Card Scanner +TCG | Sports | $45.89K | No Free Trial - Soft Paywall | [打开](apps/ludex-sports-card-scanner-tcg-1616691213.md) |
| CleanX: Photo Storage Cleaner | Utilities | $45.86K | Free Trial - Soft Paywall | [打开](apps/cleanx-photo-storage-cleaner-1575903244.md) |
| Remote for Firestick · Fire TV | Utilities | $45.76K | No Free Trial - Soft Paywall | [打开](apps/remote-for-firestick-fire-tv-1625553531.md) |
| Crayola Create and Play: Kids | Education | $45.74K | Free Trial - Soft Paywall | [打开](apps/crayola-create-and-play-kids-1431955703.md) |
| Course Hero: AI Homework Help | Education | $45.66K | No Free Trial - Soft Paywall | [打开](apps/course-hero-ai-homework-help-922208952.md) |
| Calculator Air: AI Math Solver | Utilities | $45.46K | Free Trial - Soft Paywall | [打开](apps/calculator-air-ai-math-solver-1173365557.md) |
| Real - Sports | Sports | $45.33K | No Free Trial - Soft Paywall | [打开](apps/real-sports-1514546162.md) |
| Photo Eraser - Remove Objects | Photo & Video | $45.12K | Free Trial - Soft Paywall | [打开](apps/photo-eraser-remove-objects-1465934502.md) |

---

## 按品类浏览

- [Photo & Video](categories/photo-video.md)
- [Social Networking](categories/social-networking.md)
- [Music](categories/music.md)
- [Lifestyle](categories/lifestyle.md)
- [Sports](categories/sports.md)
- [News](categories/news.md)
- [Productivity](categories/productivity.md)
- [Business](categories/business.md)
- [Finance](categories/finance.md)
- [Education](categories/education.md)
- [Health & Fitness](categories/health-and-fitness.md)
- [Medical](categories/medical.md)
- [Utilities](categories/utilities.md)
- [Entertainment](categories/entertainment.md)
- [Travel](categories/travel.md)
- [Reference](categories/reference.md)
- [Food & Drink](categories/food-and-drink.md)
- [Shopping](categories/shopping.md)
- [Books](categories/books.md)
- [Navigation](categories/navigation.md)
- [Weather](categories/weather.md)
- [Graphics & Design](categories/graphics-and-design.md)
- [Games](categories/games.md)

---

## 按付费墙模式浏览

- [Free Trial Paywalls](docs/free-trial-paywalls.md)
- [Monthly vs Annual Pricing](docs/monthly-vs-annual-pricing.md)
- [Paywall Pattern Taxonomy](docs/paywall-pattern-taxonomy.md)

---

## 适合哪些使用场景？

对独立开发者：

- 在上线订阅 App 前查找定价参考
- 学习头部 App 如何解释订阅价值
- 对比免费试用与非试用付费墙结构

对产品经理：

- Benchmark 不同品类的付费墙模式
- 为付费墙改版准备参考案例
- 理解竞品如何组织套餐和权益

对增长团队：

- 分析价格锚点
- 研究试用期呈现方式
- 寻找付费墙 A/B 测试方向

对设计师：

- 研究布局、视觉层级、套餐卡片、CTA 和权益表达方式
- 建立订阅 UX 参考库

---

## 路线图

- 格式校验批处理
- Top 100 精选数据集
- Top 500 公开数据集
- 品类索引页
- 付费墙模式索引页
- 持续扩展和更新
- 基于 GitHub Actions 的自动更新流水线

---

## 贡献

发现值得记录的付费墙？发现数据错误？

请查看 [CONTRIBUTING.zh-CN.md](CONTRIBUTING.zh-CN.md)。

---

## License 和使用说明

本仓库中的结构化元数据可用于学习、研究、评论和内部产品参考，使用时请注明出处。

你不能批量复制、重新包装、转售这些数据，或使用该数据集构建商业化竞品付费墙情报产品。

截图和 UI 版权归各自 App 开发者所有。完整条款请查看 [LICENSE](LICENSE)。

---

## Powered by PaywallPro

Open Paywall Gallery 由 PaywallPro 发布。

PaywallPro 帮助订阅 App 团队研究头部 iOS App 的付费墙、Onboarding 流程、定价模型、历史变化和变现数据信号。
