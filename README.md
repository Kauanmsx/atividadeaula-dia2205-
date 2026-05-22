# 📌 JavaScript - EventListener

Projeto educacional para praticar o uso de `addEventListener` com diferentes eventos do DOM em JavaScript puro.

---

## 📁 Estrutura do projeto

```
projeto/
└── index.html   # Arquivo principal com HTML + CSS inline + JavaScript
```

---

## 🚀 Como executar

1. Baixe ou clone o repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Nenhuma instalação ou dependência necessária

---

## 🧠 Conceitos abordados

| Conceito | Descrição |
|---|---|
| `getElementById` | Seleciona elementos HTML pelo `id` |
| `addEventListener` | Associa funções a eventos do DOM |
| `mouseover` / `mouseout` | Detecta entrada e saída do mouse em um elemento |
| `keydown` | Detecta quando uma tecla é pressionada |
| `click` | Detecta clique em um elemento |
| `style.backgroundColor` | Altera a cor de fundo via JavaScript |
| `textContent` | Atualiza o conteúdo textual de um elemento |
| `event.key` | Retorna o nome da tecla pressionada |

---

## ⚙️ Funcionalidades

- **Botão "Clique aqui"**
  - Ao passar o mouse (`mouseover`): a caixa vermelha muda para **azul**
  - Ao tirar o mouse (`mouseout`): a caixa volta para **vermelho**
  - Ao clicar (`click`): exibe mensagem no console do navegador

- **Campo de texto**
  - Ao pressionar uma tecla (`keydown`): exibe a tecla pressionada no parágrafo abaixo do input

---

## ⚠️ Problemas conhecidos no código original

| # | Problema | Solução aplicada |
|---|---|---|
| 1 | `event` usado sem ser declarado como parâmetro | Usar `function(event)` |
| 2 | Duas atribuições seguidas em `texto` — a primeira nunca aparece | Manter apenas `texto.textContent = campo.value` |

---

## ✅ Boas práticas demonstradas

- Declarar todas as variáveis com `const` antes de usá-las
- Separar cada `addEventListener` por responsabilidade
- Usar `textContent` em vez de `innerHTML` quando o conteúdo é apenas texto
- Passar `event` explicitamente como parâmetro da função do listener

---

## 🛠️ Tecnologias utilizadas

- HTML5
- JavaScript (ES6+)
- CSS inline

---

## 📚 Referências

- [MDN - EventTarget.addEventListener](https://developer.mozilla.org/pt-BR/docs/Web/API/EventTarget/addEventListener)
- [MDN - KeyboardEvent.key](https://developer.mozilla.org/pt-BR/docs/Web/API/KeyboardEvent/key)
- [MDN - HTMLElement.style](https://developer.mozilla.org/pt-BR/docs/Web/API/HTMLElement/style)
