# Arkhen

**Automação do trabalho em agências de marketing, com agentes de IA e decisões rastreáveis.**

Proposta para o **Hack Brasil 2026** · **MVP em desenvolvimento**

**Enquadramento proposto: Logística & automação.**

## A proposta para o Hack Brasil

O Arkhen propõe automatizar o fluxo de trabalho entre dados, análise, decisão e acompanhamento em agências de marketing brasileiras. O público inicial é o gestor de contas, que precisa coordenar a operação de vários clientes e manter visibilidade sobre o que exige atenção, quem decide e quem executa.

O foco da proposta é a movimentação de informação e trabalho: integrar sistemas, organizar prioridades e encaminhar ações entre pessoas e agentes especializados. Esse recorte se relaciona à trilha **Logística & automação**, que contempla integrações entre sistemas e automação de fluxos de trabalho no [regulamento do Hack Brasil, item 5.2](https://hackbrasil.com/regulamento).

## O problema

Na operação de uma agência, informações de anúncios, navegação, planilhas e resultados comerciais precisam circular entre ferramentas e profissionais. Para uma equipe que atende vários clientes, reunir essas informações e manter o trabalho coordenado exige esforço recorrente.

O gestor de contas precisa reunir os dados, entender o que mudou, priorizar problemas e coordenar a execução. Uma campanha pode continuar consumindo orçamento enquanto um sinal de queda de eficiência passa despercebido. E uma boa análise pode terminar em um relatório sem virar uma ação acompanhada.

O problema central é a distância entre detectar uma situação e encaminhar uma resposta: dados sem contexto, análises sem responsável e tarefas sem acompanhamento.

## A solução

O **Arkhen** é uma plataforma de colaboração entre pessoas e agentes de IA para a operação de agências de marketing. Sua proposta é conectar fontes de dados, análise de performance e gestão de tarefas em um mesmo fluxo de trabalho.

O objetivo é reduzir a necessidade de transportar informações manualmente entre ferramentas e transformar cada achado relevante em um próximo passo claro, com contexto, responsável e critérios de aprovação.

O MVP tem foco inicial na operação de **mídia paga**. A conexão entre investimento em marketing e resultado comercial orienta a visão de evolução do produto.

## Conheça a Luna

A **Luna** é a interface de inteligência do Arkhen. Por meio de uma conversa, o gestor pode consultar informações, explorar análises e acompanhar tarefas no contexto de cada cliente.

Na visão do produto, ela também coordena agentes especializados e interpreta os achados técnicos em linguagem de negócio. Uma variação no custo por lead, por exemplo, precisa vir acompanhada de contexto: qual campanha mudou, como isso afeta a captação e qual decisão merece atenção.

Seu papel é apresentar evidências, explicar recomendações e deixar claro o que depende de uma decisão humana.

## Como funciona

1. **Reunir dados:** conectar informações de mídia e comportamento digital, com fontes como Meta Ads, Google Ads, Google Analytics e planilhas.
2. **Analisar o contexto:** relacionar indicadores ao histórico, às metas e às características de cada cliente.
3. **Priorizar:** identificar desvios, riscos e oportunidades que merecem investigação ou ação.
4. **Encaminhar o trabalho:** transformar ações em tarefas acompanhadas em um Kanban, com responsável e aprovação definidos.
5. **Acompanhar o desfecho:** consultar o andamento e registrar o resultado das tarefas, com a Luna explicando o contexto das decisões.

### Um exemplo de uso

Um gestor começa o dia com várias contas para acompanhar. Em um cenário de uso proposto, um agente identifica uma queda de eficiência na captação de um cliente. A Luna apresenta o contexto, e a ação recomendada é encaminhada para uma tarefa com responsável e aprovação definidos.

O gestor consulta a análise, toma a decisão que lhe cabe e acompanha o andamento no mesmo ambiente. Esse fluxo busca reduzir repasses manuais e permitir que a equipe acompanhe a passagem do diagnóstico para a execução.

## Autonomia com governança

O modelo de governança proposto para o Arkhen define quem pode autorizar cada ação, considerando fatores como impacto, reversibilidade e confiança da análise.

| Nível | Quem autoriza | Papel no fluxo proposto |
| --- | --- | --- |
| **1 — Regras predefinidas** | Regras do playbook | Permitir ao agente especialista executar ações dentro de limites aprovados. |
| **2 — Avaliação da Luna** | Luna | Avaliar o mérito de ações que exigem julgamento adicional. |
| **3 — Decisão humana** | Gestor de contas | Autorizar decisões estratégicas ou que exijam responsabilidade humana. |

Nesse modelo, a execução sobre as contas fica com os agentes especializados. A Luna coordena e autoriza dentro de seu papel; o gestor mantém a autoridade sobre as decisões que cabem a ele.

## Diferenciais da proposta

- **Contexto por cliente:** considerar metas, histórico e conhecimento do negócio na interpretação dos dados.
- **Análise ligada ao trabalho:** conectar achados a tarefas, responsáveis e acompanhamento.
- **Cálculo separado da interpretação:** usar código para calcular métricas e IA para contextualizar e explicar os resultados.
- **Visão da carteira:** ajudar o gestor a priorizar a atenção entre vários clientes.
- **Decisões rastreáveis:** tornar visíveis as recomendações, aprovações e ações do fluxo.

## Impacto esperado

Para agências brasileiras que precisam coordenar várias contas com equipes enxutas, a proposta é diminuir o esforço de consolidação de dados e de repasse de tarefas, melhorar a visibilidade das prioridades e liberar tempo para decisões estratégicas e relacionamento com os clientes.

A validação desse impacto deve observar:

- Tempo necessário para reunir informações e identificar as prioridades de uma carteira.
- Tempo entre um achado relevante e seu encaminhamento para um responsável.
- Proporção de tarefas com contexto, responsável e resultado registrados.

Essas são medidas propostas para validação, sem ganhos quantitativos comprovados nesta apresentação.

## Recorte do MVP e evolução

O projeto reúne frentes de acompanhamento de performance, chat com a Luna, tarefas, análises e base de conhecimento por cliente. O recorte proposto para o evento prioriza o fluxo **dados → análise → tarefa → aprovação → acompanhamento**. A implementação e a validação dos fluxos de autonomia e das integrações continuam em desenvolvimento.

A visão de evolução inclui ampliar a conexão com dados comerciais de CRM e ERP, aproximando a leitura de mídia da receita real, além de incorporar outras especialidades de marketing.
