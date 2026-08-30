# Grupo VIP Vagas

MVP de vagas em Marketing Digital. A aba `Vagas` do Google Sheets é consultada a cada cinco minutos e somente linhas com `Status candidatura = Aberta confirmada` são publicadas.

## Rodar localmente

`pnpm dev`

## Fonte e publicação

A integração usa a exportação CSV da aba `Vagas`. Para funcionar no site publicado, a planilha precisa permitir leitura por link ou estar publicada na web. Se a fonte estiver indisponível, o site mantém uma pequena seleção de exemplo para evitar uma tela vazia.

O projeto usa Vinext e é compatível com Cloudflare. Use `pnpm build` no deploy.
