## Ziyuan Sun

Master of Applied Computing student at Lincoln University, New Zealand, graduating November 2026.
Currently on a data engineering placement at Selwyn District Council, auditing customer data.

I can comfortably handle full stack development and carry it through to delivery and deployment. The
part I want to keep working on is AI integration into real systems.

### What I work with

- **Languages:** Python, TypeScript, JavaScript, SQL
- **Web and backend:** React, Next.js, FastAPI, Django REST, PostgreSQL, MySQL, Redis
- **AWS:** for the bird sound project I ran the Django backend on ECS Fargate behind an Application
  Load Balancer, with PostgreSQL on RDS, 44 GiB of model and media files on EFS, secrets in Secrets
  Manager and logs in CloudWatch. Deploys go through GitHub Actions, with a manual rollback workflow
  that redeploys a known-good task revision.
- **AI and ML:** LLM integration, agents and tool calling, RAG, embeddings and vector search
  (pgvector, HNSW), AutoGluon and LightGBM, Gemini, GPT and DeepSeek APIs. I have taken machine
  learning and generative AI courses.
- **Data:** ETL pipelines, data quality, record linkage
- **Testing and CI:** pytest, live API tests against the deployed URL, k6 load testing, GitHub
  Actions, Docker, Linux, Git

### Live

| | What it is | Scale | Stack |
|---|---|---|---|
| 📄 **[Fine Print](https://www.nzfineprint.com)** | An AI agent over the NZ public record. Ask it about a company in plain English and it traces the notices and cites them. | 206,431 notices back to 2000, updated nightly | FastAPI · Postgres + pgvector · Redis · DeepSeek |
| 🐦 **[NZ Bird Sound Database](https://nzbirddatabase.com)** | Upload a recording, a model names the bird. Or describe one and it ranks the closest matches. | 138 species, 40GB+ of audio | Django REST · React · AWS ECS Fargate |
| 💧 **[Global Freshwater Monitoring](https://global-freshwater-monitoring.vercel.app)** | Built for AgResearch. Shows whether a river monitoring site could actually detect a nutrient reduction. | 15,313 site-nutrient records, 1,177 catchments | Next.js · Leaflet · no backend |
| 🐄 **[Parenchyma Measure](https://giddypergrid.github.io/Parenchyma-Measure-Label-Tool/)** | Lincoln dairy researchers label calf ultrasound scans with it. Replaced a manual MATLAB workflow. | in weekly use by the research group | React · Konva · runs entirely in the browser |

Each repository's README leads with the design decisions and what the thing is for.

### Reach me

[sunziyuan000@gmail.com](mailto:sunziyuan000@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/ziyuan-sun-694a27297/) · Christchurch, New Zealand

Open to software, data and AI engineering roles from November 2026. I hold a 3-year open Post Study
Work Visa.
