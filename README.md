# Detalhamento do Projeto
## Tema principal do desafio:
Plataforma de Apoio à Concorrência Pública para MEIs (Lei nº 14.133/2021)

## Área / Domínio:
Negócios / Mercado

## Contexto e Problema:
Aqui está o formulário completo para o novo desafio "Plataforma de Apoio à Concorrência Pública para MEIs (Lei nº 14.133/2021)", estruturado identicamente aos anteriores. As respostas incorporam detalhes da Nova Lei de Licitações, benefícios para MEIs (ex.: preferência em até 10% e licitações exclusivas até R$80k) e foco em Recife-PE, com viés pedagógico para turmas.

## Problema central a ser resolvido:
Dificuldade de acesso centralizado a oportunidades de licitações, interpretação de requisitos e organização de propostas, impedindo MEIs de competir efetivamente apesar dos incentivos legais.

#### Referências, dados, leis ou políticas públicas:
Lei nº 14.133/2021 - Nova Lei de Licitações e Contratos Administrativos.

## Objetivo da solução:
Democratizar a participação de MEIs em licitações, aumentando propostas submetidas em 50% e taxa de vitórias via centralização de editais e checklists, gerando impacto econômico local e conformidade com a Lei 14.133/2021.

## Descrição da solução proposta:
Aplicativo mobile multiplataforma desenvolvido com React Native e Expo para apoiar MEIs na busca de editais, interpretação de requisitos e organização de propostas. O app terá foco em experiência mobile-first, navegação por abas e pilhas, autenticação, armazenamento local para persistência de dados essenciais, integração com APIs backend e envio de notificações para alertas de prazos e oportunidades. Usuários principais são MEIs e donos de microempresas. A solução deverá contemplar fluxos reais de uso em smartphone, como onboarding, pesquisa de editais, checklist de habilitação, acompanhamento de prazos, upload/visualização de documentos e dashboard simplificado de participações.

## Tipo de solução esperada:
Aplicação Mobile

## Principais usuários da solução:
MEIs, microempresas (ME/EPP) e empreendedores individuais que participam de licitações públicas municipais, estaduais ou federais.

### Funcionalidades mínimas esperadas (MVP):
- RF01 - Busca e filtro de editais abertos (por região, valor, CNAE).
- RF02 - Análise automática de requisitos (checklist Lei 14.133/2021).
- RF03 - Organização de documentos (upload e templates para habilitação).
- RF04 - Alertas e notificações de prazos e preferências para MEIs.
- RF05 - Dashboard de histórico de participações.

### Recorte do MVP mobile (React Native + Expo):
- Tela de onboarding e autenticação do usuário.
- Tela inicial com lista de editais e filtros otimizados para uso em smartphone.
- Tela de detalhe do edital com checklist de requisitos e indicadores de elegibilidade.
- Tela de documentos com upload, visualização e status de pendências.
- Tela de alertas/notificações e calendário de prazos.
- Tela de dashboard com histórico resumido de participações e andamento das propostas.
- Navegação estruturada com React Navigation (stack/tab), gerenciamento de estado e persistência local.

### Limites do escopo:
Não inclui submissão automática de propostas a portais oficiais, assessoria jurídica ou fiscal, integrações com SICAF ou PNCP, ou garantia de aprovação em licitações. O foco é apoio preparatório, sem validade legal vinculante.

### Nível de complexidade estimado:
Médio

### Observações adicionais ou sugestões pedagógicas:
Integrar dados reais do PNCP para demonstração e transformar os requisitos do Projeto 5 em uma experiência mobile completa. Recomenda-se dividir a turma em frentes de mobile frontend (telas, componentes, navegação e estados), integração (consumo de APIs, autenticação, persistência local e tratamento de erros), qualidade (testes em dispositivos, validação de performance e acessibilidade) e apoio de negócio/ética para validação dos fluxos com MEIs locais. É desejável trabalhar com Expo Go e builds de desenvolvimento para testes contínuos em aparelhos físicos, além de protótipos navegáveis e registro de decisões de UX específicas para contexto mobile.

