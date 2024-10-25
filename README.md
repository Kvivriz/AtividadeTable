# AtividadeTable
1. Declara uma variável chamada "cadastros" e a inicializa como um array vazio.
2.
3. Declara uma função chamada "cadastrarUsuario", que recebe um parâmetro "event". Essa função será chamada quando o formulário for enviado.
4. Evita que a página recarregue ao enviar o formulário.
5. 
6. Obtém o valor do campo "nome" e o armazena na constante "nome".
7. Obtém o valor do campo "email" e o armazena na constante "email".
8. Cria um objeto "cadastro" com as propriedades "nome" e "email".
9. Adiciona o objeto "cadastro" ao array "cadastros".
10. Chama a função `atualizarTabela()" para mostrar os cadastros na tabela.
11. Reseta o formulário, limpando os campos de entrada.
12. Declara a função "atualizarTabela", que atualiza a tabela de cadastros.
13. Obtém o elemento do DOM que representa o corpo da tabela.
14. Limpa o conteúdo atual da tabela para evitar duplicatas.
15. Percorre cada item no array "cadastros".
16. Cria uma nova linha (<tr>) para a tabela.
17. Adiciona células (<td>) com o nome e o e-mail na linha.
18. Adiciona a nova linha ao corpo da tabela para exibir os dados.
