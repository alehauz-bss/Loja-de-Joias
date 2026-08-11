---
name: cadastro-e-gestao-de-marketplaces
description: Skill de Cadastro Técnico, Precificação por Canal, SEO de Marketplaces e Integração ERP (Bling/Tiny) para Semi Joias.
---

# 🛒 Skill: Cadastro & Gestão de Marketplaces para Semi Joias

## 🎯 Objetivo da Skill
Capacitar a equipe a cadastrar, otimizar e gerenciar semi joias em múltiplos canais de venda (Mercado Livre, Shopee, TikTok Shop, Shein, Amazon, Instagram Shopping e E-commerce próprio), garantindo precificação correta por comissão de canal, títulos otimizados para cada algoritmo de busca, cumprimento das políticas dos marketplaces e sincronização de estoque via ERP.

---

## 🏛️ Matriz de Canais & Regras Específicas

| Canal | Foco Principal | Estilo de Foto Recomendado | Título SEO Recomendado | Comissão Médica Est. |
| :--- | :--- | :--- | :--- | :--- |
| **Mercado Livre** | Busca direta e alta conversão rápida | Fundo branco puro (1000x1000px) sem marca d'água | `[Tipo de Peça] + [Material] + [Detalhe] + [Antialérgico]` | 11% a 19% + taxa fixa por item abaixo de R$ 79 |
| **Shopee** | Volume, kits e buscas por menor preço / cupom | Foto de produto limpa com acento de cor ou selo de garantia | Palavras-chave repetidas + variações + hashtags no final | 14% a 20% (com frete grátis ativado) |
| **TikTok Shop** | Compra por impulso via vídeos e lives | Foto de capa estilo lifestyle + vídeo curto em uso | Título curto e direto focado no benefício e tendência | 5% a 8% (taxas de introdução/promoção) |
| **Instagram Shopping** | Vitrine visual conectada ao Meta Catalog | Foto estilo editorial / lifestyle de alta resolução | Nome do produto elegante e alinhado ao site | Integrado ao e-commerce (sem comissão direta Meta) |
| **Shein** | Moda acessível, conjuntos e público jovem | Foto em modelo humana ou busto neutro | `[Estilo] + [Tipo de Joia] + Folheado a Ouro` | 10% a 16% |
| **Amazon Brasil** | Clientes Prime, busca técnica e presentes | Fundo 100% branco no produto principal | `[Marca] + [Tipo] + Folheado Ouro 18k + [Gema] + [Antialérgico]` | 13% a 15% em Acessórios |

---

## 💰 Fórmula de Precificação por Canal (Mark-up com Comissões)

Como cada canal cobra uma taxa de comissão e frete diferente, o preço final deve ser calculado individualmente para manter a **mesma margem de lucro líquida** em todas as plataformas.

$$\text{Preço no Canal} = \frac{\text{Preço Base Desejado (Site)} + \text{Taxa Fixa do Canal}}{1 - (\text{Comissão \%} + \text{Imposto \%} + \text{Margem Adicional \%})}$$

### Exemplo Prático para Anel Folheado (Preço no Site: R$ 120,00):
- **Custo da Peça**: R$ 30,00
- **Margem Líquida Alvo**: R$ 60,00
- **Preço no Mercado Livre (Comissão 16% + R$ 6,00 taxa fixa)**:
  $$\text{Preço ML} = \frac{120 + 6}{1 - 0.16} = \frac{126}{0.84} = \text{R\$ 150,00}$$
- **Preço na Shopee (Comissão 20%)**:
  $$\text{Preço Shopee} = \frac{120}{1 - 0.20} = \frac{120}{0.80} = \text{R\$ 150,00}$$

---

## 📋 Ficha Técnica Padrão de Cadastro (Template de Produto)

Para cada nova semi joia, a Ficha Técnica Operacional deve conter:

```yaml
SKU_Pai: SJ-COL-COR-001
Nome_Produto_Base: Colar Coração Folheado a Ouro 18k Antialérgico
Categoria_NCM: 7117.19.00 (Bijuterias de metais comuns, mesmo folheadas)
GTIN_EAN: 789XXXXXXXXXX (Código de Barras)
Peso_Bruto: 0.150 kg (com embalagem)
Dimensoes_Caixa: 15cm (C) x 11cm (L) x 6cm (A)
Material_Base: Latão nobre de grau joalheiro
Banho: Ouro 18k (3 a 5 mícrons)
Pedra: Zircônia Cúbica de Lapidação Brilhante
Garantia: 6 meses de garantia no banho
Antialergico: Sim (Livre de Níquel)
```

---

## ⚙️ Sincronização via ERP (Bling / Tiny)

Para cadastrar em **todos os marketplaces simultaneamente** sem retrabalho:

```
                  ┌───────────────────────────────┐
                  │   📦 CADASTRO ÚNICO NO ERP   │
                  │        (Bling ou Tiny)        │
                  └──────────────┬────────────────┘
                                 │
     ┌───────────────────────────┼───────────────────────────┐
     ▼                           ▼                           ▼
┌──────────────────┐    ┌──────────────────┐    ┌──────────────────┐
│  🛍️ NUVEMSHOP /  │    │  💛 MERCADO LIVRE│    │  🧡 SHOPEE       │
│     SHOPIFY      │    │  (Exportação)    │    │  (Exportação)    │
└──────────────────┘    └──────────────────┘    └──────────────────┘
     │                           │                           │
     ▼                           ▼                           ▼
┌──────────────────┐    ┌──────────────────┐    ┌──────────────────┐
│ 📸 INSTA SHOPPING│    │ 🎵 TIKTOK SHOP   │    │ 📦 SHEIN / AMAZON│
└──────────────────┘    └──────────────────┘    └──────────────────┘
```

1. **Cadastrar 1x no ERP**: Título base, especificações técnicas, NCM, fotos em alta resolução, estoque físico.
2. **Configurar Regras de Preço**: Aplicar acréscimo percentual automático no ERP por categoria de canal (ex: +15% para Mercado Livre, +18% para Shopee).
3. **Mapeamento de Categorias**: Associar a categoria do ERP à árvore de categorias oficial de cada marketplace.
4. **Sincronização Ativa**: Estoque atualizado automaticamente — se vendeu 1 peça na Shopee, o ERP baixa o estoque do site e do Mercado Livre na hora.

---

## 🤖 Prompt de Suporte para Cadastro em Marketplaces

```text
Você é o Gestor de E-commerce e Marketplaces de uma loja de semi joias. 
Receba as informações do produto abaixo e gere:

1. Título otimizado para Mercado Livre (máx 60 caracteres, focado em busca).
2. Título otimizado para Shopee (com palavras-chave e hashtags).
3. Título otimizado para TikTok Shop (curto e com apelo visual).
4. Tabela de Atributos da Ficha Técnica (Material, Banho, Gema, NCM, Dimensoes).
5. Preço sugerido para cada canal considerando as comissões padrão.

Produto a cadastrar:
[Nome e detalhes da peça]
```
