# Operação de campanha no TikTok Ads

Este repositório organiza a operação e a medição de uma campanha com cinco argumentos comerciais.

## Escopo autorizado

- Repositório autorizado para alterações: `jobafirmo/tiktok`.
- Trabalho nos demais repositórios, sites, aplicativos, Workers e ambientes fica fora deste projeto.
- Instalação de Pixel ou código nos sistemas IASIS, LançaMais e LanceCerto não está autorizada.
- Publicação de anúncios, ativação de campanhas, pagamentos e aumento de investimento dependem de autorização expressa do titular.
- Textos técnicos, títulos e alegações comerciais dependem de aprovação do titular antes de serem usados em anúncios.

## Operação inicial

A estrutura preferencial é uma campanha de geração de leads, com um grupo e cinco anúncios individuais. Cada anúncio usa um vídeo e o mesmo formulário instantâneo de qualificação.

A distribuição entre os anúncios pode ser desigual. O orçamento fica na plataforma, e não deve ser obrigatoriamente dividido em cinco partes iguais.

O formulário identifica a relação do interessado com a oficina. Proprietários, sócios, gerentes e administradores são prioritários. A qualidade precisa ser confirmada pelo atendimento.

## Arquivos

- `docs/operacao.md`: rotina de atendimento e limites de atuação.
- `docs/medicao.md`: definições dos indicadores e critérios de comparação.
- `modelos/metricas_por_anuncio.csv`: modelo vazio de indicadores agregados.
- `modelos/acompanhamento_leads.csv`: modelo vazio do andamento comercial.
- `AGENTS.md`: instruções para futuras alterações neste repositório.

## Dados e acesso

O repositório é público. Os modelos contêm apenas cabeçalhos; as bases preenchidas devem ficar em armazenamento privado.

Use `dados/`, `exportacoes/` ou `relatorios/` somente para trabalho local. Essas pastas são ignoradas pelo Git. O arquivo `.gitignore` não impede um envio forçado; revise cada arquivo antes de qualquer commit.

Importe IDs de leads, anúncios, grupos e campanhas como texto, preservando todos os dígitos. O acompanhamento deve manter a origem do anúncio.

## Limite da mensuração

O formulário instantâneo registra a captação no TikTok. Qualificação, demonstração, teste e assinatura paga precisam ser acompanhados pelo atendimento e pelo faturamento.

Um formulário recebido não comprova assinatura. Um clique não comprova cadastro, teste iniciado ou pagamento. Sem uma integração autorizada e validada, esses resultados comerciais são consolidados manualmente.

Não há implantação, workflow de publicação, alteração de aplicativo ou envio automático de dados neste repositório.
