# Planeamento E2 — Pastelaria Crumbly

## Contexto e estado

O projeto E1 já apresenta a pastelaria, o menu e os preços e a história fictícia, com identidade visual em creme, castanho e laranja. Para a E2 foram acrescentadas as páginas de contactos e acessibilidade, além de navegação comum para as cinco páginas e um formulário demonstrativo. As cinco páginas passaram no Nu Html Checker e as capturas E2 foram guardadas em `docs/evidencias/`.

O público-alvo previsto inclui famílias, estudantes, trabalhadores e pessoas da comunidade local que procuram pão, pastelaria, bolos, bebidas, informação de preços e formas de contacto. O sítio pretende apresentar a oferta, comunicar a identidade do estabelecimento fictício e facilitar a consulta em computadores e telemóveis.

## Etapa 1 — Análise

- **Objetivo:** compreender o projeto existente, o público e os requisitos da entrega.
- **Tarefas principais:** rever o conteúdo da E1, identificar páginas, imagens, ligações, estilos e requisitos em falta; considerar necessidades de navegação e acesso ao formulário.
- **Resultado esperado:** inventário do estado atual e lacunas que orientem a evolução, sem substituir o trabalho anterior.
- **Verificação:** comparar as páginas e documentação existentes com o enunciado e confirmar o estado do Git antes das alterações.
- **Estado:** realizada nesta preparação: três páginas E1, sete SVG locais, CSS externo responsivo, navegação inicial de três destinos e documentação E1 existente. Não foi encontrada documentação E2 anterior.

## Etapa 2 — Planeamento

- **Objetivo:** definir a organização e o âmbito do sítio com cinco páginas.
- **Tarefas principais:** organizar conteúdos em Início, Menu, Sobre nós, Contactos e Acessibilidade; manter navegação principal comum; definir um formulário com dados de contacto, assunto, preferência, interesses e mensagem; prever validação HTML5 e revisão responsiva.
- **Resultado esperado:** estrutura coerente, páginas interligadas e requisitos verificáveis por página.
- **Verificação:** confirmar que cada destino existe, que os títulos e conteúdos correspondem à navegação e que as tarefas estão representadas na checklist.
- **Estado:** estrutura aplicada ao sítio. A revisão por todo o grupo permanece por fazer.

## Etapa 3 — Desenho

- **Objetivo:** manter a identidade existente e apresentar conteúdos e controlos com hierarquia legível.
- **Tarefas principais:** conservar os tons creme, castanho e laranja, tipografia serifada, cartões e espaçamento do CSS; reutilizar o cabeçalho e rodapé; agrupar opções do formulário com `fieldset` e `legend`; prever foco visível e adaptação a ecrãs estreitos.
- **Resultado esperado:** páginas com aparência consistente e controlos compreensíveis em vários tamanhos de ecrã.
- **Verificação:** inspeção visual em computador e telemóvel, navegação por teclado e conferência dos estados de foco e contraste.
- **Estado:** estilos base e formulário responsivo implementados. A medição nos viewports de 320, 375, 700 e 1024 px não encontrou overflow horizontal; o foco visível de 3 px foi confirmado. Foram medidos rácios de 12,46:1 para texto principal, 6,61:1 para texto branco em controlos castanho-alaranjados e 6,26:1 para o foco sobre o fundo claro. Não foi feita auditoria completa com tecnologias de apoio.

## Etapa 4 — Implementação

- **Objetivo:** completar as páginas e demonstrar um formulário acessível com validação nativa.
- **Tarefas principais:** criar `contactos.html` e `acessibilidade.html`; atualizar navegação e rodapé nas cinco páginas; associar labels aos controlos; usar campos obrigatórios, `type="email"`, `type="tel"`, data, seleção, rádio, caixas de verificação e área de texto; aplicar `pattern` ao telefone; rever ligações, IDs e textos alternativos.
- **Resultado esperado:** cinco documentos HTML autónomos, sem dependências de servidor, com validação no navegador e sem alegar envio real.
- **Verificação:** inspeção estrutural e de caminhos, teste local de validação HTML5 no navegador e validação individual no Nu Html Checker.
- **Estado:** código implementado e formulário testado no navegador. Campos vazios foram rejeitados; email e telefone inválidos foram detetados; os campos preenchidos com valores válidos passaram. O Nu Html Checker vnu 26.10.18 não reportou erros nem avisos nas cinco páginas e foram guardadas capturas.

## Etapa 5 — Marketing

- **Objetivo:** definir formas realistas de dar a conhecer a pastelaria e o respetivo sítio.
- **Tarefas principais:** planear divulgação local através de cartazes e materiais no balcão, partilha do endereço nas redes sociais da pastelaria e comunicação de novidades sazonais; manter informações de menu e horário atualizadas.
- **Resultado esperado:** plano de divulgação adequado a um estabelecimento de bairro, com mensagens coerentes com a oferta e identidade.
- **Verificação:** rever se cada canal tem público e mensagem definidos e, numa fase futura, acompanhar visitas e interações com meios disponíveis.
- **Estado:** propostas planeadas neste documento; nenhuma campanha ou medição foi executada.

## Organização de conteúdo e navegação

| Página | Conteúdo principal | Ação/navegação |
|---|---|---|
| `index.html` | Apresentação, destaques e horário resumido | Acesso ao menu e à história |
| `menu.html` | Produtos, descrições e preços fictícios | Consulta da oferta |
| `sobre.html` | História fictícia, valores, localização e horário | Informação sobre a pastelaria |
| `contactos.html` | Formulário de contacto demonstrativo | Introdução e validação local dos dados |
| `acessibilidade.html` | Declaração inicial e medidas presentes | Informação sobre acessibilidade e ligação a contactos |

O formulário não tem servidor nem base de dados e não está ligado a um serviço de envio ou armazenamento. O padrão telefónico aceita um indicativo `+351` opcional e números móveis iniciados por 9 ou números fixos iniciados por 2, em grupos de nove algarismos, admitindo espaços entre os grupos.

## Revisão final e limitações

As cinco páginas foram verificadas individualmente no [Nu Html Checker](https://validator.w3.org/nu/) em 18-10-2026, sem erros nem avisos; as cinco capturas reais estão em `docs/evidencias/`. Os testes do formulário, ligações locais, layout em quatro larguras e foco visível foram realizados. Continua recomendada uma revisão humana com tecnologias de apoio, e a declaração de acessibilidade não afirma conformidade WCAG.
