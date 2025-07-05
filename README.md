# 🌦️ WeatherApp - Previsão do Tempo com Localização em Tempo Real

Este projeto é um aplicativo mobile construído com **React Native** e **Expo**, que utiliza a API do **OpenWeatherMap** para exibir informações meteorológicas com base na **localização atual** do usuário. É exibida a temperatura atual, sensação térmica, umidade, velocidade do vento e uma descrição do clima — tudo em português.

## 📱 Tecnologias Utilizadas

- **React Native**
- **Expo**
- **Axios** (requisições HTTP)
- **OpenWeatherMap API**
- **expo-location** (obtenção da localização)

## 🚀 Funcionalidades

- 📍 Detecta a localização atual do usuário via GPS
- ☁️ Consulta a previsão do tempo na API do OpenWeatherMap
- 🌡️ Exibe temperatura, sensação térmica, umidade e vento
- 🎨 Altera a cor de fundo conforme o tipo de clima
- 🔄 Atualização automática ao abrir o app

## 🛠️ Instalação e Execução

### Pré-requisitos

- Node.js instalado
- Expo CLI global (`npm install -g expo-cli`)
- Conta gratuita no [OpenWeatherMap](https://openweathermap.org/) para obter uma chave de API (já está embutida no código para testes)
