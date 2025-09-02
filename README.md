# Aplicativo de Cálculo de IMC com Flet

Este é um projeto feito em Python utilizando a biblioteca Flet para desenvolver uma interface gráfica interativa. O objetivo é permitir que o usuário calcule seu IMC (Índice de Massa Corporal) a partir das informações de peso e altura fornecidas. A aplicação também exibe a categoria correspondente ao valor calculado, com cores e mensagens visuais distintas.

⚙️ O que o aplicativo faz

Permite ao usuário inserir seu peso (em kg) e altura (em metros);

Realiza o cálculo do IMC com a fórmula:
IMC = Peso / (Altura × Altura);

Mostra o resultado com a classificação:

Abaixo do peso: IMC menor que 18,5

Peso adequado: IMC entre 18,5 e 24,9

Sobrepeso: IMC entre 25 e 29,9

Obesidade: IMC igual ou acima de 30

Traz um botão para apagar os campos e reiniciar o cálculo;

Suporte a temas claro e escuro com alternância diretamente na barra superior (AppBar);

A cor da AppBar se ajusta automaticamente para manter boa visibilidade do texto e dos ícones.

🧰 Ferramentas e Tecnologias

Python → Linguagem usada para construir toda a lógica e o funcionamento do app.

Flet → Framework que permite criar UIs modernas em Python, compatível com web e desktop.

Visual Studio Code → Editor escolhido para desenvolver e organizar o código.

Git/GitHub → Utilizados para controle de versão e hospedagem do código-fonte.

💻 Como executar o projeto
🔸 Criar e ativar ambiente virtual
python -m venv .venv
.venv\Scripts\activate

🔸 Instalar a biblioteca Flet
pip install flet-desktop
pip show flet

🔸 Iniciar o app
flet run --web nomeprojeto.py

<img width="1908" height="874" alt="Captura de tela 2025-09-02 144214" src="https://github.com/user-attachments/assets/77473026-2983-4029-ad13-ba9e9cf0342f" />
<img width="1897" height="886" alt="Captura de tela 2025-09-02 144223" src="https://github.com/user-attachments/assets/a086e9ca-5fa1-4ae2-8443-e797ddfd86d4" />



