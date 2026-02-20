---
title: "Relatório de Ordenação - Coleção Verão 2026"
category: quality
status: passing
summary: "Reordenação aplicada com sucesso. 234 produtos, 23 mudanças, 12 novos itens."
source: collection-rank-mcp
tags: [coleção, verão, ordenação]
updatedAt: "2026-02-19T16:38:42Z"
sections:
  - type: metrics
    title: "Resumo"
    items:
      - label: Produtos
        value: 234
        unit: "itens"
        status: info
      - label: Mudanças
        value: 23
        unit: "posições"
        status: info
      - label: Novos
        value: 12
        unit: "itens"
        status: info

  - type: criteria
    title: "Critérios"
    items:
      - label: "Grade de Tamanhos"
        description: "Priorizar produtos com grade completa e disponível nos tamanhos de maior giro."
      - label: "Estampa Grouping"
        description: "Agrupar produtos por estampa para melhorar a experiência de navegação."
      - label: "Disponibilidade de Estoque"
        description: "Remover produtos sem estoque nas grades principais."

  - type: note
    content: "Nesta rodada aumentamos o peso da grade (foco em P/M) e testamos, pela primeira vez, agrupamento por estampa, mantendo itens da mesma coleção juntos, mesmo com leve impacto no score individual."

  - type: ranked-list
    title: "Ordenação"
    columns: [Vendas, Grade]
    rows:
      - position: 1
        delta: 2
        label: "Blusa Tule Estampada Paisagem Solar"
        image: "https://images.unsplash.com/photo-1562157873-818bc0726f68?w=100&h=100&fit=crop"
        values: ["R$8.440", "100%"]
        note: "MUDANÇA: destaque para grade completa P/M"
      - position: 2
        delta: -1
        label: "Blusa Listex Peplum"
        image: "https://images.unsplash.com/photo-1558171813-453fa0152f3c?w=100&h=100&fit=crop"
        values: ["R$6.010", "70%"]
      - position: 3
        delta: -2
        label: "Vestido T-Shirt Big Estampado Paisagem Solar"
        image: "https://images.unsplash.com/photo-1595777457583-95e059d581b8?w=100&h=100&fit=crop"
        values: ["R$6.010", "80%"]
      - position: 4
        delta: 0
        label: "Calça Cargo Tactel"
        image: "https://images.unsplash.com/photo-1624378439575-d8705ad7ae80?w=100&h=100&fit=crop"
        values: ["R$5.200", "90%"]
        note: "NEW"
      - position: 5
        delta: 1
        label: "Short Sarja Destroy"
        image: "https://images.unsplash.com/photo-1594938298603-c8148c4dae35?w=100&h=100&fit=crop"
        values: ["R$4.890", "85%"]
      - position: 6
        delta: -1
        label: "Camiseta Básica Algodão"
        image: "https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?w=100&h=100&fit=crop"
        values: ["R$3.120", "100%"]
      - position: 7
        delta: 2
        label: "Jaqueta Jeans Oversized"
        image: "https://images.unsplash.com/photo-1551028719-00167b16eac5?w=100&h=100&fit=crop"
        values: ["R$12.500", "60%"]
      - position: 8
        delta: -1
        label: "Saia Midi Plissada"
        image: "https://images.unsplash.com/photo-1595776613215-fe04b78de7d0?w=100&h=100&fit=crop"
        values: ["R$4.200", "95%"]
---

## Detalhes

Este relatório foi gerado pelo MCP de ordenação de coleções. O parser lê este arquivo Markdown com frontmatter YAML e transforma em um objeto `Report` compatível com o `REPORTS_BINDING`.

O MCP expõe as tools `REPORTS_LIST` e `REPORTS_GET`, que leem os arquivos `.md` na pasta `reports/` e retornam no formato esperado pelo plugin do Mesh.
