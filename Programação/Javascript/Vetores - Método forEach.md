O método forEach é utilizado para percorrer elementos contidos dentro de um vetor. Ele executa uma função para o processamento desses cados, que pode conter 3 parâmetros.

![[Pasted image 20230101195846.png]]

No exemplo acima, criamos um vetor que contém alguns nomes que me vieram em mente. A idéia é justamente percorrer esses elementos, contidos dentro do vetor, e executar um script para cada conteúdo.

A sintaxe do forEach pode conter 3 parâmetros, como já mencionei:
* 'nomeAtual' - vai exibir o próprio valor contido dentro do vetor.
* 'index' - vai exibir o índice de cada valor contido, começando sempre por '0'.
* 'array' - vai exibir TODO o conteúdo do array, e de forma equivalente aos conteúdos contidos dentro do vetor-alvo.

Excluíndo qualquer um desses parâmetros faz com que, em caso de serem exibidos de alguma forma, os respectivos valores sejam ocultados da exibição final.

No exemplo abaixo, criamos um vetor com objetos, dentro dele temos alguns produtos e também um atributo chamado 'porcetagemDesconto'.

![[Pasted image 20230101200220.png]]

Seria muito trabalhoso aplicar de forma manual um desconto ao produto sempre que precisássemos, por tanto, utilizando o método forEach conseguimos realizar tal tarefa de forma mais dinâmica.

	produtosEletronicos.forEach((produtoAtual, index, array) => {

Embora eu tenha definido os valores dentro do parâmetro da função forEach, veja que acabei não os utilizando (no caso, (..., index, array)). Ao invés disso, utilizei apenas o 'produtoAtual' para exibir de forma clara os valores dentro do console.log.