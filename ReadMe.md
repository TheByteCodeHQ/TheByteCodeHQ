<div align="center">

<img src="assets/banner.svg" alt="Sujyonta Kumar Giri, Engineering Leader" width="100%"/>

### Building high-performing engineering teams and the platforms they ship on.

<sub>I lead across the full delivery lifecycle: **build it right, prove it works, ship it safely, run it reliably.**</sub>

<br/>

<a href="https://www.linkedin.com/in/Sujyonta"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:Sujyont@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-1c2541?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/TheByteCodeHQ"><img src="https://img.shields.io/badge/Portfolio-Visit-3a506b?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>

</div>

---

## 🧭 What I Lead

<table>
<tr>
<td width="50%" valign="top">

### 💻 Development
Architecture and delivery of scalable, secure services and full-stack products.<br/>
**Java · Spring Boot · Microservices · Angular · Python · PostgreSQL**

</td>
<td width="50%" valign="top">

### 🧪 QA & Automation
Quality strategy, automation frameworks and test platforms that make releases routine.<br/>
**Playwright · Selenium · TestNG · REST Assured · Performance Testing**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ DevOps & Cloud
CI/CD, containerisation and cloud-native operations that turn change into a safe, repeatable process.<br/>
**Kubernetes · Docker · GCP · GitLab CI/CD · Terraform**

</td>
<td width="50%" valign="top">

### 🏛️ Engineering
System design, technical direction and engineering standards across teams and products.<br/>
**System Design · Architecture · IIoT Platforms · Observability**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🤖 Agentic AI
Putting AI to work in every part of how software gets built, tested, shipped and run. I design agents and LLM-powered tools that take repetitive engineering work off people's plates, so teams spend their time on decisions and creativity, with humans in the loop where it matters.<br/>
**LLM Agents · Tool Use & MCP · Prompt Engineering · Workflow Automation · Evaluation & Guardrails**

</td>
</tr>
</table>

---

## 🚀 Featured Projects

Open-source work that shows how I think about quality, platforms and AI. Each one is tested, documented, and honest about its limits.

