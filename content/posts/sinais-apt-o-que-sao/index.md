---
title: 'Sinais APT - O que são?'
date: 2024-08-01T13:10:11-03:00
draft: false
author: PU2YKR
tags: ["NOAA", "Satélite", "Preparação"]
cover:
  image: img/apt-signal.jpg
---

# Sinais APT – O que são?

Os sinais APT (Automatic Picture Transmission) são um tipo de transmissão analógica usada por satélites meteorológicos da NOAA (National Oceanic and Atmospheric Administration) para enviar imagens da Terra em tempo real. Esses sinais permitem a recepção direta de imagens meteorológicas por estações terrestres, sem a necessidade de internet ou serviços intermediários.

## Como Funcionam os Sinais APT

Os sinais APT transmitem imagens em uma frequência de rádio específica, geralmente na faixa de VHF (Very High Frequency). Os satélites NOAA, como o NOAA-15, NOAA-18 e NOAA-19, capturam imagens da Terra usando seus instrumentos de bordo. Em seguida, elas são convertidas em sinais analógicos de baixa resolução, modulados em amplitude (AM) e armazenadas para transmissão. Normalmente o armazenamento é uma fita magnética contínua de alta qualidade.

Continuamente, um transmissor lê a fita de armazenamento e transmite o sinal utilizando a faixa de VHF 137 MHz. Cada satélite possui sua frequência específica para evitar interferências.

Os sinais APT foram projetados para serem facilmente acessíveis e decodificados utilizando poucos recursos computacionais. As estações terrestres recebem os sinais através de suas antenas – sendo as mais recomendadas, as QFH de polarização à direita ou a dipolo V em 120 graus de abertura entre seus elementos – e através de um simples receptor de rádio VHF sintonizado na frequência do satélite, um sinal audível muito característico é gravado para posterior processamento.

Após gravado o sinal em arquivo .wav, os sinais são processados através de softwares específicos, sendo os mais comuns o wxtoimg (caindo em desuso) e o satdump (muito poderoso e roda em Linux). O resultado são imagens do nosso planeta com a sobreposição de diversos sensores meteorológicos interessantes. O decodificador satdump adiciona algumas informações interessantes como um mapa de cores para volumes de chuva, linha das fronteiras dos países e outros recursos interessantes que podem ser tratados em outros artigos.

## Aplicações dos Sinais APT no Âmbito da Preparação

As imagens APT são usadas para monitorar condições meteorológicas em tempo real, como formações de nuvens, tempestades e frentes meteorológicas. Estas informações podem ser vitais em tempos de eventos climáticos extremos. Os sinais APT que uma estação recebe, sempre são referentes à região onde se encontra a estação receptora. Quanto maior a elevação do satélite no momento da captura, mais centralizada estará a região onde está a estação receptora.

A recepção e decodificação direta dos sinais APT permite a obtenção de dados meteorológicos sem depender de internet ou de serviços meteorológicos comerciais, o que é crucial em áreas remotas ou em situações de emergência, o que significa que é possível obter certo nível de autossuficiência na obtenção de dados meteorológicos relevantes.

Podemos perceber que esta é uma atividade enriquecedora que combina conhecimentos de radioamadorismo, eletrônica e meteorologia, promovendo a autossuficiência em comunicação off-grid e coleta de dados. Se você quer ler mais sobre este tema, fique sintonizado que em breve lançarei um post com um passo a passo simples e prático para que você possa capturar os sinais na sua estação!

Texto original: [SINAIS APT, O QUE SÃO](https://novelli.eti.br/site_novelli/sinais-apt-o-que-sao/)
