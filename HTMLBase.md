
# 🧠 Introdução ao HTML – Conceitos Fundamentais

O **HTML (HyperText Markup Language)** é a linguagem base da web, usada para estruturar o conteúdo exibido em navegadores.  
Cada página é composta por **elementos (tags)** que definem a função e o tipo de cada parte do documento.

---

## 🎯 Estrutura Básica de um Documento HTML

Um arquivo HTML segue a seguinte estrutura:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Título da Página</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>...</header>
    <main>...</main>
    <footer>...</footer>
</body>
</html>
```

### 🔹 Partes principais:

| Parte | Tag | Descrição |
|--------|-----|------------|
| Declaração de tipo | `<!DOCTYPE html>` | Indica que o documento segue o padrão HTML5. |
| Raiz do documento | `<html>` | Contém todo o conteúdo da página. |
| Cabeçalho | `<head>` | Inclui informações sobre o documento (metadados, título, links para CSS e scripts). |
| Corpo | `<body>` | Contém o conteúdo visível da página (textos, imagens, menus, etc.). |

---

## 🧩 Principais Tags e Seus Usos

| Tag | Função | Exemplo |
|-----|---------|----------|
| `<header>` | Cabeçalho do site (logo, título, menu). | `header {}` |
| `<nav>` | Área de navegação com links. | `<nav><a href="index.html">Início</a></nav>` |
| `<main>` | Conteúdo principal da página. | `<main><h1>Conteúdo</h1></main>` |
| `<section>` | Agrupa seções temáticas. | `<section><h2>Tópico</h2></section>` |
| `<article>` | Conteúdo independente (notícia, post). | `<article><p>Texto</p></article>` |
| `<footer>` | Rodapé com créditos e links finais. | `<footer>© 2025</footer>` |
| `<a>` | Cria links. | `<a href="pagina.html">Ir</a>` |
| `<img>` | Exibe imagens. | `<img src="logo.png" alt="Logo">` |
| `<link>` | Conecta arquivos externos (CSS, favicon). | `<link rel="stylesheet" href="style.css">` |
| `<script>` | Importa scripts JavaScript. | `<script src="app.js"></script>` |

---

## 💡 Exemplo Prático de Página Completa

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Exemplo Completo</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Meu Site</h1>
        <nav>
            <a href="index.html">Início</a>
            <a href="sobre.html">Sobre</a>
        </nav>
    </header>

    <main>
        <section>
            <h2>Bem-vindo!</h2>
            <p>Este é um exemplo simples de estrutura HTML.</p>
        </section>
    </main>

    <footer>
        <p>© 2025 - Meu Site</p>
    </footer>
</body>
</html>
```

---

## 🧱 Boas Práticas

1. **Indentação**: mantenha o código organizado e legível.  
2. **Semântica**: use tags que descrevem o propósito do conteúdo.  
3. **Separação de responsabilidades**: HTML para estrutura, CSS para estilo, JS para comportamento.  
4. **Evite redundância**: reutilize componentes e padrões entre páginas.  
5. **Acessibilidade**: use `alt` em imagens e estrutura hierárquica com títulos (`h1`, `h2`, etc.).

---

# Documentação Técnica e Didática – Estrutura HTML do Projeto RoadMapC

Este documento explica a estrutura e a construção das páginas HTML do projeto **RoadMapC**. Ele combina explicações técnicas e didáticas sobre a montagem de um site modular com múltiplas páginas interligadas e uso compartilhado de CSS.

---
## index.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `./css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 26 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## arrays.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 21 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## conceitos.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 11 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## devc.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 18 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## estruturas.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 19 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## funcoes.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 24 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## operadores.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 24 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## ponteiros.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 22 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## primeiro.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 16 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## projetos.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 21 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## stringsc.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 21 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## structs.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 19 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---
## variaveis.html

- Estrutura básica iniciada com a tag `<html>` contendo `<head>` e `<body>`.
### Cabeçalho (`<head>`)
- Contém 2 metadados, 1 links de estilo e 0 scripts importados.
  - Importa o CSS `../css/style.css` para estilização global.
### Corpo (`<body>`)
- Contém 19 blocos estruturais principais.
  - `<header>` define o cabeçalho da página (logo, título, menu, etc.).
  - `<nav>` organiza os links de navegação entre páginas.
  - `<main>` concentra o conteúdo principal de cada página.
  - `<footer>` contém informações de rodapé, como créditos ou links adicionais.

---

# 🧭 Passo a Passo para Construção de um Site no Formato RoadMapC

1. **Crie a estrutura de diretórios:**
   ```bash
   projeto/
   ├── index.html
   ├── css/
   │   └── style.css
   └── pages/
       ├── pagina1.html
       ├── pagina2.html
       └── ...
   ```

2. **Defina um HTML base (`index.html`)** com as seções principais:
   - `<header>` para o título ou logotipo.
   - `<nav>` para os links de navegação entre páginas.
   - `<main>` para o conteúdo principal.
   - `<footer>` para o rodapé.

3. **Use um único arquivo CSS** (`css/style.css`) para garantir consistência visual em todas as páginas.

4. **Interligue as páginas** com `<a href="pages/...">` dentro do `<nav>`.

5. **Evite duplicar código HTML:** mantenha a mesma estrutura em todas as páginas, alterando apenas o conteúdo de `<main>`.

6. **Valide o HTML** e **otimize o CSS** para responsividade e desempenho.

---
