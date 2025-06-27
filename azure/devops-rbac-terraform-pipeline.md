# DevOps RBAC & Terraform Pipeline - Enterprise Azure Deployment
> ### Client name and details obfuscated for confidentiality. Architecture and implementation reflect actual enterprise experience.

## Overview: Enterprise Deployment Scenario

| Category     | Details                                                                 |
|--------------|-------------------------------------------------------------------------|
| Industry     | Retail                                                                  |
| App Name     | **ContosoSalesApp** – A multi-tier retail management application with frontend, backend, and database layers |
| Hosting      | Azure                                                                   |
| Automation   | GitHub Actions + Terraform                                              |
| Security     | Microsoft Entra ID (Azure AD), RBAC, Key Vault, PIM, Conditional Access |


## 👤 Users, Roles, and Groups

| Name         | Email             | Role               | Group          |
|--------------|-------------------|--------------------|----------------|
| Alice Thomas | alice@contoso.com | DevOps Engineer    | AppDevTeam     |
| Bob Smith    | bob@contoso.com   | Backend Developer  | AppDevTeam     |
| Clara Lee    | clara@contoso.com | DBA                | DBAdmins       |
| David Roy    | david@contoso.com | Security Admin     | SecOps         |
| Eva Wilson   | eva@contoso.com   | Cloud Architect    | CloudOps       |
| Raj Patel    | raj@contoso.com   | Compliance Officer | GovernanceTeam |


## 🔧 Infrastructure & Services

| Component   | Technology     | Azure Resource              |
|-------------|----------------|-----------------------------|
| Frontend    | ReactJS        | App Service                 |
| Backend     | Node.js        | App Service                 |
| Database    | SQL Server     | Azure SQL DB                |
| Secrets     | API Keys, DB   | Azure Key Vault             |
| CI/CD       | GitHub + TF    | GitHub Actions + SP         |
| Monitoring  | Security Logs  | Azure Monitor + Defender    |






