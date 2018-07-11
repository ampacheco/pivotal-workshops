# Despliegue de helm en GKE. 

0. Prerequisitos


    - Instalar gcloud

        ```
        brew cask install google-cloud-sdk
        ```

        Para otros SOs revisar documentación oficial de [Google Cloud SDK](https://cloud.google.com/sdk/install).


    - Instalar [Helm](https://github.com/kubernetes/helm)

        ```
        brew install kubernetes-helm
        ```

    - Instalar [Kubectl](https://kubernetes.io/docs/tasks/tools)

        ```
        brew install kubernetes-cli
        ```

        Otra alternativa puede ser:

        ```
        gcloud components install kubectl
        ```

        Para otros SO distintos de MAC seguir las recomendaciones del sitio oficial de [Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl).

    Comprobar que las herrmientas requeridas CLIs han sido instaladas correctamente. 

        ```
        ```

1. Para usar SDK en estación de Trabajo Local, seguir los siguientes pasos: 

2. Otra alternativa, puede ser usar la interfaz de comando de la consola de administración de Servicios Web de Google.

3. Desplegar un clúster de 3 nodos

    ```
    gcloud container clusters create my-gke-cluster --num-nodes=3
    ```

4. Crear services account in kubernetes
