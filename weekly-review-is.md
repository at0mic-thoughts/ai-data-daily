📰 **AI Data Weekly — Vikan sem var, 9.-15. mars 2026**

━━━━━━━━━━━━━━━━━━━━

🏆 **Saga vikunnar**

📌 **Microsoft slekkur á V-Order sjálfkrafa í nýjum Fabric lakehouses** — Microsoft breytti hljóðlega sjálfgefnu V-Order stillingunum í Fabric lakehouses þessa viku (1. mars uppfærsla). V-Order, dálkalagageymslubæting þeirra sem bætti fyrirspurnargógn, er nú slökkt fyrir nýja lakehouses. Þeir sem til eru halda sínum stillingum. Af hverju skiptir þetta máli? Ef þú ert að setja upp ný Fabric umhverfi þarftu að virkja V-Order handvirkt til að fá frammistöðuávinninginn sem þú gætir búist við. Microsoft hefur ekki útskýrt ástæðuna, en það er líklega tengt geymslukostnaði eða skrifgógn málamiðlunum.

━━━━━━━━━━━━━━━━━━━━

📊 **Vikan í tölum**

**83** veikindi lagfærð í Microsoft's mars 2026 Patch Tuesday, þar á meðal einn sem er virkur zero-day  
**1** ný Azure Databricks Data Engineer Associate vottun sett af stað  
**153** upvotes á r/dataengineering fyrir falda BigQuery eiginleika sem flestir vita ekki um  
**439.917** meðlimir í data engineering subreddit að ræða prófunaraðferðir og AI áhrif  

━━━━━━━━━━━━━━━━━━━━

🔥 **Fimm sem þú gætir hafa misst af**

⚡ **Ný Microsoft Azure Databricks vottun kemur út** — Microsoft setti af stað Azure Databricks Data Engineer Associate vottunina 13. mars. Nær yfir Unity Catalog, Delta Lake hönnunarmynstur, Azure samþættingar og öryggisbestu starfshætti. Ef þú ert að vinna í Microsoft + Databricks vistkerfinu er þetta skilríkið sem sannar að þú þekkir báðar hliðar girðingarinnar.

🎯 **Faldir eiginleikar BigQuery eru í raun gagnlegir** — Viral Reddit færsla deildi 5 minna þekktum BigQuery eiginleikum: keðjuð fall köll, UNION ALL BY NAME og WITH segðir (ekki CTEs). Keðjuðu föllin eru raunverulega praktísk: `SELECT (name).TRIM().REPLACE(' ', '_').UPPER()` í stað hreiðraðs falls helvítis. Þess virði að bókamerkja ef þú ert fastur í BigQuery landinu.

🤖 **AI kulnun kemur öðruvísi fyrir data teymi** — r/dataengineering átti áhyggjufull umræður um AI verkfæri að auka vinnuálag í stað þess að minnka það. Einn DE deildi því hvernig Claude umboðsmenn komu í stað dashboard vinnu hans á meðan þróunaraðilar senda eiginleika hraðar, sem lætur hann efast um hlutverk sitt. Raunveruleikaskoðunin: AI minnkar ekki vinnu, það hækkar væntingar.

🧪 **Data prófunarmennir halda áfram að vera ósamkvæmt** — Vinsæll þráður um prófanir í data engineering leiddi í ljós að samfélagið er skipti milli teymi með fullt dbt prófunarsvítur og Great Expectations leiðslum á móti teymi sem "sjá í gegnum röðtölur og biðja." Samþykktin: DE prófun er áratugi á eftir hefðbundinni hugbúnaðarþróun.

📈 **dbt + Unity Catalog bestu starfshættir fá uppfærslu** — dbt skjölin voru uppfærð með fersku leiðbeiningar um Unity Catalog samþættingu, með áherslu á þvert-catalog gögn tilvísanir og Delta Live Tables efnislegar skoðanir. Ef þú ert að keyra dbt í Unity Catalog umhverfi, þess virði að endurskoða fyrir hagræðingartækifæri.

━━━━━━━━━━━━━━━━━━━━

🔮 **Framundan**

Microsoft Build kemur í maí, en búast má við fleiri Fabric uppfærslum allan mars. V-Order breytingin bendir til þess að þeir séu enn að stilla frammistöðu sjálfgildin.

Databricks mun líklega tilkynna fleiri Unity Catalog eiginleika eftir nýja vottunarsetningu.

OpenAI's ýmsugerð GPT-5 gæti valdið AI verkfæralandslag ef það skilar lofuðum rökhugsun bættum.

━━━━━━━━━━━━━━━━━━━━

📌 **Uppfærslur á kerfum**

**Microsoft Fabric** — V-Order slökkt sjálfkrafa fyrir nýja lakehouses (1. mars)  
**Azure** — Databricks Data Engineer Associate vottun tiltæk (13. mars)  
**BigQuery** — Keðjuð fall köll og aðrir valdaeiginleikar fá meiri athygli  
**Unity Catalog** — Uppfærðar dbt samþættingar bestu starfshættir birtar  

*Heimildir: Microsoft Fabric Blog, Azure Tech Community, Databricks Blog, r/dataengineering, dbt Developer Hub, Microsoft öryggisbréf*