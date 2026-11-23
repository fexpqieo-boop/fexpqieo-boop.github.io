# BEN 10 ARCHIVE — The Ultimate Fan Database

Site estático de fã sobre a franquia Ben 10, em português (Brasil), preparado para publicação no **GitHub Pages**.

## O que já vem no projeto

- Página responsiva com identidade visual original inspirada em ficção científica.
- Separação entre continuidade clássica, reboot de 2016, nova série de quadrinhos da Dynamite (2026) e conteúdo feito por fãs.
- Linha do tempo inicial da franquia.
- Filtros e busca de séries, filmes, especiais e aliens.
- Catálogo inicial de aliens e dispositivos Omnitrix.
- Área de quadrinhos: Cartoon Network Action Pack!, BOOM! Studios, graphic novels de Omniverse e Dynamite 2026.
- Seções de concept art e AUs, com indicação de autoria e procedência.
- Lista inicial de jogos e links de referência.

## Como abrir no computador

1. Extraia o ZIP.
2. Abra a pasta `ben10-archive`.
3. Dê dois cliques em `index.html` para visualizar no navegador.

Não é necessário instalar Node, Python ou qualquer framework.

## Como publicar no GitHub Pages

### Opção A — endereço `seuusuario.github.io`

1. Entre no GitHub e crie um repositório público chamado exatamente `SEUUSUARIO.github.io` (substitua pelo seu nome de usuário).
2. Envie todos os arquivos e pastas deste projeto para a raiz do repositório. O arquivo `index.html` precisa ficar diretamente na raiz.
3. Abra **Settings → Pages** no repositório.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
6. O endereço será `https://SEUUSUARIO.github.io/`.

### Opção B — projeto dentro de um repositório

1. Crie um repositório chamado, por exemplo, `ben10-archive`.
2. Envie os arquivos do projeto para a raiz do repositório.
3. Em **Settings → Pages**, selecione **Deploy from a branch**, branch `main` e pasta `/ (root)`.
4. O endereço será `https://SEUUSUARIO.github.io/ben10-archive/`.

O GitHub pode levar alguns minutos para publicar a primeira versão. Não coloque o projeto dentro de uma segunda pasta `ben10-archive/` ao enviar: `index.html` deve estar na raiz selecionada pelo Pages.

## Como atualizar o conteúdo

Edite `assets/js/data.js`. Os principais blocos são:

- `timeline`: marcos da franquia.
- `media`: séries, filmes e especiais.
- `aliens`: formas alienígenas e habilidades.
- `devices`: Omnitrix e dispositivos relacionados.
- `comics`: HQs e graphic novels.
- `variants`: versões alternativas oficiais.
- `fanAUs`: universos alternativos criados por fãs.
- `games`: jogos.

### Como adicionar uma AU

No final de `assets/js/data.js`, localize `fanAUs: []` e acrescente itens neste formato:

```js
fanAUs: [
  {
    name: "Nome da AU",
    creator: "Nome ou apelido do criador",
    description: "Resumo original da história e do que torna essa AU diferente."
  }
]
```

Se já houver itens em `fanAUs`, acrescente uma vírgula depois do último objeto e insira o novo objeto. Não publique e-mail, telefone, endereço ou outros dados pessoais de colaboradores.

## Artes conceituais e direitos autorais

O site usa elementos gráficos originais e áreas ilustrativas feitas em CSS; não inclui logotipos oficiais, capturas de episódios, páginas de quadrinhos ou artes de produção copiadas. Para adicionar imagens reais, use apenas arquivos que você criou, materiais com licença compatível ou imagens cujo uso tenha sido autorizado. Identifique sempre artista, fonte, série e contexto. Prefira links para a publicação original quando não houver autorização para hospedar uma imagem.

## Precisão e manutenção

- Datas e calendários de quadrinhos podem mudar; confirme sempre no site oficial da editora.
- A nova série da Dynamite de 2026 está separada das continuidades animadas neste arquivo até que uma fonte editorial indique explicitamente uma conexão.
- Conteúdo fan-made e AUs devem permanecer marcados como **FAN-MADE**.
- Este projeto é uma enciclopédia inicial expansível, não um catálogo oficial nem uma reprodução completa de cada episódio, HQ ou arte.

## Referências iniciais

- Dynamite Entertainment — https://dynamite.com/titles/ben-10/
- Dynamite — Ben 10 #1 — https://dynamite.com/BEN-10-1/
- Dynamite — Ben 10 Creator Files #1 — https://dynamite.com/BEN-10-CREATOR-FILES-1/
- BOOM! Studios — https://www.boom-studios.com/search/BEN%2010
- BOOM! Studios — anúncio do programa de graphic novels — https://www.boom-studios.com/archives/boom-studios-launches-new-ben-10-graphic-novel-program/
- CB Lee — https://cb-lee.com/ben-10/
- Grand Comics Database — https://www.comics.org/feature/2087/issues/
- Ben 10 Wiki (comunidade, usar como referência secundária) — https://ben10.fandom.com/wiki/Franchise

---

Projeto independente de fã. Ben 10 e elementos relacionados pertencem aos seus respectivos titulares.