## Artefatos mobile esperados
- Mapa de navegação do aplicativo e definição das rotas principais.
- Protótipo de baixa e/ou média fidelidade das telas centrais.
- Backlog técnico do app com épicos, histórias e critérios de aceite.
- Repositório Expo organizado com componentes, telas, serviços e hooks.
- Builds ou demonstrações executáveis para validação em dispositivo real.
- Evidências de testes funcionais, de usabilidade e de integração.

## Intersecção com a disciplina
- Desenvolver aplicações móveis nativas multiplataforma em React Native que implementem, na prática, o MVP definido no Projeto 5, explorando recursos de dispositivos móveis (navegação, sensores, armazenamento local, notificações, etc.) e boas práticas de engenharia de software para apps mobile.
- Projetar e construir telas, fluxos de navegação e componentes reutilizáveis em React Native, integrando o app com APIs backend, serviços em nuvem e camadas de segurança, garantindo boa experiência de usuário, performance adequada em dispositivos reais e aderência aos requisitos de negócio e de segurança definidos no semestre.

## Intersecção da disciplina com as demais para o semestre
- Integra com Segurança da Informação ao aplicar, na camada mobile, práticas de proteção de dados (armazenamento seguro, comunicação criptografada com backend, autenticação/autorização), alinhadas às políticas, normas e análise de riscos definidas na disciplina de Segurança.
- Integra com Negócios na Internet ao traduzir o modelo de negócio, jornada do usuário e requisitos legais (como LGPD) em fluxos e funcionalidades do app React Native, permitindo experimentar e validar estratégias de engajamento, monetização e relacionamento com o cliente em contexto mobile.
- Integra com as Eletivas do semestre (Eletiva 2 / Eletiva 3) ao consumir APIs, bibliotecas ou serviços oriundos dessas disciplinas (por exemplo, módulos de dados, algoritmos ou recursos avançados), incorporando-os como funcionalidades diferenciadas dentro do aplicativo móvel em React Native.
- Integra com Projeto 5 como principal frente de implementação do cliente mobile do MVP, participando do planejamento de sprints, definição de releases da aplicação (builds para teste e produção), testes em dispositivos, coleta de feedback de usuários e ajustes incrementais, articulando dimensões técnicas, de negócio e de segurança na entrega final.



## Pontos de avaliação pela disciplina

- **Aderência ao problema e ao escopo do projeto:** clareza na relação entre a solução mobile proposta e o problema de negócio, respeito ao recorte do MVP e consistência com os objetivos definidos para o semestre.
- **Qualidade da experiência mobile:** organização das telas, coerência do fluxo de navegação, usabilidade em smartphone, responsividade, acessibilidade básica e tratamento adequado de estados de carregamento, erro e vazio.
- **Implementação técnica em React Native e Expo:** estrutura do projeto, componentização, reaproveitamento de código, uso correto de navegação, gerenciamento de estado, integração com APIs/serviços e adoção de boas práticas de desenvolvimento mobile.
- **Funcionalidade do MVP:** funcionamento efetivo dos fluxos principais do aplicativo, incluindo consulta de editais, visualização de detalhes, checklist, documentos, alertas e dashboard, conforme a proposta aprovada.
- **Integração com backend e dados:** qualidade do consumo de APIs, tratamento de falhas, persistência local quando necessária, segurança básica na comunicação e coerência dos dados apresentados no app.
- **Qualidade de testes e validação:** evidências de testes em emuladores e dispositivos reais, registro de bugs encontrados/corrigidos, validação dos fluxos críticos e demonstração de estabilidade mínima para uso em apresentação.
- **Performance e robustez:** tempo de resposta percebido, fluidez de navegação, organização do carregamento de dados, prevenção de travamentos e tratamento de exceções.
- **Documentação e organização do projeto:** clareza do repositório, padronização de código, documentação do setup, descrição das decisões arquiteturais, backlog, protótipos e evidências das entregas intermediárias.
- **Processo e evolução ao longo do semestre:** cumprimento das milestones/capstones, participação nas entregas parciais, capacidade de incorporar feedback e evolução progressiva do produto.
- **Apresentação final e defesa da solução:** qualidade da demonstração do aplicativo, domínio técnico da equipe, clareza na comunicação das decisões tomadas, limitações, aprendizados e próximos passos.

