# sit323-2024-t1-prac9p

This is the Jifeng Chen's implementation of SIT323 7.1P

To utilize this demonstration, please follow the steps below:

1. **Firstly**, create the persistent volume and persistent volume claim:
    ```bash
    kubectl apply -f ./createPersistentVolume.yaml
    kubectl apply -f ./createPersistentVolumeClaim.yaml
    ```

2. **Next**, create the storage class:
    ```bash
    kubectl apply -f ./createStorageClass.yaml
    ```

3. **Finally**, create the service and deployment:
    ```bash
    kubectl apply -f ./createService.yaml
    kubectl apply -f ./createDeployment.yaml
    ```