<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0284c7,40:7c3aed,100:ea580c&height=220&section=header&text=Priya%20Bhagoriya&fontSize=52&fontColor=ffffff&fontAlign=50&fontAlignY=40&desc=QA%20Automation%20Engineer%20%7C%20SDET%20%7C%20Mumbai&descSize=19&descAlign=50&descAlignY=62&animation=fadeIn" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&height=60&lines=Python+%C2%B7+Playwright+%C2%B7+AI-assisted+Testing;5%2B+years+building+quality+at+scale;Selenium+%E2%86%92+Playwright+%E2%86%92+LLM+test+pipelines;QA+Engineer+%7C+SDET+%7C+Mumbai" alt="Priya Bhagoriya" />

<br /><br />

[![Profile Views](https://komarev.com/ghpvc/?username=Priya123z&style=for-the-badge&color=0d1117&label=PROFILE+VIEWS)](https://github.com/Priya123z)

</div>

---

### About me

I test software for a living. At Deloitte I'm responsible for the quality of Amplifon's retail platform — 750+ test cases across a system that processes thousands of orders, SQL validation deep into the data layer, and being the person who surfaces the critical bug before release. The work is methodical and demanding and I find it genuinely interesting.

My technical stack is in transition. I spent four years building and maintaining Selenium/Java automation suites at LTIMindtree. I'm now rebuilding that skill set around **Python + Playwright** — not as a portfolio exercise but because the tooling is genuinely superior: no `WebDriverWait` boilerplate, first-class trace viewer for CI failures, single API across Chromium, Firefox, and WebKit, and parallel execution that actually works without flakiness tuning.

The third piece of the puzzle is **AI in testing**. Not "use ChatGPT to write tests" — I mean building structured pipelines where an LLM generates test case skeletons from user stories, with Pydantic enforcing output schema so the result is always parseable code, never raw prose. The goal isn't to replace test design judgment — it's to eliminate the 40 minutes of Gherkin boilerplate that precedes it.

Previously at Google India (Test Analyst Lead, 100+ API tests across 20+ services) and building Selenium automation across UK banking and US auto finance at LTIMindtree.

---

### Currently building

**[playwright-python-framework](https://github.com/Priya123z/playwright-python-framework)** &nbsp; `Python` `Playwright` `Pytest` `Allure` `GitHub Actions`

Page Object Model framework testing the SauceDemo application. 27 tests across login, inventory, cart, and checkout flows. CI matrix runs on every push across Chromium, Firefox, and WebKit in parallel. The `ARCHITECTURE.md` explains the design choices — why POM over Screenplay, why Pytest fixtures over class-based test setup, why `fail-fast: false` in the CI matrix.

**[api-test-pytest](https://github.com/Priya123z/api-test-pytest)** &nbsp; `Python` `Pytest` `Requests` `JSON Schema`

33 REST API tests against the Reqres.in public API. The differentiator is JSON Schema validation on every `GET` response — when a backend team renames a field, a status-200 test still passes; a schema test doesn't. Includes response-time SLA assertions, environment-aware base URL config, and CI artifact upload of the HTML report.

**[ai-testcase-generator](https://github.com/Priya123z/ai-testcase-generator)** &nbsp; `Claude API` `Streamlit` `Pydantic`

User story → Gherkin scenarios + Pytest skeletons via the Anthropic Claude API. Pydantic models (`TestSuite → GherkinScenario → GherkinStep`) validate the LLM output on every call — malformed JSON raises a `ValueError` rather than silently producing an unparseable result. Versioned system prompts in `prompts.py` mean strategy changes are a one-file diff. Unit tests mock the LLM client so CI passes with no API key.

---

### Stack

**Automation & Testing**

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=38bdf8)
![Playwright](https://img.shields.io/badge/Playwright-0d1117?style=for-the-badge&logo=playwright&logoColor=38bdf8)
![Pytest](https://img.shields.io/badge/Pytest-0d1117?style=for-the-badge&logo=pytest&logoColor=38bdf8)
![Selenium](https://img.shields.io/badge/Selenium-0d1117?style=for-the-badge&logo=selenium&logoColor=38bdf8)
![Java](https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=38bdf8)
![Cucumber](https://img.shields.io/badge/Cucumber-0d1117?style=for-the-badge&logo=cucumber&logoColor=38bdf8)

**CI / Cloud / DevOps**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1117?style=for-the-badge&logo=github-actions&logoColor=f97316)
![Jenkins](https://img.shields.io/badge/Jenkins-0d1117?style=for-the-badge&logo=jenkins&logoColor=f97316)
![GCP](https://img.shields.io/badge/GCP-0d1117?style=for-the-badge&logo=google-cloud&logoColor=f97316)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0d1117?style=for-the-badge&logo=azure-devops&logoColor=f97316)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=f97316)
![Git](https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=f97316)

**AI in Testing**

![Claude API](https://img.shields.io/badge/Claude_API-0d1117?style=for-the-badge&logoColor=a78bfa)
![Streamlit](https://img.shields.io/badge/Streamlit-0d1117?style=for-the-badge&logo=streamlit&logoColor=a78bfa)
![Pydantic](https://img.shields.io/badge/Pydantic-0d1117?style=for-the-badge&logo=pydantic&logoColor=a78bfa)
![Postman](https://img.shields.io/badge/Postman-0d1117?style=for-the-badge&logo=postman&logoColor=a78bfa)
![DeepEval](https://img.shields.io/badge/DeepEval-0d1117?style=for-the-badge&logoColor=a78bfa)

---

### Experience

| | |
|---|---|
| **Deloitte** — Consultant QA | Jul 2023 – Present · Mumbai |
| Amplifon retail/inventory platform — 750+ test cases, SQL validation across inventory, contracts, payments. SIT/UAT/regression in Agile. | |
| Google India (Test Analyst Lead) — led 3 engineers, 100+ API tests, 20+ REST services in Postman, 30% coverage increase. | |
| **LTIMindtree** — Senior Software Engineer QA | Nov 2019 – May 2023 · Mumbai |
| Charles Stanley (UK banking) — 250+ Selenium/Java scripts at 70% coverage, Jenkins CI. | |
| American Honda Finance (US) — 300+ test scripts in Azure DevOps, mentored 5 engineers, 4% bug detection improvement. | |

---

### Certifications

![GCP](https://img.shields.io/badge/Google_Cloud_Certified_Digital_Leader-0d1117?style=for-the-badge&logo=google-cloud&logoColor=38bdf8)
![Selenium](https://img.shields.io/badge/Selenium_WebDriver_with_Java-0d1117?style=for-the-badge&logo=selenium&logoColor=f97316)
![UFT](https://img.shields.io/badge/HP_UFT_%2F_QTP_with_VBScript-0d1117?style=for-the-badge&logoColor=a78bfa)

---

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-priya123z.github.io-0ea5e9?style=for-the-badge)](https://priya123z.github.io)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/priya-bhagoriya)
&nbsp;
[![Email](https://img.shields.io/badge/Email-prbhagoriya20%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prbhagoriya20@gmail.com)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ea580c,60:7c3aed,100:0284c7&height=110&section=footer" />
