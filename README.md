# Portfólio Acadêmico com Jekyll

![GitHub Pages](https://github.com/vguardiano/personal-jekyll-site/actions/workflows/pages/pages-build-deployment/badge.svg)
[![Licença: MIT](https://img.shields.io/badge/Licença-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Um template de site estático, minimalista e rápido, construído com Jekyll. Ideal para estudantes, pesquisadores e acadêmicos que desejam um portfólio online profissional, de fácil manutenção e hospedado gratuitamente no GitHub Pages.

### ➡️ [Veja uma demonstração ao vivo](https://vguardiano.github.io/personal-jekyll-site/)

![Demonstração do Portfólio](https://i.imgur.com/link-para-uma-imagem-do-seu-site.png)
*(Dica: Tire um screenshot do seu site pronto e substitua o link acima para ter uma pré-visualização aqui!)*

---

## ✨ Sobre o Projeto

Este projeto foi criado para ser uma alternativa simples e sem complicações às plataformas de construção de sites. Em vez de depender de frameworks complexos, ele usa a potência do **Jekyll** para transformar arquivos de texto simples (como YAML e Markdown) em um site estático completo. Todo o conteúdo é gerenciado de forma centralizada, tornando as atualizações rápidas e fáceis.

### Principais Funcionalidades

-   **Gerenciado por Dados:** Todo o conteúdo, desde o seu nome até as publicações, é configurado em arquivos `.yml` fáceis de editar.
-   **Templates com Jekyll:** Uso de layouts e includes para evitar repetição de código (`DRY`).
-   **Design Minimalista e Responsivo:** Layout limpo que se adapta a desktops, tablets e celulares.
-   **Tema Claro/Escuro:** Seletor de tema com ícone e atalho de teclado (`C`), que salva a preferência do usuário.
-   **Página "Sobre Mim" Completa:** Uma página dedicada com foto, biografia e uma timeline de sua jornada acadêmica.
-   **Otimizado para GitHub Pages:** Deploy automático a cada `git push`.

## 🚀 Como Usar

Siga estes passos para configurar sua própria versão do portfólio.

### 1. Pré-requisitos

Para rodar o site localmente, você precisará ter o **Ruby** e o **Jekyll** instalados. Siga o [guia oficial de instalação do Jekyll](https://jekyllrb.com/docs/installation/) para o seu sistema operacional.

### 2. Crie seu Repositório a partir deste Template

Clique no botão verde **"Use this template"** no topo desta página e selecione **"Create a new repository"**. Isso criará uma cópia idêntica do projeto na sua conta do GitHub.

### 3. Clone seu Repositório

No seu computador, execute o comando abaixo para baixar os arquivos, substituindo `SEU-USUARIO` e `NOME-DO-REPO`:

```bash
git clone [https://github.com/SEU-USUARIO/NOME-DO-REPO.git](https://github.com/SEU-USUARIO/NOME-DO-REPO.git)
cd NOME-DO-REPO
```

### 4. Personalize o Conteúdo

Esta é a parte principal. Todas as customizações são feitas em dois arquivos:

#### A. Configurações Globais (`_config.yml`)

Abra o arquivo `_config.yml` e altere as informações do site, como seu nome, descrição e o caminho para o seu favicon.

**Importante:** Se o seu repositório **NÃO** se chama `SEU-USUARIO.github.io`, você **PRECISA** configurar o `baseurl`:

```yaml
# Exemplo para o repositório 'personal-jekyll-site'
baseurl: "/personal-jekyll-site" 
```

#### B. Seções da Página (`_data/secoes.yml`)

Abra `_data/secoes.yml` para editar o conteúdo principal:
-   Adicione suas **Notas de Estudo**, **Publicações**, **Projetos**, etc.
-   Para ocultar uma seção, mude a flag `ocultar: true`.
-   A ordem das seções no arquivo define a ordem no site.

#### C. Página Sobre Mim (`sobre.md`)

Edite o arquivo `sobre.md` para alterar sua foto e o texto da sua biografia. Não se esqueça de colocar sua foto na pasta `assets/img/`.

### 5. Rode o Site Localmente

Para pré-visualizar suas alterações em tempo real, execute o servidor do Jekyll:

```bash
bundle exec jekyll serve --livereload
```

Abra seu navegador e acesse `http://localhost:4000`.

### 6. Faça o Deploy

Quando estiver satisfeito com as mudanças, envie-as para o GitHub.

```bash
git add .
git commit -m "Personaliza conteúdo do portfólio"
git push origin main
```

Aguarde alguns minutos e seu site estará no ar!

---

## 📜 Licença

Este projeto é distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.