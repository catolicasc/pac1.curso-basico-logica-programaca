# Documentação Técnica e Didática – Estilos CSS do Projeto RoadMapC

Este documento explica os estilos definidos no arquivo `style.css`, detalhando a função de cada seletor e seu papel na construção visual do site.

---
## Seletor `:root`
- **--primary-color**: define `#667eea`.
- **--secondary-color**: define `#764ba2`.
- **--sucess-color**: define `#43fc4c`.
- **--sucess-border-color**: define `#00bb09`.
- **--accent-color**: define `#f8f9fa`.
- **--text-color**: define `#333`.
- **--background-color**: define `#f4f5f7`.
- **--header-text-color**: define `#ffffff`.
- **--section-title-color**: define `var(--primary-color)`.
- **--subsection-title-color**: define `#495057`.
- **--code-bg**: define `#2d3748`.
- **--code-header-bg**: define `#4a5568`.
- **--code-text-color**: define `#e2e8f0`.
- **--card-bg**: define `#ffffff`.
- **--card-border-top**: define `var(--primary-color)`.
- **--card-shadow**: define `rgba(0, 0, 0, 0.1)`.
- **--sidebar-bg**: define `var(--accent-color)`.
- **--sidebar-shadow**: define `rgba(0, 0, 0, 0.07)`.
- **--sidebar-link-bg-hover**: define `#e9ecef`.
- **--sidebar-link-text**: define `var(--primary-color)`.
- **--sidebar-link-hover-text**: define `#495057`.
- **--nav-tab-bg**: define `var(--accent-color)`.
- **--nav-tab-text**: define `var(--primary-color)`.
- **--nav-tab-border**: define `var(--primary-color)`.
- **--nav-tab-hover-bg**: define `#e9ecef`.
- **--nav-tab-hover-text**: define `#495057`.

## Seletor `*`
- **margin**: define `0`.
- **padding**: define `0`.
- **box-sizing**: define `border-box`.

## Seletor `html`
- **scroll-behavior**: define `smooth`.

## Seletor `body`
- **font-family**: define `"Segoe UI", Tahoma, Geneva, Verdana, sans-serif`.
- **line-height**: define `1.6`.
- **color**: define `var(--text-color)`.
- **background**: define `linear-gradient(`.
- **display**: define `flex`.
- **align-items**: define `center`.
- **flex-flow**: define `column wrap`.

## Seletor `article`
- **display**: define `flex`.
- **flex-direction**: define `column`.
- **flex**: define `1`.
- **gap**: define `30px`.
- **margin**: define `0 20px`.

## Seletor `header`
- **text-align**: define `center`.
- **color**: define `var(--header-text-color)`.
- **margin-bottom**: define `40px`.
- **padding**: define `40px 20px`.
- **max-width**: define `60em`.

## Seletor `header h1`
- **font-size**: define `3rem`.
- **margin-bottom**: define `10px`.
- **text-shadow**: define `2px 2px 4px rgba(0, 0, 0, 0.3)`.

## Seletor `header p`
- **font-size**: define `1.2rem`.
- **opacity**: define `0.9`.

## Seletor `.content`
- **display**: define `flex`.
- **background**: define `var(--card-bg)`.
- **border-radius**: define `15px`.
- **box-shadow**: define `0 20px 40px var(--card-shadow)`.
- **overflow**: define `hidden`.
- **margin**: define `0 5px 30px 5px`.
- **width**: define `99%`.
- **max-width**: define `80em`.

## Seletor `.roadmap`
- **display**: define `flex`.
- **flex-direction**: define `column`.
- **align-items**: define `center`.
- **gap**: define `1rem`.
- **position**: define `relative`.

## Seletor `.btn-start`
- **background**: define `var(--primary-color)`.
- **color**: define `#fff`.
- **padding**: define `0.7rem 1.1rem`.
- **border-radius**: define `8px`.
- **cursor**: define `pointer`.
- **font-weight**: define `700`.
- **box-shadow**: define `0 6px 18px rgba(59, 130, 246, 0.12)`.
- **z-index**: define `3`.

## Seletor `.roadmap-container`
- **max-width**: define `90%`.
- **padding**: define `1.2rem 0`.
- **display**: define `flex`.
- **flex-direction**: define `column`.
- **align-items**: define `center`.
- **gap**: define `1.6rem`.
- **position**: define `relative`.

