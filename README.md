# Controle Reserva de Salas

[![Java](https://img.shields.io/badge/Java-21-orange.svg)](https://openjdk.java.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.4-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-19.1.0-blue.svg)](https://reactjs.org/)
[![Docker](https://img.shields.io/badge/Docker-Compose-blue.svg)](https://docs.docker.com/compose/)
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Message%20Broker-orange.svg)](https://www.rabbitmq.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-blue.svg)](https://www.mysql.com/)

---

## Visão Geral

Este é um sistema moderno para gerenciar reservas de salas. Ele usa uma arquitetura de **microserviços** com **Domain-Driven Design (DDD)** e **Event-Driven Architecture**, garantindo controle completo de usuários, salas e reservas com comunicação assíncrona.

---

## Principais Características

* **Microserviços:** Arquitetura modular e isolada.
* **Comunicação Assíncrona:** Usa RabbitMQ para troca de mensagens.
* **Interface:** Frontend moderno em React com Material-UI.
* **Containerização:** Aplicação completa com Docker.
* **Validação em Tempo Real:** Validações de serviços cruzados.
* **Monitoramento:** Integrado com Adminer e RabbitMQ Management.
* **Tolerância a Falhas:** Mensagens persistidas no RabbitMQ.
* **Load Balancing:** Nginx como reverse proxy.

---

## Stack Tecnológica

### Backend
* **Java**
* **Spring Boot**
* **Lombok**

### Frontend
* **React 19.1.0**
* **Tailwind CSS**
* **Axios**

### Infraestrutura
* **Nginx**
* **RabbitMQ**
* **MySQL 8.0**
* **Adminer**

---

### Execução Rápida

```bash
# Clone o repositório
git clone (https://github.com/FelipeBoufleuher/projeto-microsservicos)
cd controle-sala


docker-compose up --build
```