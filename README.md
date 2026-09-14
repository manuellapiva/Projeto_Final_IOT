# 🌡️ IOTClimate

Projeto de monitoramento ambiental em tempo real utilizando sensores IoT, comunicação MQTT e dashboard web para visualização de dados como temperatura, umidade e qualidade do ar.

## 📌 Visão geral

O IOTClimate foi desenvolvido como um sistema de coleta e análise de dados ambientais, com foco em oferecer uma visualização clara e acessível dos indicadores climáticos em tempo real. O projeto combina hardware, comunicação via rede e interface web para monitorar as condições do ambiente de forma prática e eficiente.

A aplicação web recebe informações de um broker MQTT e atualiza automaticamente os valores exibidos em um painel, permitindo acompanhar o comportamento do ambiente em tempo real.

## 🚀 Funcionalidades

- Monitoramento de temperatura;
- Monitoramento de umidade;
- Monitoramento da qualidade do ar;
- Conexão em tempo real com broker MQTT;
- Dashboard interativo para exibição dos dados;
- Interface simples e responsiva para uso em navegador;
- Visualização de informações em tempo real para análise do ambiente.

## 🧩 Tecnologias utilizadas

- HTML5;
- CSS3;
- JavaScript;
- MQTT com Paho.js;
- Broker Mosquitto;
- Estrutura de páginas web com navegação entre Home, Dashboard e Projeto.

## 🏗️ Estrutura do projeto

```text
Projeto_Final_IOT/
├── assets/
│   └── img/
├── src/
│   ├── js/
│   │   └── index.js
│   ├── pages/
│   │   ├── dashboard.html
│   │   ├── index.html
│   │   └── sobreProjeto.html
│   └── styles/
│       ├── dashboard.css
│       ├── index.css
│       └── sobreProjeto.css
├── README.md
└── ...
```

## 🔧 Como executar

1. Certifique-se de que o broker MQTT esteja em funcionamento.
2. Ajuste as configurações de conexão no arquivo `src/js/index.js`, incluindo o endereço do host e a porta do broker.
3. Abra a página inicial do projeto em um navegador.
4. Acesse a página de dashboard para visualizar os dados em tempo real.

Exemplo de configuração:

```javascript
const MQTT_HOST = "IP_DO_BROKER";
const MQTT_PORT = 9001;
```

> O projeto foi pensado para receber dados publicados em tópicos específicos do MQTT, como temperatura, umidade e qualidade do ar.

## 🌐 Páginas do projeto

- Home: apresentação do grupo e do conceito do projeto;
- Dashboard: visualização dos dados ambientais em tempo real;
- Projeto: informações detalhadas sobre a proposta e objetivo da solução.

## 👥 Equipe

Grupo 02 - Técnico em Desenvolvimento de Sistemas

- Ayla Cristina da Silva Vilela
- Gabriella Camacho Stavarengo
- Gustavo Millamonte
- Manuella da Silva Piva
- Maria Vitória Guedes Ferreira

## 📝 Descrição do objetivo

O objetivo principal do projeto é criar uma solução inteligente para monitorar indicadores ambientais e apoiar a análise de condições do ambiente por meio de tecnologia IoT. O sistema permite acompanhar mudanças em tempo real e compreender melhor os padrões de temperatura, umidade e qualidade do ar.

## ✅ Conclusão

O IOTClimate representa uma aplicação prática de IoT aplicada ao monitoramento ambiental, unindo tecnologia, dados em tempo real e uma interface acessível para análise e tomada de decisão.
