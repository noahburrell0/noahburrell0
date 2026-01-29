# Noah Burrell

Senior Technical Support Engineer at [Akuity](https://akuity.io), the company founded by the creators of Argo CD. I've spent the last 5 years building and managing GitOps workflows, helping teams adopt Kubernetes and continuous delivery at scale.

---

## About Me

My background in system administration and DevOps gives me a practical perspective on infrastructure challenges. I work with GitOps and Argo CD daily, both professionally and in my own environments.

Visit my website at [burrell.tech](https://burrell.tech/)

---

## Homelab

I run a [production-grade Kubernetes cluster](https://github.com/noahburrell0/k8s) at home that serves as my personal infrastructure. Everything is managed through Argo CD using the App-of-Apps pattern, with the Git repository as the single source of truth.

The stack runs on Talos Linux nodes provisioned through Omni on Proxmox. Longhorn handles distributed storage, MetalLB provides load balancing, and cert-manager automates TLS certificates through Let's Encrypt. I use a two-tier approach for secrets: Sealed Secrets for bootstrapping and External Secrets for runtime operations.

The cluster hosts 20+ applications across internal services, external-facing apps, and infrastructure components. Argo CD monitors everything, including its own configuration, automatically reconciling any drift from the declared state.

---

## Technologies & Tools

### GitOps & Continuous Delivery
![](https://img.shields.io/badge/Argo_CD-informational?style=flat&logo=argo&logoColor=white&color=EF7B4D)
![](https://img.shields.io/badge/Helm-informational?style=flat&logo=helm&logoColor=white&color=0F1689)
![](https://img.shields.io/badge/Kustomize-informational?style=flat&logo=kubernetes&logoColor=white&color=326CE5)
![](https://img.shields.io/badge/GitHub_Actions-informational?style=flat&logo=githubactions&logoColor=white&color=2088FF)

### Container Orchestration & Cloud
![](https://img.shields.io/badge/Kubernetes-informational?style=flat&logo=kubernetes&logoColor=white&color=326CE5)
![](https://img.shields.io/badge/Docker-informational?style=flat&logo=docker&logoColor=white&color=2496ED)
![](https://img.shields.io/badge/Google_Cloud-informational?style=flat&logo=googlecloud&logoColor=white&color=4285F4)
![](https://img.shields.io/badge/Azure-informational?style=flat&logo=microsoftazure&logoColor=white&color=0078D4)

### Infrastructure as Code
![](https://img.shields.io/badge/Terraform-informational?style=flat&logo=terraform&logoColor=white&color=7B42BC)
![](https://img.shields.io/badge/Ansible-informational?style=flat&logo=ansible&logoColor=white&color=EE0000)

### Systems & Networking
![](https://img.shields.io/badge/Linux-informational?style=flat&logo=linux&logoColor=white&color=FCC624)
![](https://img.shields.io/badge/Bash-informational?style=flat&logo=gnu-bash&logoColor=white&color=4EAA25)
![](https://img.shields.io/badge/NGINX-informational?style=flat&logo=nginx&logoColor=white&color=009639)
![](https://img.shields.io/badge/Proxmox-informational?style=flat&logo=proxmox&logoColor=white&color=E57000)

---

## Professional Experience

| Period | Role |
|--------|------|
| 2023 - Present | Senior Technical Support Engineer @ [Akuity](https://akuity.io/) |
| 2021 - 2023 | SysAdmin / GitOps Engineer @ [Empire Life](https://www.empire.ca/) |
| 2019 - 2021 | SysAdmin @ [Telecom Metric](https://www.telecommetric.com/) |
| 2017 - 2019 | Research Assistant @ [Algonquin College ARIE](https://www.algonquincollege.com/arie/) |

See my full experience on [LinkedIn](https://www.linkedin.com/in/noahburrell/)

---

## Consulting & Opportunities

I take on freelance consulting work related to Kubernetes, GitOps, Argo CD, and Linux systems. Whether you need help implementing a GitOps workflow, troubleshooting a deployment issue, training your team, or just want another perspective on your infrastructure, I'm happy to help.

I'm always open to conversations about interesting opportunities. Reach out at [noah@burrell.tech](mailto:noah@burrell.tech) or visit [burrell.tech](https://burrell.tech).
