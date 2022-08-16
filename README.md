# microservice-common-library
Common code for all the microservices. 


## Authenticating Github using PAT Token

```sh

dotnet nuget add source --username USERNAME --password ${{ secrets.GITHUB_TOKEN }} --store-password-in-clear-text --name github "https://nuget.pkg.github.com/natarajanganapathi/index.json"

```