# K&V — pacote pronto para GitHub Pages

O `index.html` fica na raiz e já contém o CSS e o JavaScript. Assim, não há pastas `css/` e `js/` para configurar ou esquecer no envio. O MP3 fornecido está incluído em `assets/audio/`.

## Publicar no GitHub Pages

1. Extraia `aventura-kv-github-pages.zip`.
2. Envie **os arquivos de dentro do ZIP** para a raiz do repositório. A estrutura deve ficar assim:

   ```text
   seu-repositorio/
   ├── index.html
   ├── README.md
   └── assets/
       ├── audio/nossa-musica.mp3
       └── images/photo-placeholder.svg
   ```

   Não coloque a pasta `aventura-kv-github-pages` inteira dentro do repositório. O `index.html` deve aparecer logo na página principal do repositório, ao lado do README.

3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, escolha a branch `main` e a pasta `/(root)`, e salve.
5. Aguarde a publicação indicada nessa mesma tela. O site usa caminhos relativos para mídia, então funciona também no endereço de projeto do GitHub Pages.

Se o repositório já tiver outro site, faça uma cópia do `index.html` atual antes de substituí-lo.

## Fotos

Victória pode adicionar e trocar fotos na tela da etapa **Nosso cantinho de memórias**. As fotos escolhidas ficam salvas no navegador e aparelho dela. Não são enviadas ao repositório nem sincronizadas com outros dispositivos.

## Música

O MP3 fornecido está no pacote como `assets/audio/nossa-musica.mp3`. Para trocá-lo, substitua por outro arquivo com o mesmo nome e envie a alteração ao repositório.

## Editar mensagens e aparência

O conteúdo, estilos e scripts estão juntos no `index.html` para simplificar o deploy. No futuro, abra esse arquivo no VS Code e procure `window.ADVENTURE`, `window.SECRET_MESSAGE` ou `window.FINAL_MESSAGE` para editar textos. Faça uma cópia do arquivo antes de alterar.
