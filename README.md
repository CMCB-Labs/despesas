# Execução Orçamentária e Despesas - CMCB

Painel interativo de consulta e transparência da **Execução Orçamentária e Despesas por Natureza** da Câmara Municipal de Coronel Barros/RS. Os dados são sincronizados diretamente com a base de dados abertos do Tribunal de Contas do Estado do Rio Grande do Sul (TCE-RS - Órgão `75101`).

---

## 🌐 Acesso Direto
- **URL do Painel:** [https://cmcb-labs.github.io/despesas/](https://cmcb-labs.github.io/despesas/)

---

## 💻 Código para Incorporação (Embed / Iframe)

### 1. Para o Card: "Despesas por Natureza da Despesa"
```html
<iframe 
  src="https://cmcb-labs.github.io/despesas/?view=natureza&embed=1&hide_header=1" 
  width="100%" 
  height="820" 
  frameborder="0" 
  style="border: none; width: 100%; min-height: 700px; display: block;">
</iframe>
```

### 2. Para o Card: "Movimentações Diárias / Execução Orçamentária"
```html
<iframe 
  src="https://cmcb-labs.github.io/despesas/?view=movimentacoes&embed=1&hide_header=1" 
  width="100%" 
  height="820" 
  frameborder="0" 
  style="border: none; width: 100%; min-height: 700px; display: block;">
</iframe>
```

### 3. Para página institucional própria (com cabeçalho completo)
```html
<iframe 
  src="https://cmcb-labs.github.io/despesas/?embed=1" 
  width="100%" 
  height="900" 
  frameborder="0" 
  style="border: none; width: 100%; min-height: 750px; display: block;">
</iframe>
```

---

## ⚙️ Parâmetros Suportados na URL

| Parâmetro | Valores Aceitos | Descrição |
| :--- | :--- | :--- |
| `embed` | `1` | Ativa o modo embutido com fundo transparente e ajuste para iframes. |
| `hide_header` | `1` | Oculta o cabeçalho superior (ideal quando inserido dentro do Plone). |
| `view` | `natureza`, `movimentacoes` | Seleciona a aba inicial exibida na interface. |
| `ano` | `2026`, `2025`, `2024`, `2023`, `2022` | Define o exercício orçamentário carregado por padrão. |
