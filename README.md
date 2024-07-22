![image](https://github.com/user-attachments/assets/ec8e904c-9daa-49db-8f0b-56a6364ac5a1)

# NLW Journey (Java)

API para organizar viagens à trabalho ou lazer. Sendo possível criar uma viagem com nome, data de início e fim. Dentro da viagem o usuário pode planejar sua viagem adicionando atividades para realizar em cada dia.

## Requisitos

- Java v17;
- Maven;

## Requisitos funcionais

- [x] O usuário cadastra uma viagem informando o local de destino, data de início, data de término, e-mails dos convidados e também seu nome completo e endereço de e-mail;
- [x] O criador da viagem recebe um e-mail para confirmar a nova viagem através de um link. Ao clicar no link, a viagem é confirmada, os convidados recebem e-mails de confirmação de presença e o criador é redirecionado para a página da viagem;
- [x] Os convidados, ao clicarem no link de confirmação de presença, são redirecionados para a aplicação onde devem inserir seu nome (além do e-mail que já estará preenchido) e então estarão confirmados na viagem;
- [x] Na página do evento, os participantes da viagem podem adicionar links importantes da viagem como reserva do AirBnB, locais para serem visitados e outros;
- [x] Ainda na página do evento, o criador e os convidados podem adicionar atividades que irão ocorrer durante a viagem com título, data e horário;
- [x] Novos participantes podem ser convidados dentro da página do evento através do e-mail e assim devem passar pelo fluxo de confirmação como qualquer outro convidado;

## HTTP

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=planner&uri=https%3A%2F%2Fgithub.com%2FCarolinatxrs%2Fplanner%2Fblob%2Fmaster%2Frequests)
