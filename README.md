# Subject Collector
Um sistema de estudos que decide aleatoriamente qual assunto vai ser estudado

O sistema é desenvolvido em Java/Spring Boot e armazena os dados com MySQL

## Estrutura e Funcionalidades
### Página Principal
- Adicionar novos assuntos
- Conferir se certo assunto já foi adicionado
- Acessar a coleção de assuntos (que terá uma página dedicada)
- Selecionar aleatoriamente um dos assuntos armazenados
  - Trocar: Outro assunto é selecionado e a probabilidade do assunto anterior aparecer novamete deve diminuir
  - Deletar: O assunto pode ser deletado na própria página inicial

### Banco de Assuntos
- Listar os assuntos (por padrão dos mais antigos para os mais recentes) conforme os filtros aplicados
- Atualizar
- Deletar
