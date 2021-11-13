# GHA-CampusParty2021
Exemplo de utilização de GitHub Actions apresentado durante a **Campus Party 2021**

Comando utilizado para gerar as permissões de acesso ao **Azure App Service**:

az ad sp create-for-rbac --name ""GroffeGitHubActionsSiteContagem" --role contributor --scopes /subscriptions/<SUBSCRIPTION_ID>/resourceGroups/<RESOURCE_GROUP>/providers/Microsoft.Web/sites/<WEB APP> --sdk-auth
