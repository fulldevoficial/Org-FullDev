# Estrategia do Discord da FullDev

Este documento registra a estrategia para o Discord da FullDev como rede a parte, com proposito proprio, cadencia viva e estrutura de moderacao e tecnologia que sustente o movimento.

## Por que o Discord precisa de estrategia propria

Discord nao e duplicacao do WhatsApp. E uma rede com logica diferente:

- WhatsApp e o canal de avisos, networking informal e moderacao reativa.
- Discord precisa ser um espaco de **convivencia tecnica e ritual**, com cargos, canais segmentados, voz, video, bots, gravacoes e historico pesquisavel.

Sem proposito claro, qualquer servidor de Discord vira chat morto - e chat morto e pior do que nao ter Discord, porque transmite a sensacao de que a comunidade nao se sustenta.

## Posicionamento: o Discord como lar tecnico da FullDev

A proposta e posicionar o Discord como **o lar tecnico da FullDev**:

- Espaco de estudo, pair programming, code review e duvidas tecnicas.
- Casa das aulas e atividades ao vivo da FullDev School.
- Canal de AMAs, papo com convidados, sessoes com parceiros tecnicos.
- Local de calls abertas (noite de estudo, cafe tecnico, dojo).
- Repositorio de cargos por interesse (back, front, data, mobile, devops, design, carreira).

Isso diferencia explicitamente Discord (lar tecnico) de WhatsApp (avisos + networking informal). O membro precisa saber por que vale entrar.

## Tres frentes que precisam andar juntas

Discord so se sustenta se essas tres frentes operarem em conjunto. Falhou uma, o servidor esfria.

### 1. Rituais recorrentes (cadencia viva)

Sem agenda fixa, Discord nao anda. A proposta inicial de rituais:

- **Noite de estudo semanal** (call aberta, dia fixo): membros entram para estudar em conjunto, com camera ligada opcional. Sem palestra - so presenca.
- **Cafe tecnico quinzenal** (call de 30-45min): tema da semana, papo aberto, sem slide. Host rotativo entre membros da comunidade.
- **Sala aberta durante aulas da School**: canal de voz e texto dedicado em paralelo a transmissao do YouTube para duvidas e interacao ao vivo.
- **AMA mensal com convidado**: dev/empresa parceira responde duvidas da comunidade ao vivo. Gravacao publicada depois.
- **Dojo / pair programming sob demanda**: agendado quando alguem propoe um problema ou exercicio.
- **Show & Tell trimestral**: membros apresentam projetos pessoais em 5min, com feedback da comunidade.

Cada ritual precisa de:

- Dia e horario fixos (ou previsiveis).
- Responsavel pela execucao.
- Checklist minimo (canal criado, divulgacao, gravacao quando aplicavel).
- Lembrete automatico via bot na vespera e no dia.

### 2. Time de moderacao ampliado

Joao e o responsavel oficial pelo Discord, mas nao consegue sustentar a rede sozinho. A proposta:

- **Pool de 2-3 mods adicionais**, rotativos, recrutados entre os proprios membros mais engajados.
- **Criterios de promocao a mod**: tempo de presenca, historico positivo, alinhamento com codigo de conduta, disponibilidade minima e indicacao do owner do Discord (Joao).
- **Rotina dos mods**: revisar canais com baixo movimento, aplicar codigo de conduta, acolher novos entrantes, registrar incidentes e propor ajustes de estrutura.
- **Encontro mensal de mods** (call de 30min) para alinhar moderacao e propor melhorias.

Esse time amplia o "olho" no servidor e cria sucessao - se Joao precisar sair temporariamente, o Discord continua.

### 3. Automacao e integracao (Tecnico / Plataforma)

Carlos, como Tech Advisor, lidera a camada tecnica do Discord. Pontos minimos:

