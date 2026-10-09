# Mapas temáticos CISC Curitiba

Este repositório publica **somente os três mapas selecionados** do boletim CISC:

- **Áreas verdes** — `areas-verdes/`
- **Unidades administrativas** — `unidades-administrativas/`
- **Hidrografia** — `hidrografia/`

## Como concluir a publicação

1. Em **Settings → Pages → Build and deployment**, escolha **GitHub Actions** como fonte.
2. Baixe o arquivo **CISC_Mapas_3_prontos_GitHub_Pages.zip** fornecido na conversa.
3. Na raiz deste repositório, selecione **Add file → Upload files**, envie o arquivo ZIP **sem descompactar** e confirme o commit na branch `main`.
4. O workflow `.github/workflows/publicar-mapas.yml` extrairá o ZIP e publicará os mapas no GitHub Pages.
5. Confira a execução em **Actions** e, após o deploy, abra https://douglasg1997.github.io/mapa-boletim-cisc/.

O ZIP de publicação contém apenas os três mapas desejados; **não use o ZIP original** que também contém outras camadas temáticas.

As camadas geográficas volumosas foram armazenadas como `.json.gz` e são descomprimidas pelo navegador para reduzir transferência. Não altere os nomes de pastas nem dos arquivos.
