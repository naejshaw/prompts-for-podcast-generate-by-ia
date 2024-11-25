## 🧠 Prompts


ChatGPT：

|   Ação   | prompt                                                                                                                                                                                                                                                                         |
| :------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  título  | 
``Você é um roteirista de podcast e vamos criar um podcast de [área], focado em [tema] e eu gostaria de uma ajuda para criar 5 sugestões

de nomes criativos para um podcast de [tema] feito por [criadores] e que tenha algum trocadilho de [área] no nome



O podcast vai falar sobre [foco]



{REGRAS}

>Substitua: 

	[área] por tecnologia;

	[tema] por JavaScript;

	[foco] por bibliotecas e Frameworks;

	[criadores] por desenvolvedores sênior;

	[restrições] por ofensivas ou em outras línguas;

	[exclusões] por javascript;

>O nome deve ser enxuto, um título e subtítulo

>O nome tenha algum trocadilho de [área], podendo fazer referências a empresas, personagens ou acontecimentos da área de [área]

>O nome deve conter alguma palavra forte que remeta a [tema]



{REGRAS NEGATIVAS}

>Não quero que o nome contenha palavras [restrições]

>Não quero que utilize nenhuma palavra desta lista: [exclusões] |
``
                                                   
| conteúdo |
`` Você é um roteirista de podcast, e vamos criar um  roteiro de um podcast de [área], focado em [tema] cujo o nome é [nome] e tem foco em [foco],  com o público alvo de [público]

O formato do roteiro deve ser
[INTRODUÇÃO]
[CURIOSIDADE 1]
[CURIOSIDADE 2]
[FINALIZAÇÃO]

{REGRAS}
>Substitua: 
	[área] por tecnologia;
	[tema] por JavaScript;
	[foco] por bibliotecas e Frameworks;
	[subárea] por ReactJS e NextJS;
	[referências] por uma abertura de podcast descontraída, onde é apresentado o [nome] e o assunto que será debatido;
	[autoridade] por Filipe Deschamps;
	[apresentador] por Jean Almeida;
	[nome] por Reactando;
> No bloco [INTRODUÇÃO] substitua por uma introdução igual a [referências], como se fossem escritos pelo [autoridade]
> No bloco [CURIOSIDADE 1] substitua por uma curiosidade de [subárea]
> No bloco [CURIOSIDADE 2] sobre uma ferramenta para [tema]
> No bloco [FINALIZAÇÃO] substitua por uma despedida cool com o final 'Eu sou [apresentador] e esse foi o [nome] dessa semana'
> Use termos de fácil explicação
> O podcast vai ser apresentado somente por uma pessoa, chamada [apresentador]
> O podcast deve ser curto

{REGRAS NEGATIVAS}

- Não use muitos termos técnicos
- Não use muitos termos de difícil assimilação
- Não ultrapasse 5 minutos de duração
``