- **Boas-vindas automatica** com bot: mensagem padrao, regras, link para canais principais e atribuicao de cargo inicial.
- **Self-assign de cargos por interesse**: bot que permite ao membro escolher cargos (back, front, data, mobile, devops, design, carreira, eventos). Permite mencionar grupos especificos sem usar @everyone.
- **Lembretes de eventos**: bot anuncia rituais recorrentes na vespera e no dia, no canal certo, mencionando o cargo correspondente.
- **Integracao com School**: canal dedicado por trilha, com permissoes por turma; gravacao das aulas linkada apos a sessao.
- **Integracao com pagina de links**: o Discord aparece como porta de entrada na pagina oficial, e a pagina aparece em destaque no canal de boas-vindas.
- **Sincronizacao com calendario**: rituais recorrentes alimentam um calendario publico (Google Calendar ou similar) consultavel pelo membro.

Essa camada e o que diferencia "ter um servidor" de "ter uma comunidade viva no servidor".

## Estrutura sugerida de canais

Base inicial, ajustavel pelo time de moderacao:

- **Boas-vindas e regras**
  - boas-vindas, regras, codigo-de-conduta, escolha-de-cargos.
- **Conversa geral**
  - geral, off-topic, vagas-e-oportunidades.
- **Areas tecnicas** (com cargo correspondente para mention)
  - back-end, front-end, mobile, data, devops, design, carreira, ia.
- **Estudo e pratica**
  - duvidas, code-review, projetos-pessoais, pair-programming.
- **FullDev School**
  - aulas-ao-vivo, trilha-back, trilha-front, certificados, suporte-aluno.
- **Eventos e rituais**
  - calendario, noite-de-estudo, cafe-tecnico, ama, show-and-tell.
- **Voz**
  - lounge, sala-de-estudo, sala-de-aula, sala-de-evento.
- **Moderacao** (privado)
  - mods, incidentes, ajustes.

## Como o Discord se correlaciona com as outras frentes

- **Comunidade WhatsApp:** divulga rituais do Discord e leva membros engajados para la. Mods de WhatsApp e Discord trocam contexto via grupo do Nucleo Operacional.
- **Comunicacao e Marca:** divulga rituais nos canais publicos, prepara material para AMAs e mantem tom institucional.
- **FullDev School:** usa o Discord como sala de aula viva (canal de voz + canal de duvidas) e como repositorio de gravacoes e materiais.
- **Tecnico / Plataforma (Carlos):** sustenta bots, automacoes, integracoes e seguranca do servidor.
- **Eventos:** rituais recorrentes do Discord aparecem no calendario geral; eventos externos da FullDev tem canal de cobertura no Discord.
- **Conselho Central:** Joao reporta indicadores e propoe mudancas estruturais. Decisoes que impactam marca, regras ou novos canais oficiais passam pelo Conselho.

## Indicadores minimos para acompanhar

- Membros ativos por semana (mensagem ou voz).
- Numero de calls realizadas no mes (por ritual).
- Tempo medio em voz por semana.
- Taxa de retencao de novos membros em 30 dias.
- Numero de incidentes de moderacao por mes.
- Cargos atribuidos por interesse (mapeamento da audiencia).

Operacoes (Hernando) consolida o relatorio mensal junto com Joao.

## Proximos passos

1. **Validar posicionamento** (Discord como lar tecnico) com o Conselho.
2. **Definir o primeiro ritual** (sugestao: noite de estudo semanal) e rodar por 4 semanas para testar cadencia.
3. **Recrutar 2 mods adicionais** entre os membros mais engajados.
4. **Configurar boas-vindas e self-assign de cargos** com Carlos.
5. **Definir indicadores e responsavel pelo relatorio mensal**.
6. **Reavaliar em 60 dias** se a estrategia esta sustentando movimento ou precisa pivotar.

## Risco principal

Lancar estrutura sem cadencia. Se os rituais nao acontecerem nas primeiras semanas, o servidor reforca a percepcao de "Discord da FullDev e morto" - e recuperar dai e mais caro do que comecar do zero.

Por isso a recomendacao e iniciar com **um unico ritual semanal funcionando de verdade**, antes de abrir todos os outros canais e eventos.