### Evidências para avaliação
- Protótipos e mapa de navegação do aplicativo.
- Backlog priorizado com histórias, tarefas e critérios de aceite.
- Repositório com histórico de evolução e organização por módulos.
- Prints, vídeos ou build demonstrável do app em execução.
- Relato de testes executados, bugs corrigidos e melhorias implementadas.
- Documentação técnica mínima para instalação, execução e apresentação do projeto.

## Cronograma

| Semana | Período       | Foco                              | Tarefas / Processo                                                                                                                                                           | Entrega / Milestone                                                    |
| ------ | ------------- | --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| 7      | 31/03 a 04/04 | Descoberta mobile e arquitetura   | Definição do escopo mobile, mapeamento de jornadas no app, arquitetura inicial com React Native + Expo, setup do repositório, padronização de pastas, rotas e design system. |                                                                        |
| 8      | 07/04 a 11/04 | UX mobile e prototipação          | Criação de wireframes e protótipos navegáveis das principais telas, definição do fluxo de autenticação, navegação e estados vazios/erro/carregamento.                        |                                                                        |
| 9      | 14/04 a 18/04 | Fundação do app                   | Implementação da base do projeto Expo, tema global, componentes reutilizáveis, React Navigation, gerenciamento de estado inicial e integração com dados mockados/API.        |                                                                        |
| 10     | 28/04 a 02/05 | Módulo de editais                 | Desenvolvimento das telas de listagem, busca, filtros e detalhe do edital, incluindo tratamento de loading, erro e empty state.                                              | **Capstone 1:** fluxo de consulta de editais funcionando ponta a ponta |
| 11     | 05/05 a 09/05 | Módulo de requisitos e documentos | Implementação do checklist de habilitação, organização de documentos, persistência local e integração com backend/serviços.                                                  | **Milestone 1:** fluxo de acompanhamento de proposta operacional       |
| 12     | 12/05 a 16/05 | Alertas, dashboard e segurança    | Implementação de notificações, dashboard resumido, autenticação, armazenamento seguro e ajustes de regras de negócio.                                                        | **Capstone 2:** MVP funcional integrado para demonstração interna      |
| 13     | 19/05 a 23/05 | Qualidade e testes                | Testes em dispositivos reais e emuladores, validação de responsividade, acessibilidade, performance, correção de bugs e melhoria da experiência.                             | **Milestone 2:** versão candidata à entrega homologada pela equipe     |
| 14     | 26/05 a 30/05 | Validação com usuários            | Coleta de feedback com usuários/alunos/professor, ajustes finos de UX, revisão técnica e preparação do build final.                                                          | **Capstone 3:** release candidate com feedback incorporado             |
| 15     | 02/06 a 06/06 | Fechamento e apresentação         | Consolidação da documentação, evidências de testes, vídeo/demo, pitch técnico e revisão final do backlog entregue.                                                           | **Milestone 3:** pacote final pronto para banca/avaliação              |
| 16     | 09/06 a 13/06 | Entrega integrada final           | Apresentação do aplicativo, demonstração do fluxo completo em dispositivo, lições aprendidas e integração com as demais disciplinas.                                         | **Entrega final integrada do projeto**                                 |

### Marcos esperados por entrega
- **Capstone 1:** protótipo navegável com fluxos principais e identidade visual do app.
- **Capstone 2:** fluxo de consulta de editais e detalhe funcionando no app.
- **Capstone 3:** MVP integrado com checklist, documentos, alertas e dashboard.
- **Capstone 4:** versão candidata com validação em dispositivos e feedback de usuários.
- **Entrega final:** app demonstrável, repositório organizado, documentação e apresentação integradas.

## Detalhamento de entrega
- Incluir o professor como colaborador do projeto no GitHub `mr-costaalencar`