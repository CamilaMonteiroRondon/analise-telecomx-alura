# 📉 Análise de Retenção e Churn: TelecomX

## 📝 Sobre o Projeto
Este projeto analisa os dados de cancelamento (churn) da TelecomX. O objetivo é identificar os fatores que levam o cliente a abandonar o serviço e fornecer embasamento estratégico para reduzir a evasão e proteger a receita da empresa.

## 📊 Análise dos Indicadores

### 🚩 1. Panorama Geral de Evasão
Atualmente, enfrentamos uma taxa de churn de **26,5%**. Este indicador é o ponto de partida que justifica as ações urgentes de retenção.
![Proporção de Churn](grafico_proporcao_churn.png)

### 💸 2. Sensibilidade ao Preço (Ticket Médio)
Identificamos que a "barreira de saída" é baixa para faturas entre **R$ 70,00 e R$ 110,00**. Clientes com contas mais altas são os primeiros a abandonar a rede.
![Análise de Densidade](grafico_densidade.png)

### ⚔️ 3. O "X" da Questão: Tempo vs. Gasto
Clientes que evadem permanecem apenas **18 meses** na base, pagando um ticket médio elevado de **R$ 74,44**. Em contraste, clientes fiéis ficam **38 meses** com faturas de **R$ 61,27**.
![O X da Questão](grafico_x_da_questao.png)

### 🔗 4. Correlação de Variáveis
Análise estatística que comprova: quanto maior o tempo de casa (`tenure`), menor a chance de churn, atuando como um escudo natural do negócio.

## 💡 Conclusão Final
Recomendamos a **fidelização agressiva no 1º ano** e a **migração forçada de contratos mensais para anuais**. O foco deve ser o cliente de ticket alto nos primeiros 18 meses, onde o risco de perda é máximo.

## 🛠️ Tecnologias Utilizadas
* **Python** 🐍
* **Pandas** 🐼 (Tratamento de dados)
* **Matplotlib** 📈 (Visualização de dados)
* **VS Code** 💻

---

## 👩‍💻 Autoria
**Camila Monteiro Rondon** *Estudante de Data Science* 
🚀 Integrante do programa **Alura + Oracle Next Education (ONE)**