# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed![Screenshot from 2022-09-25 19-10-16](https://user-images.githubusercontent.com/73060979/192158621-8d087701-91da-46f6-b8cd-20c08b9a8819.png)


* GitHub actions pipline ![Screenshot from 2022-09-25 00-40-57](https://user-images.githubusercontent.com/73060979/192158694-aca4b0f3-211f-4c4e-8e8e-7c468db85604.png)

* github actions  showing a successful build and deploy job

![Screenshot from 2022-09-25 17-48-57](https://user-images.githubusercontent.com/73060979/192158703-895b0c85-6ced-4e85-8157-d45a08b6a0b0.png)




## Kubernetes
```bash
kubectl get pods

```
* To verify Kubernetes pods are deployed properly![Screenshot from 2022-09-25 17-29-11](https://user-images.githubusercontent.com/73060979/192158771-8ebc3104-c020-4f4e-93e2-3fbb994c9d0e.png)



* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
![Screenshot from 2022-09-25 17-28-30](https://user-images.githubusercontent.com/73060979/192158880-1875dc59-6505-46a9-aff5-0d9cb5a080f6.png)
![Screenshot from 2022-09-25 17-28-52](https://user-images.githubusercontent.com/73060979/192158892-6e583fe9-a634-445c-b3a8-14d4b76b2f95.png)


* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
![Screenshot from 2022-09-25 18-43-52](https://user-images.githubusercontent.com/73060979/192159001-617f818c-539c-4bac-a59d-5898312a736d.png)

