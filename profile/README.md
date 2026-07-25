# RiftOniX 🛠️

Tools and shared automation for DevOps, SRE, and platform engineers. RiftOniX
projects focus on reproducible CI, cloud-native infrastructure, and Kubernetes
delivery. ☁️

We build small, composable tools that make engineering workflows easier to
repeat across repositories and environments.

Our home page is [riftonix.io](https://riftonix.io). It provides a central
entry point to the organization and its components.

## Projects 🚀

### [Kelm](https://github.com/riftonix/kelm) ⚙️

A Kubernetes operator for managing the lifecycle of ephemeral namespaces. Kelm
uses labels, annotations, TTL policies, and webhook-driven events to clean up
temporary test and preview environments. 🧹

### [Daggerverse](https://github.com/riftonix/daggerverse) 🧩

Reusable Dagger modules and ready-to-run CI scenarios for container images,
Helm charts, OpenTofu, Git operations, and static sites. It is the portable
execution layer behind several RiftOniX workflows. ⚙️

### [Container Images](https://github.com/riftonix/container-images) 📦

Source repository for base OCI images. Images are maintained with Dockerfiles
and Docker Buildx Bake manifests, then verified and published through released
Dagger scenarios. 🐳

### [Shared Helm Charts](https://github.com/riftonix/helm-shared) ⎈

Reusable Helm charts for deploying and operating Kubernetes workloads, centered
on `appchart`, a universal chart for configuring and deploying different types
of application components. The repository also contains library charts that
extend and support `appchart`, with room for additional standalone charts as
the platform evolves. 📚

### [Shared Terraform Modules](https://github.com/riftonix/terraform-shared) 🏗️

Reusable Terraform modules for infrastructure automation. Each module is
maintained independently so projects can compose common infrastructure without
duplicating its implementation. 🌍

### [Kafgres](https://github.com/riftonix/kafgres) 🎯

A minimal Go microservice that periodically reads data from PostgreSQL and
publishes it to Kafka. It is designed as an interview exercise for practical
troubleshooting, covering service configuration, database and message-broker
integration, health checks, and deployment diagnostics. 🧪

### [RiftOniX Website](https://github.com/riftonix/riftonix.github.io) 🌐

The source repository for the [riftonix.io](https://riftonix.io) static site,
including organization documentation, component guides, agent skills, and
instructions for AI coding assistants. 📚
