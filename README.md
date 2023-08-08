```bash
helm repo add phonebook-repo  https://github.com/IrinaZ1/phonebook-repo.git
helm install phonebook-app phonebook-repo/phonebook-chart
```
- To use own images execute as below:
```bash
helm install phonebook-app phonebook-repo/phonebook-chart --set webserver_image=<image-name> --set resultserver_image=<image-name>
