Esse trabalho foi desenvolvido com o objetivo de criar um sistema semelhante a sistemas de jogos de rpg eletronicos
ele se trata de um inventario onde o jogador pode armazenar seus itens que coleta e organizare e manipular eles
A classe "Iten" do sistema é a classe abstrata que define os atributos base de cada iten, como nome, peso, raridade e etc..., e possui os metodos "comparaIten" que ser posteriormente para organizar o inventario em orde de nome e peso. possui o metodo abstrato "getTipo" que serve para dizer qual tipo de item é. E os metodos imprimeDados e imprimeFicha sendo o primeiro um metodo abstrato que serve para imprimir todos os dados das subsclasses de iten, e outro imprime todos os dados base do iten.
Temos também as classes "Arma" e "Armaduras" que são subclasses da classe "Iten" e cada uma possui seus próprios atributos exclusivos e possuem os metodos get para cada atributo e as duas possuem suas implementação dos metodos "getTipo" e "imprimeDados" que herdaram da classe "Iten".
E por ultimo temos a classe "Inventario" ela basicamente seria a classe CRUD do nosso sistema, ou seja ela que é responsavel por armazenar os itens dentro de um arquivo binario e manipular esse arquivo, podendo adcionar ou remover itens, procurar e atualizar itens, alem de poder imprimir todos os itens armazenados ou imprimir só os itens de um tipo.
*Para testar*
Para testar esse programa vc pode executar ele e ir testando cada uma de suas opções, quando vc o executar será exibido no terminal uma lista de ações que vc pode fazer, como adcionar/remover iten, procurar um iten e atualiza-lo. Assim vc pode ir testando para ver se está tudo certo com o programa