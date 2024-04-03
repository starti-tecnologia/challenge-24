# Desafio para a Vaga de Desenvolvedor na Starti

![alt](https://res.cloudinary.com/site-starti/image/upload/f_auto,q_auto,w_100/v1/starti/logo)

![workflow](https://github.com/starti-tecnologia/challenge-24/assets/11998949/7f71ea10-e4cb-4a6b-955d-db988a0df8d6)
Dado o workflow acima, o desafio envolve a captura de informações no agente, sua transferência para o servidor, que por sua vez encaminhará esses dados para uma fila. Essa fila será consumida por dois processadores (consumers), os quais armazenarão as informações em um banco de dados.

### Pré-requisitos:
* PHP, NodeJS, GoLang, Rust (uma ou mais linguagens podem ser usadas)
* MySQL, MongoDB, ClickHouse, TypeSense
* Apache Kafka, RabbitMQ
* Docker

### Detalhes
* **WS Server:** Servidor WebSocket responsável por receber conexões do agente e conectar com uma fila;
* **WS Agent:** Conectará no WS Server e enviará informações do host (ex: cpu, mem, hd);
* **Queue:** Responsável por armazenar as informações recebidas do agent.
* **Consumer:** Responsável por ler a fila e tratar os dados e salvá-los no banco de dados.

### Entrega do desafio
* Criar um fork do desse projeto;
* Altere o arquivo README.md com as informações necessárias para executar o seu teste;
* Ao finalizar, enviar PR.

### Boa sorte!
