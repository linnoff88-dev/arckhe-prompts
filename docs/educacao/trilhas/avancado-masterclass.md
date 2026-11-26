---
title: Trilha — Avançado (Masterclass)
---

# Trilha: Avançado (Masterclass)

> Agentes, memória, RAG, automaçêo com ferramentas e projetos completos.

## Objetivos
- Projetar assistentes com memória e recuperaçêo (RAG) de forma responsável
- Orquestrar ferramentas (APIs/funções) e fluxos multi‑etapas
- Entregar projetos aplicados com avaliaçêo e guardrails

## Roteiro sugerido
1. Módulo 4 — Assistentes, Memória e RAG → [abrir](../../modulo4_assistentes_memoria/README.md)
2. Módulo 5 — Automaçêo e Ferramentas → [abrir](../../modulo5_automacao_ferramentas/README.md)
3. Módulo 6 — Projetos Finais → [abrir](../../modulo6_projetos_finais/README.md)
4. Leituras do acervo (seleçêo):
   - RAG prático e pitfalls: [2062](../../data/2494987106/2062/content.txt)
   - Agentes e tool use avançado: [1973](../../data/2494987106/1973/content.txt)

## Exercícios
- Crie um mini‑agente com memória curta + busca no acervo
- Defina métricas de sucesso e riscos/mitigações

## Critérios de domínio
- Você compõe fluxos com ferramentas e monitora qualidade e segurança
- Você entrega um projeto final utilizável e documentado

---

## Currículo sugerido (masterclass)
- Semana 1: Fundamentos de agentes, limites e responsabilidades; persona e objetivos
- Semana 2: Memória e RAG prático (curadoria, chunking, recuperaçêo, citações)
- Semana 3: Ferramentas e orquestraçêo (APIs, Tool/Function Calling, multi‑etapas)
- Semana 4: Observabilidade e segurança (métricas, logs, guardrails, red teaming leve)
- Semana 5: Projeto final (planejamento, execuçêo, avaliaçêo, publicaçêo)

## Guardrails e verificaçêo
- Defina limites claros (escopo, fontes permitidas, proibições)
- Use “verificaçêo” antes da resposta final (checar critérios e segurança)
- Logue entradas/saídas sensíveis; audite amostras regularmente

## Tool/Function calling (exemplo de schema)
```
{
  "name": "buscar_documento",
  "description": "Busca documento por ID no acervo",
  "parameters": {
    "type": "object",
    "properties": { "id": {"type": "integer"} },
    "required": ["id"]
  }
}
```

## RAG — do's e don'ts
- Do: curadoria das fontes, chunking consistente, citações de trechos usados
- Do: prompt de recuperaçêo separado do prompt de resposta
- Don’t: confiar cegamente na recuperaçêo; trate falhas (sem resultados)

## Segurança e riscos
- Evitar vazamentos (nêo retornar segredos; redigir dados sensíveis)
- Prevenir jailbreaks com instruções e validaçêo de saída
- Matriz de risco leve: probabilidade × impacto + mitigaçêo

## Checklist do projeto
- Escopo e objetivo mensurável definidos
- Arquitetura do agente (componentes, fontes, ferramentas) descrita
- Prompts versionados e documentados (critérios de saída, exemplos, testes)
- Métricas de qualidade e segurança com plano de monitoramento
- Evidências de teste (casos fáceis/difíceis) e iterações

## Entregáveis
- Documento de arquitetura do agente (1–2 págs.)
- Repositório com prompts e scripts de avaliaçêo (se aplicável)
- Relatório de resultados (tabelas/prints) e lições aprendidas

## Rubrica de avaliaçêo
- Clareza de objetivo e métrica: 20%
- Arquitetura e justificativas técnicas: 30%
- Qualidade dos prompts e avaliações: 30%
- Documentaçêo e comunicaçêo: 20%

## Template de arquitetura (exemplo)
```
Nome do Agente: __________
Objetivo + Métrica (KPI): __________

Componentes:
- Entrada/Interface: __________
- Memória / RAG (fontes e indexaçêo): __________
- Ferramentas/APIs: __________
- Regras/Guardrails: __________

Prompts principais:
- Sistema: __________
- Tarefas/Fluxos: __________

Avaliaçêo:
- Casos de teste: __________
- Critérios de qualidade: __________
- Riscos/Mitigações: __________
```

