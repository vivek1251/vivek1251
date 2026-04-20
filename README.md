<div align="center">

# Vivek Bommalla

### DevOps Engineer · AWS Certified · Open to Work

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vivekbommalla1251)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vivekbommalla1251@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-vivek1251-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vivek1251)

</div>

---

<div align="center">

### 💡 I build real DevOps platforms on live AWS infrastructure — not tutorials, not sandboxes.

</div>

---

## 🏆 Projects — Ranked by Complexity

### 🥇 [EKS GitOps Platform](https://github.com/vivek1251/eks-gitops-platform) — *Enterprise-Grade*

> Production-style Kubernetes platform on AWS with full GitOps, triple observability stack, and multi-tool IaC. **25+ pods, 7 namespaces, 332 CloudWatch metrics, 789 live log events.**

```
git push → GitHub Actions → ECR → ArgoCD → EKS (auto-sync, self-healing)
```

**What's running inside:**

| Layer | What I Built | Key Numbers |
|-------|-------------|-------------|
| ☁️ Infrastructure | EKS v1.31 (CDK) · VPC (CloudFormation) · S3 (Terraform) | 3 nodes · ap-south-1 |
| 🔄 GitOps | ArgoCD v3.3.6 auto-sync from GitHub · Helm charts | Healthy ✅ Synced ✅ |
| 📊 Logs | Elasticsearch 8.5 + Kibana + Filebeat DaemonSet | 789 events · 44/min |
| 📈 Metrics | Prometheus + Grafana (15+ dashboards) | CPU 54% · Mem 85% |
| 🔍 AWS Native | CloudWatch Container Insights + CloudTrail | 332 metrics flowing |
| 🚀 CI/CD | GitHub Actions · AWS CodeBuild + ECR · GitLab CI | 3 pipelines |
| 🌱 PaaS | Elastic Beanstalk Docker deployment | Green health ✅ |

**Real problems I debugged (not tutorial steps):**
- 🐛 Pods stuck in `Pending` → hit t3.small 11-pod limit → scaled node group 1→3
- 🔐 ALB not provisioning silently → missing `DescribeListenerAttributes` IAM permission
- 🔑 Kibana auth failure after restart → stale token → regenerated via ES security API
- 📦 Git push rejected on 685MB file → Terraform binary in repo → rewrote history with `filter-branch`

`AWS EKS` `ArgoCD` `Terraform` `AWS CDK` `CloudFormation` `Helm` `Prometheus` `Grafana` `Elasticsearch` `Kibana` `Filebeat` `GitHub Actions` `AWS CodeBuild` `GitLab CI` `Docker` `CloudWatch` `Elastic Beanstalk` `Ansible` `Python`

---

### 🥈 [AI-Powered Root Cause Analysis System](https://github.com/vivek1251/ai-rca-system) — *AIOps*

> Detects application errors and generates AI-driven root cause analysis automatically — **no API keys, no data leaving your machine**, powered by a local LLM.

```
App Error → Loki (logs) → Prometheus (metrics) → Phi-4-mini (local AI) → RCA Report
```

**Why this stands out:** Most engineers use cloud AI APIs. This runs entirely locally with Ollama + Phi-4-mini — zero cost, zero latency, zero data exposure. Production-safe AIOps.

`Python` `Flask` `Loki` `Prometheus` `Grafana` `Phi-4-mini` `Ollama` `Docker Compose`

---

### 🥉 [DevSecOps Pipeline](https://github.com/vivek1251/devsecops-pipeline) — *Security-First CI/CD*

> CI/CD pipeline with automated security gates at **every stage** — nothing reaches production without passing secrets scanning, SAST, DAST, and container scanning.

```
Code Push → Gitleaks → SonarCloud (SAST) → Build → Trivy (container) → OWASP ZAP (DAST) → Deploy → Slack Alert
```

`Python` `GitHub Actions` `Gitleaks` `SonarCloud` `OWASP ZAP` `Trivy` `Docker` `AWS EC2` `Slack`

---

### 🏅 [Self-Healing CI/CD Pipeline](https://github.com/vivek1251/self-healing-cicd) — *Resilient Deployments*

> Flask app on AWS EC2 that detects deployment failures and **automatically recovers** — no human intervention needed.

```
git push → GitHub Actions → Deploy to EC2 → Health Check → Auto-Heal on Failure
```

`Python` `Flask` `GitHub Actions` `AWS EC2` `Docker`

---

## 🛠️ Full Tech Stack

<div align="center">

| Domain | Technologies |
|--------|-------------|
| ☁️ Cloud | AWS EKS · EC2 · ECR · S3 · Lambda · RDS · VPC · IAM · CloudWatch · Beanstalk · CloudTrail |
| 🏗️ IaC | Terraform · AWS CDK · CloudFormation |
| 🔄 GitOps & CI/CD | ArgoCD · GitHub Actions · AWS CodeBuild · GitLab CI · Helm |
| 🐳 Containers | Docker · Kubernetes · Helm · Kustomize |
| 📊 Observability | Prometheus · Grafana · Elasticsearch · Kibana · Filebeat · CloudWatch Insights |
| 🛡️ Security | Trivy · SonarCloud · OWASP ZAP · Gitleaks · IAM · IRSA |
| 🤖 AI / AIOps | Ollama · Phi-4-mini · Local LLM inference |
| 💻 Languages | Python · Bash · YAML · SQL |

</div>

---

## 📊 By The Numbers

<div align="center">

| Metric | Value |
|--------|-------|
| AWS Services Used | 12+ |
| Live Pods Deployed | 25+ |
| Kubernetes Namespaces | 7 |
| CloudWatch Metrics | 332 |
| Grafana Dashboards | 15+ |
| Log Throughput | 44 events/min |
| CI/CD Pipelines | 3 (GitHub · CodeBuild · GitLab) |
| IaC Tools | 3 (Terraform · CDK · CloudFormation) |

</div>

---

<div align="center">

**📬 Available for AWS DevOps / Cloud Engineer roles — Hyderabad or Remote**

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vivekbommalla1251)
[![Email](https://img.shields.io/badge/vivekbommalla1251%40gmail.com-Email%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vivekbommalla1251@gmail.com)

*Every component deployed, debugged, and verified on real AWS infrastructure.*

</div>
