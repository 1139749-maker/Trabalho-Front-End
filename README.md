# Trabalho G1 - Front-End
Nome: Luisa Lima Migliorini 
Matrícula: 1139749 

Referência visual da página:
[Places, de Peter McKinnon](https://www.petermckinnon.com/places).

# Proposta

Reproduzir a organização editorial da referência: marca no cabeçalho, título de página, galeria fotográfica em grade e formulário de newsletter no rodapé. A implementação foi construída do zero a partir da observação visual da página, sem copiar seu código-fonte. 

**Análise Estrutural da Referência:**
- **Cabeçalho (`header` / `nav`):** Identificou-se uma navegação minimalista no topo centrada na marca do autor.
- **Conteúdo Principal (`main` / `section`):** Título de página em destaque editorial seguido por uma galeria de fotos disposta em grade.
- **Galeria (`figure` / `figcaption`):** Imagens de alto impacto visual e foco em composição limpa.
- **Rodapé (`footer` / `form`):** Formulário de captura de e-mail (newsletter) e links sociais ao final da página.

## Checklist da Parte 1

- [x] **1.1 HTML semântico e acessível:** uso de `header`, `nav`, `main`, `section`, `figure`, `figcaption` e `footer`. Todas as imagens possuem `alt` descritivo. O formulário possui `label`, `input` com `type="email"`, `required` e mensagem de status acessível.
- [x] **1.2 Fidelidade visual:** foram mantidos o fundo claro, a tipografia editorial, a navegação minimalista, o título `Places`, a galeria e o rodapé com inscrição. A fonte original foi substituída por Playfair Display e DM Mono, pois são gratuitas e próximas da linguagem visual.
- [x] **1.3 CSS:** o arquivo utiliza variáveis em `:root`, seletores de classe, seletores descendentes, pseudo-classes como `:hover` e `:focus`, além de box model com `box-sizing`, espaçamentos e bordas para deixar mais personalizado.
- [x] **1.4 Responsividade:** o CSS começa pelo layout mobile, usa Grid e Flexbox e possui media queries com `min-width` para reorganizar a galeria e o cabeçalho em telas maiores.
- [x] **1.5 Personalização:** as fotografias são próprias com licença autoral e tem abaixo, no final, minhas redes sociais, Instagram e LinkedIn. O nome do autor Peter McKinnon modifiquei para Luisa Migliorini.

## Estrutura dos arquivos

- `index.html`: estrutura semântica, conteúdo da galeria, formulário e JavaScript básico.
- `style.css`: variáveis, tipografia, layout mobile-first, Grid, Flexbox e responsividade.
- `README.md`: identificação, referência e justificativas dos requisitos.

# Git - Hitórico de Commits

Dia 1 — 23/09/2026: estrutura e galeria

1. `estrutura semantica inicial da pagina`
	- Criar `index.html` com `header`, `nav`, `main`, `section`, `figure`, `form` e `footer`.

2. `estrutura inicial da galeria de fotos`
	- Adicionar a grade, as imagens e os textos alternativos (`alt`).

3. `imagens locais na pasta da galeria`
	- Organizar as fotos na pasta `imagem.png` e usar caminhos relativos no HTML.

Dia 2 — 25/09/2026: CSS, formulário e responsividade

4. `estilos base tipografia e variaveis css`
	- Criar variáveis de cor, tipografia, espaçamento e borda no `:root`.

5. `layout da galeria com css grid`
	- Organizar quatro fotos por linha, com bordas arredondadas e espaçamento leve.

6. `formulario de newsletter acessivel`
	- Adicionar `label`, `type="email"`, `required` e mensagem de confirmação via JavaScript.
	- Estrutura HTML com atributos ARIA, script JS de feedback e estilização CSS do formulário e footer.

Dia 3 — 26/09/2026: personalização e entrega

7. `responsividade e personalizacao da pagina`
	- Responsividade para telas maiores: Ajustar mobile e desktop com media queries. Além de aproveitar a tela: aumentando os espaçamentos internos (paddings).
	- Personalizar a marca para `LUISA MIGLIORINI` invés de Peter Mckinnon. As fotos são autorais, fotos da natureza, flores, paisagens e animais, com o intuito de ser minimalista, seguindo o modelo do site do autor.

8. `links sociais, personalização do rodapé, revisao e documentacao final`
	- Adicionar Instagram e LinkedIn, revisar acessibilidade 
	- Completar o README com prints comparativos.