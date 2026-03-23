# test-job-EffectiveMobile
Test assigment for the Junior DevOps vacancy from the Effective Mobile team

### Languages

The instructions are available in 2 languages. 
English and Russia 🇷🇺

# Requirements

- Docker 20+
- Docker Compose

Make sure Docker is running before starting the project

## Quick Start

docker compose up --build

# Short description

The user sends a GET request to Nginx. 
Nginx, in turn, acts as a reverse proxy and sends it to the backend, which is located inside the docker network.
The backend processes the request and returns it to Nginx. 
Nginx transmits the received response to the user

## Technologies Used

- Docker
- Docker Compose
- Nginx
- Python

# Instruction

1. First you need to clone the project: 
git clone https://github.com/ibragimhedshot1849-lab/test-job-EffectiveMobile.git

2. go to the repository:
cd project

3. In the terminal need write:
docker compose up --build

4. After assembly you need to open tab in browser and write to the line:
http://localhost:8080

5. We have to get:
Hello from Effective Mobile!

6. You can check it in the terminal:
curl http://localhost:8080

# Описание на Русском

# Требования

- Docker 20+
- Docker Compose

Перед запуском проекта убедитесь, что Docker запущен

## Быстрый запуск

docker compose up --build

# Краткое описание

Пользователь отправляет запрос GET в Nginx. 
Nginx, в свою очередь, действует как обратный прокси-сервер и отправляет его серверной части backend, которая находится внутри сети docker.
Серверная часть обрабатывает запрос и возвращает его Nginx. 
Nginx передает полученный ответ пользователю

# Инструкция

1. Сначала вам нужно клонировать проект: 
git clone https://github.com/ibragimhedshot1849-lab/test-job-EffectiveMobile.git

2. перейдите в репозиторий:
cd project

3. В терминале нужно написать:
docker compose up --build

4. После сборки нужно открыть вкладку в браузере и написать в строку:
http://localhost:8080

5. Мы должны получить:
Привет от Effective Mobile!

6. Вы можете проверить это в терминале:
curl http://localhost:8080