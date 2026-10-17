# Calculadora Científica Avançada

Calculadora científica leve, responsiva e executada diretamente no navegador. O projeto reúne operações aritméticas, funções matemáticas, suporte a teclado e uma interface escura com fundo fotográfico.

## Visão geral

A aplicação é um único arquivo HTML que inclui a estrutura, os estilos e o JavaScript. Não exige instalação de dependências, servidor ou processo de compilação.

## Recursos

- Operações aritméticas: adição, subtração, multiplicação e divisão.
- Funções científicas: seno (`sin`), cosseno (`cos`), tangente (`tan`), logaritmo natural (`log`), raiz quadrada (`√`) e constante π (`π`).
- Uso de parênteses e potenciação com `^`.
- Limpeza completa (`AC`) e remoção do último caractere (`⌫`).
- Exibição da expressão calculada e do resultado.
- Entrada pela interface ou pelo teclado.
- Layout responsivo, efeitos visuais e fundo com imagem externa.

## Tecnologias

- HTML5
- CSS3
- JavaScript (sem bibliotecas ou frameworks)

## Estrutura do projeto

```text
.
├── calculadora02.html
└── README.md
```

## Como executar

1. Baixe ou clone o repositório.
2. Abra `calculadora02.html` em um navegador moderno.
3. Digite a expressão usando os botões ou o teclado e pressione `=` ou `Enter`.

Não é necessário instalar pacotes ou iniciar um servidor local.

### Publicar com GitHub Pages

1. Envie `calculadora02.html` e este `README.md` para a raiz do repositório.
2. No GitHub, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch desejada e a pasta `/ (root)`; salve.
5. Aguarde a publicação e acesse o endereço informado na página do GitHub Pages.

> Para usar o endereço principal do site como a página da calculadora, renomeie `calculadora02.html` para `index.html`.

## Como usar

| Ação | Como fazer |
|---|---|
| Inserir números e operadores | Clique nos botões ou use as teclas correspondentes |
| Calcular | Clique em `=` ou pressione `Enter` |
| Limpar a expressão | Clique em `AC` ou pressione `Escape` |
| Apagar o último caractere | Clique em `⌫` ou pressione `Backspace` |
| Agrupar operações | Digite `(` e `)` pelo teclado |
| Potenciação | Digite `^` pelo teclado; por exemplo, `2^3` |
| Usar funções científicas | Selecione a função e informe o argumento entre parênteses |

Exemplos:

```text
2+3*4
2^3
Math.sin(1)
Math.sqrt(25)
```

As funções trigonométricas seguem o comportamento padrão do JavaScript e recebem valores em **radianos**. A função `log` corresponde ao logaritmo natural (`Math.log`).

## Observações

- A imagem de fundo é carregada do Unsplash. É necessária uma conexão com a internet para exibi-la; sem conexão, a cor de fundo alternativa continua disponível.
- A interface mostra erros de expressão como `Erro`.
- O cálculo usa `Function` para interpretar a expressão digitada. Não use a aplicação para avaliar conteúdo recebido de fontes não confiáveis nem a incorpore a um sistema que aceite expressões de usuários sem validação adequada.
- O projeto não declara uma licença. Antes de reutilizar ou redistribuir o código, defina uma licença apropriada no repositório.

## Contribuições

Sugestões e melhorias são bem-vindas. Abra uma issue para relatar um problema ou propor uma funcionalidade; para contribuir com código, envie um pull request com uma descrição clara das alterações.
