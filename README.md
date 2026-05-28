# Konsulentens Labmateriale

&nbsp;

## 📝 Bidra?

> Dette er et levende dokument som vokser med fellesskapet (forhåpentlig)

Commit rett i nettleser, eller såklart:
```
Klone → Endre → Pull Request → Merge
```

> Konkret innspill til en utviklers prosess - legg inn i struktur under. Generell kilde? Sleng inn i listen over *Brukbare kilder*.

### Nyttige "ting" å legge inn
- Tidløse og nyere forskningsartikler
- Gode verktøy
- Erfaringer med teknologivalg
- Blogger fra flinke folk
- Bøker
- Videor

## Generelt brukbare kilder
- *hva som helst her*

&nbsp;

&nbsp;

> Fra fresh til produksjonsklar uten omveier

---

## ⚡ Hurtigstart `1-2 Dager`
```
Git → Docker → FastAPI → Rust → Produksjon
```
- `2t` [Interaktiv Git](https://learngitbranching.js.org/) - Visuell grenkontroll
- `2t` [Docker Speedrun](https://docs.docker.com/get-started/) - Containeriser alt
- `1d` [Rust på 4 timer](https://doc.rust-lang.org/book/ch01-00-getting-started.html) - Minnesikker systemprogrammering
- `1d` [FastAPI + Deployment](https://fastapi.tiangolo.com/tutorial/first-steps/) - API til produksjon

---

&nbsp;

## 📚 Kjerneferdigheter `2-4 Uker`

### Informatikk
```
Matematikk → Algoritmer → Systemer → Ytelse
```
- [3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Visualisert informatikkmatematikk
- [Princeton Algoritmer](https://www.coursera.org/learn/algorithms-part1) - Industristandard
- [Bygg et OS](https://os.phil-opp.com/) - Systemprogrammering i Rust
- [Lag Programmeringsspråk](https://craftinginterpreters.com/) - Språkdesign

#### Ekstra kilder
- [TS Dybdedykk](https://basarat.gitbook.io/typescript/) - Viderekommet TypeScript
- [Testmønstre](https://testing-library.com/docs/react-testing-library/examples) - Profesjonell testing
- [Redis Universitet](https://university.redis.com/) - Cachehåndtering
- [Systemdesign](https://github.com/donnemartin/system-design-primer) - Skaleringskunst

---

&nbsp;

## 🔬 Avanserte Emner `1-3 Måneder`

### KI & ML

- [Original Transformer](https://arxiv.org/abs/1706.03762) - KI-grunnlag
- [GPT Implementering](https://github.com/karpathy/minGPT) - Bygg GPT
- [Fast.ai](https://www.fast.ai/) - ML for utviklere
- [LangChain](https://python.langchain.com/docs/get_started/quickstart) - KI-agenter

### Systemer
```
Ytelse → Distribusjon → WebAssembly → Edge
```
- [Linux Ytelse](http://www.brendangregg.com/linuxperf.html) - Systembeherskelse
- [DDIA](https://github.com/jeffrey-xiao/papers/blob/master/textbooks/designing-data-intensive-applications.md) - Distribuerte systemer
- [WASM + Rust](https://rustwasm.github.io/docs/book/) - Nativ kode i nettleseren
- [Deno Deploy](https://fresh.deno.dev/) - Edge-databehandling

---

&nbsp;

## 📈 Utviklingsbane for å nå neste nivå

### Teknisk Bane
- Behersk minst ett språk ordentlig dypt
- Bidra til større åpen kildekode
- Skriv tekniske dybdeanalyser

### Bli flinkere sammen
- Mentor for juniorer
- Led arkitekturbeslutninger
- Hold tekniske foredrag
- Bygg utviklingskultur

---

&nbsp;

## 🛠️ Eksempler på Moderne Stack
> Det finnes utallige kombinasjoner av teknologier, men disse er i det minste relevante for industrien.

#### 1. Tradisjonell Web Stack
```
TypeScript → React → Node.js → PostgreSQL
```
- Frontend: React + TypeScript
- Backend: Node.js + Express
- Database: PostgreSQL
- Verktøy: Docker, Jest, Prettier
- Deploy: AWS/Vercel

#### 2. Moderne Fullstack JavaScript
```
Next.js → Prisma → PostgreSQL → Vercel
```
- Framework: Next.js 13+ (App Router)
- ORM: Prisma
- Database: PostgreSQL
- Styling: Tailwind CSS
- Deploy: Vercel/Self-host/GCP

#### 2.1 Enda modernere (end-to-end typesafe) B2B SPA Stack (no SEO/SSR)
```
PNPM monorepo → TypeScript → Vite → BiomeJS → React 
```
- Frontend: React + TypeScript
- API: TanStack Query + tRPC
- ORM: Prisma/Drizzle
- Database: PostgreSQL
- Validation: Zod
- Routing: TanStack Router
- Styling: CSS Modules
- Deploy: github actions + selvvalgt
- Build: Vite
- Lint/Formatting: BiomeJS

#### 3. Python Enterprise Stack
```
FastAPI → SQLAlchemy → PostgreSQL → Kubernetes
```
- API: FastAPI + Pydantic
- ORM: SQLAlchemy
- Database: PostgreSQL
- Cache: Redis
- Deploy: Kubernetes på GCP/AWS

#### 4. Startup Stack
```
T3 Stack → tRPC → Planetscale → Vercel
```
- Framework: Next.js + tRPC
- Database: PlanetScale (MySQL)
- Auth: Clerk/Auth.js
- Styling: Tailwind CSS
- Deploy: Vercel

#### 5. AI/ML Stack
```
Python → FastAPI → PyTorch → Kubernetes
```
- ML: PyTorch/TensorFlow
- API: FastAPI
- Queue: Celery + Redis
- Serving: TorchServe
- Deploy: Kubernetes på AWS

#### 6. Moderne .NET Stack
```
.NET 8 → Blazor → SQL Server → Azure
```
- Framework: .NET 8
- Frontend: Blazor WASM
- Database: SQL Server
- ORM: Entity Framework Core
- Deploy: Azure

#### 7. Hjemmesnekret og gratis
```
Node.js → React → MongoDB → Vercel
```
- Frontend: React tsx
- Backend: Node.js
- Auth: Hjemmelaget
- Deploy: Alt på vercel gratisversjon
- Ekstra: Ingenting

#### Vanlige Verktøy
```
Git → Docker → GitHub Actions → Datadog
```
- Versjonskontroll: Git + GitHub
- Containere: Docker + Compose
- CI/CD: GitHub Actions
- Logging: ELK Stack
- Monitorering: Datadog/Grafana
- Testing: Jest, PyTest, xUnit

#### Vurderingskriterier for stack
1. **Skalerbarhet**: Hvor godt skalerer løsningen?
2. **Utviklerhastighet**: Hvor raskt kan team levere?
3. **Stabilitet**: Hvor moden er teknologiene?
4. **Kostnader**: Lisenser, hosting, vedlikehold
5. **Økosystem**: Tilgang på biblioteker og verktøy
6. **Kompetanse**: Tilgang på utviklere

#### Åpenbare tips for stackvalg
- Start enkelt, utvid ved behov
- Velg etablerte teknologier for kjernekomponenter
- Eksperimenter i mindre kritiske deler
- Vurder teamets kompetanse
- Tenk på langsiktig vedlikehold

---

&nbsp;

## ∿ Pro-tips

> Systematisk forbedring gjennom regelmessige vaner

### Daglig
```
Morgen → Lunch → Ettermiddag → Kveld
```
- Test 1 ny hurtigtast i din hovededitor
- Skriv minst 1 test for eksisterende kode
- Les 1 GitHub issue i et prosjekt du følger
- Commit tidlig, commit ofte
- Ta 5 min til å dokumentere noe du lærte
- Refaktorer én liten bit kode
- Review én PR

### Ukentlig
```
Lær → Implementer → Del → Gjenta
```
- Les én teknisk artikkel grundig
- Optimaliser én flaskehals i kode
- Del én læring med teamet
- Oppdater avhengigheter i ett prosjekt
- Skriv/oppdater teknisk dokumentasjon

### Månedlig
```
Planlegg → Utforsk → Evaluer → Juster
```
- Les en teknisk bok eller whitepaper
- Prøv ett nytt utviklerverktøy
- Bidra til ett open source prosjekt
- Automatiser en repeterende oppgave

### Kvartalsvis
```
Analyser → Bygg → Publiser → Reflekter
```
- Sett opp et fungerende miljø for én ny teknologistack fra bunnen
- Test en ny teknologi grundig
- Evaluer og oppdater verktøykassen din
- Start et side-prosjekt
- Gjennomgå og optimaliser arbeidsflyten din
---

&nbsp;

&nbsp;

&nbsp;

〰️ Dette er bunn.  〰️