### 🤖 Agentic AI

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [agent-runtime](https://github.com/TheByteCodeHQ/agent-runtime)
**An agent runtime where safety is code, not a prompt.**

- Tool policies, human approvals, budgets and loop detection
- Untrusted content forces a human gate on risky calls, even for allow-listed tools
- Hash-chained audit trail, and replay of an incident against a stricter policy

`Python` · `Agents` · `Guardrails`

</td>
<td width="50%" valign="top">

#### 📏 [ai-eval-harness](https://github.com/TheByteCodeHQ/ai-eval-harness)
**Measures AI systems properly, and gates a build on the result.**

- Pass rates with confidence intervals, repeats that expose flakiness, per-tag breakdowns
- Paired comparison names the exact cases that regressed
- A guarded LLM judge: steering attempts are refused, outages count as failures

`Python` · `Evals` · `Statistics`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🤖 [ai-qa-assistant](https://github.com/TheByteCodeHQ/ai-qa-assistant)
**An AI agent that turns requirements into reviewed test cases and Jira story drafts.**

- Input guardrails: secret and personal-data redaction, prompt-injection handling
- Review loop, plus output checks that drop invented or duplicate test cases
- Deterministic evaluation score, usable as a CI gate

`Python` · `Gemini` · `Pydantic`

</td>
<td width="50%" valign="top">

#### 🧪 [mcp-test-tools](https://github.com/TheByteCodeHQ/mcp-test-tools)
**An MCP server that lets an AI agent run tests, read results and file bugs safely.**

- Agents pick a suite, never a command; no shell access
- Bugs are drafts until a human confirms, with duplicate detection and caps
- Redaction of secrets in everything returned or filed

`Python` · `MCP` · `JUnit`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 🔍 [ai-code-risk-scanner](https://github.com/TheByteCodeHQ/ai-code-risk-scanner)
**Reviews a git diff with deterministic rules plus an optional AI review, and verifies every AI finding against the real diff before showing it.**

- Secrets, injection, unsafe execution, destructive migrations and risky change shape, with SARIF output for GitHub code scanning
- Baselines and inline suppressions so a team can adopt it on an existing codebase

`Python` · `Gemini` · `SARIF`

</td>
</tr>
</table>

### 🧪 QA & Automation

<table>
<tr>
<td width="50%" valign="top">

#### 🎭 [pytest-playwright-framework](https://github.com/TheByteCodeHQ/pytest-playwright-framework)
**A UI and API test framework where every failure explains itself, with a bundled demo shop to test.**

- Page objects, a typed API client, parallel runs and rich failure evidence
- Found and fixed real races and security gaps in its own demo app
- No flaky tests across 5 repeated runs

`Python` · `Playwright` · `pytest`

</td>
<td width="50%" valign="top">

#### 🎲 [flaky-test-detector](https://github.com/TheByteCodeHQ/flaky-test-detector)
**Finds flaky, broken and slow tests in the JUnit XML your CI already produces.**

- Calls a test flaky only on proof: it passed and failed on the same commit, or failed then passed on a rerun
- Weaker evidence is labelled as such, and it tells you what to quarantine; no dependencies to install

`Python` · `JUnit` · `CI`

</td>
</tr>
</table>

### ☁️ DevOps, Engineering & Development

<table>
<tr>
<td width="33%" valign="top">

#### ☸️ [k8s-test-runner](https://github.com/TheByteCodeHQ/k8s-test-runner)
**Runs test suites as isolated Kubernetes Jobs behind a stateless API and dashboard.**

- Non-root, read-only, resource-limited pods
- Kubernetes is the only store, so the API scales freely

`Python` · `FastAPI` · `Kubernetes`

</td>
<td width="33%" valign="top">

#### 📘 [engineering-playbook](https://github.com/TheByteCodeHQ/engineering-playbook)
**An opinionated playbook for building, testing, shipping and running software well.**

- Test strategy, quality gates, release, incidents and AI guardrails
- Templates, plus a DORA metrics dashboard tool

`Markdown` · `Python` · `DORA`

</td>
<td width="33%" valign="top">

#### 🧱 [spring-angular-project](https://github.com/TheByteCodeHQ/spring-angular-project)
**A production-minded full-stack starter: Spring Boot API and Angular app.**

- JWT security, Flyway migrations, architecture rules enforced by tests
- 88 tests and 99% backend line coverage

`Java` · `Spring Boot` · `Angular`

</td>
</tr>
</table>

---

## 🎯 How I Lead

> Leadership, for me, is making the right way the easy way: for the product, the pipeline and the people building them.

| | Focus | Principle | How it shows up |
|:-:|:--|:--|:--|
| 💻 | **Development** | **Simple, secure, built to evolve** | Clean architecture and API-first design, reviews that teach as well as catch, and security and performance considered from the first design, not the last sprint. |
| 🧪 | **QA & Automation** | **Quality is built in, not bolted on** | A test pyramid the whole team owns, with automation, quality gates and fast feedback in every pipeline, so releases become routine rather than events. |
| ☁️ | **DevOps & Cloud** | **Ship small, ship safely, run reliably** | Everything as code: CI/CD, containers, Kubernetes and infrastructure. Repeatable deployments, safe rollbacks, and observability that finds problems before users do. |
| 🤖 | **Agentic AI** | **Augment people, keep humans in the loop** | AI applied across the lifecycle to remove toil and speed up decisions, with evaluation, guardrails and clear accountability so the output can be trusted. |
| 🏛️ | **Engineering** | **Clarity over heroics** | Clear ownership, written decisions and shared standards, so teams move fast without depending on individual firefighting. |
| 🔁 | **Automation mindset** | **Automate the repeatable** | If a team does something twice, it becomes a tool, a pipeline or a platform. |
| 🌱 | **People & Culture** | **Grow people, grow the product** | Mentoring, ownership and psychological safety, with a high bar held together rather than enforced from above. |
| 📈 | **Outcomes** | **Measure what matters** | Decisions backed by data such as lead time, change failure rate, defect leakage, reliability and coverage, not by opinion. |

---

## 🛠️ Technology Toolbox

<div align="center">

**Languages & Frameworks**<br/>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)

**Quality & Automation**<br/>
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Agentic AI**<br/>
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**DevOps & Cloud**<br/>
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0DB7ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-5835CC?style=flat-square&logo=terraform&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-2C5263?style=flat-square&logo=jenkins&logoColor=white)

**Data & Delivery**<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0A0FFF?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172BF4?style=flat-square&logo=confluence&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

</div>

---

## 📊 GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.shion.dev/api?username=TheByteCodeHQ&theme=tokyonight&hide_border=true&include_all_commits=false&count_private=false" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.shion.dev/api/top-langs/?username=TheByteCodeHQ&theme=tokyonight&hide_border=true&layout=compact" alt="Top languages" />

</div>

---

## 🤝 Let's Connect

I'm happy to talk about **engineering leadership, quality strategy, automation platforms and cloud-native delivery**, and always open to collaborating on open-source work and AI-powered engineering tools.

<div align="center">

<a href="https://www.linkedin.com/in/Sujyonta"><img src="https://img.shields.io/badge/Let's%20talk-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

<img src="assets/footer.svg" width="100%" alt="Footer"/>

</div>
