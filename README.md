# 🧮 Calculadora Científica Avançada

Uma aplicação web moderna, responsiva e intuitiva de uma calculadora científica. Desenvolvida apenas com tecnologias nativas da web (HTML5, CSS3 e JavaScript puro), ela oferece suporte tanto para operações aritméticas básicas quanto para funções científicas avançadas, com um visual elegante em modo escuro (Dark Mode).

---

## ✨ Funcionalidades

- **Operações Básicas:** Adição (`+`), subtração (`-`), multiplicação (`*`), divisão (`/`) e exponenciação (`^` via teclado).
- **Funções Científicas:**
  - Trigonometria: Seno ($\sin$), Cosseno ($\cos$) e Tangente ($\tan$).
  - Logaritmo natural ($\ln$ / `Math.log`).
  - Raiz quadrada ($\sqrt{x}$).
  - Constante Pi ($\pi$).
- **Histórico de Operações:** Exibe a expressão anterior logo acima do resultado atual.
- **Suporte Completo ao Teclado:** Digite expressões, apague caracteres ou calcule resultados diretamente pelo teclado físico.
- **Tratamento de Erros:** Feedback visual imediato caso uma expressão matemática inválida seja inserida.
- **Design Responsivo e Moderno:** Interface em *Dark Mode* com variáveis CSS, transições suaves e adaptação para telas menores (celulares).

---

## 🚀 Tecnologias Utilizadas

O projeto foi construído em um único arquivo (*Single-File Application*), utilizando:

- **HTML5:** Estruturação semântica dos elementos e visor da calculadora.
- **CSS3:** Estilização moderna utilizando *CSS Grid* para os botões, *Flexbox* para o alinhamento na tela, e *CSS Variables* (`:root`) para fácil manutenção da paleta de cores.
- **JavaScript (ES6+):** Lógica de construção da expressão matemática, manipulação do DOM, eventos de teclado e avaliação segura das expressões utilizando o construtor `Function()`.

---

## 🛠️ Como Executar o Projeto

Por ser uma aplicação web estática contida em um único arquivo, você não precisa instalar dependências ou configurar servidores complexos.

1. Faça o download ou copie o código para um arquivo chamado `index.html`.
2. Dê um duplo clique no arquivo `index.html` para abri-lo em qualquer navegador web moderno (Google Chrome, Firefox, Edge, Safari, etc.).
3. Pronto! A calculadora já estará funcionando.

---

## ⌨️ Atalhos de Teclado

Além de clicar nos botões da interface, você pode utilizar o teclado do seu computador para agilizar os cálculos:

| Tecla | Ação na Calculadora |
| :--- | :--- |
| `0` a `9` | Insere os números correspondentes |
| `+`, `-`, `*`, `/` | Insere os operadores matemáticos básicos |
| `^` | Insere operador de potência (convertido para `**`) |
| `.` | Insere o ponto decimal |
| `(` e `)` | Abre e fecha parênteses (essencial para fechar funções científicas) |
| `Enter` | Calcula o resultado da expressão (`=`) |
| `Backspace` | Apaga o último caractere digitado (`⌫`) |
| `Escape` (Esc) | Limpa todo o visor e o histórico (`AC`) |

> **💡 Dica de Uso:** Ao clicar em funções como `sin`, `cos`, `tan`, `log` ou `√`, a calculadora adiciona automaticamente a abertura do parêntese — por exemplo, `Math.sqrt(`. Lembre-se de fechar o parêntese `)` utilizando o seu teclado após digitar o número desejado, ou deixe como último elemento simples antes de calcular!

---

## 🎨 Personalização de Cores

O projeto utiliza variáveis CSS logo no início da tag `<style>`. Se desejar alterar o tema da calculadora, basta modificar os valores no bloco `:root`:

```css
:root {
    --primary-color: #5e35b1;   /* Cor padrão dos botões numéricos */
    --secondary-color: #3949ab; /* Cor dos botões ao passar o mouse (hover) */
    --accent-color: #7c4dff;    /* Cor dos operadores e botão de igual */
    --text-color: #ffffff;      /* Cor dos textos e números */
    --error-color: #ff5252;     /* Cor do botão de limpar (AC) */
    --dark-bg: #121212;         /* Cor de fundo da página */
    --light-bg: #1e1e1e;        /* Cor de fundo do corpo da calculadora */
}
```

---

## 📌 Possíveis Melhorias Futuras

Caso queira expandir este projeto no futuro, aqui estão algumas ideias:
- Adicionar botões visuais na interface para abrir `(` e fechar `)` parênteses, facilitando o uso de funções científicas em dispositivos móveis.
- Implementar alternância entre Radianos e Graus para as funções trigonométricas.
- Criar uma aba lateral para armazenar uma lista com todo o histórico de cálculos da sessão.

---

## 📄 Licença

Este projeto é de código aberto e pode ser utilizado livremente para fins de estudo, portfólio ou projetos pessoais.
