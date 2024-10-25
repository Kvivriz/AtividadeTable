# AtividadeTable
1. Declara uma variável chamada `cadastros` e a inicializa como um array vazio.  

2.  
   
3. Declara uma função chamada `cadastrarUsuario`, que recebe um parâmetro `event`. Essa função será ativada quando o formulário for enviado. Abre as chaves da função.  

4. Impede que a página recarregue ao enviar o formulário.  

5.  
   

6. Obtém o valor do campo `nome` e armazena na constante `nome`.  

7. Obtém o valor do campo `email` e armazena na constante `email`.  

8.  
   

9. Cria um objeto `cadastro` que contém as propriedades `nome` e `email`.  

10. Adiciona o objeto `cadastro` ao array `cadastros`.  

11.  
   

12. Chama a função `atualizarTabela()` para exibir os cadastros na tabela.  

13.  
   

14. Limpa o formulário, restaurando os campos de entrada.  

15.  
   

16. Fecha a chaves da função `cadastrarUsuario`.  

17.  
   

18. Declara a função `atualizarTabela`, que é responsável por atualizar a tabela de cadastros. Abre as chaves da função.  

19.  
   

20. Obtém o elemento da página que representa o corpo da tabela.  

21. Remove o conteúdo atual da tabela para evitar entradas duplicadas.  

22. Percorre cada item no array `cadastros`.  

23. Cria uma nova linha (`<tr>`) para a tabela.  

24. Adiciona células (`<td>`) com o nome e o e-mail na linha.  

25. Insere a nova linha ao corpo da tabela para exibir as informações.  

26. Fecha as chaves da função `atualizarTabela`.  
