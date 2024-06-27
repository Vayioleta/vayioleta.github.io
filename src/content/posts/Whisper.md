---
title: WhisperIA-Docker-Local
published: 2022-11-28
tags: [Python, IA]
description: "Whisper OpenIA Docker Local"
category: IA
draft: false
---

# Links
- [GitHub Repository](https://github.com/Vayioleta/WhisperIA-Docker)

# Whisper IA en Docker
> Requisitos:
> Docker en GPU: https://github.com/Vayioleta/Wiki/blob/main/Run%20Docker%20in%20GPU.md

# Compilar y Ejecutar
> Para compilarlo, ejecuta esto en la carpeta:
`docker build -t whisper .`

> Para ejecutarlo, ejecuta esto en la carpeta:
`docker container run -it -v <CARPETA LOCAL>:/ia/ --gpus=all whisper`

> Ejemplo:
`docker container run -it -v D:\contenedores\Whisper\volumen:/ia/ --gpus=all whisper`

# Comandos dentro del terminal del contenedor
> Transcribir audio:
`whisper "./audio.mp3" --task transcribe --model medium`
> Traducir audio:
`whisper "/content/audio.mp3" --task translate --model medium`

# Referencias (¡gracias!)
> https://github.com/openai/whisper

> https://colab.research.google.com/drive/1CvvYPAFemIZdSOt9fhN541esSlZR7Ic6?usp=sharing#scrollTo=UlVRSbPC7IRJ