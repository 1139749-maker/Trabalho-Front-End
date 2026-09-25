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

# Git

Dia 1 — 23/09/2026: estrutura e galeria

1. `estrutura semantica inicial da pagina`
	- Criar `index.html` com `header`, `nav`, `main`, `section`, `figure`, `form` e `footer`.

2. `estrutura inicial da galeria de fotos`
	- Adicionar a grade, as imagens e os textos alternativos (`alt`).

3. `imagens locais na pasta da galeria`
	- Organizar as fotos na pasta `imagem.png` e usar caminhos relativos no HTML.

### Dia 2 — 25/09/2026: CSS, formulário e responsividade

4. `estilos base tipografia e variaveis css`
	- Criar variáveis de cor, tipografia, espaçamento e borda no `:root`.

5. `layout da galeria com css grid`
	- Organizar quatro fotos por linha, com bordas arredondadas e espaçamento leve.

6. `formulario de newsletter acessivel`
	- Adicionar `label`, `type="email"`, `required` e mensagem de confirmação via JavaScript.