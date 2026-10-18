# Checklist E2 — Planeamento e formulários

As cinco linhas abaixo resumem os requisitos da E2. Se a ficha da unidade curricular usar títulos diferentes, substituir os títulos pelos da ficha.

Estados: **Concluída**, **Pendente**, **Pendente de validação ou evidência**.

| Meta de trabalho | Estado | Situação/evidência |
|---|---|---|
| Planeamento das cinco etapas (análise, planeamento, desenho, implementação e marketing) | Concluída | O [plano E2](./planeamento-E2.md) apresenta objetivos, tarefas, resultados esperados e formas de verificação para cada etapa. |
| Sítio com cinco páginas, estrutura semântica e navegação comum | Concluída | As cinco páginas passaram no Nu Html Checker vnu 26.10.18, sem erros nem avisos. |
| Formulário acessível com os controlos pedidos e validação nativa | Concluída | O navegador bloqueou o formulário vazio e detetou email e telefone inválidos. Com os campos válidos, a validação passou. |
| CSS coerente, responsivo e informação inicial de acessibilidade | Concluída | A 320, 375, 700 e 1024 px não houve deslocamento horizontal. O foco tem contorno visível de 3 px. A declaração não afirma conformidade WCAG. |
| Validação HTML oficial sem erros e cinco capturas Nu Html Checker | Concluída | As cinco capturas dos resultados estão em `docs/evidencias/` com o prefixo `w3c-E2-`. |

## Passos de verificação

1. Cada página foi verificada separadamente no Nu Html Checker. Os cinco resultados e respetivas capturas estão guardados em `docs/evidencias/`.
2. O formulário foi experimentado no navegador com campos vazios, email inválido, telefone fora do formato e dados válidos.
3. As cinco páginas foram abertas em larguras de 320, 375, 700 e 1024 px. Não houve deslocamento horizontal. O foco foi confirmado numa ligação de navegação. Ainda não foi feita uma revisão completa com tecnologias de apoio.
