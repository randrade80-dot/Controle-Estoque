# Estoque Semanal

App simples para controle de estoque por **contagem semanal** (toda sexta). Você não anota o que sai: conta o estoque, lança o que recebeu e o app calcula o consumo e **o que pedir**, por fornecedor.

Funciona no celular como app instalável (PWA), sem servidor e sem custo. Os dados ficam no próprio aparelho.

## Como usar

1. **Itens**: cadastre seus produtos com unidade, fornecedor, estoque mínimo e ideal (ou toque em "Carregar itens de exemplo").
2. **Contagem**: toda sexta, crie a semana e digite a contagem de cada item e o que entrou na semana.
3. **Pedir**: veja o status (PEDIR / ATENÇÃO / OK), a quantidade sugerida e toque em "Copiar pedido" para mandar ao fornecedor.
4. **Backup**: exporte de vez em quando. Se limpar os dados do navegador, os dados se perdem.

Consumo da semana = contagem da sexta anterior + entradas − contagem de hoje.

## Publicar no GitHub Pages

1. Crie uma conta em https://github.com (se ainda não tiver).
2. Clique em **New repository**, dê um nome (ex.: `estoque-semanal`), deixe **Public** e crie.
3. Clique em **uploading an existing file** e envie TODOS os arquivos desta pasta
   (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `.nojekyll`, `README.md`). Clique em **Commit changes**.
4. Vá em **Settings > Pages**. Em **Branch**, escolha `main` e a pasta `/ (root)`, e clique em **Save**.
5. Espere 1 a 2 minutos. O endereço será `https://SEU-USUARIO.github.io/estoque-semanal/`.

## Instalar no celular

- **Android (Chrome)**: abra o endereço, toque nos três pontos e em **Instalar app** / **Adicionar à tela inicial**.
- **iPhone (Safari)**: abra o endereço, toque em Compartilhar e em **Adicionar à Tela de Início**.

## Atualizar o app

Edite o arquivo no GitHub (ícone de lápis) e salve. O app pega a versão nova na próxima vez que abrir com internet.
