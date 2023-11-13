# Harpia


Projeto em Desenvolvimento:

Ideia: 

- WebScraping dos dados de balanços das instituições financeiras disponivel do Bacen - Linguagem escolhida: GO pela sua rapidez, assim consigo extrair todos os dados e fazer um pre tratamento mais rápido
- Subir em um Banco de Dados em SQL
- Utilizando o Python, criar uma "biblioteca" com OOP que seja capaz de calcular métrica, DFC, DRE e mostrar tanto dem um DataFrame quanto exportar ao excel
- por exemplo, se o nome da função for DRE e o objeto que representa os dados da instituição financeira no banco seja "ITAU".: 
    - ITAU.DRE() -> retornaria a DRE do objeto ITAU mes a mes 
    - ITAU.DRE().VERTICAL() -> retornaria a DRE já com a análise vertical
    - etc ...

  Pretendo com isso, facilitar a obtenção de balancetes e a análise dele.

  Ideia Futura:

  Utilizar as séries temporais para um modelo de valuation / previsão a fim de precificar as ações.
  

