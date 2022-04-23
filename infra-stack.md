# Platform stack

* **Kubernetes** as an orchestrator for platform. Probably the best way to manage it - **GKE**.
* **Pulumi** to deploy infrastructure from Github Actions. I assume it will be required also to introduce CD for Kubernetes such as **Flux** or **ArgoCD** later.
* **Stackdriver** for monitoring unless it will be possible to setup separate monitoring stack (Prometheus+Grafana+AlertManager)
* **PostgreSQL** as a database for platform

# Client stack

* **Kubernetes** for microservices
* **VMs** for arenas
* **PostgreSQL** and **MySQL** as a database
* **Vector** to collect logs and metrics