## Seletor `.roadmap-line`
- **position**: define `absolute`.
- **left**: define `50%`.
- **transform**: define `translateX(-50%)`.
- **top**: define `55px`.
- **width**: define `6px`.
- **height**: define `0`.
- **/* começa com 0; será aumentado por**: define `checked */`.
- **background**: define `var(--primary-color)`.
- **border-radius**: define `4px`.
- **transition**: define `height 0.5s cubic-bezier(0.2, 0.9, 0.3, 1)`.
- **z-index**: define `0`.
- **box-shadow**: define `0 6px 18px rgba(59, 130, 246, 0.08)`.

## Seletor `.desc`
- **display**: define `flex`.
- **align-items**: define `center`.
- **justify-content**: define `center`.
- **text-align**: define `center`.

## Seletor `.desc-fim`
- **display**: define `none`.
- **flex-direction**: define `column`.
- **align-items**: define `center`.
- **gap**: define `1rem`.

## Seletor `.roadmap-item`
- **display**: define `none`.
- **padding**: define `0.6rem 1rem`.
- **border**: define `2px solid var(--primary-color)`.
- **border-radius**: define `10px`.
- **background**: define `#fff`.
- **color**: define `var(--primary-color)`.
- **font-weight**: define `600`.
- **cursor**: define `pointer`.
- **z-index**: define `2`.
- **transition**: define `all 0.2s ease`.
- **width**: define `220px`.
- **text-align**: define `center`.

## Seletor `.roadmap-fim`
- **display**: define `none`.
- **padding**: define `0.6rem 1rem`.
- **border**: define `2px solid var(--primary-color)`.
- **border-radius**: define `10px`.
- **background**: define `#fff`.
- **color**: define `var(--primary-color)`.
- **font-weight**: define `600`.
- **cursor**: define `pointer`.
- **z-index**: define `2`.
- **transition**: define `all 0.2s ease`.
- **width**: define `220px`.
- **text-align**: define `center`.

## Seletor `.roadmap-item:hover`
- **background**: define `var(--primary-color)`.
- **color**: define `#fff`.
- **transform**: define `translateY(-3px)`.

## Seletor `.roadmap-fim:hover`
- **transform**: define `translateY(-3px)`.
- **background**: define `var(--sucess-color)`.
- **border**: define `2px solid var(--sucess-color)`.
- **color**: define `#fff`.

## Seletor `#fim:checked ~ .roadmap-fim`
- **background**: define `var(--sucess-color) !important`.
- **border**: define `2px solid var(--sucess-color) !important`.
- **color**: define `#fff`.

## Seletor `input[type="checkbox"]`
- **position**: define `absolute`.
- **left**: define `-9999px`.

## Seletor `#step5:checked ~ .roadmap-fim`
- **display**: define `inline-block`.
- **animation**: define `fadeIn 0.35s ease`.

## Seletor `#start:not(:checked) ~ .desc-start`
- **display**: define `flex !important`.

## Seletor `#start:checked ~ .desc-1`
- **display**: define `flex !important`.

## Seletor `#step1:checked ~ .desc-1`
- **display**: define `none !important`.

## Seletor `#step1:checked ~ .desc-2`
- **display**: define `flex !important`.

## Seletor `#step2:checked ~ .desc-2`
- **display**: define `none !important`.

## Seletor `#step2:checked ~ .desc-3`
- **display**: define `flex !important`.

## Seletor `#step3:checked ~ .desc-3`
- **display**: define `none !important`.

## Seletor `#step3:checked ~ .desc-4`
- **display**: define `flex !important`.

## Seletor `#step4:checked ~ .desc-4`
- **display**: define `none !important`.

## Seletor `#step4:checked ~ .desc-5`
- **display**: define `flex !important`.

## Seletor `#step5:checked ~ .desc-5`
- **display**: define `none !important`.

## Seletor `#step5:checked ~ .desc-6`
- **display**: define `flex !important`.

## Seletor `#fim:checked ~ .desc-6`
- **display**: define `none !important`.

## Seletor `#fim:checked ~ .desc-fim`
- **display**: define `flex !important`.

## Seletor `#fim:checked + .roadmap-fim`
- **background**: define `var(--primary-color)`.
- **color**: define `#fff`.
- **border-color**: define `var(--primary-color)`.
- **box-shadow**: define `0 6px 18px rgba(59, 130, 246, 0.08)`.

