<div align="center">

<!-- Animated header banner -->
<img src="assets/header.svg" width="100%" alt="Muhammad Rizki Perdana Putra" />

<br/>

<!-- Typing SVG with multiple animated lines -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2500&pause=800&color=00D2FF&center=true&vCenter=true&multiline=true&repeat=true&width=620&height=80&lines=%E2%9A%A1+Technical+Consulting+Manager+%40+Metrodata;%F0%9F%9A%80+TypeScript+%7C+Next.js+%7C+NestJS+%7C+Go+%7C+Python;%F0%9F%94%A5+Big+Data+%7C+Spark+%7C+Kafka+%7C+Cloudera;%F0%9F%A4%96+Data+%26+AI+Architect+%7C+Full+Stack+Engineer" alt="Typing SVG" />
</a>

<br/><br/>

<!-- Social badges with hover effects -->
<a href="https://linkedin.com/in/YOUR_LINKEDIN_USERNAME">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="https://instagram.com/YOUR_INSTAGRAM_USERNAME">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>
&nbsp;
<a href="https://discordapp.com/users/YOUR_DISCORD_ID">
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
</a>
&nbsp;
<a href="mailto:rizki.putra@metrodata.co.id">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/insiderhack">
  <img src="https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=insiderhack&label=Profile+Views&color=00D2FF&style=flat-square" />
&nbsp;&nbsp;
<img src="https://img.shields.io/github/followers/insiderhack?label=Followers&style=flat-square&color=7F52FF&labelColor=0D1117&logo=github&logoColor=white" />
&nbsp;&nbsp;
<img src="https://img.shields.io/github/stars/insiderhack?affiliations=OWNER&label=Stars&style=flat-square&color=FFC107&labelColor=0D1117&logo=github&logoColor=white" />

</div>

<img src="assets/divider.svg" width="100%" />

## <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"> &nbsp;About Me

<table>
<tr>
<td width="50%">

```yaml
name        : Muhammad Rizki Perdana Putra
short_name  : Muhammad Rizki
role        : Technical Consulting Manager
company     : Metrodata
location    : Indonesia 🇮🇩
```

</td>
<td width="50%">

```yaml
focus       : Full Stack · Data · AI Architecture
stack       : TypeScript, Go, Java, Python
frameworks  : Next.js, NestJS, Spark
big_data    : Kafka, Cloudera, Confluent
tools       : Talend, Tableau, SQL
currently   : Building data-driven platforms
```

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" />

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28"> &nbsp;Tech Stack & Expertise

<div align="center">

<img src="assets/skills.svg" width="100%" alt="Skills" />

</div>

<img src="assets/divider.svg" width="100%" />

## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28"> &nbsp;GitHub Stats & Metrics

<div align="center">

<img src="assets/stats.svg" height="195" alt="GitHub Stats" />
&nbsp;&nbsp;
<img src="assets/langs.svg" height="195" alt="Top Languages" />

</div>

<br/>

<div align="center">

<!-- Streak stats -->
<img src="https://streak-stats.demolab.com/?user=insiderhack&theme=tokyonight-duo&background=0D1117&hide_border=true&ring=00D2FF&fire=FF6FD8&currStreakNum=00D2FF&sideNums=7F52FF&sideTitles=BDC3C7&dates=6B7A99&currStreakLabel=00D2FF" width="65%" alt="GitHub Streak" />

</div>

<img src="assets/divider.svg" width="100%" />

## 🏆 GitHub Trophies

<div align="center">

<img src="assets/trophies.svg" width="100%" alt="GitHub Trophies" />

</div>

<img src="assets/divider.svg" width="100%" />

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=insiderhack&radius=6&theme=tokyo-night&bg_color=0D1117&color=00D2FF&line=7F52FF&point=FF6FD8&hide_border=true&area=true&area_color=7F52FF" width="100%" alt="Activity Graph" />

</div>

<img src="assets/divider.svg" width="100%" />

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/insiderhack/insiderhack/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/insiderhack/insiderhack/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake"
    src="https://raw.githubusercontent.com/insiderhack/insiderhack/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

<details>
<summary>⚙️ Snake workflow setup (click to expand)</summary>

Create `.github/workflows/snake.yml`:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Go to **Settings → Actions → General → Workflow permissions → Read and write**, then run the workflow once manually.

</details>

<img src="assets/divider.svg" width="100%" />

## 🎯 Weekly Development Breakdown

<!--START_SECTION:waka-->
```text
TypeScript   7 hrs 12 mins   ████████████░░░░░░░░░   30.00%
Go           4 hrs 48 mins   ████████░░░░░░░░░░░░░   20.00%
Python       4 hrs 05 mins   ███████░░░░░░░░░░░░░░   17.00%
Java         3 hrs 36 mins   ██████░░░░░░░░░░░░░░░   15.00%
SQL          2 hrs 24 mins   ████░░░░░░░░░░░░░░░░░   10.00%
Spark/Scala  1 hr 12 mins    ██░░░░░░░░░░░░░░░░░░░    5.00%
YAML/Config  43 mins         █░░░░░░░░░░░░░░░░░░░░    3.00%
```
<!--END_SECTION:waka-->

<img src="assets/divider.svg" width="100%" />

## 💬 Random Dev Quote

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="70%" alt="Dev Quote" />

</div>

<img src="assets/divider.svg" width="100%" />

## 🏠 Data & Infrastructure Stack

<div align="center">
<table>
<tr>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="48" height="48" alt="TypeScript" />
  <br>TypeScript
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="48" height="48" alt="Next.js" />
  <br>Next.js
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" width="48" height="48" alt="NestJS" />
  <br>NestJS
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="48" height="48" alt="Go" />
  <br>Go
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="48" height="48" alt="Java" />
  <br>Java
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="48" height="48" alt="Python" />
  <br>Python
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" width="48" height="48" alt="Kafka" />
  <br>Kafka
</td>
</tr>
<tr>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="48" height="48" alt="Docker" />
  <br>Docker
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="48" height="48" alt="K8s" />
  <br>K8s
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="48" height="48" alt="PostgreSQL" />
  <br>PostgreSQL
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="48" height="48" alt="Redis" />
  <br>Redis
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" width="48" height="48" alt="Grafana" />
  <br>Grafana
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="48" height="48" alt="Terraform" />
  <br>Terraform
</td>
<td align="center" width="96">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" width="48" height="48" alt="Nginx" />
  <br>Nginx
</td>
</tr>
</table>
</div>

---

<div align="center">

<!-- Footer wave -->
<img src="assets/footer.svg" width="100%" alt="" />

<br/>

<img src="https://img.shields.io/badge/Made%20with-❤️%20and%20☕-FF6FD8?style=flat-square&labelColor=0D1117" />

<br/><br/>

**⚡ "The best infrastructure is the one you never have to think about."**

<br/>

<sub>🔧 This profile auto-updates via GitHub Actions</sub>

</div>
