# kubernetes-hello

Learning about Kubernetes

- [[GitHub] kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) - Production-Grade Container Scheduling and Management

## What is kubernetes?

- [Kubernetes](https://kubernetes.io/), also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications. It groups containers that make up an application into logical units for easy management and discovery. Originally designed by Google, Kubernetes is now maintained by a worldwide community of contributors and is held by the Cloud Native Computing Foundation.

- [What Is Kubernetes? | Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

- [What is Kubernetes? | Microsoft Azure](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-kubernetes/)

- [What Is Kubernetes? | IBM](https://www.ibm.com/topics/kubernetes)

- [What is Kubernetes? | Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

## What is pod?

- A Kubernetes **pod** is the smallest deployable unit in Kubernetes, representing a group of one or more containers running instances of an application. Pods encapsulate containers and provide environmental dependencies like storage, networking, and configuration information to efficiently run containers. They simplify communication and data sharing between containers by sharing the same network namespace, allowing them to communicate via localhost. Pods are created by controllers, managed by Kubernetes, and can be automatically replicated or replaced based on demand or failures within the cluster.

- [What Is Kubernetes Pod? Explained With Practical Examples | DevopsCube](https://devopscube.com/kubernetes-pod/) (2023/10/14)

## Learning

- [[YouTube] Kubernetes Explained in 100 Seconds | Fireship](https://www.youtube.com/watch?v=PziYflu8cB8) (2020/09/24)

- [[YouTube] Kubernetes Explained in 6 Minutes - k8s Architecture | ByteByteGo](https://www.youtube.com/watch?v=TlHvYWVUZyc) (2023/01/11)

- [[YouTube] Kubernetes Basics: Pods, Nodes, Containers, Deployments and Clusters | Anton Putra](https://www.youtube.com/watch?v=B_X4l4HSgtc) (2021/11/17)

- [[YouTube] Do NOT Learn Kubernetes Without Knowing These Concepts... | Travis Media](https://www.youtube.com/watch?v=wXuSqFJVNQA) (2023/11/12)

- [Introduction to Kubernetes - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/intro-to-kubernetes/) - get acquainted with the Kubernetes open-source container-orchestration system for automating application deployment, scaling, and management.

- [[YouTube] Kubernetes Crash Course: Learn the Basics and Build a Microservice Application | KodeKloud](https://www.youtube.com/watch?v=XuSQU5Grv1g) (2023/03/31)

  - [YouTube Labs - Kubernetes Crash Course Course | KodeKloud](https://beta.kodekloud.com/courses/youtube-labs-kubernetes-crash-course)

- [[YouTube] Kubernetes Crash Course for Absolute Beginners | TechWorld with Nana](https://www.youtube.com/watch?v=s_o8dwzRlu4) (2021/09/30)

  - [[GitLab] nanuchi/k8s-in-1-hour](https://gitlab.com/nanuchi/k8s-in-1-hour)

- [[YouTube] Kubernetes Roadmap - Complete Step-by-Step Learning Path | TechWorld with Nana](https://www.youtube.com/watch?v=S8eX0MxfnB4) (2023/08/09)

- [How to Learn Kubernetes (Complete Roadmap & Resources) | DevopsCube](https://devopscube.com/learn-kubernetes-complete-roadmap/) (2024/01/09)

- [[YouTube Playlist] Kubernetes | Jim's Garage](https://www.youtube.com/playlist?list=PLXHMZDvOn5sVXjb88kYXSI7UMx4rhQwOj)

- [[YouTube] Kubernetes Tutorial: Container vs. Pod vs. Deployment vs. StatefulSet & More | Anton Putra](https://www.youtube.com/watch?v=4MEgCP7h8UU) (2023/12/10)

  - [[GitHub] antonputra/tutorials/lessons/182](https://github.com/antonputra/tutorials/tree/main/lessons/182)

### Migrate Docker Apps to Kubernetes

- [[YouTube] How To Migrate Docker Apps to Kubernetes Using Helm & Manifest Files. Portainer & WireGuard | Jim's Garage](https://www.youtube.com/watch?v=cm51M5uTBhE) (2023/11/07)

  - [[GitHub] JamesTurland/JimsGarage/Kubernetes/Create-manifest-helm](https://github.com/JamesTurland/JimsGarage/tree/main/Kubernetes/Create-manifest-helm)

### Deploying Application

- [[YouTube] Most Common Kubernetes Deployment Strategies (Examples & Code) | Anton Putra](https://www.youtube.com/watch?v=lxc4EXZOOvE) (2023/08/08)

  - [[GitHub] antonputra/tutorials/lessons/171](https://github.com/antonputra/tutorials/tree/main/lessons/171)

- [[YouTube] Kubernetes 101: Deploying Your First Application! | DevOps Directive](https://www.youtube.com/watch?v=XltFOyGanYE) (2022/08/01)

## Tools

### HELM

- [Helm](https://helm.sh/) - The Kubernetes Package Manager.

  - [[GitHub] helm/helm](https://github.com/helm/helm)

- [[YouTube] What is Helm? - Helm Concepts Explained | KodeKloud](https://www.youtube.com/watch?v=kJscDZfHXrQ) (2021/12/22)

- [[YouTube] Helm and Helm Charts Explained - Helm Tutorial for Beginners | DevOps Journey](https://www.youtube.com/watch?v=w51lDVuRWuk) (2022/09/30)

- [[YouTube] How to Create Helm Charts - The Ultimate Guide | DevOps Journey](https://www.youtube.com/watch?v=jUYNS90nq8U) (2022/10/14)

  - [[GitHub] devopsjourney1/helm-webapp](https://github.com/devopsjourney1/helm-webapp)

- [[YouTube] Package Management with Helm // Kubernetes Tutorial | Christian Lempa](https://www.youtube.com/watch?v=zka4lJbA-y4) (2021/11/23)

### Rancher

- [Rancher](https://www.rancher.com/), the open-source multi-cluster orchestration platform, lets operations teams deploy, manage and secure enterprise Kubernetes.

  - [[YouTube] What is Rancher? | Rancher by SUSE](https://www.youtube.com/watch?v=nRVBNkcr4eM) (2020/07/10)

  - [[GitHub] rancher/rancher](https://github.com/rancher/rancher) - Complete container management platform

  - [Rancher Academy](https://www.rancher.academy/) - free, community training for Kubernetes & Rancher

  - [[YouTube] Rancher Demystified: Simplifying Kubernetes Deployment & Management | Virtual Elephant](https://www.youtube.com/watch?v=DTtaAHBJhXg) (2024/03/18)

    - [[GitHub] virtualelephant/k8s-sample-application](https://github.com/virtualelephant/k8s-sample-application) - Sample application used to demo multiple features and functionalities within Kubernetes and the surrounding ecosystem

  - [[YouTube] Deploying Rancher to Manage Kubernetes. Kubernetes At Home - Part 4 | Jim's Garage](https://www.youtube.com/watch?v=hT2_O2Yd_wE) (2023/10/17)

    - [[GitHub] JamesTurland/JimsGarage/Kubernetes/Rancher-Deployment](https://github.com/JamesTurland/JimsGarage/tree/main/Kubernetes/Rancher-Deployment)

- [Rancher Desktop](https://rancherdesktop.io/) - an open-source application that provides all the essentials to work with containers and Kubernetes on the desktop

  - [[GitHub] rancher-sandbox/rancher-desktop](https://github.com/rancher-sandbox/rancher-desktop) - container Management and Kubernetes on the Desktop