## Seletor `#start:checked ~ .line-1`
- **height**: define `54px`.

## Seletor `#step1:checked ~ .line-2`
- **height**: define `120px`.

## Seletor `#step2:checked ~ .line-3`
- **height**: define `186px`.

## Seletor `#step3:checked ~ .line-4`
- **height**: define `262px`.

## Seletor `#step4:checked ~ .line-5`
- **height**: define `338px`.

## Seletor `#step5:checked ~ .line-6`
- **height**: define `422px`.

## Seletor `@keyframes fadeIn`
## Seletor `from`
- **opacity**: define `0`.
- **transform**: define `translateY(6px)`.

## Seletor `to`
- **opacity**: define `1`.
- **transform**: define `translateY(0)`.


## Seletor `.section-title`
- **color**: define `var(--section-title-color)`.
- **font-size**: define `2rem`.
- **margin-bottom**: define `20px`.
- **border-bottom**: define `3px solid var(--section-title-color)`.
- **padding-bottom**: define `10px`.

## Seletor `.subsection-title`
- **color**: define `var(--subsection-title-color)`.
- **font-size**: define `1.5rem`.
- **margin**: define `30px 0 15px 0`.

## Seletor `.code-container`
- **background**: define `var(--code-bg)`.
- **border-radius**: define `10px`.
- **padding**: define `20px`.
- **margin**: define `20px 0`.
- **overflow-x**: define `auto`.

## Seletor `.code-header`
- **background**: define `var(--code-header-bg)`.
- **color**: define `var(--header-text-color)`.
- **padding**: define `10px 20px`.
- **margin**: define `-20px -20px 20px -20px`.
- **font-weight**: define `bold`.
- **border-radius**: define `10px 10px 0 0`.

## Seletor `.code`
- **color**: define `var(--code-text-color)`.
- **font-family**: define `"Courier New", monospace`.
- **font-size**: define `14px`.
- **line-height**: define `1.5`.
- **white-space**: define `pre-wrap`.

## Seletor `.benefits-grid`
- **display**: define `grid`.
- **grid-template-columns**: define `repeat(auto-fit, minmax(300px, 1fr))`.
- **gap**: define `20px`.
- **margin**: define `30px 0`.

## Seletor `.benefit-card`
- **background**: define `var(--card-bg)`.
- **padding**: define `25px`.
- **border-radius**: define `10px`.
- **box-shadow**: define `0 5px 15px var(--card-shadow)`.
- **border-top**: define `4px solid var(--card-border-top)`.
- **transition**: define `transform 0.3s ease`.

## Seletor `.benefit-card:hover`
- **transform**: define `translateY(-5px)`.

## Seletor `.benefit-title`
- **color**: define `var(--section-title-color)`.
- **font-size**: define `1.2rem`.
- **font-weight**: define `bold`.
- **margin-bottom**: define `10px`.

## Seletor `.analogy-box`
- **background**: define `linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%)`.
- **padding**: define `25px`.
- **border-radius**: define `15px`.
- **margin**: define `25px 0`.
- **border-left**: define `5px solid #ff6b6b`.

## Seletor `.analogy-title`
- **font-size**: define `1.3rem`.
- **font-weight**: define `bold`.
- **color**: define `#d63031`.
- **margin-bottom**: define `15px`.

## Seletor `.sidebar`
- **min-width**: define `240px`.
- **background**: define `var(--sidebar-bg)`.
- **border-radius**: define `15px`.
- **box-shadow**: define `0 4px 12px var(--sidebar-shadow)`.
- **padding**: define `30px 10px`.
- **margin-right**: define `30px`.
- **height**: define `fit-content`.

## Seletor `.sidebar ul`
- **list-style**: define `none`.
- **padding**: define `0`.
- **margin**: define `0`.

## Seletor `.sidebar li`
- **margin-bottom**: define `12px`.

## Seletor `.sidebar .nav-tab`
- **display**: define `block`.
- **padding**: define `12px 18px`.
- **color**: define `var(--sidebar-link-text)`.
- **background**: define `none`.
- **border-radius**: define `8px`.
- **font-weight**: define `500`.
- **text-decoration**: define `none`.
- **transition**: define `background 0.2s, color 0.2s`.

