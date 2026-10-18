# Checklist E2 — Planeamento e formulários

> O enunciado fornecido descreve os requisitos, mas não inclui a formulação literal das cinco metas oficiais. Os cinco itens abaixo são agrupamentos de trabalho derivados desse enunciado; confirmar os títulos oficiais com a ficha da unidade curricular antes da entrega.

Estados: **Concluída**, **Pendente**, **Pendente de validação ou evidência**.

| Meta de trabalho | Estado | Situação/evidência |
|---|---|---|
| Planeamento das cinco etapas (análise, planeamento, desenho, implementação e marketing) | Concluída | `docs/planeamento-E2.md` distingue trabalho realizado de trabalho futuro. Rever em grupo. |
| Sítio com cinco páginas, estrutura semântica e navegação comum | Concluída | Cinco páginas carregadas individualmente no Nu Html Checker vnu 26.10.18; cada uma sem erros nem avisos. |
| Formulário acessível com os controlos pedidos e validação nativa | Concluída | Teste de validade no navegador: vazio inválido; email e telefone inválidos detetados; todos os campos preenchidos com valores válidos aceites. |
| CSS coerente, responsivo e informação inicial de acessibilidade | Pendente de validação ou evidência | CSS e declaração implementados; falta revisão visual em tamanhos/dispositivos distintos, teclado e tecnologia de apoio. |
| Validação HTML oficial sem erros e cinco capturas Nu Html Checker | Pendente de validação ou evidência | Validação oficial concluída sem erros nem avisos para as cinco páginas; faltam guardar cinco capturas reais em `docs/evidencias/`. |

## Passos de verificação

1. Abrir individualmente `index.html`, `menu.html`, `sobre.html`, `contactos.html` e `acessibilidade.html` em `https://validator.w3.org/nu/`.
2. Corrigir erros e avisos relevantes, voltar a validar e guardar uma captura real por página em `docs/evidencias/`.
3. No navegador, tentar submeter o formulário vazio, usar email inválido, testar telefone fora do padrão e preencher todos os campos com dados válidos. Confirmar que a mensagem do navegador é nativa e que o projeto não afirma enviar os dados.
4. Rever navegação por teclado, foco, layout estreito e descrição das imagens; atualizar os estados desta lista com os resultados reais.
