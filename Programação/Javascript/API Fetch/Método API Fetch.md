Um método utilizado para realizar requisições web, de conteúdos diversos. Um método muito utilizado para realizar requisições para APIs na internet, e utilizar seus conteúdos dentro de uma aplicação. 

1. Fornece uma interface para buscar recursos na rede.
2. Utiliza o método `fetch()` para realizar as requisições.
	Principais comandos: GET, POST, PUT & DELETE.
	Pode ser usado para incluir headers no cabeçalho. 
	Pode ser usado para incluir dados no corpo da requisição.
	Tratar os dados recebidos na resposta & tratar erros de requisição.

```
`fetch('url_da_busca', {
	method: 'GET' // POST, PUT, DELETE...
});`
```

Dessa forma, podemos 'puxar' os dados necessários para nossa tarefa, bem como incluir, enviar ou deletar os mesmos.

```
fetch('url_da_busca', {
	headers: {
		'Accept': 'application/json',
		'Content-Type': 'application/json',
		'Authorization': 'Bearer ${token}',
	}
});
```

TO BE CONTINUED.