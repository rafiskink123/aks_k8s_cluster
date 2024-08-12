# aks_k8s_cluster

1. Define Pipeline: Set up a pipeline in Azure DevOps with the YAML provided.
2. Create AKS: The pipeline creates an AKS cluster and sets up a namespace.
3. Build & Push Container: Include steps (not shown above) to build and push your Docker container to Azure Container Registry (ACR).
4. Deploy to AKS: The pipeline deploys your application to the AKS cluster using the Kubernetes manifest files.
