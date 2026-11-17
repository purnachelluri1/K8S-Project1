
## 📂 Project Structure

```text
K8S-Project1/
├── DEPLOYMENT.md
├── Docker-app/
│   ├── Dockerfile
│   └── multistage/
│       └── Dockerfile
├── Docker-db/
│   ├── Dockerfile
│   └── db_backup.sql
├── Dockerfile
├── README.md
├── compose.yml
├── k8s/
│   ├── 01-namespace.yaml
│   ├── 02-resourcequota.yaml
│   ├── 03-configmap.yaml
│   ├── 04-secret.yaml
│   ├── 05-storageclass.yaml
│   ├── 06-statefulset-db.yaml
│   ├── 07-service.yaml
│   ├── 08-deployment.yaml
│   ├── 09-hpa.yaml
│   ├── 10-pdb.yaml
│   ├── 11-ingress.yaml
│   └── 12-networkpolicy.yaml
├── kops/
│   └── create-cluster.sh
├── manifests/
│   ├── app-deployment.yml
│   └── db-deployment.yml
├── pom.xml
└── src/
    ├── main/
    │   ├── java/
    │   ├── resources/
    │   └── webapp/
    └── test/
        └── java/
```
