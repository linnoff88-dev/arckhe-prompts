# Histórico — Reorganizaçêo do Projeto (2025-10-23)

Responsável: bmad-orchestrator

## Objetivos
- Reorganizar o repositório de Engenharia de Prompts mantendo o acervo.
- Limpar definições antigas de navegaçêo e criar a nova seçêo de Educaçêo com trilhas.
- Preparar base para enviar recursos depois.

## Decisões
- `mkdocs.yml` aponta para `docs/` e traz novo menu (Educaçêo → Trilhas, Módulos, Acervo, Exercícios).
- Dados legados do acervo permanecem em `docs/data/` (referência histórica).
- Diretórios de build serêo movidos para `archive/` (nêo-destrutivo).

## Mudanças aplicadas
- Atualizado: `mkdocs.yml` (docs_dir, nav e rótulos).
- Criado: `docs/educacao/index.md` e trilhas (`fundamentos.md`, `tecnicas.md`, `avancado-masterclass.md`).
- Criado: `docs/exercicios/index.md`.
- Reescrito: `README.md` com estrutura e próximos passos.
- Correçêo em massa: links dos módulos para acervo trocados de `(data/...)` para `(../data/...)`.

## Próximos passos sugeridos
- Completar a página de Exercícios com listas por trilha/módulo e templates.
- Opcional: adicionar índice navegável do acervo e busca contextual.
- Validar build local (`mkdocs build`) e ativar Pages no repositório.

