# Fleas
## *"Ideas are like rivers and incomplete ones can be as annoying as fleas on a dog ... but all rivers flow into the sea"*
Um sistema de estudos baseado em correntes de assuntos

Basicamente um editor de texto especializado. O sistema é desenvolvido em Java/Spring Boot e armazena os dados com MySQL

## Adicionar novo Fluxo
Cada fluxo vai conter 
- Título: Assunto que deseja aprender ou questão que iniciou o problema
- Desenvolvimento: Pontos altos e destaques do que tenho visto, só pra não perder a visão geral do que tenho visto
- Alerta: O próximo ponto que eu desejo buscar ou o ponto que ficou incompleto
- Redirecionar fluxo: Quando se deseja dedicar um fluxo para um assunto dentro de outro ou criar uma ligação entre dois fluxos (ramificações e link)
- Categorizar: Ajuntar fluxos em grupos
- Arquivar: Uma vez concluído, caso o usuário não deseje excluir o fluxo, ele pode armazenar tudo que registrou. Esse registro não vai mais aparecer na página principal e poderá ser acessado em uma página dedicada. Caso o fluxo tenha alertas abertos (no fluxo principal ou em uma das suas ramificações), não vai ser possível arquivá-lo

## Situação dos fluxos
- Alerta de todos os fluxos
- Últimos fluxos editado
- Ter um campo "esquecidos" para os últimos fluxos editados mais antigos
- lista dos títulos de todos os fluxos
- (Não fazer categorização nem usar tags)
