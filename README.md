# Fleas
## *"Ideas are like rivers and incomplete ones can be as annoying as fleas on a dog ... but all rivers flow into the sea"*
Um sistema de controle de estudos baseado em correntes de assuntos

É difícil manter os estudos orgnizados usando aplicativos de nota. Muito tempo valioso é perdido tentando lembrar onde parou e o que é preciso estudar, principalmente estudando vários assuntos ao mesmo tempo. Essa aplicação se propõe a solucionar isso

Basicamente um editor de texto especializado. O sistema é desenvolvido em Java/Spring Boot e armazena os dados com MySQL

## Adicionar novo Fluxo
Cada fluxo vai conter lembretes e anotações e aparecem em forma de percurso, como se cada atributo adicionada fosse um ponto diferente do percurso percorrido
- Título: Assunto que deseja aprender ou questão que iniciou o problema
- Lembrete:
  - Dúvida
  - Pesquisa
  - Material
  - Revisão
  - Personalizar lembrete
    - Adicionar uma descrição detalhando o lembrete
  - Anotação
    - No percurso aparece apenas o título da anotação, que clicando poderá ser acessada clicando no ícone dela. Se vai ser direcionado para outra página ou aparecer na mesma do percurso, ainda não sei
    - As anotações podem ser referenciadas por lembretes, do mesmo jeito que acontece nas conversas do whatsapp
  
- Redirecionar fluxo: Quando se deseja dedicar um fluxo para um assunto dentro de outro ou criar uma ligação entre dois fluxos (ramificações e link)
- Categorizar: Ajuntar fluxos em grupos
- Arquivar: Uma vez concluído, caso o usuário não deseje excluir o fluxo, ele pode armazenar tudo que registrou. Esse registro não vai mais aparecer na página principal e poderá ser acessado em uma página dedicada. Caso o fluxo tenha alertas abertos (no fluxo principal ou em uma das suas ramificações), não vai ser possível arquivá-lo

## Adicionar novo Objetivo de estudo
Metas que se pretende atingir

A parte de "gerenciamento de tarefas" do aplicativo

Vão poder ser categorizadas
  - Por curto-médio-longo prazo
  - Por áreas de estudo
  - Por período de tempo (metas do dia, da semana, do mês)
  - Personalizadas

## Situação dos fluxos
- Alerta de todos os fluxos
- Últimos fluxos editado
- Ter um campo "esquecidos" para os últimos fluxos editados mais antigos
- lista dos títulos de todos os fluxos
- (Não fazer categorização nem usar tags)
