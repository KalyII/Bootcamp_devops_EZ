# 🚀 Terraform AWS EC2 Deployment – TP 2

Ce projet déploie une instance EC2 sur AWS via Terraform, avec une configuration dynamique grâce à l’utilisation de variables. Il est conçu pour être réutilisable, sécurisé et facile à personnaliser.

---

## 📦 Contenu du projet

- `ec2.tf` – Déclaration du provider AWS et de l’instance EC2
---

## ✅ Prérequis

- Un compte AWS fonctionnel
- [Terraform](https://www.terraform.io/downloads.html) installé localement
- Une clé SSH créée dans la console AWS (EC2 → Key Pairs)
- Configuration AWS faite via :

```bash
aws configure
