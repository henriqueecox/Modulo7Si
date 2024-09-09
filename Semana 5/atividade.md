# Cutover Semana 5 Henrique Cox

O documento refere-se a um Plano de Cutover específico para um projeto de implementação de SAP. Ele descreve as atividades necessárias para a transição de sistemas legados para o ambiente de produção SAP, seguindo as fases da metodologia SAP Activate. O principal objetivo deste plano é garantir que a migração de dados, funcionalidades e sistemas ocorra de forma ordenada e sem falhas, minimizando o impacto no ambiente de produção.

## Os principais elementos do plano são:

- **Estratégia de Cutover**: Define o tipo de migração (Big bang ou faseada), as sequências de atividades e o uso ou não de sistemas paralelos com o legado.
- **Cronograma de Cutover**: Um cronograma detalhado com fases importantes, como a preparação do ambiente de produção, a migração de dados e a execução de processos chave antes e depois do Go Live.

<div style="text-align: center; margin: 20px 0;">
  <img src=".\Semana 5\Captura de tela 2024-09-08 160533.png" alt="print 1" style="width: 80%; border: 1px solid #ccc;" />
  <p style="font-style: italic;"></p>
</div>

- **Critérios de Aceitação do Go Live**: Define as métricas e condições que devem ser atingidas para que o Go Live seja considerado bem-sucedido, como níveis aceitáveis de testes de integração e carga de dados.
- **Organização e Responsabilidades**: Claramente define os papéis e responsabilidades das equipes envolvidas, como o Gerente de Cutover, Equipe de Migração de Dados, Coordenadores de Site, e Usuários Chave.

<div style="text-align: center; margin: 20px 0;">
  <img src="Semana 5\Captura de tela 2024-09-08 160657.png" alt="print 2" style="width: 80%; border: 1px solid #ccc;" />
  <p style="font-style: italic;"></p>
</div>

- **Simulações de Cutover**: Testes realizados antes da migração para garantir que todos os sistemas e processos estão funcionando como deveriam.
- **Plano de Contingência**: Preparação para lidar com problemas inesperados, incluindo restauração do sistema legado e pontos de decisão para avançar ou não com o Cutover.

<div style="text-align: center; margin: 20px 0;">
  <img src="Semana 5\Captura de tela 2024-09-08 160810.png" alt="print 3" style="width: 80%; border: 1px solid #ccc;" />
  <p style="font-style: italic;"></p>
</div>

- **Suporte de Implementação (Hyper Care)**: Um período de suporte intensivo pós-Go Live, para garantir que possíveis problemas sejam resolvidos rapidamente, seguido da transição para o suporte a longo prazo.

## Pontos positivos e negativos

### Pontos positivos:
- **Planejamento detalhado**: O documento possui um cronograma bem montado e detalhado, o que facilita o acompanhamento das atividades e garante a realização e entrega das atividades com mais qualidade.
- **Critérios de aceitação claros**: A definição dos critérios específicos de aceitação garante que as metas do projeto sejam atingidas antes de prosseguir com o Go Live, aumentando a segurança e a confiança no processo.
- **Plano de contingência**: A inclusão de um plano de contingência ajuda a mitigar riscos, garantindo que problemas inesperados possam ser resolvidos sem grandes impactos no projeto.

### Pontos negativos:
- **Foco exclusivo no SAP**: Embora o plano seja eficiente, ele é altamente específico para implementações SAP, o que limita suas aplicações em outros contextos ou sistemas ERP.
- **Dependência de múltiplas equipes**: A complexidade da organização e divisão de responsabilidades pode acabar virando uma complicação para times menores, onde há menos recursos disponíveis para gerenciamento e revisão dos passos do projeto.
- **Exigência de simulações frequentes**: Mesmo que as simulações sejam importantes, elas consomem muito tempo e recursos, o que pode ser ruim para empresas com cronogramas apertados ou restrições de orçamento.
