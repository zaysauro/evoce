# É Você — Estúdio de Propostas

Aplicação web brasileira para elaborar propostas comerciais e orçamentos. Funciona sem backend, login ou chaves externas.

## Funcionalidades
- Editor de propostas com itens, quantidades, valores e totais em BRL
- Pré-visualização em tempo real
- Exportação PDF via impressão do navegador
- Salvamento local, backup e restauração JSON
- Layout responsivo e documento A4 para impressão
- Sanitização de texto inserido no preview para evitar injeção HTML

## Executar
Abra `index.html` em um navegador ou execute `python3 -m http.server 8000` e acesse localhost:8000.

## Deploy
Aplicação estática, compatível com Vercel, Netlify e GitHub Pages. Na Vercel, importe o repositório, selecione Framework Preset: Other, deixe Build Command vazio e Output Directory como raiz.

## Limitações importantes
**Não é um SaaS multiempresa e ainda não está pronto para cobrar assinaturas.** Os dados ficam somente no navegador e podem ser perdidos se o armazenamento local for limpo. Não há login, armazenamento em nuvem, envio de e-mails, cobrança, assinatura digital certificada ou sincronização entre dispositivos. Não substitui emissão de NFS-e.

## Próximos passos para comercialização
Adicionar autenticação, banco de dados com isolamento multiempresa, histórico de propostas, links de aceite com auditoria, faturamento recorrente, templates e integração de pagamento.

## Licença
Código original deste repositório. Nenhuma base de terceiros foi copiada. Verifique licenças de futuras dependências antes da incorporação.
