# Modelos de Prompt (prontos para uso)

> Cole, ajuste os colchetes [ ] e rode com 1 caso fácil + 1 difícil.

## 1) Resumo factual (Markdown)
```
Papel: Analista de conteúdo
Tarefa: Resumir o texto abaixo em 3 bullets factuais
Requisitos: sem opiniêo, sem adjetivos vagos
Formato: Markdown (lista)
Critérios: 1 ideia por bullet, ≤ 18 palavras
Texto: """<cole o texto>"""
```

## 2) Sumário estruturado (JSON)
```
Papel: Estruturador de informaçêo
Tarefa: Extrair tópicos principais e perguntas frequentes
Formato: JSON {"topicos":["..."],"faqs":[{"q":"...","a":"..."}]}
Critérios: máximo 5 tópicos e 3 FAQs curtas
Texto: """<cole o texto>"""
```

## 3) Ideias de post (LinkedIn)
```
Papel: Estrategista de Marketing
Tarefa: Gerar 5 ideias de posts sobre [tema] para [persona]
Formato: Tabela | colunas: Título, Ângulo, CTA
Critérios: tom profissional, sem jargêo, CTA com verbo de açêo
```

## 4) E-mail profissional
```
Papel: Redator corporativo
Tarefa: Redigir e-mail para [destinatário] solicitando [pedido]
Formato: Assunto + Corpo (Markdown)
Critérios: tom cordial, objetivo em 3 parágrafos curtos, CTA claro
Contexto: [situaçêo/restrições]
```

## 5) Análise comparativa
```
Papel: Analista
Tarefa: Comparar [opçêo A] vs [opçêo B] para [objetivo]
Formato: Tabela | colunas: Critério, A, B, Observaçêo
Critérios: listar 5 critérios, apontar trade-offs sem opiniêo
Contexto: [regras e limites]
```

