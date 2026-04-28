# portfolio

Portifólio pessoal desenvolvido com HTML e CSS puro — sem frameworks, sem dependências. Design dark minimalista com tipografia serifada, cursor customizado e animações baseadas em scroll.

---

## Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-0a0a0a?style=flat-square&logo=html5&logoColor=c9b99a)
![CSS3](https://img.shields.io/badge/CSS3-0a0a0a?style=flat-square&logo=css3&logoColor=c9b99a)
![JavaScript](https://img.shields.io/badge/JavaScript-0a0a0a?style=flat-square&logo=javascript&logoColor=c9b99a)

- **HTML5** — estrutura semântica
- **CSS3** — variáveis, animações, grid e media queries (sem bibliotecas externas)
- **Vanilla JS** — cursor customizado, scroll reveal e animação das skill bars
- **Google Fonts** — Fraunces + DM Mono

### Projetos

Cada projeto é um bloco `<a class="project-card">`. Para editar, ajuste:

```html
<div class="project-number">01</div>
<div class="project-title">Nome do Projeto</div>
<p class="project-desc">Descrição curta do projeto.</p>
<div class="project-tags">
  <span class="tag">React</span>
  <span class="tag">CSS</span>
</div>
```

E adicione o link real no atributo `href` do `<a>`.

### Skills

As barras de progresso usam a variável CSS `--w`. Altere o percentual conforme seu nível:

```html
<div class="skill-bar" style="--w:85%"></div>
```

### Paleta de cores

Todas as cores estão centralizadas em variáveis CSS no topo do `<style>`:

```css
:root {
  --bg: #0a0a0a;        /* fundo */
  --accent: #c9b99a;    /* dourado — cor de destaque */
  --text: #e8e4dc;      /* texto principal */
  --muted: #5a5650;     /* texto secundário */
}


## Estrutura do projeto

```
portfolio/
└── index.html   # tudo em um único arquivo
```

---

## Licença

MIT — sinta-se livre para usar, adaptar e distribuir.
