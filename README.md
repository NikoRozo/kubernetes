# Curso Completo de Kubernetes

Este repositorio contiene material de aprendizaje para un curso completo de Kubernetes, desde conceptos básicos hasta despliegues avanzados en la nube.

## Estructura del Curso

### Fundamentos
- **01-intro-k8s**: Introducción a Kubernetes y sus conceptos básicos
- **02-local-cluster**: Configuración de un cluster local
- **03-architecture**: Arquitectura y componentes de Kubernetes
- **04-kubectl-api**: Uso de kubectl y la API de Kubernetes
- **05-declarative-vs-imperative**: Enfoques declarativo vs imperativo

### Componentes Básicos
- **06-pods-replicasets-deployments**: Trabajando con Pods, ReplicaSets y Deployments
- **07-services-ingress**: Configuración de Services e Ingress
- **08-configs-secrets**: Configuración de aplicaciones con ConfigMaps y Secrets
- **09-networking**: Conceptos de networking en Kubernetes

### Almacenamiento y Aplicaciones
- **10-services-clusterip-nodeport-loadbalancer**: Tipos de servicios en detalle
- **11-storage-pv-pvc**: Volúmenes persistentes y claims
- **12-daemonsets-statefulsets**: Trabajando con DaemonSets y StatefulSets
- **13-multi-tier**: Implementación de aplicaciones multi-capa
- **14-jobs-cronjobs**: Trabajos programados y cronjobs

### Escalado y Monitoreo
- **15-autoscaling-hpa-vpa**: Auto-escalado horizontal y vertical
- **16-scaling-demo**: Demostración de escalado

### Kubernetes en la Nube
- **17-intro-cloud-k8s**: Introducción a Kubernetes en la nube
- **18-cloud-setup**: Configuración de entornos cloud
- **20-aws-eks-deploy**: Despliegue en AWS EKS

### Operaciones y Mantenimiento
- **21-troubleshooting-guide**: Guía de solución de problemas
- **22-others-use-cases**: Otros casos de uso
- **23-certifications**: Información sobre certificaciones
- **24-final-deploy**: Despliegue final de un proyecto completo

## Requisitos Previos
- Docker instalado
- Conocimientos básicos de contenedores
- Kubectl instalado
- Minikube o Kind para pruebas locales
- Una cuenta en un proveedor de nube (AWS, GCP, Azure) para las secciones avanzadas

## Cómo usar este repositorio
Cada directorio contiene material específico para cada tema, incluyendo:
- Archivos README con explicaciones detalladas
- Archivos YAML de ejemplo para despliegues
- Scripts de configuración

Recomendamos seguir los directorios en orden numérico para una progresión lógica del aprendizaje.

## Recursos Adicionales
- [Documentación oficial de Kubernetes](https://kubernetes.io/docs/home/)
- [Kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) 