## Seletor `.sidebar .nav-tab:hover`
- **background**: define `var(--sidebar-link-bg-hover)`.
- **color**: define `var(--sidebar-link-hover-text)`.

## Seletor `.active-nav`
- **color**: define `var(--secondary-color) !important`.

## Seletor `.sidebar.accordion details`
- **border**: define `1px solid #e5e7eb`.
- **border-radius**: define `8px`.
- **margin-bottom**: define `8px`.
- **background**: define `#fff`.

## Seletor `.sidebar.accordion summary`
- **display**: define `flex`.
- **align-items**: define `center`.
- **padding**: define `10px 12px`.
- **cursor**: define `pointer`.
- **list-style**: define `none`.
- **font-weight**: define `600`.
- **color**: define `var(--primary-color)`.

## Seletor `.sidebar.accordion summary::-webkit-details-marker`
- **display**: define `none`.

## Seletor `.sidebar.accordion summary::after`
- **content**: define `"▸"`.
- **margin-left**: define `auto`.
- **color**: define `#6b7280`.
- **transition**: define `transform 0.2s ease`.

## Seletor `.sidebar.accordion details[open] summary::after`
- **transform**: define `rotate(90deg)`.

## Seletor `.sidebar.accordion ul`
- **margin**: define `0`.
- **padding**: define `8px 0 10px 0`.

## Seletor `.sidebar.accordion li`
- **list-style**: define `none`.

## Seletor `.sidebar.accordion .nav-tab:focus`
- **background**: define `var(--accent-color)`.
- **outline**: define `none`.

## Seletor `.sidebar .active-nav`
- **background**: define `var(--primary-color)`.
- **color**: define `#fff !important`.

## Seletor `footer`
- **display**: define `flex`.
- **flex-flow**: define `column wrap`.
- **background**: define `var(--background-color)`.
- **color**: define `var(--text-color)`.
- **border-radius**: define `15px 15px 0 0`.
- **width**: define `99%`.
- **max-width**: define `80em`.

## Seletor `footer .footer-inner`
- **padding**: define `16px 20px`.
- **text-align**: define `center`.
- **font-size**: define `0.95rem`.

## Seletor `.footer-buttons`
- **display**: define `flex`.
- **justify-content**: define `center`.
- **align-items**: define `center`.
- **gap**: define `12px`.
- **flex-direction**: define `row wrap`.

## Seletor `.footer-links`
- **margin-bottom**: define `12px`.
- **display**: define `flex`.
- **justify-content**: define `center`.
- **gap**: define `12px`.

## Seletor `footer .footer-links a`
- **color**: define `var(--primary-color)`.
- **text-decoration**: define `underline`.

## Seletor `footer .footer-links a:focus`
- **color**: define `#111827`.
- **outline**: define `none`.

## Seletor `.buttons-footer`
- **display**: define `inline-block`.
- **padding**: define `8px 16px`.
- **background**: define `var(--primary-color)`.
- **color**: define `#fff`.
- **text-decoration**: define `none`.
- **border-radius**: define `8px`.
- **transition**: define `background 0.2s`.

## Seletor `.buttons-footer:hover`
- **background**: define `var(--secondary-color)`.

## Seletor `.buttons-footer:active`
- **background**: define `var(--primary-color)`.

## Seletor `@media (max-width: 768px)`
## Seletor `header h1`
- **font-size**: define `2rem`.

## Seletor `.tab-content`
- **padding**: define `20px`.

## Seletor `.code`
- **white-space**: define `pre-line`.


## Seletor `@media (max-width: 900px)`
## Seletor `.content`
- **flex-direction**: define `column`.

## Seletor `.sidebar`
- **margin-right**: define `0`.
- **margin-bottom**: define `20px`.
- **width**: define `100%`.



---

# 🧭 Passo a Passo para Organização do CSS

1. **Centralize todos os estilos em um único arquivo `style.css`** para manter consistência entre páginas.
2. **Agrupe seletores por função** (estrutura, navegação, tipografia, cores).
3. **Use classes** (`.classe`) para estilos reaproveitáveis e **IDs** (`#id`) apenas quando o elemento for único.
4. **Priorize legibilidade**: mantenha o código indentado e bem comentado.
5. **Teste o CSS** em diferentes tamanhos de tela para garantir responsividade.
6. **Evite duplicidade**: crie estilos genéricos aplicáveis em todas as páginas.

---
