# projeto-github

Projeto desenvolvido durante o Workshop de GitHub na COTI Informática.

Este repositório contém um pequeno projeto front-end (HTML/CSS/JavaScript) usado como material didático no workshop.

## Tecnologias usadas
- HTML (estrutura da página)
- CSS (estilos)
- JavaScript (comportamento/interatividade)

> Observação: no momento o repositório contém apenas o arquivo `index.html`, mas a estrutura suporta adicionar arquivos `.css` e `.js` conforme o exercício do workshop.

## Estrutura do repositório (top-level)
- .gitignore — padrões de arquivos ignorados pelo Git
- README.md — este arquivo
- index.html — página de exemplo do workshop

## Como abrir e rodar o projeto no VS Code
Siga estes passos mínimos para abrir e visualizar o projeto localmente usando o Visual Studio Code (VS Code):

1. Clone o repositório e abra-o no VS Code

```bash
# clonar o repositório
git clone https://github.com/AugustoRepository/projeto-github.git
cd projeto-github
# abrir no VS Code
code .
```

2. Abrir o arquivo de entrada
- No VS Code, abra `index.html` na barra lateral ou via Command Palette (Ctrl/Cmd+P -> digite `index.html`).

3. Visualizar no navegador — opções:

Opção A — (recomendado) usar a extensão Live Server no VS Code
- Instale a extensão "Live Server" (procure por "Live Server" no painel Extensões).
- Abra `index.html`, clique com o botão direito e escolha "Open with Live Server".
- A página será aberta em `http://127.0.0.1:5500/` (ou outra porta disponível) e atualizada automaticamente ao salvar arquivos.

Opção B — abrir diretamente no navegador
- Dê um duplo clique em `index.html` no seu gerenciador de arquivos para abri-lo no navegador. Funciona para páginas estáticas simples, porém alguns recursos (requisições AJAX/Fetch) podem exigir um servidor local.

Opção C — usar um servidor HTTP simples (via Python ou Node)

```bash
# com Python 3 (executar na pasta do projeto):
python -m http.server 8000
# então abra http://localhost:8000 no navegador

# com Node (http-server):
npx http-server -p 8000
# então abra http://localhost:8000
```

## Como contribuir
- Faça um fork e crie uma branch com sua feature/ajuste
- Abra um Pull Request descrevendo a alteração

## Dúvidas / Contato
Se precisar que eu inclua instruções específicas (por exemplo: configurar um preprocessor CSS, usar um bundler simples, ou adicionar exemplos de CSS/JS), posso atualizar este README com passos detalhados.
