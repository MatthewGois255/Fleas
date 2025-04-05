# Fleas
## *"Ideas are like rivers and incomplete ones can be as annoying as fleas on a dog ... but all rivers flow into the sea"*
Um sistema de controle de estudos baseado em correntes de assuntos

É difícil manter os estudos orgnizados usando aplicativos de nota. Muito tempo valioso é perdido tentando lembrar onde parou e o que é preciso estudar, principalmente estudando vários assuntos ao mesmo tempo. Essa aplicação se propõe a solucionar isso

Basicamente um editor de texto especializado. O sistema é desenvolvido em Java/Spring Boot e armazena os dados com MySQL

## Adicionar novo Fluxo
Cada fluxo vai conter 
- Título: Assunto que deseja aprender ou questão que iniciou o problema
- Adicionar :

  Dúvida

  Pesquisa

  Personalizar lembrete
  
- Redirecionar fluxo: Quando se deseja dedicar um fluxo para um assunto dentro de outro ou criar uma ligação entre dois fluxos (ramificações e link)
- Categorizar: Ajuntar fluxos em grupos
- Arquivar: Uma vez concluído, caso o usuário não deseje excluir o fluxo, ele pode armazenar tudo que registrou. Esse registro não vai mais aparecer na página principal e poderá ser acessado em uma página dedicada. Caso o fluxo tenha alertas abertos (no fluxo principal ou em uma das suas ramificações), não vai ser possível arquivá-lo

## Situação dos fluxos
- Alerta de todos os fluxos
- Últimos fluxos editado
- Ter um campo "esquecidos" para os últimos fluxos editados mais antigos
- lista dos títulos de todos os fluxos
- (Não fazer categorização nem usar tags)
