# azure-dockeragent

[📚 **Source**](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker)

⚠ À lancer en mode **Windows container**, et ne pas oublier de revenir aux **Linux containers** après !

```sh
docker run -e AZP_URL=<Azure DevOps instance> -e AZP_TOKEN=<PAT token> -e AZP_AGENT_NAME=mydockeragent dockeragent:latest
```