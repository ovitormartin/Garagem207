# Garagem do 207

App para celular de gestão do Peugeot 207 Quiksilver 1.4 8V Flex 2010. Ele cuida de:

- Combustível: consumo por ciclo, custo por km, etanol × gasolina.
- Manutenção: plano preventivo, serviços, problemas e garantias.
- Gastos: custos e comparativo semanal, mensal e anual.
- Vencimentos.
- Guia técnico do carro.

O app funciona sem internet depois de aberto pela primeira vez. Os dados ficam guardados no próprio celular.

## Publicar no GitHub Pages

1. Entre em github.com e crie um repositório novo chamado `garagem-207`. Ele precisa ser **público**, porque o GitHub Pages gratuito só funciona com repositório público. Somente o código fica visível. Os seus registros nunca vão para o GitHub.
2. Na página do repositório, clique em **Add file › Upload files**. Envie `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` e a pasta `icons` com os 4 arquivos dentro. Depois clique em **Commit changes**.
3. Vá em **Settings › Pages**. Em *Build and deployment*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e clique em **Save**.
4. Em um ou dois minutos o app fica disponível em `https://SEU-USUARIO.github.io/garagem-207/`.

## Instalar no celular

**Android (Chrome)**
1. Abra o endereço acima no Chrome.
2. Toque em **⋮ › Instalar app** ou **Adicionar à tela inicial**.

**iPhone (Safari)**
1. Abra o endereço no Safari.
2. Toque em **Compartilhar › Adicionar à Tela de Início**.

O ícone aparece junto com os outros apps. O app abre em tela cheia e funciona offline.

## Trazer os dados que já existem

No app instalado, abra **Guia › Seus dados › Importar backup** e escolha o arquivo `garagem-207-backup-2026-10-21.json`.

## Backup

Os dados ficam só no aparelho. Se você limpar os dados do navegador, desinstalar o app ou trocar de celular, eles se perdem. Uma vez por mês, toque em **Guia › Seus dados › Fazer backup** e salve o arquivo no Google Drive. O painel avisa quando o último backup tem mais de 30 dias.

## Atualizar o app

1. Substitua os arquivos no repositório pela versão nova.
2. Em `sw.js`, aumente o número em `VERSION` (por exemplo `garagem-207-v2`). Isso faz os celulares baixarem a atualização.
3. No celular, feche o app e abra de novo.

Os seus registros não são apagados em uma atualização.
