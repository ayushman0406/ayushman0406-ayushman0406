# ayushman0406-ayushman0406
<div align="center">

  <!-- Dynamic Typing Header -->
  <a href="https://github.com/ayushman0406">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3200&pause=1000&color=38BDF8&center=true&vCenter=true&multiline=true&repeat=true&width=850&height=90&lines=Hi%2C+I'm+Ayushman+Kumar+%F0%9F%91%8B;Data+Scientist+%40+HPE+%7C+Agentic+AI+%26+LLM+Systems+Architect;Building+Autonomous+PySpark%2C+RAG+%26+ML+Pipelines" alt="Typing SVG" />
  </a>

  <!-- Contact & Achievement Pills -->
  <p>
    <a href="https://www.linkedin.com/in/ayushman-kumar-a418bb213/">
      <img src="https://img.shields.io/badge/LinkedIn-Ayushman_Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:kumarayushman0406@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <img src="https://img.shields.io/badge/Focus-Agentic_AI_%26_Data_Science-8B5CF6?style=for-the-badge&logo=sparkles&logoColor=white" alt="Focus" />
    <img src="https://img.shields.io/badge/Award-VIT_Top_Coder_'26-F59E0B?style=for-the-badge&logo=trophy&logoColor=black" alt="VIT Top Coder 2026" />
  </p>

</div>

## ⚡ `agent://ayushman0406` — System Manifest

```yaml
identity:
  name: "Ayushman Kumar"
  role: "Data Scientist @ Hewlett Packard Enterprise (HPE)"
  location: "Bengaluru, India"
  education: "B.Tech CSE (Data Science) @ VIT Vellore (CGPA: 8.74 | VIT Top Coder 2026)"

core_directives:
  - "Architecting multi-agent LLM workflows that automate end-to-end data engineering & BI"
  - "Benchmarking RAG pipelines, TTFT latency, and code ROI via AST/Radon telemetry"
  - "Previously engineered healthcare & financial Agentic AI at Sonata Software (showcased at Microsoft Fabric Community Conference, Las Vegas)"

off_duty_threads:
  - "Modeling macroeconomic indices against real-world consumer behavior"
  - "Organizing 6-a-side football leagues & tracking urban metro infrastructure (BMRCL/CMRL)"

### Bonus: Automated Contribution Snake Action

To activate the animated snake eating your contribution graph at the bottom of the profile via [Platane/snk](https://github.com/platane/snk), add `.github/workflows/snake.yml` to your `ayushman0406/ayushman0406` repo:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
