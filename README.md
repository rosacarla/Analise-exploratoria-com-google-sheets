# Análise Exploratória com Google Sheets

Projeto desenvolvido para análise da base de dados da bolsa de valores explorando o aplicativo Google Sheets, com PROCV (ou VLOOKUP), SE (ou IF) e ChatGPT.  
É uma proposta de trabalho feita na Imersão Python: Do Excel à Análise de Dados, promovida pela Alura.  
<img src=''>  

---
## Fórmulas  
- `Variação %` = Var. Dia %/100
- `Valor inicial (R$)` =Último R$/(Variação % + 1)
- `Quantidade de ações` =PROCV(Ativo;Total_de_acoes!A:B;2;0)
- `Variação R$` =(Último R$ - Valor inicial (R$)) * Quantidade de ações
- `Resultado` =SE(Variação R$>0;"Subiu";SE(Variação R$<0;"Desceu";"Estável"))

---  
## Prompt do ChatGPT para criação de novas colunas  
<img src=''>  

---  
## Desafio  
<img src=''>  

---  



