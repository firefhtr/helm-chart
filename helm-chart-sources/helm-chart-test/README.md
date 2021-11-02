**Helm-Chart**

This is a simple example of a helm chart built with helm commands for deployment on Rancher.

This chart will deploy a simple nginx.

In the values file, you can modify the following:

    image:
       repository: nginx
       pullPolicy: *IfNotPresent**
    
    service:
       type: **ClusterIP**
