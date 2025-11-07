# 😺 Simple-App-Manifests: Automação de ciclo de desenvolvimento CI/CD, com Dockerhub e ArgoCD

Olá! O Simple-App é um projeto prático que visa automatizar o processo de desenvolvimento, deployment e execução de uma aplicação simples em FastAPI, com ferramentas de CI/CD.

Este repositório faz parte do projeto Simple-App, e nele está contido o arquivo manifesto no formato YAML para reger a instalação e atualização do cluster Kubernetes local, em um ciclo completo de integração e entrega contínuas, tendo a função de ser a "fonte única da verdade".

O repositório conterá o arquivo manifest, escrito no formato YAML, que conterá as informações de deployment e services para a criação do cluster Kubernetes. Ele conterá também um arquivo simples chamado *VERSION*, que registrará o versionamento da imagem, atualizada e enviada ao DockerHub.

A aplicação que será instalada no cluster K8S (ou Kubernetes) está disponível aqui: [simple-app](https://github.com/DonaMaxii/simple-app/).
