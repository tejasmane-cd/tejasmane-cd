# 👋 Hi there, I'm **Tejas Mane**  
### ☁️ System Engineer @ [CloudDrove](https://clouddrove.com) | DevOps | AWS | Kubernetes | Terraform

> _Automate everything. Observe deeply. Scale efficiently._

---

> 🧠 Want to know what I’m currently working on?  
> Checkout [@tejasmane’s projects](https://github.com/users/tejasmane/projects)

*PS: Currently focusing on improving our **EKS + Terraform automation pipelines** at [CloudDrove](https://clouddrove.com), while contributing to internal DevOps tools and observability stack setups using Prometheus, Grafana, and OpenTelemetry.*

---

[<img align="left" width="390" alt="🧭 Overview" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/general.svg">](#)
[<img align="right" width="390" alt="📊 Metrics" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/medias.svg?p">](#)
[<img align="right" width="390" height="80" alt="🧩 Placeholder" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/placeholder.svg">](#)

[<img align="left" width="390" alt="💼 Sponsors" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/sponsors.svg">](#)
[<img align="right" width="390" alt="🏆 Achievements" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/achievements.svg">](#)

[<img width="100%" height="1" alt="🧭 Divider" src="https://gist.githubusercontent.com/lowlighter/3c6eaedf50273adfb7a510822672f570/raw/placeholder.svg">](#)

[<img align="right" alt="🧠 Profile" src="https://github.com/lowlighter/lowlighter/assets/22963968/f03a6539-5f5e-4e29-8cc5-8f2138660440">](#)

<sub>📊 These infographics were generated using [lowlighter/metrics](https://github.com/lowlighter/metrics)</sub>

---

## 🧩 About Me

I’m a **System Engineer at CloudDrove**, passionate about building and automating **scalable, secure, and observable** cloud environments.  
With hands-on experience in **AWS, Docker, Kubernetes, Terraform, and Jenkins**, I focus on infrastructure reliability and developer productivity.

---

## ⚙️ What I Work With

| Category | Tools & Platforms |
|-----------|-------------------|
| **Cloud & Infra** | AWS (EC2, EKS, RDS, S3, Route 53, CloudFormation) |
| **IaC & CI/CD** | Terraform, Helm, Jenkins, GitHub Actions, ArgoCD |
| **Containers** | Docker, Kubernetes |
| **Monitoring** | Prometheus, Grafana, CloudWatch |
| **Security** | Trivy, OWASP ZAP, SonarQube |
| **Scripting** | Bash, Linux |
| **Version Control** | Git, GitHub, GitLab |

---

## 📊 My DevOps Metrics Dashboard

> _Generated using [lowlighter/metrics](https://github.com/lowlighter/metrics) with custom plugins._

### 🌍 Example (replace `tejasmane` with your GitHub username)
```yaml
name: Metrics
on:
  schedule: [{cron: "0 * * * *"}] # Update every hour
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: tejasmane
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Kolkata
          plugin_isocalendar: yes
          plugin_languages: yes
          plugin_achievements: yes
          plugin_lines: yes
          plugin_stargazers: yes
          plugin_repositories: yes
          plugin_traffic: yes
