# stora1

Upplýsingar um keyrslu á verkefni:
Um er að ræða þrjár HTML síður. Index.html er forsíðan sem inniheldur hlekki á annarsvegar kaupa.html og hins vegar um.html, um.html inniheldur texta 
sem að lýsir þjónustunni sem verið er að bjóða og á kaupa.html má slá inn persónuupplýsingar til að kaupa þessa þjónustu. Síður voru útbúnar með BEM syling elementum 
í huga og lýsandi divum og divklösum. Til þess að útfæra útlit síðanna var notast við minni scss skrár og miðlæga styles.css sem tekur við breytingum í scss skrám, 
allar scss skrárnar eru í einni möppu sem heitir scss. Allar breytingar á scss skrám eru beinþýddar yfir í styles.css sem að ræður útliti síðanna. Til þess að þessi 
tenging verði þarf vefhönnuður að hafa node og niðurhala package.json skrá (npm install) í command glugga verkefnis. Keyra skal lint (npm run lint) sem að finnur villur í stílbroti í scss skrám,
og síðasta skrefið er svo að keyra dev (npm run dev) þá opnast vafrinn `http://localhost:3000` og allar breytingar sem við gerum endurhlaðast sjálfkrafa.
Notast var við grid til að stýra útlíti síðna, því var stýrt með því að gefa klösum í html nafn sem að lýsir því hversu marga dálka hvert klausa á að taka og svo stílað í grid.scss.
 

Um er að ræða 10 scss skrár sem að stíla mismunandi atriðum:
button - stílar alla takka
card - stílar kortið á forsíðu
cardlist - cardlist stílar myndalista á forsíðu
footer - stílar síðufót (footer)
form - stílar formi á kaupa.html
grid - inniheldur upplýsingar og stílar grid
header - stílar haus á um.html og kaupa.html
heading - stílar fyrirsögnum
hero - stílar haus á forsíðu index.html
nav - stílar yfirlitsstiku
text - stílar allan texta

Til þess að deila nýjustu útfærslum af verkefninu var github notað, þar bjuggum til sameiginlegt verkefni kallað stora1. Í upphaf hvers vinnutíma var náð í nýjustu útgáfu
af verkefninu (git pull origin master) og í lok hverra breytinga var bætt við (git add .), staðfest (git commit -m "komment frá notanda") og nýjustu útgáfu ýtt frá sér
 (git origin push master). Þessu var öllu stýrt úr command glugga verkefnis.

Undir verkefni stóra eru þrjár möppur, undir möppunni gögn eru öll gögn sem að við þurfum þ.e.a.s. allar myndir. Undir node eru pakkarnir sem að stýra tengingum scss og css
og undir scss eru allar scss skrárnar. Inní möppunni stora1 eru svo html síðurnar og aðrir file-ar sem að ekki var unnið með. Styles er þar inni og ekki skal eiga neitt við 
þá skrá.

Þetta verkefni var unnið af: 
Manuelu Magnúsdóttur, mam5@hi.is
Vilborgu Gísladóttur, vig5@hi.is og
Þorbjörgu Þórhildi Snorradóttur, ths242@hi.is