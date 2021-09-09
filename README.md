# Kubernetes

## Sumário

<!-- TOC -->
- [Kubernetes](#kubernets)
  - [Sumário](#sumário)
  - [o que é?](#o-que-é?)
  - [K8s](#k8s)
  - [Por que você precisa do K8s?](#por-que-você-precisa-do-k8s?)
  - [Componentes do K8s](#componentes-do-k8s)

<!-- TOC -->

## O que é?

É um sistema de orquestração de containers open-source que automatiza a implantação, o dimensionamento e a gestão de aplicações em containêres. Ele foi projetado pelo Google onde teve seu código aberto em 2014, atualmente é mantido pela Cloud Native Computing Foundation.

## k8s

K8s é a abreviação derívada pela troca das oito letras "ubernete" por "8", se tornando k8s

## Por que você precisa do K8s?

Quando possuimos aplicações sendo executadas em contêineres é necessário gerencia-los para garantir que não exista tempo de inatividade. Por exemplo se um contêiner cair, outro contêiner precisa ser iniciado, o k8s te ajuda com isso.

O Kubernetes oferece uma estrutura para executar sistemas distribuidos de forma resiliente, ele cuida do escalonamento e da recuperação de falha e muito mais.

O K8s oferece a você:

- Descoberta de serviço e balanceamento de carga
- Orquestração de armazenamento
- Lançamento e reversões automatizadas
- Melhor distribuição de recursos
- Autocorreção
- Gerenciamento de configuração e segredos

## Componentes do K8s