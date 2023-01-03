Nesta documentação de JavaScript conheceremos o método map, do objeto Array, que nos permite **percorrer um vetor e obter um novo array cujos itens são o resultado de uma função de callback que recebe como parâmetro cada item original**. Por exemplo, podemos partir de um array de valores numéricos e obter um novo contendo o quadrado de cada item original.

### Como funciona o map?

O método map é invocado a partir de um array e recebe como parâmetro uma função de callback, que é invocada para cada item e retorna o valor do item equivalente no array resultante. 

![[Pasted image 20230101202038.png]]

Diferente do método forEach, o método map criará um novo vetor, contendo os valores selecionados ou que passaram por uma comparação, e fará uma nova tarefa (manipulação, atribuição, exclusão...).

![[Pasted image 20230101203055.png]]

No exemplo acima, a idéia era apenas triplicar os valores contidos dentro do vetor 'numeros'. Ao invocar o método map, foi pedido que, á cada índice contabilizado fosse triplicado e retornado via console. 
Os valores dados como resposta foram: 3, 9 e 15.

Um outro exemplo, mais complexo entretanto, seria como poderíamos manipular tais dados usando a função map e forEach.

![[Pasted image 20230101220322.png]]

Criamos um objeto, com seus respectivos atributos: id, nome, cpf, pai e estado... Agora, precisamos exibir apenas uma parte dos dados no console do navegador. Para isso:

![[Pasted image 20230101220430.png]]

Pronto! Usando o método map conseguimos percorrer cada setor do array, e ao mesmo tempo colocamos todos os conteúdos pertinentes ao que queremos fazer em uma nova variável, no caso, 'pessoasSimplificado'.
No console veremos de tal forma:

![[Pasted image 20230101220549.png]]

Mas e se quisermos verificar a idade de cada pessoa, para talvez permitir um acesso ou verificar se ela pode ou não criar uma conta em nossa plataforma? Bem, podemos fazer isso sem problema, veja:

![[Pasted image 20230101220751.png]]

Como resultado final, o método map percorerrá por cada informação do nosso vetor-objeto, e vai criar uma nova instância das informações que queremos dentro da variável 'pessoa'. A mesma é retornada ao final, e armazenada dentro de 'pessoasSimplificado'.
Usando essa mesma variável como alvo do método forEach, vamos agora comparar a informação 'idade' contida em cada um dos novos objetos que criamos.
Parece complicado, eu sei... vetores são bem difíceis de se entender (sempre!).

