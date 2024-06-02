![brazil](https://github.com/pedromxavier/flag-badges/raw/main/badges/BR.svg)

**O que este código faz:**

Este código LaTeX calcula a função composta $gof(x)$, onde:

*$f(x) = 3x - 1$
*$g(x) = x^2 + x - 1$

**Explicação:**

O código determina $gof(x)$ seguindo estas etapas:

1. **Defina as funções:** O código começa definindo as funções `f(x)` e `g(x)` usando a sintaxe LaTeX.
2. **Calcule $gof(x)$:** Em seguida, aplica a definição de funções compostas. $gof(x)$ é encontrado avaliando `g` em `f(x)`. Neste caso, `g(f(x)) = g(3x - 1)`.
3. **Expanda a expressão:** O código expande a expressão resultante usando a propriedade distributiva e simplifica os termos.
4. **Combinar termos semelhantes:** Finalmente, o código combina termos semelhantes para obter o resultado final: `gof(x) = 9x^2 - 3x - 1`.

**Compilando o código:**

Para compilar este código LaTeX e gerar um documento PDF, você precisará de um compilador LaTeX como pdfLaTeX, XeLaTeX ou LuaLaTeX. Aqui estão as etapas gerais:

1. Salve o código como um arquivo `.tex` (por exemplo, `main.tex`).
2. Abra um terminal ou prompt de comando.
3. Navegue até o diretório onde você salvou o arquivo.
4. Execute o comando LaTeX apropriado com base no seu compilador:
 - `pdflatex main.tex` (para pdfLaTeX)
 - `xelatex main.tex` (para XeLaTeX)
 - `lualatex main.tex` (para LuaLaTeX)
5. Isso criará um arquivo PDF (por exemplo, `função_composta.pdf`) contendo a saída formatada.

**Notas Adicionais:**

* Sinta-se à vontade para modificar o código para explorar outras funções ou cálculos.
* Para recursos mais avançados do LaTeX, consulte a documentação ou tutoriais do LaTeX.

**Imagem:**

![imagem](https://github.com/DeiseFreire/S-221801062024/blob/main/img.png)
