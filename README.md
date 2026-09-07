<p align="center">
  <img src="docs/BANNER1.PNG" alt="banner" width="1000">
</p>

---

Análise técnica e operacional da plataforma GLPI (ITIL

![GLPI](https://img.shields.io/badge/GLPI-004385?style=flat&logo=glpi&logoColor=white)
![ITIL v4](https://img.shields.io/badge/ITIL%20v4-005A9C?style=flat&logoColor=white)
![COBIT 2019](https://img.shields.io/badge/COBIT%202019-003366?style=flat&logoColor=white)
![ISO/IEC 20000](https://img.shields.io/badge/ISO%2FIEC%2020000-4A154B?style=flat&logoColor=white)

**Natureza:** Acadêmico / Simulação Corporativa -|- **Status:** ✔

---
## Visão Geral

Execução da avaliação técnica e operacional do GLPI como solução centralizada de Service Desk. O projeto validou a conformidade da plataforma com boas práticas de governança de TI por meio da estruturação de catálogo de serviços, definição de SLAs, parametrização de perfis de acesso (RBAC) e auditoria de aderência aos frameworks ITIL, COBIT e ISO/IEC 20000 em cenário de simulação corporativa.

## Contexto e Problema

Eliminar a falta de rastreabilidade, a inconsistência operacional e a baixa mensuração de desempenho causadas pelo uso de canais de suporte informais (e-mail, telefone e mensagens). Centralizar o atendimento em ferramenta governada por processos padronizados de gestão de serviços.

## Objetivos

- Avaliar funcionalidade e usabilidade do GLPI nos perfis de Solicitante, Técnico e Administrador.
- Estruturar catálogo de serviços de TI com SLAs, janelas de atendimento e fluxos de aprovação.
- Identificar lacunas de governança na configuração padrão da ferramenta.

## Escopo

**Inclusões:** Configuração do ambiente de teste, definição de catálogo de serviços (Hardware, Software, Rede, Acessos, etc.), testes de usabilidade por perfil, auditoria de funcionalidades e elaboração de relatório de conformidade.  
**Exclusões:** Integração com sistemas externos de ERP, RH ou ferramentas de monitoramento de infraestrutura em tempo real.  
**Limites:** Cenário de simulação corporativa em ambiente de laboratório, sem impacto em operações de produção.

## Papel e Responsabilidades

Atuação na configuração do ambiente de testes, elaboração do catálogo de serviços com definição de SLAs, execução dos testes de usabilidade nos perfis de Usuário, Técnico e Administrador, e redação do relatório técnico comparativo entre as funcionalidades do GLPI e os requisitos dos frameworks de governança.

## Metodologia e Abordagem

O projeto foi conduzido em fases estruturadas:
1. **Configuração do Ambiente:** Provisionamento do GLPI em ambiente de laboratório e acesso controlado via VPN.
2. **Estruturação do Serviço:** Definição de categorias de chamados, campos obrigatórios e regras de negócio (SLAs e janelas de atendimento).
3. **Testes de Usabilidade (RBAC):** Execução de fluxos de ponta a ponta simulando as ações de um Usuário (abertura de chamado), Técnico (atendimento e histórico) e Administrador (configuração e relatórios).
4. **Auditoria de Conformidade:** Análise cruzada das funcionalidades do GLPI com as práticas de ITIL v4, COBIT 2019 (Domínio DSS) e ISO/IEC 20000.
5. **Análise de Gaps e Recomendações:** Identificação de limitações da ferramenta e proposição de melhorias de processo e configuração.

## Frameworks e Boas Práticas

- **ITIL v4:** Utilizado como base para a estruturação do Catálogo de Serviços, Gerenciamento de Incidentes, Gerenciamento de Requisições de Serviço e Gerenciamento de Ativos de TI.
- **COBIT 2019 (Domínio DSS):** Aplicado para avaliar a capacidade da ferramenta em "Gerenciar Solicitações e Incidentes de Serviços" (DSS02) e "Gerenciar Problemas" (DSS03).
- **ISO/IEC 20000:** Utilizado como referência para a definição e parametrização de Acordos de Nível de Serviço (SLA) e Gestão de Níveis de Serviço.

## Tecnologias e Ferramentas

- **Plataforma de Service Desk:** GLPI (Open Source).
- **Acesso e Rede:** ZeroTier (VPN para acesso controlado ao ambiente de laboratório).
- **Documentação e Modelagem:** Ferramentas de edição de texto e planilhas para estruturação do catálogo e SLAs.

## Solução e Arquitetura

A solução proposta foi a configuração do GLPI para operar como um Service Desk estruturado. A arquitetura lógica da ferramenta foi organizada em um Catálogo de Serviços dividido em 8 categorias principais (Hardware, Software, Rede, Acessos e Segurança, E-mail, Telefonia, Sistemas Corporativos e Outros). Para cada item, foram definidos: solicitante permitido, necessidade de aprovação, informações obrigatórias, SLA em horas e janela de atendimento, garantindo a rastreabilidade e a padronização do fluxo de trabalho.

## Evidências e Entregáveis

- **Catálogo de Serviços de TI:** Documento detalhado com 20+ itens de serviço, incluindo descrições, SLAs, janelas de atendimento e requisitos de aprovação.
- **Relatório Técnico de Avaliação:** Documento comparativo detalhando o alinhamento (Alinhado, Parcial ou Não Alinhado) do GLPI com práticas específicas de ITIL, COBIT e ISO 20000.
- **Resultados dos Testes de Usabilidade:** Análise crítica da experiência do usuário, destacando pontos fortes (ex: histórico de ações para técnicos) e pontos de atenção (ex: campos não obrigatórios que podem gerar chamados incompletos).
- **Matriz de Recomendações:** Lista de melhorias de configuração e processo para otimizar a adoção da ferramenta.

<p align="center">
  <img src="docs/GLPI.PNG" alt="Logo GLPI" width="600">
</p>
*[Espaço reservado para inserção de imagens do Catálogo de Serviços, dashboards do GLPI ou trechos do relatório de conformidade]*

## Resultados e Validação

- Validação do GLPI como uma solução robusta, escalável e de baixo custo para a gestão de serviços de TI em PMEs.
- Confirmação de que a ferramenta atende bem aos processos de Gerenciamento de Incidentes, Requisições e Ativos de TI, mas requer customização manual para processos mais complexos (como Gerenciamento de Mudanças avançado ou Projetos).
- Identificação de que o sucesso da ferramenta depende criticamente de um planejamento inicial rigoroso (definição de categorias e SLAs) e de treinamento dos usuários para evitar a abertura de chamados vazios ou mal categorizados.

## Aprendizados e Limitações

- **Aprendizado:** Ferramentas open-source de ITSM são altamente flexíveis, mas essa flexibilidade exige um esforço inicial significativo de modelagem de processos. A tecnologia sozinha não resolve gaps de governança; ela apenas os automatiza.
- **Limitação:** O GLPI, em sua configuração padrão, possui limitações nativas para processos complexos de Gerenciamento de Projetos e Gerenciamento de Relacionamento com o Cliente (CRM), exigindo plugins de terceiros ou adaptações de processo para cobrir essas lacunas.

---

## Documentação, Evidências e Recursos

- [Relatório Técnico de Avaliação de Service Desk - GLPI](docs/REPORT%20-%20AVALIAÇÃO%20DE%20SERVICE%20DESK%20-27.04.2025.pdf)
- [Relatório Alinhamento GLPI Vs MELHORES PRÁTICAS DO COBIT E ITIL/ISO 20000
](docs/COMPARA%C3%87%C3%83O%20COM%20AS%20MELHORES%20PR%C3%81TICAS%20DO%20COBIT%20-%20ITIL%20-%20ISO%2020000.pdf)
- [Catálogo de Serviços de TI - GLPI](docs/CATALOGO%20DE%20SERVIÇOS%20DE%20TI%20-%20GLPI%2021.04.2025.pdf)
- [Catálogo ITIL e Mapeamento de SLAs](docs/Catalogo%20ITIL%2002.pdf)



## Documentação, Evidências e Recursos


---

###### 🔒 Nota de Confidencialidade
###### *Tratando-se de um projeto desenvolvido em ambiente de simulação corporativa e laboratório de testes, quaisquer topologias de rede, endereços IP, credenciais de acesso ou configurações específicas mencionadas na documentação original foram omitidas ou sanitizadas neste repositório, preservando as boas práticas de segurança da informação.*

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguelhcruz)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mig.kruz@gmail.com)

---

## 🧭 Navegação do Portfólio

[⬅️ Voltar ao Perfil Principal](https://github.com/mighcruz) 

[📂 Voltar ao Hub Central de Projetos](https://github.com/mighcruz/portfolio-ti)
