#### 📈 ANÁLISE EXPLORATÓRIA COM GOOGLE SHEETS

Projeto desenvolvido para análise da base de dados da bolsa de valores explorando o aplicativo Google Sheets, com PROCV (ou VLOOKUP), SE (ou IF) e ChatGPT.  
É uma proposta de trabalho feita na <i>Imersão Python: Do Excel à Análise de Dados</i>, promovida pela Alura.    

<img src='https://github.com/rosacarla/analise-exploratoria-com-google-sheets/blob/main/images/aula01.png'>  

---

#### 📄 FÓRMULAS DO GOOGLE SHEETS  
- `Variação %` = Var. Dia %/100
- `Valor inicial (R$)` =Último R$/(Variação % + 1)
- `Quantidade de ações` =PROCV(Ativo;Total_de_acoes!A:B;2;0)
- `Variação R$` =(Último R$ - Valor inicial (R$)) * Quantidade de ações
- `Resultado` =SE(Variação R$>0;"Subiu";SE(Variação R$<0;"Desceu";"Estável"))

☑️ Ver [resolução](https://github.com/rosacarla/analise-exploratoria-com-google-sheets/blob/main/Resolucao%20-%20Imersao%20Python%20-%20Tabela%20de%20acoes.xlsx).

---  

#### 💬PROMPT DO CHATGPT PARA CRIAR NOVAS COLUNAS  
<img src='https://github.com/rosacarla/analise-exploratoria-com-google-sheets/blob/main/images/aula01-chatgpt.png'>  

---  

#### 🧠 DESAFIO DA AULA 1
<img src='https://github.com/rosacarla/analise-exploratoria-com-google-sheets/blob/main/images/aula01-desafio.png'> 

- Fazer os cálculos com as colunas de porcentagem (variação semanal; mensal; anual e 12 meses);  
- Pegar via Chat GPT as faixas de idade;  
- Pedir para o GPT gerar a fórmula IF para as faixas de idade.

<img src='https://github.com/rosacarla/analise-exploratoria-com-google-sheets/blob/main/images/aula01-solucao.png'>

---  

#### ✍️ AUTORA  
Carla Edila Silveira  
Contato: rosa.carla@pucpr.edu.br  

---

#### ©️ LICENÇA

[MIT](https://choosealicense.com/licenses/mit/)  

---  

#### 🔗 LINKS ÚTEIS  

[Análise exploratória: primeiros passos](https://www.alura.com.br/artigos/analise-exploratoria?_gl=1*v2kvnv*_ga*MTkyMTEwNTQ2Ni4xNzA5NTk0NTU0*_ga_1EPWSW3PCS*MTcxMTQxOTkxMS4yMy4wLjE3MTE0MTk5MTEuMC4wLjA.*_fplc*TmtySU9mMkZvOXRhNkJFTnpuTHRsSDFMdU5lM0YzcyUyRlNjaDFOQ3pqOWU3Tk1QZFJvZWJXMyUyQkRTYnElMkZEJTJCMlA5bjZ4ZTFvUnZQSzhzcEt0ZCUyQjhaUlM4NjZyRkloNGxFUHN5VXB6dWtFOHhJeGRJTXVBTTdBelo0dUk4M0FuQSUzRCUzRA..)  
[O que é IA generativa?](https://www.alura.com.br/artigos/inteligencia-artificial-ia-generativa-chatgpt-gpt-midjourney?_gl=1*ltt5gj*_ga*MTkyMTEwNTQ2Ni4xNzA5NTk0NTU0*_ga_1EPWSW3PCS*MTcxMTQyNjU5My4yNC4wLjE3MTE0MjY1OTMuMC4wLjA.*_fplc*TmtySU9mMkZvOXRhNkJFTnpuTHRsSDFMdU5lM0YzcyUyRlNjaDFOQ3pqOWU3Tk1QZFJvZWJXMyUyQkRTYnElMkZEJTJCMlA5bjZ4ZTFvUnZQSzhzcEt0ZCUyQjhaUlM4NjZyRkloNGxFUHN5VXB6dWtFOHhJeGRJTXVBTTdBelo0dUk4M0FuQSUzRCUzRA..)  
[Tendências e inovações no mercado financeiro | Hipsters](https://www.alura.com.br/podcast/hipsterstech-tendencias-e-inovacoes-no-mercado-financeiro-deep-dive-bradesco-1-hipsters-ponto-tech-361-a2326?_gl=1*ltt5gj*_ga*MTkyMTEwNTQ2Ni4xNzA5NTk0NTU0*_ga_1EPWSW3PCS*MTcxMTQyNjU5My4yNC4wLjE3MTE0MjY1OTMuMC4wLjA.*_fplc*TmtySU9mMkZvOXRhNkJFTnpuTHRsSDFMdU5lM0YzcyUyRlNjaDFOQ3pqOWU3Tk1QZFJvZWJXMyUyQkRTYnElMkZEJTJCMlA5bjZ4ZTFvUnZQSzhzcEt0ZCUyQjhaUlM4NjZyRkloNGxFUHN5VXB6dWtFOHhJeGRJTXVBTTdBelo0dUk4M0FuQSUzRCUzRA..)  
[ChatGPT: dicas e como usar](https://www.alura.com.br/artigos/chatgpt?_gl=1*1czxbrx*_ga*MTkyMTEwNTQ2Ni4xNzA5NTk0NTU0*_ga_1EPWSW3PCS*MTcxMTQyNjU5My4yNC4xLjE3MTE0MjY3MzguMC4wLjA.*_fplc*TmtySU9mMkZvOXRhNkJFTnpuTHRsSDFMdU5lM0YzcyUyRlNjaDFOQ3pqOWU3Tk1QZFJvZWJXMyUyQkRTYnElMkZEJTJCMlA5bjZ4ZTFvUnZQSzhzcEt0ZCUyQjhaUlM4NjZyRkloNGxFUHN5VXB6dWtFOHhJeGRJTXVBTTdBelo0dUk4M0FuQSUzRCUzRA..)  

---




