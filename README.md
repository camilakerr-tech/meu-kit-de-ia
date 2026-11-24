# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real

Escolhi o tratamento de uma demanda real da minha rotina na área de regulação em planos de saúde: analisar um gargalo nas reclamações de atraso em autorizações cirúrgicas/procedimentos (quando o prestador ainda está em análise contratual) e estruturar um e-mail inicial curto, informal e didático para propor uma melhoria de fluxo à coordenação.

A tarefa vale a pena porque hoje esses chamados caem por erro na Análise Técnica e são encerrados sem tratativa ("erro de abertura"), gerando rechamadas no teleatendimento e risco de NIPs por descumprimento dos prazos da ANS (RNs 566/2022 e 623/2024).

### Meus Atalhos

Utilizei primeiro um atalho próprio de **entrevista diagnóstica** (para a IA me ajudar a organizar o problema e elaborar a proposta-base) e, em seguida, adaptei apenas o **modelo de melhoria de texto da pasta `01-prompts`** (estrutura `CONTEXTO + INSTRUÇÃO + OBJETIVO + FORMATO + CONTEÚDO BASE`).

* **O que ficou fixo:** no primeiro atalho, a persona regulatória e a regra de fazer uma pergunta por vez; no modelo da pasta `01-prompts`, a estrutura de 5 blocos, meu papel na área de regulação e a instrução de revisão/reorganização.
* **O que muda a cada uso:** o gargalo tratado na entrevista, o destinatário, o objetivo específico da mensagem, o tom do e-mail e o `CONTEÚDO BASE` que entra para revisão.

```text
Assuma o perfil de um analista regulatório sênior em planos de saúde, que atue em análises de processos de análise e autorização de procedimentos cirúrgicos e exames de alta complexidade.
Seja direta e objetiva e me faça uma pergunta por vez para entendimento da demanda.

Demanda da vez: Reclamações de atraso em autorizações cirúrgicas envolvendo prestadores em análise contratual que são abertas por erro para a Análise Técnica e encerradas sem tratativa.

### Minha Delegação

```text
Objetivo: Estruturar uma proposta de melhoria no fluxo de reclamações sobre atraso em autorizações (prioridades cirúrgicas e procedimentos) com prestadores em análise contratual e transformar essa proposta em um e-mail inicial curto, informal e didático para apresentar a ideia à coordenação.

Contexto: Atuo como analista na área de regulação de uma operadora de planos de saúde, tratando reclamações oriundas do teleatendimento. Hoje, quando essas demandas são abertas por erro para a Análise Técnica, não há atuação médica possível sem prestador habilitado e o sistema não permite encaminhar o chamado à Gestão de Rede. Com isso, a demanda é encerrada por "erro de abertura", o beneficiário fica sem posicionamento até uma rechamada e aumenta o risco de NIPs por atraso e falha de informação (RNs 566/2022 e 623/2024 da ANS).

Recursos: Respostas fornecidas durante a entrevista diagnóstica (limitação do sistema, ausência de informação sobre o SLA atual da Gestão de Rede, viabilidade de contingência via Backoffice e responsabilidade da Gestão de Rede pela indicação de rede alternativa) + rascunho reorganizado no modelo de melhoria de texto da pasta 01-prompts.

Limites: Conduzir o levantamento fazendo uma pergunta por vez; não inventar SLAs internos inexistentes (deixar a definição dos prazos internos para validação posterior com a coordenação); manter linguagem objetiva, e-mail curto e sem repetições; e não expor nomes pessoais ou dados da empresa no texto final do desafio.

Sucesso: Ter um desenho de fluxo viável em duas frentes (curto prazo via Backoffice e médio prazo via ajuste sistêmico), com papéis definidos após o envio à Gestão de Rede (habilitado vs. não habilitado), e um e-mail inicial enxuto que permita à coordenação bater o olho e entender problema, impacto, solução e ganhos regulatórios.

### O Plano da IA

<img width="961" height="547" alt="image" src="https://github.com/user-attachments/assets/ce1876ea-122d-4c48-ab4e-ee951143b53f" />


Antes de partir para o texto final do e-mail, o plano foi construído em checkpoints (uma pergunta por vez na entrevista inicial), onde fiz os seguintes direcionamentos e ajustes de rota:

1. **Restrição real do sistema e da área:** esclareci que o encerramento ocorre porque não existe opção de envio à Gestão de Rede e a Análise Técnica não pode atuar sem prestador habilitado.
2. **Falta do SLA da Gestão de Rede:** informei que eu não possuía esse prazo médio, evitando que a IA inventasse um SLA e ajustando o plano para tratar a definição de prazos internos como uma etapa posterior de validação com a coordenação.
3. **Viabilidade e responsabilidade:** confirmei que tanto a contingência via Backoffice quanto o ajuste sistêmico eram viáveis e alinhei que, quando o prestador não está habilitado, a própria Gestão de Rede indica a rede credenciada ao beneficiário.
4. **Escopo do primeiro contato:** após ver a estrutura completa, pedi para a IA não enviar o detalhamento todo de imediato, mas sim resumir apenas ideia principal, motivo e finalidade em um e-mail curto (que depois refinei com o modelo de melhoria de texto da pasta `01-prompts`).

### O Resultado

<img width="925" height="397" alt="image" src="https://github.com/user-attachments/assets/a42f2db7-7584-4782-9223-87f2b4889101" />


Antes de considerar o e-mail pronto para envio, fiz a revisão seguindo o checklist **Pare, Confira, Use** (`03-checklists/01-pare-confira-use.md`):

* **Conferência de conteúdo e diagnóstico:** após gerar uma primeira versão no modelo de melhoria de texto (`01-prompts`), validei se nenhum ponto essencial da entrevista inicial havia ficado de fora — garantindo que ficasse claro que a Análise Técnica encerra hoje por impossibilidade técnica e sistêmica (sem prestador habilitado e sem opção de transferência), e não por falta de atuação da equipe.
* **Validação regulatória e de escopo:** conferi a coerência da menção às **RNs 566/2022 e 623/2024 da ANS**, ao risco real de **NIPs** por atraso e falta de clareza, e ajustei o texto para contemplar "cirurgias/procedimentos" (sem restringir o problema caso haja outros procedimentos no mesmo fluxo) e sem inventar prazos internos de SLA ainda não validados.
* **Ajuste de tamanho, tom e privacidade:** eliminei repetições para deixar o e-mail mais curto, informal e didático para leitura rápida da coordenação, e removi/ocultei nomes reais antes de documentar o resultado no repositório público.

### Como Foi para Você

O exercício mudou a forma como tiro problemas complexos da cabeça no dia a dia. Em vez de gastar tempo tentando estruturar sozinho uma proposta operacional e regulatória ou acabar mandando um e-mail longo demais para a coordenação, aprendi a usar a IA primeiro como entrevistadora para organizar minhas próprias ideias e depois aplicar um modelo pronto do kit (`01-prompts`) para calibrar o tom e o tamanho do texto. Na prática, ganhei agilidade e clareza na comunicação sem perder o controle técnico, a conferência dos fatos e a decisão final.
