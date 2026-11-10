# Execução Orçamentária e Despesas - CMCB

Painel interativo de consulta e transparência das **Despesas por Natureza** e **Movimentações Diárias da Execução Orçamentária** da Câmara Municipal de Coronel Barros/RS. Os dados são sincronizados diretamente com a base de dados abertos do Tribunal de Contas do Estado do Rio Grande do Sul (TCE-RS - Órgão `75101`).

---

## 🌐 Páginas Dedicadas (Acesso Direto)

| Página | Finalidade | URL Oficial no GitHub Pages |
| :--- | :--- | :--- |
| **Card 1: Movimentações Diárias** | Acompanhamento de empenhos, liquidações e pagamentos em tempo real. | [https://cmcb-labs.github.io/despesas/movimentacoes.html](https://cmcb-labs.github.io/despesas/movimentacoes.html) |
| **Card 2: Despesas por Natureza** | Demonstrativo consolidado por classificação econômica do orçamento (Pessoal, Custeio, Investimentos). | [https://cmcb-labs.github.io/despesas/natureza.html](https://cmcb-labs.github.io/despesas/natureza.html) |
| **Hub Central** | Acesso conjunto com ambos os cards para navegação unificada. | [https://cmcb-labs.github.io/despesas/](https://cmcb-labs.github.io/despesas/) |

---

## 💻 Como Linkar no Portal da Câmara (Plone)

Nos cards da página `/transparencia/despesas` no Plone, substitua os links dos botões pelas URLs dedicadas acima:

1. **No Botão "Consultar Movimentações ›":**
   * **Link:** `https://cmcb-labs.github.io/despesas/movimentacoes.html`
   * *(Opcional: abrir em nova aba com `target="_blank"`)*

2. **No Botão "Acessar por Natureza ›":**
   * **Link:** `https://cmcb-labs.github.io/despesas/natureza.html`
   * *(Opcional: abrir em nova aba com `target="_blank"`)*

---

## ✨ Recursos de Acessibilidade e Auditoria ATRICON

- **Zero Scrollbar Horizontal:** Layout 100% responsivo com alternância automática para cards no mobile.
- **Tratamento de Dados Zerados:** Quando um exercício não tem despesas registradas, exibe declaração formal com carimbo de sincronização e data/hora.
- **Exportação em Formatos Abertos:** Botões para download imediato em **CSV**, **JSON** e **Impressão**.
