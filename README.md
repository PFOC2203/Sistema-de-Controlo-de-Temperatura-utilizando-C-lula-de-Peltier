# Sistema-de-Controlo-de-Temperatura-utilizando-C-lula-de-Peltier
"Sistema IoT de controlo de temperatura com ESP32C3, Célula de Peltier e interface Web.
# 🌡️ Termóstato IoT - Célula de Peltier com ESP32-C3

Este repositório contém o hardware e o software desenvolvidos para o projeto da disciplina de [Nome da Disciplina] no [Nome da Escola/Universidade].

O objetivo deste projeto foi desenvolver uma máquina térmica baseada numa Célula de Peltier, capaz de aquecer ou arrefecer, controlada de forma remota via Wi-Fi através de um Web Server assíncrono.

## 🛠️ Tecnologias e Componentes
* **Microcontrolador:** XIAO ESP32-C3
* **Eletrónica de Potência:** MOSFETs N-Channel (IRLB8721) e Relé DPDT Finder.
* **Sensor Térmico:** PT1000 com condicionamento de sinal via AmpOp (TL084).
* **Software:** C++ (Arduino IDE) com LittleFS (HTML5/JS separados do código fonte).

## 📂 Estrutura do Projeto
- `/Hardware`: Esquemas elétricos e design da PCB desenvolvidos no KiCad.
- `/Software`: Código fonte do ESP32 e ficheiros do Web Server (`index.html` e `script.js`).
- `/Imagens`: Fotografias da montagem física e da interface web.

## ⚙️ Como Funciona
O ESP32 cria uma rede Wi-Fi local (Access Point). O utilizador acede a uma página Web moderna armazenada na memória Flash do chip (LittleFS). Através de JavaScript e Fetch API, o site comunica em tempo real com o hardware, definindo um alvo térmico e ativando os MOSFETs e o Relé mediante a necessidade de aquecer ou arrefecer.

## 👨‍💻 Autor
* **Pedro Cardoso** - [Teu Número de Aluno]
