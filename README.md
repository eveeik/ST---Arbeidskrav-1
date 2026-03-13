# Arbeidskrav 1 – Skytjenester

Dette prosjektet demonstrerer bruk av:

- Azure CLI
- Terraform
- Ansible

## Infrastruktur

Terraform oppretter:

- Resource Group
- Virtual Network
- 2 Subnets
- Network Security Groups
- VM1 (Ansible controller med public IP)
- VM2 (kun privat IP)

## Konfigurasjon

Ansible brukes fra VM1 til VM2 for å:

- opprette en gruppe
- opprette to brukere
- legge brukerne i gruppen
- installere nginx
