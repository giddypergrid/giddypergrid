## Ziyuan Sun

Master of Applied Computing student at Lincoln University, New Zealand, graduating November 2026.
Currently on a data engineering placement at Selwyn District Council, auditing customer data.

Here are some stuff I built that are live.

### Live

| | What it is | Scale | Stack |
|---|---|---|---|
| 📄 **[Fine Print](https://www.nzfineprint.com)** | An AI agent over the NZ public record. Ask it about a company in plain English and it traces the notices and cites them. | 206,431 notices back to 2000, updated nightly | FastAPI · Postgres + pgvector · Redis · DeepSeek |
| 🐦 **[NZ Bird Sound Database](https://nzbirddatabase.com)** | Upload a recording, a model names the bird. Or describe one and it ranks the closest matches. | 138 species, 40GB+ of audio | Django REST · React · AWS ECS Fargate |
| 💧 **[Global Freshwater Monitoring](https://global-freshwater-monitoring.vercel.app)** | Built for AgResearch. Shows whether a river monitoring site could actually detect a nutrient reduction. | 15,313 site-nutrient records, 1,177 catchments | Next.js · Leaflet · no backend |
| 🐄 **[Parenchyma Measure](https://giddypergrid.github.io/Parenchyma-Measure-Label-Tool/)** | Lincoln dairy researchers label calf ultrasound scans with it. Replaced a manual MATLAB workflow. | in weekly use by the research group | React · Konva · runs entirely in the browser |

### Repositories worth opening

Each README leads with the design decisions rather than setup instructions.

- **[nzfineprint-backend](https://github.com/giddypergrid/nzfineprint-backend)**, the flagship. Three
  search routes, a four-tool agent, and a `DECISIONS.md` covering the calls I got wrong first.
- **[NZBirdSoundDatabase-AWS](https://github.com/giddypergrid/NZBirdSoundDatabase-AWS)**, the same
  app taken from "works on my machine" to ECS Fargate, with load shedding and 33 live API tests.
- **[global-freshwater-monitoring](https://github.com/giddypergrid/global-freshwater-monitoring)**,
  a statistics tool where the arithmetic runs in the browser and there is no server.

### Before study

Two years of production work in China: in-game UI and live state syncing for Eggy Party
(NetEase, Dekeinfo), and GPT integration on a PHP backend at a legal-tech startup.

### Reach me

[sunziyuan000@gmail.com](mailto:sunziyuan000@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/ziyuan-sun-694a27297/) · Christchurch, New Zealand

Open to software, data and AI engineering roles from November 2026. I hold a 3-year open Post Study
Work Visa.
