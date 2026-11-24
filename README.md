# Ben 10 — Arquivo Omniverso

Site de fã responsivo, com visual sci-fi verde inspirado no tema do Omnitrix e estrutura semelhante a um audiobook interativo.

## Recursos já incluídos

- Linha do tempo da franquia.
- Catálogo inicial das cinco séries animadas principais.
- Filmes e especiais.
- Catálogo de quadrinhos, com destaque para a série da Dynamite iniciada em 2026.
- Área para organizar artes conceituais por categoria e registrar procedência.
- Cadastro local de AUs (universos alternativos) com créditos e link para a publicação original.
- Banco inicial de aliens com busca e filtro por era.
- Audiobook com 11 capítulos narrados pela voz em português disponível no navegador (Web Speech API).
- Quiz de 10 perguntas.
- Progresso dos capítulos e AUs guardados no navegador (localStorage).
- PWA instalável e cache básico para uso offline após a primeira visita.

## Como testar

1. Extraia o ZIP.
2. Abra `index.html` em um navegador moderno para testar os recursos principais.
3. Para instalar como aplicativo e testar o modo offline, publique em um endereço HTTPS, por exemplo GitHub Pages. O service worker não funciona em `file://`.

## Como publicar no GitHub

1. Crie um repositório público ou privado no GitHub.
2. Entre no repositório e use **Add file → Upload files**.
3. Envie os arquivos e pastas que estão dentro desta pasta (`index.html`, `styles.css`, `app.js`, `manifest.json`, `sw.js`, `assets/` e `README.md`).
4. Confirme em **Commit changes**.
5. Para ativar o GitHub Pages, abra **Settings → Pages**, escolha a branch principal e a pasta `/ (root)`, e salve.

## Como expandir sem bagunçar o projeto

- As séries, filmes, quadrinhos, aliens, capítulos e questões ficam no começo de `app.js`, em listas separadas (`SERIES`, `MOVIES`, `COMICS`, `ALIENS`, `CHAPTERS`, `QUIZ`).
- Para adicionar uma edição de HQ, inclua título, data, resumo, status e link oficial quando houver.
- Para adicionar áudio gravado por você, crie uma pasta `audio/` e use um elemento `<audio controls>` na página do capítulo. Esta versão usa voz do navegador e não inclui gravações oficiais.
- Para inserir arte, use apenas imagens cuja publicação/uso seja permitido e registre artista, fonte e status. Não trate arte de fã como concept art oficial.
- A área de AUs salva apenas no navegador atual; para uma galeria pública com contribuições de várias pessoas, será necessário conectar uma base de dados e moderação.

## Limites e créditos

Projeto independente de fã, sem afiliação com Cartoon Network, Warner Bros. Discovery, Man of Action, Dynamite Entertainment, IDW ou quaisquer titulares. Ben 10, nomes, personagens e marcas pertencem aos seus respectivos proprietários. Este repositório não contém episódios, páginas de quadrinhos, artes oficiais ou trilhas sonoras.

A linha de quadrinhos da Dynamite é catalogada de acordo com as informações disponíveis em 23 de novembro de 2026. Datas futuras estão marcadas como previstas e podem mudar.
