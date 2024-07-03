# Jogo da Forca

O jogo da forca tem como principal objetivo descobrir uma palavra adivinhando as letras que ela possui. Cada rodada, o jogador irá se deparar com uma dica e a quantidade de letras da palavra correspondente a dica, o jogador deve escolher uma letra que suspeite fazer parte da palavra. Caso a letra contenha na palavra, será mostrado em que posição ela está.

## Regras do Jogo

- As palavras são selecionadas de acordo com a sua escolha, de um número de 1 a 100.
- Leia a dica da palavra oculta.
    - Exemplo: “DICA 66: PARTE DO CORPO HUMANO”
- Cada traço representa uma letra na posição da palavra.
    - Exemplo: “C A S A = _ _ _ _”
- A quantidade de letras na palavra também é dita.
    - Exemplo: “ -> A PALAVRA POSSUI [4] LETRAS”
- Escolha letras que acredite estar na palavra para tentar adivinhá-la.
- Você pode cometer no máximo 5 erros, caso ultrapasse você perderá.
- Você ganhará quando descobrir qual é a palavra oculta.
- O tempo não será limitado.

## Categorias

| **Categoria**           | **Subcategoria**                    |
|-------------------------|-------------------------------------|
| **Animais**             | Mamíferos, Aves                     |
| **Biologia**            | Parte do corpo humano, Conteúdos de biologia |
| **Comidas e bebidas**   | Frutas, Comidas, Comidas típicas brasileiras, Sobremesas |
| **Ciência**             | Elementos químicos, Conteúdos de física, Conteúdos de química |
| **Geografia**           | Estados brasileiros, Capitais do Brasil |
| **Literatura**          | Obras brasileiras, Cantores brasileiros |
| **Esportes**            | -                                   |
| **Vocabulários**        | Heróis da Marvel, Cor, Profissões, Roupas e acessórios, Objetos |

## Como Jogar

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/jogo-da-forca.git
    ```

2. Compile o código:
    ```sh
    gcc -o jogo_da_forca jogo_da_forca.c
    ```

3. Execute o jogo:
    ```sh
    ./jogo_da_forca
    ```

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e correções de bugs.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
