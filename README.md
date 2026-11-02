## Gustavo Silveira · Senior Data & BI Analyst

I turn operational data into numbers people agree on. I clarify the business rules first, write them into SQL
Server once, check them against independent queries, and deliver them in Power BI dashboards or a Python web
app. I have worked in telecom operations reporting since 2018. Based in Pamplona, Spain; remote work welcome.

**Scylla Data Lab** is the name I use for my portfolio and freelance work.

### What I can help with

| Need | How I usually solve it | Shown in |
|---|---|---|
| Dashboards that answer a management question | Power BI on a star schema, measures that stay correct under any filter | [Telecom operations](https://github.com/scylladl/telecom-operations-intelligence), [Sales & revenue](https://github.com/scylladl/sales-revenue-analytics) |
| Reports everyone trusts | Rules in SQL views and procedures, data quality checks, validation against the source | [Telecom operations](https://github.com/scylladl/telecom-operations-intelligence), [Sales & revenue](https://github.com/scylladl/sales-revenue-analytics) |
| Actual versus budget, and why the margin moved | Budget prepared from the finance Excel in Power Query, margin bridge, incremental SQL load | [Sales & revenue](https://github.com/scylladl/sales-revenue-analytics) |
| A small internal web app on company data | Streamlit with login, the same SQL rules as the dashboards | [Telecom operations](https://github.com/scylladl/telecom-operations-intelligence/tree/main/app), [Operations portal](https://github.com/scylladl/operations-management-portal) |
| A workflow with approvals and an audit trail | Roles and rules enforced in SQL Server, every change audited in the same transaction, tested per role | [Operations portal](https://github.com/scylladl/operations-management-portal) |
| Manual Excel reporting that takes hours | Python and SQL automation, scheduled refresh | — |

### Featured projects

**[B2B Network Operations Intelligence](https://github.com/scylladl/telecom-operations-intelligence)** (simulated client and data):
incident volume, SLA, repeat failures, backlog and the real effect of improvement actions for a fictional
Spanish telecom operator. SQL Server processing with logging and data quality checks, a Power BI report in three
designs, and a Streamlit app with login. Every main KPI matches independent SQL: 21 of 21.

![Overview of the Power BI report](https://raw.githubusercontent.com/scylladl/telecom-operations-intelligence/main/docs/screenshots/01-overview.png)

**[Sales & Revenue Analytics](https://github.com/scylladl/sales-revenue-analytics)** (simulated company and data):
sales, margin and budget for a fictional Spanish coffee roaster with three channels. Incremental SQL Server load
that a test proves equal to a full reload, the budget prepared from an Excel workbook in Power Query, a margin
bridge, and a Power BI report in a light and a dark design. Every main KPI matches independent SQL: 231 of 231.

![Overview of the sales report](https://raw.githubusercontent.com/scylladl/sales-revenue-analytics/main/docs/screenshots/01-overview.png)

**[Operations Management Portal](https://github.com/scylladl/operations-management-portal)** (simulated company and data):
the internal portal where the same fictional operator requests, approves, carries out and verifies improvement
actions. Four roles with authorization in SQL Server stored procedures, an audit trail written in the same
transaction as each change, optimistic concurrency, Argon2id passwords, and an export that feeds the existing
report unchanged. 903 automated tests, including every role × transition × status.

![Action page of the operations portal](https://raw.githubusercontent.com/scylladl/operations-management-portal/main/docs/screenshots/12-verified-history.png)

### Tools

SQL Server (T-SQL, stored procedures, views) · Power BI (DAX, Power Query, PBIP) · Python (pandas, Streamlit) ·
PowerShell · Git

### Contact

[LinkedIn](https://www.linkedin.com/in/gustavo-d-silveira-72b9b9218/) · [scylla.datalab@outlook.com](mailto:scylla.datalab@outlook.com)

---

**En español.** Analista Sénior de Datos y BI. Defino las reglas de negocio con el cliente, las implemento una vez
en SQL Server, las valido contra la fuente y las entrego en Power BI o en una aplicación web con Python. Trabajo
en reporting de operaciones de telecomunicaciones desde 2018. Pamplona, España; disponible en remoto.
