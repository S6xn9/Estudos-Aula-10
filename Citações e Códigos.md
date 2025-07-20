
# Anotações de Estudo: Citações e Códigos em HTML

## 1. Introdução: Semântica para Referências e Exibição de Código

Esta aula foca em tags HTML essenciais para dois tipos específicos de conteúdo: **citações de outras fontes** e **blocos de código de programação**.  
Usar as tags corretas garante que esse conteúdo seja interpretado corretamente por navegadores, leitores de tela e motores de busca.

---

## 2. Tags para Citações

### `<blockquote>` - Citação em Bloco
- **Uso:** Para blocos de citação longos.
- **Dica:** Pode usar `cite` com a URL da fonte.
```html
<p>No livro "1984", George Orwell escreveu:</p>
<blockquote cite="https://www.exemplo.com/1984">
    <p>O Grande Irmão está te observando.</p>
    <p>Guerra é Paz. Liberdade é Escravidão. Ignorância é Força.</p>
</blockquote>
```

### `<q>` - Citação Curta Inline
- **Uso:** Trechos curtos de citação dentro de um parágrafo.
```html
<p>Sócrates disse: <q cite="https://www.exemplo.com/socrates">Só sei que nada sei</q>.</p>
```

### `<cite>` - Título da Fonte
- **Uso:** Para citar títulos de obras.
```html
<p>Como dito em <cite>O Pequeno Príncipe</cite>, "Tu te tornas eternamente responsável por aquilo que cativas".</p>
```

---

## 3. Tags para Códigos de Programação

### `<code>` - Código Inline
- **Uso:** Pequenos trechos de código no meio do texto.
```html
<p>Use a função <code>console.log()</code> para imprimir no console.</p>
```

### `<pre><code>` - Bloco de Código
- **Uso:** Preserva a indentação e estrutura de blocos inteiros.
```html
<pre><code>
function greet(name) {
    if (name) {
        console.log("Hello, " + name + "!");
    } else {
        console.log("Hello, stranger!");
    }
}
</code></pre>
```

### `<samp>` - Saída de Exemplo
```html
<p>Ao executar o comando, você verá: <samp>Hello World!</samp></p>
```

### `<kbd>` - Entrada do Usuário
```html
<p>Pressione <kbd>Ctrl</kbd> + <kbd>C</kbd> para copiar.</p>
```

### `<var>` - Variável
```html
<p>A equação é E = m<var>c</var><sup>2</sup></p>
```

---

## 4. Importância do Uso Semântico

- **Clareza e Contexto:** Define melhor o propósito do conteúdo.
- **Acessibilidade:** Melhora a leitura por leitores de tela.
- **SEO:** Estrutura mais organizada para os buscadores.
- **Manutenibilidade:** Código limpo e mais fácil de entender.

---

## Conclusão

As tags de citação e código vão além da aparência. Elas atribuem **significado** ao conteúdo, permitindo que humanos e máquinas compreendam melhor o que está sendo exibido.
