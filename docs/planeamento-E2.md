# Planeamento E2 — Pastelaria Pão Quente

## Contexto e estado

O projeto E1 já apresenta a pastelaria, o menu e os preços e a história fictícia, com identidade visual em creme, castanho e laranja. Para a E2 foram acrescentadas as páginas de contactos e acessibilidade, além de navegação comum para as cinco páginas e um formulário demonstrativo. A validação oficial das cinco páginas após estas alterações e as respetivas capturas continuam por realizar.

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
- **Estado:** estilos base e formulário responsivo implementados. A verificação visual com diferentes dispositivos e tecnologias de apoio ainda está planeada.

## Etapa 4 — Implementação

- **Objetivo:** completar as páginas e demonstrar um formulário acessível com validação nativa.
- **Tarefas principais:** criar `contactos.html` e `acessibilidade.html`; atualizar navegação e rodapé nas cinco páginas; associar labels aos controlos; usar campos obrigatórios, `type="email"`, `type="tel"`, data, seleção, rádio, caixas de verificação e área de texto; aplicar `pattern` ao telefone; rever ligações, IDs e textos alternativos.
- **Resultado esperado:** cinco documentos HTML autónomos, sem dependências de servidor, com validação no navegador e sem alegar envio real.
- **Verificação:** inspeção estrutural e de caminhos, teste local de validação HTML5 no navegador e validação individual no Nu Html Checker.
- **Estado:** código implementado. Os testes manuais do formulário e validação oficial após as alterações ainda estão pendentes.

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

O formulário não tem servidor nem base de dados: a submissão não envia nem guarda dados. O padrão telefónico aceita um indicativo `+351` opcional e números móveis iniciados por 9 ou números fixos iniciados por 2, em grupos de nove algarismos, admitindo espaços entre os grupos.

## Revisão e evidências por completar

Validar separadamente as cinco páginas no [Nu Html Checker](https://validator.w3.org/nu/), corrigir todos os erros e guardar capturas reais em `docs/evidencias/`. Testar formulário vazio, email inválido, telefone fora do padrão e preenchimento válido. Rever links, teclado, foco e apresentação em ecrã pequeno. Nenhuma validação ou captura referente às alterações E2 é declarada como concluída neste documento.
