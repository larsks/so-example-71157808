To deploy this example:

1. Create the target namespace:

    ```
    kubectl create ns podlister-example
    ```

2. Deploy the manifests:

    ```
    kubectl apply -k .
    ```

3. Verify it worked as expected:

    ```
    kubectl -n podlister-example logs kubectl
    ```
