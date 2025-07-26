# Kiosk Menu Microservice

[![NestJS](https://img.shields.io/badge/NestJS-red?logo=nestjs&logoColor=white)](https://nestjs.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![MinIO](https://img.shields.io/badge/MinIO-EF3C3A?logo=minio&logoColor=white)](https://min.io/)
[![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)](https://kafka.apache.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue?style=flat-square)

Microsserviço responsável pela gestão dos itens de cardápio no sistema de autoatendimento de restaurantes **Kiosk**.

#### 📌 Descrição

Este serviço permite:

- Criar, editar e remover itens do cardápio.
- Armazenar metadados dos itens em um banco relacional (PostgreSQL).
- Fazer upload de imagens para um storage de objetos (MinIO).
- Emitir eventos Kafka (`menu-updated`) sempre que houver alterações.

Este é o primeiro dos microsserviços do sistema **Kiosk**, que será composto por:

- `kiosk-menu-ms`: gerenciamento de cardápio (este repositório)
- `kiosk-order-ms`: gerenciamento de pedidos
- `kiosk-kitchen-ms`: gerenciamento da fila de preparo
- `kiosk-payment-ms`: processamento de pagamentos

### 🛠️ Tecnologias usadas

- NestJS
- TypeScript
- PostgreSQL
- MinIO
- Apache Kafka
- Docker (para serviços de infraestrutura)

### Arquitetura usada no projeto

Esse projeto foi projetado usando a arquitetura Hexagonal (Ports & Adapters), visando facilitar a extensão e manutenção do projeto a longo prazo. O domínio é isolado de frameworks e detalhes técnicos, promovendo testabilidade e evolução.

### Como subir o projeto localmente (em construção)

### Configuração (em construção)

### Testes (em construção)

### API (Swagger) (em construção)


### 📂 Estrutura de pastas (em construção)

```bash
.
├── src
│   ├── main
│   │   ├── ...
│   └── test
├── docker-compose.yml        # Infra local: PostgreSQL, Kafka, MinIO
├── README.md
└── ...
```

### Diagramas de Sequência das Funcionalidades Principais (em construção)

### Como contribuir (em construção)

### Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](../LICENSE) para mais detalhes.

### Responsáveis

- [Janaina Paula](https://github.com/JanainaPaula)
