# 🖐️ Hand Tracking & PC Control System

Uma Prova de Conceito (PoC) explorando Visão Computacional e Interação Humano-Máquina (HCI) para controle de interfaces sem a necessidade de hardware periférico.

## 🎯 O Projeto

Este projeto exploratório foi desenvolvido em 2024 para entender e aplicar na prática os fundamentos de Visão Computacional. O sistema utiliza a webcam para mapear os pontos de articulação (landmarks) das mãos em tempo real e traduzir esses gestos em comandos diretos para o sistema operacional do computador.

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem base da aplicação.
* **OpenCV:** Captura e processamento do feed de vídeo em tempo real.
* **MediaPipe:** Framework do Google utilizado para a detecção de alta precisão dos *Hand Landmarks* (rastreamento de 21 pontos 3D da mão).

## 🚀 Funcionalidades e Desafios Técnicos

* Processamento de frames de vídeo em tempo real otimizando o uso de processamento.
* Mapeamento espacial coordenado (traduzindo coordenadas capturadas pela câmera para a resolução da tela).
* Criação de gatilhos acionáveis baseados em padrões de distâncias matemáticas entre os pontos da mão (ex: reconhecer o gesto de "pinça" para simular o clique do mouse).

## 📺 Demonstração em Vídeo

Gravei um vídeo curto demonstrando a latência e a precisão do sistema funcionando na prática.

<div align="center">
  <a href="https://www.linkedin.com/feed/update/urn:li:activity:7196867609546354692/" target="_blank">
    <img src="pre-linkedin.png" alt="Demonstração do Projeto no LinkedIn">
  </a>
</div>

> 💡 **Dica:** Clique na imagem acima para assistir ao vídeo completo da demonstração no meu LinkedIn. Aproveite e [conecte-se comigo por lá](https://www.linkedin.com/in/felipecezarcruz/)!

---
*Projeto desenvolvido em 2024. Mantido neste portfólio como registro de evolução técnica e interesse em tecnologias de Inteligência Artificial e Visão Computacional.*
