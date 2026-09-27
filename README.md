⚡ Calculadora de Consumo Elétrico

📋 Sobre o projeto

A Calculadora de Consumo Elétrico é um programa desenvolvido em Python para estimar o consumo mensal de energia de um aparelho elétrico.

O usuário informa:

⚡ Nome do aparelho

🔌 Potência do aparelho em watts (W)

⏱️ Tempo médio de utilização por dia, em horas

Com essas informações, o programa calcula o consumo estimado em kWh por mês e também apresenta uma estimativa de custo com base no valor de R$ 0,75 por kWh.

🎯 Objetivo

O objetivo do projeto é facilitar a compreensão do consumo de energia elétrica dos aparelhos utilizados no dia a dia, ajudando o usuário a ter uma estimativa do gasto mensal.

🛠️ Tecnologias utilizadas

🐍 Python

💻 Visual Studio Code

🐙 Git e GitHub

🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a seguinte fórmula:

consumoMensal = (potencia × horasDia × 30) / 1000

Onde:

potencia = potência do aparelho em watts (W)

horasDia = quantidade média de horas de utilização por dia

30 = quantidade estimada de dias no mês

1000 = conversão de Wh para kWh

O custo estimado é calculado por:

custoMensal = consumoMensal × valorKwh

Neste projeto, foi utilizado o valor fixo de:

R$ 0,75 por kWh

ℹ️ O valor de R$ 0,75 é apenas uma referência para o exercício. O preço real da energia varia de acordo com a região, distribuidora, tarifa e outros componentes da conta de luz.

▶️ Como executar
1. Clone o repositório
git clone https://github.com/DiegoSoutoFonseca/consumo-eletrico

2. Acesse a pasta
cd consumo-energia

3. Execute o programa
python app.py

Em alguns sistemas, pode ser necessário utilizar:

python3 app.py

💻 Exemplo de utilização
⚡ Calculadora de Consumo Elétrico
----------------------------------------
Digite o nome do aparelho: Geladeira
Digite a potência do aparelho em watts (W): 150
Digite o tempo médio de uso diário (horas): 10

📊 Resultado
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
💰 Custo estimado: R$ 33.75 por mês

💡 Dica: reduzir o tempo de uso pode ajudar a diminuir o consumo de energia.

📁 Estrutura do projeto
consumo-energia/
├── app.py
└── README.md

🚀 Funcionalidades

 Cadastro do nome do aparelho

 Entrada da potência em watts

 Entrada do tempo médio de uso diário

 Cálculo do consumo mensal

 Estimativa do custo mensal

 Exibição de dicas para economia de energia

 Documentação do projeto

👨‍💻 Projeto de iniciação em tecnologia

Projeto desenvolvido como atividade prática de introdução à programação, Git, GitHub e desenvolvimento de aplicações em Python.

⚡ Consumo consciente começa com informação!
