# 💻 Lógica
> Mini projeto feito durante as aulas de lógica da UFCG


## Especificação:

Submeta uma especificação em Alloy com o seguinte sistema:

A UFCG vai implantar um sistema de Uber interno (quando todos estiverem devidamente vacinados). 

No sistema, passageiros só podem ser alunos, professores e servidores da UFCG. Esses podem agendar corridas para a UFCG, dentro de certos intervalos de tempo para ida e volta; usuários serão agrupados por região da cidade, para facilitar a combinação. O sistema permite também que alunos da UFCG que moram em outras cidade ofereçam e recebam corridas.

Alunos, professores e servidores podem ser motoristas também, sendo cadastrados como tal no sistema. 

O sistema armazenará um registro de corridas a pagar e a receber, independente do valor. Quem usar o serviço carona cria um débito, e quem servir como motorista recebe um crédito - no final do mês essa contabilidade é feita pra saber se o usuário deve pagar ou receber.

Cada carro poderá receber três passageiros, além do motorista. As corridas podem ser agendadas em 4 horários:

ida para UFCG: 7:30, 9:30, 13:30, 15:30
saída da UFCG: 10:00, 12:00, 16:00, 18:00
Para simplificar, assuma que todas as corridas acontecem todos os dias da semana, no horário agendado.

Considere apenas 5 regiões: Centro, Leste, Oeste, Norte e Sul
