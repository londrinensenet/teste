# Feed sintético de imóveis

Ambiente público controlado para testar o pipeline do Portal Londrinense como se fosse o feed XML de uma imobiliária.

## URL

- Cloudflare Pages: `https://teste-7jt.pages.dev/imoveis.xml`
- Domínio definitivo: `https://teste.londrinense.net/imoveis.xml`

O arquivo contém 24 imóveis inteiramente fictícios de Londrina/PR, distribuídos entre venda, aluguel, casas, apartamentos, terrenos, comerciais, galpões e rurais. Não existem ofertas, pessoas, telefones ou credenciais reais.

O painel do portal deve guardar essa URL somente na configuração privada do cliente de teste `cliente-teste-001`. O navegador público do portal continuará consumindo somente os JSONs produzidos pelo pipeline.
