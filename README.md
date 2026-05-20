# 🇪🇸 Emprego Espanha · Atalhos para todos os portais de trabalho

Aplicação web rápida e organizada que reúne **mais de 60 sites de emprego na Espanha** – desde portais gerais até setores específicos (jurídico, TI, turismo, engenharia, meio ambiente, trabalho remoto, moda, governo, etc.).  

Desenvolvida em HTML/CSS/JS puro, sem dependências externas pesadas, funcionando como um **dashboard de atalhos** com pesquisa dinâmica e categorias visuais.

---

## 🚀 Funcionalidades

- ✅ **Lista completa** com todos os links do ficheiro `lista_sites_emprego_espanha.txt` (InfoJobs, Indeed, LinkedIn, Tecnoempleo, Michael Page, EURES, etc.)
- 🔍 **Filtro instantâneo** por nome, categoria, setor ou palavra-chave (ex: “TI”, “Jurídico”, “remoto”, “agro”)
- 📁 **Organização por categorias** (Portais Gerais, Alta Direção, Engenharia, Meio Ambiente, Trabalho Remoto, etc.)
- 🎨 **Cards interativos** com ícone, nome do site, etiqueta da área e link direto (abre em nova aba)
- 📱 **Design responsivo** – funciona bem no desktop, tablet e mobile
- 📊 **Contador dinâmico** de resultados visíveis / total de atalhos
- ⚡ **Sem recarregamento de página** – busca e renderização em tempo real

---

## 🧰 Como usar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3. Navegue pelas categorias ou digite no campo de busca para filtrar os portais.
4. Clique em qualquer card para ser redirecionado diretamente ao site de emprego (nova aba).
5. Use o botão **“Limpar filtro”** para restaurar a lista completa.

> 💡 Dica: você pode fixar o atalho no seu navegador ou até transformar em um aplicativo desktop via “instalar como app” (PWA leve).

---

## 📁 Estrutura do projeto

/
├── index.html # Aplicação completa (estilos, componentes e lógica)
└── README.md # Este ficheiro de documentação

> O projeto é **standalone** – nenhuma build ou servidor necessário. Todos os dados dos portais estão embutidos no JavaScript.

---

## 📋 Lista de portais incluídos (por categoria)

| Categoria | Exemplos de sites |
|-----------|------------------|
| Portais Gerais | InfoJobs, Indeed, LinkedIn, Jobandtalent, Monster, Jooble |
| Jurídico | Iuris Talent, Iterlegis, ICAB |
| Agrário e Pecuária | Infoagro, Infocarne, El Campo no para |
| Criativo / Audiovisual | Domestika, Platino Empleo |
| Alta Direção | Catenon, Michael Page, Experteer |
| Construção | Archijobs, Construfy |
| Educação | Educajob, Colejobs, Educaspain |
| Farmacêutico e Saúde | Pmfarma, Farmatalent |
| Engenharia | Buscoingenieros, Ingenierojob |
| Portais Governamentais | Empléate, EURES España |
| Marketing e Digital | Dimajobs, Marketing Directo |
| Moda e Luxo | Luxe Talent, Fashion United |
| Meio Ambiente | Ambientum, Comunidad ISM |
| Trabalho Remoto | Remotive, We Work Remotely, Workana |
| Outros Setores | Hosteleo, Trovit, Turijobs |

🔁 **Total**: 60+ atalhos verificados a partir da lista original.

---

## 🛠 Personalização

Caso queira adicionar ou remover sites:

1. Edite o array `sitesData` dentro do `<script>` no `index.html`.
2. Cada objeto segue o formato:
   ```js
   { name: "Nome do Site", url: "https://...", category: "Categoria", note: "descrição opcional" }
Para criar uma nova categoria, adicione-a no array categoryOrder (na ordem desejada).

As alterações são refletidas automaticamente.

🌐 Tecnologias utilizadas
HTML5 semântico

CSS3 com Flexbox, Grid e variáveis

JavaScript puro (ES6+) – DOM manipulation, eventos, filter, template dinâmico

Font Awesome 6 (ícones)

Google Fonts (Inter)

📄 Licença
Este projeto é de código aberto e pode ser usado livremente para fins profissionais ou pessoais. Os links dos sites de emprego pertencem aos respectivos proprietários.

✨ Motivação
Organizar dezenas de bookmarks de portais de trabalho na Espanha de forma visual, pesquisável e rápida – ideal para candidatos, recrutadores ou estudantes que buscam oportunidades no país.

Desenvolvido com ❤️ para quem procura trabalho na Espanha.
Se encontrar algum link quebrado ou quiser sugerir um novo portal, fique à vontade para contribuir.


