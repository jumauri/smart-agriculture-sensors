# Projeto: Sensores Inteligentes em Agricultura

Este projeto utiliza **Apache Kafka** e **Python** para processar dados de sensores agrícolas em tempo real, com armazenamento em um banco de dados PostgreSQL. Os sensores simulam a coleta de dados de temperatura e umidade em uma fazenda.

## Estrutura do Projeto

- `producer.py`: Simula a geração de dados de sensores e os envia para um tópico Kafka.
- `consumer.py`: Consome os dados enviados para o Kafka e armazena em um banco de dados PostgreSQL.
- `data/`: Diretório para armazenar o dataset baixado do Kaggle.

## Pré-requisitos

1. **Python 3.8 ou superior**
2. **Apache Kafka instalado**
3. **PostgreSQL**
4. Dependências do Python (ver `requirements.txt`)

## Instalação

### 1. Clonar o repositório

```bash
git clone https://github.com/seuusuario/smart-agriculture-sensors.git
cd smart-agriculture-sensors

