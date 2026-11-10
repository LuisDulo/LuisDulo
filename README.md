# Luis Okal Dulo

**Software developer** - BSc Informatics and Computer Science, Strathmore University (graduating July 2027) - Nairobi, Kenya

[![Portfolio](https://img.shields.io/badge/Portfolio-luisdulo.github.io-064E3B?style=flat-square&logo=githubpages&logoColor=white)](https://luisdulo.github.io) [![CV](https://img.shields.io/badge/CV-PDF-0D9488?style=flat-square&logo=readthedocs&logoColor=white)](https://luisdulo.github.io/cv/Luis_Okal_CV.pdf) [![Email](https://img.shields.io/badge/Email-luisokal15%40gmail.com-D6A84F?style=flat-square&logo=gmail&logoColor=white)](mailto:luisokal15@gmail.com) ![Phone](https://img.shields.io/badge/Phone-%2B254%20796%20890%20292-1F2937?style=flat-square&logo=whatsapp&logoColor=white)

I build software that handles real money and real data for people in Kenya: school meal payments over M-Pesa, savings groups, fuel price data, and plain-language answers about tax, SHA and HELB rules. I work across the stack, from Django and FastAPI back ends to React and React Native front ends, and I like proving that things work: a test for every fix, evaluation sets for models, and quality checks before data is published.

**Open to internships now, and graduate software roles from July 2027.**

## Featured projects

| Project | What it is | Result | Stack |
|---|---|---|---|
| [Smart School Feeding](https://github.com/LuisDulo/smart-school-feeding) | Capstone with Webmasters Kenya. Parents top up a child's meal balance by M-Pesa, kitchen staff serve meals by QR code, admins see balances, demand forecasts and suspicious payments. | XGBoost forecasts meals with an R-squared of 0.81; the meal anomaly detector caught all 53 injected anomalies at 88% precision; 244 backend tests | Django REST, PostgreSQL, React, React Native, scikit-learn, XGBoost |
| [CHAMA](https://github.com/LuisDulo/chama) | Platform for running savings groups: many chamas per account, versioned rules, M-Pesa STK Push and a double-entry ledger. | 12 of 12 acceptance criteria met, 129 backend tests | Django REST, PostgreSQL, React, TypeScript, M-Pesa Daraja |
| [Sheria RAG](https://github.com/LuisDulo/sheria-rag) | Chatbot for Kenyan tax, SHA and HELB rules that answers only from official guidance and says so when the pages do not cover a question. | Hit@12 of 0.98 on 44 labelled questions | Python, FastAPI, pgvector, Claude API, React |
| [Kenya Prices Pipeline](https://github.com/LuisDulo/kenya-prices-pipeline) | Daily pipeline for EPRA pump prices and CBK inflation into a PostgreSQL star schema and Power BI. | 8 quality checks before every publish; a failed check rolls the run back | TypeScript, Node.js, PostgreSQL, GitHub Actions |
| [Security review](https://github.com/LuisDulo/smart-school-feeding-security-review) | OWASP Top 10 review of my capstone, starting from the money. Found a critical flaw where a forged M-Pesa callback could credit an account without payment. | 10 of 11 findings fixed, each proved by a test; CI with security scans added | pytest, pip-audit, bandit, npm audit |

Every project is run like a team project: a public roadmap board, sprint milestones, and one issue and pull request per change. The apps also have screenshots of the running system in their `docs/` folders.

## Open source

- **[react/metro#2216](https://github.com/react/metro/pull/2216)** (React Native's bundler, open): fixes a Windows crash where OneDrive placeholder files are reported as symlinks, with a test.

## Experience

**IT and Digital Transformation attachment** - Isuzu East Africa, 2026
- Resolved help desk tickets, and set up and networked new machines.
- Kept the IT asset records up to date.
- Automated support workflows with Power Apps and Power Automate.

## Education

**BSc Informatics and Computer Science** - Strathmore University, Nairobi - graduating July 2027
- Capstone: Smart School Feeding, with Webmasters Kenya as partner organisation, run in Agile Scrum over five two-week sprints.

## Skills

[![Skills](https://skillicons.dev/icons?i=py,django,fastapi,js,ts,react,nodejs,express,postgres,mongodb,kotlin,githubactions,git,powershell)](https://luisdulo.github.io)

| Area | Tools |
|---|---|
| Back end | Django REST Framework, FastAPI, Node.js and Express, REST API design, JWT auth |
| Front end and mobile | React, TypeScript, React Native and Expo, Kotlin with Jetpack Compose |
| Data and machine learning | PostgreSQL, pgvector, scikit-learn, XGBoost, ETL pipelines, Power BI |
| Payments | M-Pesa Daraja: STK Push, callbacks, reconciliation |
| Quality and security | pytest, Vitest, GitHub Actions CI, OWASP Top 10, pip-audit, bandit |
| Ways of working | Agile Scrum, issues and pull requests, code review |

## Other projects

- [Artify](https://github.com/LuisDulo/ICS-Project1-): art marketplace with an in-browser canvas, live chat and M-Pesa payments (Node.js, Express, MongoDB).
- [TicketMaster App](https://github.com/LuisDulo/TicketMasterApp): Android event ticketing with M-Pesa STK Push and Firebase (Kotlin, Jetpack Compose).
- [C and Assembly](https://github.com/LuisDulo/assembly-c-activity): a C program calling a hand-written x86-64 factorial routine.
- [Portfolio site](https://github.com/LuisDulo/LuisDulo.github.io): React site whose language chart is measured from these repositories by a tested Python script.
