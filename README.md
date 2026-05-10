Automação de Impressão de Etiquetas com Zebra 2.3

Sistema desenvolvido em Python para automatizar preenchimento e impressão de etiquetas utilizando automação de mouse e teclado.

Repositório oficial:
Automação de impressão de etiquetas com zebra 2.3

📌 Funcionalidades
Interface gráfica simples usando Tkinter
Captura automática da posição do campo serial
Automação de preenchimento de números sequenciais
Suporte para dois tipos de barra:
normal
lateral
Pausa da automação usando F8
Confirmação visual das posições antes de iniciar
Controle de continuidade ou encerramento da automação
Impressão automática via atalho CTRL + P
🖥️ Interface

O programa possui:

Campo para serial inicial
Campo de quantidade
Seleção do tipo de barra
Captura da posição do campo serial
Botão de iniciar automação
Sistema de pausa em tempo real
⚙️ Tecnologias Utilizadas
Python
Tkinter
PyAutoGUI
Keyboard
Threading
📚 Bibliotecas
import tkinter as tk
from tkinter import messagebox
import threading
import pyautogui as Auto
import time
import keyboard
📦 Instalação

Clone o repositório:

git clone https://github.com/Alex984V/Automatiza-o-de-impress-o-de-etiquetas-com-o-zebra-2-3.git

Entre na pasta:

cd Automatiza-o-de-impress-o-de-etiquetas-com-o-zebra-2-3

Instale as dependências:

pip install pyautogui keyboard
▶️ Como Usar
1️⃣ Execute o programa
python automacao.py
2️⃣ Capture a posição do serial

Clique em:

Capturar Campo Serial

Depois posicione o mouse sobre o campo desejado.

3️⃣ Configure os dados

Preencha:

Serial inicial
Quantidade
Tipo de barra
4️⃣ Inicie a automação

Clique em:

Iniciar

O sistema irá:

testar posições
pedir confirmação
iniciar preenchimento automático
imprimir automaticamente
⏸️ Controles
Tecla	Função
F8	Pausar automação

Ao pausar:

Sim → continua
Não → encerra
⚠️ Observações
Não mova o mouse durante a automação
Utilize resolução compatível com as posições configuradas
O sistema depende das coordenadas capturadas
Algumas funções podem exigir execução como administrador
📁 Estrutura do Projeto
📦 Automatiza-o-de-impress-o-de-etiquetas-com-o-zebra-2-3
 ┣ 📜 automacao.py
 ┣ 📜 README.md
🚀 Objetivo

Projeto criado para estudo de:

automação desktop
interface gráfica em Python
automação de processos repetitivos
controle de teclado e mouse
threads e multitarefa
👨‍💻 Autor

Alex Vieira

GitHub:
Alex984V GitHub
