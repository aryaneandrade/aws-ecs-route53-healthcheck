# 🛰️ Monitoramento 24/7 de Aplicação na AWS com ECS, Route 53 e CloudWatch

Este repositório documenta a implementação de um cenário prático de **monitoramento 24/7** de uma aplicação na **Amazon Web Services (AWS)**, utilizando **mecanismos externos** à aplicação para garantir **alta disponibilidade e resiliência em escala global**.

---

## 🔍 Visão Geral do Projeto

A arquitetura implementada garante a observabilidade contínua da aplicação através de monitoramento externo, além de balanceamento de carga, escalabilidade automática e notificações em tempo real em caso de falhas.

### ✅ Principais Componentes

- **Amazon ECS (EC2 Launch Type):** Execução da aplicação em containers.
- **Amazon RDS:** Persistência de dados.
- **Amazon Route 53:** Gerenciamento de domínio e Health Checks globais.
- **Application Load Balancer (ALB):** Balanceamento de carga entre containers.
- **Amazon CloudWatch:** Monitoramento e alarmes baseados nos Health Checks.
- **Amazon SNS:** Notificações por e-mail e SMS.

---

## 📌 Funcionalidades Implementadas

- Monitoramento externo **24/7** via **Route 53 Health Checks**.
- Verificação da **disponibilidade global** da aplicação com respostas automatizadas.
- Criação de **alarmes no CloudWatch** com ações integradas ao **SNS**.
- Entrega de **notificações imediatas** em caso de falha.
- Infraestrutura com **alta disponibilidade** e **escalabilidade horizontal** por meio do **ALB** e **ECS**.

---

## 🖼️ Arquitetura da Solução

> _Adicione aqui o diagrama de arquitetura:_  
> `![Arquitetura](./images/arquitetura.png)`

---

## 📷 Capturas de Tela

> _Adicione aqui capturas da aplicação, console da AWS, configurações de alarmes etc:_  
> `![Tela da Aplicação](./images/app.png)`  
> `![CloudWatch Alarm](./images/alarmes.png)`

---

## 🚀 Como Foi Feito

O foco foi aplicar boas práticas de **alta disponibilidade**, **monitoramento contínuo** e **resposta a incidentes** com serviços nativos da AWS. Toda a infraestrutura foi provisionada e configurada via AWS Console.

---

## 🧠 Aprendizados

- Uso de **monitoramento externo** para detectar falhas reais de endpoint.
- Criação de fluxos de notificação automatizados via **SNS**.
- Configuração de ambientes altamente disponíveis e escaláveis com **ECS + ALB**.
- Integração de múltiplos serviços AWS para **observabilidade e resiliência**.

---

## 📎 Recursos Utilizados

- AWS Management Console  
- ECS (EC2 launch type)  
- RDS (MySQL)  
- Route 53  
- Application Load Balancer  
- CloudWatch  
- SNS  

---

## 👩‍💻 Autor(a)

**Aryane Andrade**  
Formação AWS | Mentoria Henrylle Maia

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aryane%20Andrade-blue?logo=linkedin)](https://www.linkedin.com/in/aryane-andrade)  
---
