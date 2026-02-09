# 🖥️ Kubernetes On-Prem Platform com Ansible, GitOps e Observabilidade

Este repositório contém a **infraestrutura e a plataforma Kubernetes on-premise**, automatizada do zero utilizando **Ansible**, com **GitOps via Argo CD** e **observabilidade completa com Prometheus e Grafana**.

O foco deste repositório é a **criação, configuração e operação da plataforma**, simulando um ambiente corporativo real, sem dependência de provedores cloud, e faz parte de um projeto maior de **plataforma Kubernetes on-premise**.

---

## 🎯 Objetivo do Repositório

Demonstrar, de forma prática e automatizada, como:

- Preparar servidores Linux para Kubernetes
- Provisionar e configurar um cluster Kubernetes on-premise
- Implementar Ingress em ambiente sem Load Balancer de cloud
- Operar a plataforma utilizando GitOps
- Implementar observabilidade real de cluster, nodes e hosts externos

---

## 🏗️ Arquitetura da Plataforma

- **Ambiente:** On-Premise (VMware Workstation)
- **Sistema Operacional:** Debian 12
- **Cluster Kubernetes:** 1 Control Plane + 2 Workers
- **Container Runtime:** containerd
- **CNI:** Calico
- **Ingress Controller:** NGINX (NodePort)
- **GitOps:** Argo CD
- **Observabilidade:** Prometheus + Grafana
- **Monitoramento adicional:** Host Windows via windows_exporter
