# Base operacional — Hub Joias

Atualizado em 11 de agosto de 2026 a partir das páginas públicas da Hub Joias.

## Dados confirmados

| Tema | Informação confirmada | Uso na loja |
|---|---|---|
| Modelo | Dropshipping nacional: a revendedora vende e a Hub despacha diretamente ao cliente, sem pedido mínimo e sem estoque próprio. | Não incluir custo de estoque na precificação inicial. |
| Despacho | Até 24 horas após o pedido entrar no sistema. | Comunicar como prazo de postagem, nunca como prazo de entrega. |
| Materiais | Semijoias douradas: banho de ouro 24K com 10 milésimos; semijoias prateadas: banho de ródio com 10 milésimos; prata 925: prata legítima maciça. | Preencher `banho_material` com uma destas três classificações, conferindo item a item no catálogo oficial/integrado. |
| Qualidade | Tecnologia antialérgica e garantia de 2 anos são informadas pela Hub para os três tipos de acessórios. | Usar somente com a política de garantia publicada pela loja. |
| Conteúdo | A Hub informa mais de 1.500 imagens e vídeos; cada peça tem ao menos still e foto com modelo. | Usar como conteúdo de produto e criativos, observando os termos do plano contratado. |
| Atualização | A coleção é atualizada a cada 75 dias. | Revisar catálogo, preços e itens ativos periodicamente. |
| Integrações | Hub lista Mercado Livre, Shopee, Bling, Shopify, Nuvemshop, WooCommerce, Tray e Yampi. | Escolher apenas um canal de loja para o lançamento. |
| Plano fornecedor | R$ 107/mês no mensal; indicado para quem já possui site. | Custo fixo mensal de operação quando a loja for externa. |
| Plano completo | R$ 197/mês no mensal; inclui loja virtual própria e integrações. | Alternativa prioritária para lançar sem montar plataforma separada. |

Fontes: https://www.hubjoias.com.br/ e https://www.hubjoias.com.br/catalogo

## Lacunas que continuam bloqueando o preço final

| Lacuna | Por que importa | Como resolver |
|---|---|---|
| Frete por CEP, produto e pedido com múltiplos itens | Define o custo real do pedido e a regra de frete grátis. | Simular CEPs representativos no painel/demonstração e confirmar com a Hub. |
| Taxa do checkout e parcelamento | Muda a margem líquida de PIX e cartão. | Confirmar o gateway, as taxas por método e o custo de antecipação. |
| Impostos e emissão fiscal | Não é seguro definir margem sem o enquadramento da empresa. | Validar com contador antes de publicar a loja. |
| Embalagem personalizada | Não há preço, prazo, mínimo ou especificação pública. | Solicitar tabela e amostra à Hub. |
| Estoque e indisponibilidade | O catálogo público não apresenta saldo ou SLA de reposição. | Confirmar sincronização e procedimento de ruptura. |
| Trocas e garantia entre loja e Hub | A garantia existe, mas o site público não especifica o fluxo B2B, frete reverso ou responsável por cada custo. | Formalizar o fluxo antes do lançamento. |
| Dados físicos e variações | Peso, medidas, tamanho de anéis e GTIN não estão no export local. | Obter via painel/API ou ficha oficial. |

## Regra de precificação a adotar

`Preço = (custo Hub + frete Hub + embalagem + custo fixo por pedido + CAC previsto) / (1 - taxas variáveis - impostos - margem de contribuição alvo)`

Calcular separadamente para PIX, cartão parcelado, site próprio e cada marketplace. O custo fixo por pedido inclui a mensalidade Hub dividida pela projeção conservadora de pedidos mensais.

## Decisão recomendada para o lançamento

1. Definir marca e domínio.
2. Solicitar/confirmar os seis pontos operacionais pendentes com a Hub.
3. Contratar inicialmente o plano Completo caso a demonstração e as taxas atendam à operação; ele reduz a necessidade de configurar uma plataforma externa no começo.
4. Subir somente 20 a 30 produtos, com preço calculado e categorias mais específicas.
5. Realizar um pedido-teste real antes de ativar anúncios ou marketplaces.

## Perguntas prontas para a Hub Joias

1. Como é calculado e cobrado o frete por pedido? Há cotação por CEP no checkout e regra para múltiplas peças?
2. Quais são as transportadoras e os prazos de entrega depois do despacho em até 24 horas?
3. Qual a taxa do checkout para PIX, cartão e parcelamento? Há custo de antecipação?
4. Qual é o preço, prazo e pedido mínimo da embalagem personalizada? Ela segue sem identificação da Hub?
5. Como funciona a troca, defeito e garantia de 2 anos no dropshipping: quem aprova, quem paga o frete reverso e para qual endereço a peça retorna?
6. O estoque é sincronizado automaticamente? Como são tratados itens esgotados após uma venda?
7. O plano Completo permite domínio próprio, e-mail transacional com a marca, pixels, exportação de dados e integração com WhatsApp?
8. Há acesso a API, ficha técnica com peso/dimensões e variações de tamanho, especialmente para anéis?
