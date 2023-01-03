Uma estrutura de repetição simples, porém poderosa. **Ela executa uma tarefa enquanto a condição especificada for verdadeira.**
Embora pareça simples, é sempre necessário determinar um modo de parar o laço de repetição, para evitar pequenos conflitos dentro de uma aplicação.

O método `while` utiliza a seguinte sintaxe:

![[Pasted image 20230103021343.png]]

A variável 'main' se trata apenas de um valor genérico, que permite que o usuário altere o valor-alvo da tabuada gerada. 'x' e 'y' se tratam de variáveis de apoio, onde, dentro da própria estrutura de repetição serão utilizadas para o cálculo resultante no corpo da tabuada.

`x * y++` a cada interação, 1 será multiplicado por `y`, que por fim, recebe um novo valor á cada interação do laço de repetição.

`acc` vem de **acumulador**, e será o principal 'controle' do laço. Veja que, como parâmetro, ele também serve de comparação (caso `acc` seja menor que 10, quero que você realize as seguintes tarefas...). Bem ali no final, essa mesma variável recebe um acréscimo (`acc++`) de sí mesma, criando um controle, **no final das contas, uma hora teremos um `acc` MAIOR que 10, gerando uma parada brusca em todo o laço de repetição e não mais exibindo os valores solicitados no console do navegador.**

Mais detalhes podem ser visualizados nesse [link](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/while)


