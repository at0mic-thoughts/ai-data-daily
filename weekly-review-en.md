📰 **AI Data Weekly Review — Week of March 9-15, 2026**

━━━━━━━━━━━━━━━━━━━━

🏆 **Story of the Week**

📌 **Microsoft disables V-Order by default in new Fabric lakehouses** — Microsoft quietly changed the default V-Order configuration in Fabric lakehouses this week (March 1 update). V-Order, their columnar storage optimization that improved query performance, is now disabled for new lakehouses. Existing ones keep their configuration. Why does this matter? If you're spinning up new Fabric environments, you'll need to manually enable V-Order to get the performance benefits you might expect. Microsoft hasn't explained the reasoning, but it's likely related to storage costs or write performance trade-offs.

━━━━━━━━━━━━━━━━━━━━

📊 **The Week in Numbers**

**83** vulnerabilities fixed in Microsoft's March 2026 Patch Tuesday, including one actively exploited zero-day  
**1** new Azure Databricks Data Engineer Associate certification launched  
**153** upvotes on r/dataengineering for hidden BigQuery features that most people don't know about  
**439,917** members in the data engineering subreddit discussing testing practices and AI impact  

━━━━━━━━━━━━━━━━━━━━

🔥 **Top 5 Stories You Might Have Missed**

⚡ **New Microsoft Azure Databricks certification drops** — Microsoft launched the Azure Databricks Data Engineer Associate certification on March 13th. Covers Unity Catalog, Delta Lake design patterns, Azure integrations, and security best practices. If you're working in the Microsoft + Databricks ecosystem, this is the credential that proves you know both sides of the fence.

🎯 **BigQuery's hidden features are actually useful** — A viral Reddit post shared 5 lesser-known BigQuery features: chained function calls, UNION ALL BY NAME, and WITH expressions (not CTEs). The chained functions are genuinely handy: `SELECT (name).TRIM().REPLACE(' ', '_').UPPER()` instead of nested function hell. Worth bookmarking if you're stuck in BigQuery land.

🤖 **AI burnout hits data teams differently** — r/dataengineering had a sobering discussion about AI tools increasing workload instead of reducing it. One DE shared how Claude agents replaced his dashboard work while developers ship features faster, leaving him questioning his role. The reality check: AI doesn't reduce work, it raises expectations.

🧪 **Data testing culture remains inconsistent** — A popular thread about testing in data engineering revealed the community is split between teams with full dbt test suites and Great Expectations pipelines versus teams that "eyeball row counts and pray." The consensus: DE testing is decades behind traditional software development.

📈 **dbt + Unity Catalog best practices get an update** — The dbt docs were updated with fresh guidance on Unity Catalog integration, emphasizing cross-catalog data references and Delta Live Tables materialized views. If you're running dbt in a Unity Catalog environment, worth reviewing for optimization opportunities.

━━━━━━━━━━━━━━━━━━━━

🔮 **What to Watch This Week**

Microsoft Build is coming in May, but expect more Fabric updates to drop throughout March. The V-Order change suggests they're still tuning performance defaults. 

Databricks is likely to announce more Unity Catalog features following the new certification launch. 

OpenAI's rumored GPT-5 could shake up the AI tooling landscape if it delivers the promised reasoning improvements.

━━━━━━━━━━━━━━━━━━━━

📌 **Platform Updates**

**Microsoft Fabric** — V-Order disabled by default for new lakehouses (March 1)  
**Azure** — Databricks Data Engineer Associate certification available (March 13)  
**BigQuery** — Chained function calls and other power features getting more attention  
**Unity Catalog** — Updated dbt integration best practices published  

*Sources: Microsoft Fabric Blog, Azure Tech Community, Databricks Blog, r/dataengineering, dbt Developer Hub, Microsoft security bulletins*