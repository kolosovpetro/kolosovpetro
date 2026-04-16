# DevOps

## 📚 Table of Contents
- [Kubernetes](#kubernetes)
- [CI/CD](#cicd)
- [Security](#security)
- [Azure DevOps](#azure-devops)
- [Terraform](#terraform)
- [Monitoring](#monitoring--observability)
- [Automation](#automation)
- [Documentation](#documentation)
- [Mathematics](#mathematics)

---

## ⭐ Core Patterns (Must Remember)

- [blue-green-deployment-azure-app-service](https://github.com/kolosovpetro/blue-green-deployment-azure-app-service) — blue/green, PaaS
- [aks-nginx-ingress-with-tls-certmanager](https://github.com/kolosovpetro/aks-nginx-ingress-with-tls-certmanager) — ingress, TLS automation
- [azure-vm-managed-identity-rbac-keyvault](https://github.com/kolosovpetro/azure-vm-managed-identity-rbac-keyvault) — identity, RBAC, KeyVault
- [terraform-template](https://github.com/kolosovpetro/terraform-template) — reusable baseline

---

## Kubernetes

- [aks-module-terraform](https://github.com/kolosovpetro/aks-module-terraform) — AKS, Terraform module
- [manual-kubernetes-cluster-from-scratch](https://github.com/kolosovpetro/manual-kubernetes-cluster-from-scratch) — bare-metal learning
- [aks-sealed-secrets-example](https://github.com/kolosovpetro/aks-sealed-secrets-example) — secrets

### Networking & Access

- [private-aks-bastion-same-vnet](https://github.com/kolosovpetro/private-aks-bastion-same-vnet)
- [private-aks-bastion-peered-vnet](https://github.com/kolosovpetro/private-aks-bastion-peered-vnet)

### Ingress & TLS

- [aks-app-gateway-ingress-tls-akv2k8s](https://github.com/kolosovpetro/aks-app-gateway-ingress-tls-akv2k8s)
- [aks-nginx-ingress-tls-certs-in-keyvault-akv2k8s](https://github.com/kolosovpetro/aks-nginx-ingress-tls-certs-in-keyvault-akv2k8s)
- [aks-nginx-ingress-with-tls-certmanager](https://github.com/kolosovpetro/aks-nginx-ingress-with-tls-certmanager)

### Integrations

- [aks-private-endpoint-to-acr-terraform](https://github.com/kolosovpetro/aks-private-endpoint-to-acr-terraform)
- [aks-keyvault-integration-csi](https://github.com/kolosovpetro/aks-keyvault-integration-csi)

---

## CI/CD

### Deployment Patterns

- [legacy-net-framework-deployment-iis](https://github.com/kolosovpetro/azdo-legacy-net-framework-deployment-iis)
- [movies-api-deployments](https://github.com/kolosovpetro/movies-api-deployments-linux-iis-k8s-etc)

#### SSH / Nginx (.NET)

- GitHub Actions:  
  https://github.com/kolosovpetro/movies-api-deployments-linux-iis-k8s-etc/blob/master/.github/workflows/ubuntu-deploy.yml  
- Azure DevOps:  
  https://github.com/kolosovpetro/movies-api-deployments-linux-iis-k8s-etc/blob/master/azure-pipelines/azdo-webapp-nginx-deploy.yml  

#### Frontend

- [angular-github-pages-deployment](https://github.com/kolosovpetro/razumovsky.me)
- [angular-ssh-nginx-deployment](https://github.com/kolosovpetro/razumovsky.me)

#### Blue/Green

- [azure-load-balancer-vms](https://github.com/kolosovpetro/blue-green-deployment-azure-load-balancer-vms-backend)
- [traffic-manager](https://github.com/kolosovpetro/blue-green-deployment-traffic-manager-and-vms)
- [azure-app-service](https://github.com/kolosovpetro/blue-green-deployment-azure-app-service) — GitHub Actions, Azure DevOps

---

### Build & Artifacts

- [gha-push-nuget-artifacts](https://github.com/kolosovpetro/gha-nuget-package-publish-github)
- [azdo-push-nuget-artifacts](https://github.com/kolosovpetro/azdo-nuget-artifacts)

#### Docker

- GitHub Actions:  
  https://github.com/kolosovpetro/CarsIslandProject/blob/master/.github/workflows/docker-build-push-webapi.yml  
- Azure DevOps:  
  https://github.com/EventTriangle/EventTriangleAPI/blob/main/build/templates/docker-build-push-jobs.yml  

---

### Configuration Management

- [json-xml-config-transformations](https://github.com/kolosovpetro/json-xml-config-transformations) — GitHub Actions, Azure DevOps

---

### Pipeline Performance

- [azdo-npm-cache](https://github.com/kolosovpetro/azdo-npm-cache) — Azure DevOps

---

## Security

### Static Code Analysis

- [sonarcloud](https://github.com/kolosovpetro/sonarcloud-azure-devops-cicd)  — Azure DevOps
- [trivy](https://github.com/kolosovpetro/trivy-cve-scan-azure-devops-cicd)  — Azure DevOps
- [snyk](https://github.com/kolosovpetro/snyk-security-scan-azure-devops-cicd)  — Azure DevOps

### Dynamic Code Analysis

- OWASP ZAP:  
  https://github.com/kolosovpetro/movies-api-deployments-linux-iis-k8s-etc/blob/master/azure-pipelines/azdo-owasp-scan.yml  

---

## Azure DevOps

- [azdo-variable-transfer-between-stages-and-jobs](https://github.com/kolosovpetro/azdo-variable-transfer-between-stages-and-jobs)
- [azdo-provider-terraform](https://github.com/kolosovpetro/azdo-provider-terraform)
- [azdo-agent-research](https://github.com/kolosovpetro/azdo-agent-research)
- [terraform-azdo-provider-template](https://github.com/kolosovpetro/terraform-azdo-provider-template)
- [azdo-cicd-keyvault-integration](https://github.com/MangoInstantMessenger/MangoMessengerAPI/blob/main/build/templates/terraform-apply-stages-template.yml)

---

## Packer images

- [packer-windows-server-images-azure](https://github.com/kolosovpetro/packer-windows-server-images-azure)
- [packer-linux-server-images-azure](https://github.com/kolosovpetro/packer-linux-server-images-azure)

---

## Terraform

- [terraform-template](https://github.com/kolosovpetro/terraform-template)

### Compute

- [windows-vm](https://github.com/kolosovpetro/azure-windows-vm-terraform)
- [linux-vm](https://github.com/kolosovpetro/azure-linux-vm-terraform)

### Networking

- [nat-gateway](https://github.com/kolosovpetro/azure-nat-gateway-for-azdo-agent)
- [firewall](https://github.com/kolosovpetro/azure-firewall-for-selfhosted-azdo-agent)

### Azure App Gateway

- [app-gateway-paas-backend](https://github.com/kolosovpetro/azure-app-gateway-paas-backend-terraform)
- [app-gateway-vm-backend](https://github.com/kolosovpetro/azure-app-gateway-vm-backend-terraform)

### VPN

- [s2s-azure-digital-ocean](https://github.com/kolosovpetro/azure-s2s-vpn-digital-ocean)
- [p2s-azure](https://github.com/kolosovpetro/azure-p2s-vpn-terraform)

### Identity & Access

- [managed-identity-keyvault](https://github.com/kolosovpetro/azure-vm-managed-identity-rbac-keyvault)
- [private-tf-module-ssh-auth](https://github.com/kolosovpetro/azdo-agent-terraform-private-module-ssh-auth)

### Cost Optimization

- [vm-start-stop](https://github.com/kolosovpetro/azure-vm-start-stop-automation-terraform)

---

## Monitoring & Observability

- [prometheus-grafana-stack](https://github.com/kolosovpetro/prometheus-grafana-stack)
- [elk-aks](https://github.com/kolosovpetro/elk-filebeat-aks-integration)

---

## Automation

- [ssh-cicd-playground](https://github.com/kolosovpetro/azdo-gha-ssh-cicd-playground) — GitHub Actions, Azure DevOps
- [azcopy-pipelines](https://github.com/kolosovpetro/azcopy-azdo-gha-yaml-pipelines) — GitHub Actions, Azure DevOps

---

## Ansible

- [ansible-playground](https://github.com/kolosovpetro/ansible-playground)

---

## Cloudflare

- [cloudflare-dns-records-management-powershell](https://github.com/kolosovpetro/cloudflare-dns-records-management-powershell)

---

## Documentation

- [devops-book](https://github.com/kolosovpetro/devops-book)
- [devops-hub](https://github.com/kolosovpetro/devops-hub)
- [private-public-cidr](https://github.com/kolosovpetro/private-public-cidr)
- [cmd-vs-entrypoint](https://github.com/kolosovpetro/DevOpsBook/blob/main/markdown/docker/cmd_vs_entrypoint.md)
- [kube-resource-allocation](https://github.com/kolosovpetro/kube-resource-allocation)
- [release-flow-proposal](https://github.com/kolosovpetro/release-flow-proposal)
- [azure-pipelines-best-practices](https://github.com/kolosovpetro/azure-pipelines-best-practices)
- [azure-ubuntu-vm-deploy-guide](https://github.com/kolosovpetro/azure-ubuntu-vm-deploy-guide)
- [sonarcloud-github-actions-guide](https://github.com/kolosovpetro/sonarcloud-github-actions-guide)
- [net-core-secure-azure-oidc](https://github.com/kolosovpetro/net-core-secure-azure-oidc)

### LaTeX templates

- [github-latex-template](https://github.com/kolosovpetro/github-latex-template)
- [latex-russian-template](https://github.com/kolosovpetro/latex-russian-template)
- [latex-beamer-template](https://github.com/kolosovpetro/latex-beamer-template)

---

## Other

- [osds-projects-list](https://github.com/kolosovpetro/osds-projects)
- [verify-encoding](https://github.com/kolosovpetro/VerifyEncoding)

---

# Mathematics

## Sums of Powers
- [Newton's interpolation formula (2026)](https://github.com/kolosovpetro/NewtonsInterpolationFormulaAndSumsOfPowers)
- [Backward differences (2026)](https://github.com/kolosovpetro/SumsOfPowersViaBackwardFiniteDifferencesAndNewtonFormula)
- [Central differences (2026)](https://github.com/kolosovpetro/SumsOfPowersViaCentralFiniteDifferencesAndNewtonFormula)

## Research

- [Unexpected polynomial identities arising from a classical interpolation problem (2025)](https://github.com/kolosovpetro/unexpected-polynomial-identities-classical-interpolation)
- [MinimalGoldbachPairsInPrimesCounting](https://github.com/kolosovpetro/MinimalGoldbachPairsInPrimesCounting) &mdash; Counting `minimal Goldbach pairs` in the set of `prime numbers`
- [AnEfficientMethodOfSplineApproximation](https://github.com/kolosovpetro/AnEfficientMethodOfSplineApproximation) &mdash; An efficient method for `spline approximation`
- [UnexpectedPolynomialIdentity](https://github.com/kolosovpetro/UnexpectedPolynomialIdentity) &mdash; Discovery of an `unexpected identity` involving `polynomials`
- [DiscussionOnCoefficientsOfOddPolynomialIdentity](https://github.com/kolosovpetro/DiscussionOnCoefficientsOfOddPolynomialIdentity) &mdash; Discussion about coefficients in odd polynomial identity
- [ACuriosityAboutPolynomialInterpolation](https://github.com/kolosovpetro/ACuriosityAboutPolynomialInterpolation) &mdash; A curiosity related to `polynomial interpolation`
- [OddPowerIdentityViaMultiplicationOfCertainMatrices](https://github.com/kolosovpetro/OddPowerIdentityViaMultiplicationOfCertainMatrices) &mdash; `Odd power identity` derived via `matrix multiplication`
- [ANovelProofOfPowerRuleInCalculus](https://github.com/kolosovpetro/ANovelProofOfPowerRuleInCalculus) &mdash; A novel proof of the `power rule` in `calculus`
- [PolynomialIdentitiesInvolvingCentralFactorialNumbers](https://github.com/kolosovpetro/PolynomialIdentitiesInvolvingCentralFactorialNumbers) &mdash; `Polynomial identities` involving `central factorial numbers`
- [RowSumsConjectureInRascalTriangle](https://github.com/kolosovpetro/RowSumsConjectureInRascalTriangle) &mdash; A conjecture about `row sums` in the `Rascal triangle`
- [IdentitiesInRascalTriangle](https://github.com/kolosovpetro/IdentitiesInRascalTriangle) &mdash; Various `identities` discovered in the `Rascal triangle`
- [HistoryAndOverviewOfPolynomialP](https://github.com/kolosovpetro/HistoryAndOverviewOfPolynomialP) &mdash; A historical and structural overview of `Polynomial P`
- [FindingTheDerivativeOfPolynomialsViaDoubleLimit](https://github.com/kolosovpetro/FindingTheDerivativeOfPolynomialsViaDoubleLimit) &mdash; Finding polynomial derivatives using a `double limit` approach
- [PolynomialIdentityInvolvingBTandFaulhaber](https://github.com/kolosovpetro/PolynomialIdentityInvolvingBTandFaulhaber) &mdash; A `polynomial identity` involving `Bernoulli triangles` and `Faulhaber's formula`
- [AnotherApproachToGetDerivativeOfOddPower](https://github.com/kolosovpetro/AnotherApproachToGetDerivativeOfOddPower) &mdash; An alternative method for deriving `odd power` functions
- [AStudyOnDynamicEquations](https://github.com/kolosovpetro/AStudyOnDynamicEquations) &mdash; A study focused on `dynamic equations` and their behavior
- [OnTheBinomialTheoremAndDiscreteConvolution](https://github.com/kolosovpetro/OnTheBinomialTheoremAndDiscreteConvolution) &mdash; Relation between the `binomial theorem` and `discrete convolution`
- [PolynomialIdentitiesInvolvingPascalsTriangleRows](https://github.com/kolosovpetro/PolynomialIdentitiesInvolvingPascalsTriangleRows) &mdash; `Polynomial identities` derived from `Pascal's triangle` rows
- [OnTheBertrandsPostulate](https://github.com/kolosovpetro/OnTheBertrandsPostulate) &mdash; Insights and exploration of `Bertrand's Postulate`
- [RSAEncryptionExplained](https://github.com/kolosovpetro/RSAEncryptionExplained) &mdash; Explanation and implementation of `RSA encryption`
- [DiffieHellmanKeyExchange](https://github.com/kolosovpetro/DiffieHellmanKeyExchange) &mdash; Practical explanation of the `Diffie–Hellman key exchange`
- [PlotsOfClosedForms](https://github.com/kolosovpetro/PlotsOfClosedForms) &mdash; Closed forms of polynomials
- [Math.Shared](https://github.com/kolosovpetro/Math.Shared) &mdash; Shared repository
- [MathWritingCheatSheet](https://github.com/kolosovpetro/MathWritingCheatSheet) &mdash; Auxiliary