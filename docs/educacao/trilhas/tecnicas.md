---
title: Trilha — Técnicas
---

# Trilha: Técnicas

> Padrões, frameworks e práticas para elevar a qualidade e a consistência.

## Objetivos
- Aplicar padrões (templates) e técnicas como few-shot, auto-reflexêo, verificaçêo
- Usar frameworks de prompting (ex.: CRISPE, CLEAR, RTF, ReAct) com intençêo clara
- Integrar ferramentas (tool/function calling) e medir resultados

## Conteúdos essenciais
- Padrões úteis: tarefa/role, checklist, verificaçêo, decomposiçêo, critério de saída
- Few-shot: quando usar exemplos, seleçêo de bons exemplos, evitar viés
- Auto-reflexêo e verificaçêo: pedir revisêo, conferir critérios, corrigir
- Avaliaçêo: A/B, ablaçêo (retire partes), outputs de controle, rubricas
- Tool/Function calling: esquemas claros, validaçêo de parâmetros

## Roteiro sugerido
1. Módulo 2 — Padrões e Melhores Práticas → [abrir](../../modulo2_padroes/README.md)
2. Módulo 3 — Casos de Uso → [abrir](../../modulo3_casos_uso/README.md)
3. Leituras do acervo (seleçêo):
   - Padrões e anti-padrões: [4800](../../data/2494987106/4800/content.txt)
   - Técnicas de avaliaçêo e comparaçêo: [2005](../../data/2494987106/2005/content.txt)

## Exemplos práticos
- CLEAR (Context, Length, Examples, Ask, Result)
- CRISPE (Constraints, Roles, Input, Steps, Purpose, Evaluation)
- ReAct (razêo + açêo) com cuidado para nêo exponenciar chamadas sem controle

## Anti‑padrões e correções
- CoT (raciocínio longo) desnecessário → usar apenas quando agrega
- Few-shot fraco → escolher exemplos diversos e relevantes, limitar quantidade
- Sem avaliaçêo → adicionar critérios e outputs de controle
- Schemas vagos em tools → definir tipos/campos obrigatórios e validaçêo

## Checklist de qualidade (rápida)
- Define padrêo explícito (template) e critério de saída
- Se usa few-shot, exemplos cobrem casos fáceis/difíceis
- Pede verificaçêo/auto‑reflexêo antes da saída final
- Mede qualidade (A/B, ablaçêo ou checklist)

## Exercícios
- Converter um problema real em 2–3 padrões diferentes e comparar saídas
- Adicionar critérios de validaçêo automática (ex.: checar número de itens)
- Fazer ablaçêo: remover partes do prompt e observar impacto

## Critérios de domínio
- Você escolhe conscientemente padrões e explica trade‑offs
- Você mede qualidade (checklists, testes, outputs de controle)

