# Codex Handoff — Oficinas de Artes 12.º ano

## Objetivo
Publicar no GitHub Pages o website já preparado para o Projeto 01 de Oficinas de Artes — 12.º ano.

## Conta GitHub
- Username esperado: `ritelian`
- Repositório pretendido: `oficinas-artes`
- Visibilidade: `public`
- Branch principal: `main`
- Publicação: GitHub Pages a partir de `main` / pasta `/ (root)`
- URL esperado, se o repositório ficar nesse nome: `https://ritelian.github.io/oficinas-artes/`

## Ficheiros existentes
- `index.html` — website completo, single-page, responsivo.
- `README.md` — notas básicas de publicação.
- `CODEX_HANDOFF.md` — este documento.

## O que já está implementado no `index.html`
- Hero fullscreen com obra de Monet.
- Grandes secções visuais com Van Gogh, Kandinsky e Mondrian.
- Efeito parallax em scroll.
- Navegação fixa/transparente que muda durante o scroll.
- Microanimações de entrada.
- Layout editorial/galeria de arte.
- Responsividade mobile/tablet/desktop.
- `prefers-reduced-motion` respeitado.
- Conteúdo pedagógico do projeto em português.
- Estrutura do método de design em 6 etapas.
- Galeria de referências artísticas.
- Exemplo de aplicação da linguagem impressionista.
- Estrutura do PowerPoint final e checklist.

## Restrições de conteúdo/design
1. Não remover nem resumir o conteúdo pedagógico existente.
2. Não transformar o site num template corporativo genérico.
3. Preservar o aspeto de exposição/galeria digital.
4. Manter imagens hero grandes e parallax suave.
5. Manter boa legibilidade e contraste.
6. Preservar acessibilidade, incluindo `prefers-reduced-motion`.
7. Não substituir obras por imagens com watermark.
8. Não introduzir frameworks desnecessárias: o projeto deve continuar simples e compatível com GitHub Pages estático.

## Tarefa principal
1. Inspeciona primeiro os ficheiros existentes e o estado de autenticação Git/GitHub.
2. Se tiveres permissões para criar repositórios através do GitHub CLI/API, cria `ritelian/oficinas-artes` como repositório público.
3. Inicializa/configura Git localmente se necessário.
4. Garante que `index.html`, `README.md` e este ficheiro ficam versionados.
5. Adiciona um ficheiro `.nojekyll` vazio na raiz.
6. Faz commit para `main` com uma mensagem clara, por exemplo: `Publish Oficinas de Artes project site`.
7. Faz push para `origin/main`.
8. Ativa GitHub Pages para publicar a branch `main` a partir de `/ (root)` se as permissões/API disponíveis o permitirem.
9. Confirma o estado do deployment e a URL pública.
10. Abre/verifica a página publicada (ou usa `curl`) e confirma que:
   - a homepage responde;
   - o HTML carrega;
   - os links de imagens externas não estão partidos;
   - o layout não apresenta erros JS óbvios.

## Se não conseguires criar o repositório
Não alteres a aplicação para contornar o problema. Diz exatamente qual permissão/autenticação está em falta e dá a Rita o passo mínimo necessário. Depois continua automaticamente assim que o repositório estiver disponível.

## Se conseguires criar repo mas não ativar Pages
Faz todo o resto (repo, commit, push) e indica apenas o passo exato que falta em GitHub > Settings > Pages.

## Critérios de aceitação
- Repositório público `ritelian/oficinas-artes` criado ou reutilizado.
- `main` contém a versão fornecida de `index.html`.
- `.nojekyll` presente.
- GitHub Pages ativo.
- URL pública funcional.
- Nenhuma alteração editorial substancial sem necessidade.

## Nota sobre recursos externos
O site usa imagens remotas do Wikimedia Commons e Google Fonts. Não é necessário descarregar esses assets para o repositório, salvo se houver algum problema real de carregamento, CORS ou estabilidade.
