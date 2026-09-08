<p align="center">
  <img src="docs/BANNER1.PNG" alt="Banner do projeto" width="1000">
</p>

# Avaliação Técnica e Operacional do GLPI — Service Desk / ITSM

**Natureza:** Acadêmico / Simulação Corporativa ✔

---

## Visão Geral

Avaliação técnica e operacional do **GLPI** como solução centralizada de **Service Desk / ITSM**, realizada em ambiente de laboratório com cenário de simulação corporativa.

O projeto avaliou a capacidade da plataforma de apoiar processos estruturados de **Gestão de Serviços de TI**, considerando catálogo de serviços, SLAs, controle de acesso baseado em funções (RBAC), fluxos de atendimento e rastreabilidade.

A análise comparou as funcionalidades avaliadas com referências de **ITIL v4, COBIT 2019 e ISO/IEC 20000**, permitindo identificar capacidades, limitações e oportunidades de melhoria relacionadas à configuração e aos processos de gestão de serviços.

## Indicadores do Projeto

| Indicador | Resultado |
|---|---:|
| Categorias de serviços | **8** |
| Serviços parametrizados | **20+** |
| Perfis de acesso avaliados | **3** |
| Frameworks / referenciais analisados | **3** |
| Ambiente | **Laboratório / Simulação Corporativa** |

## Contexto e Problema

O cenário analisado apresentava **falta de rastreabilidade, inconsistência operacional e baixa capacidade de mensuração de desempenho** decorrentes do uso de canais de suporte informais, como e-mail, telefone e mensagens.

Esse modelo dificultava:

- A padronização dos atendimentos;
- O acompanhamento de SLAs;
- A definição de responsabilidades;
- A rastreabilidade das solicitações;
- A geração de informações para análise de desempenho.

Diante desse cenário, o projeto avaliou a utilização do **GLPI** como plataforma centralizada para estruturar e organizar o processo de atendimento de TI.

## Objetivos

- Avaliar a funcionalidade e usabilidade do GLPI nos perfis de **Solicitante, Técnico e Administrador**.
- Estruturar um **Catálogo de Serviços de TI** com categorias, SLAs, janelas de atendimento e fluxos de aprovação.
- Avaliar mecanismos de controle de acesso e responsabilidades por perfil.
- Identificar lacunas de governança e limitações na configuração avaliada.
- Comparar as funcionalidades observadas com práticas de **ITIL v4, COBIT 2019 e ISO/IEC 20000**.
- Elaborar recomendações de configuração e melhoria dos processos.

## Escopo

### Incluído

- Provisionamento e configuração do GLPI em ambiente de laboratório.
- Estruturação do Catálogo de Serviços de TI.
- Definição de categorias e campos obrigatórios.
- Parametrização de SLAs e janelas de atendimento.
- Configuração e avaliação de perfis de acesso.
- Definição de regras e fluxos de aprovação.
- Execução de testes funcionais e de usabilidade.
- Avaliação de aderência a boas práticas de ITSM.
- Elaboração de documentação técnica e matriz de recomendações.

### Excluído

- Integrações com sistemas externos de ERP ou RH.
- Integração com ferramentas de monitoramento em tempo real.
- Implantação em ambiente produtivo.
- Automação de processos corporativos fora do escopo do Service Desk.

### Limitações da Avaliação

A avaliação foi conduzida em **ambiente de laboratório e simulação corporativa**, sem impacto sobre operações reais de produção.

Os resultados representam o comportamento observado no cenário configurado e não constituem uma validação de implantação produtiva ou certificação de conformidade.

## Atuação e Responsabilidades

As principais atividades realizadas no projeto foram:

- Configuração do ambiente de testes e provisionamento da infraestrutura.
- Estruturação do Catálogo de Serviços de TI.
- Parametrização de SLAs, horários e regras de atendimento.
- Configuração e avaliação dos perfis de acesso.
- Execução de testes funcionais e de usabilidade.
- Avaliação dos fluxos de abertura, tratamento e encerramento de chamados.
- Análise comparativa entre funcionalidades da plataforma e referências de governança.
- Identificação de gaps e elaboração de recomendações.
- Produção da documentação técnica e dos artefatos de avaliação.

## Metodologia e Abordagem

A avaliação foi estruturada em cinco etapas.

### 1. Configuração do Ambiente

Provisionamento do GLPI em ambiente de laboratório isolado, com acesso controlado por VPN.

### 2. Estruturação do Serviço

Definição das categorias de atendimento, campos obrigatórios, regras de aprovação, SLAs e janelas de atendimento.

### 3. Testes de Usabilidade e RBAC

Execução de fluxos ponta a ponta utilizando os diferentes perfis de acesso:

- **Solicitante**
- **Técnico**
- **Administrador**

Foram avaliadas navegação, abertura e acompanhamento de chamados, responsabilidades, permissões e limitações de cada perfil.

### 4. Avaliação de Aderência

Comparação das funcionalidades avaliadas com práticas e conceitos relacionados a:

- **ITIL v4**
- **COBIT 2019**
- **ISO/IEC 20000**

A análise teve caráter comparativo e acadêmico, considerando o cenário e a configuração implementados no laboratório.

### 5. Análise de Gaps e Recomendações

Identificação das limitações encontradas na configuração avaliada e elaboração de propostas de melhoria relacionadas a processos, parametrização e governança.

## Frameworks e Boas Práticas

![GLPI](https://img.shields.io/badge/GLPI-004385?style=flat&logo=glpi&logoColor=white)
![ITIL v4](https://img.shields.io/badge/ITIL%20v4-005A9C?style=flat&logoColor=white)
![COBIT 2019](https://img.shields.io/badge/COBIT%202019-003366?style=flat&logoColor=white)
![ISO/IEC 20000](https://img.shields.io/badge/ISO%2FIEC%2020000-4A154B?style=flat&logoColor=white)

### ITIL v4

Utilizado como referência para estruturação do **Catálogo de Serviços**, Gestão de Incidentes, Requisições e Ativos de TI.

### COBIT 2019

Utilizado como referência de governança, com foco no **Domínio DSS — Deliver, Service and Support**, especialmente nos processos relacionados à entrega e suporte de serviços.

### ISO/IEC 20000

Utilizada como referência para conceitos relacionados à **Gestão de Serviços de TI**, incluindo definição de níveis de serviço e SLAs.

## Tecnologias e Ferramentas

![GLPI](https://img.shields.io/badge/GLPI-004385?style=flat&logo=glpi&logoColor=white)
![ZeroTier](https://img.shields.io/badge/ZeroTier-FFB441?style=flat&logo=zerotier&logoColor=white)

- **Service Desk / ITSM:** GLPI
- **Rede / VPN:** ZeroTier
- **Documentação:** Markdown e PDF
- **Modelagem e controle:** Planilhas eletrônicas
- **Ambiente:** Laboratório de simulação corporativa

# Solução e Arquitetura

O GLPI foi utilizado como plataforma centralizada de Service Desk, com um catálogo estruturado em **oito categorias principais**:

- Hardware
- Software
- Rede
- Acessos e Segurança
- E-mail
- Telefonia
- Sistemas Corporativos
- Outros

A configuração contemplou:

- Catálogo de Serviços;
- Perfis de acesso;
- Regras de aprovação;
- Campos obrigatórios;
- SLAs;
- Janelas de atendimento;
- Fluxos de abertura e tratamento de chamados;
- Mecanismos de rastreabilidade.

### Fluxo Conceitual

<p align="center">
  <img src="docs/fluxo.png" alt="Banner do projeto" width="1000">
</p>

---

## Documentação, Evidências e Recursos

- [Relatório Técnico de Avaliação de Service Desk - GLPI](docs/REPORT%20-%20AVALIAÇÃO%20DE%20SERVICE%20DESK%20-27.04.2025.pdf)
- [Relatório de Alinhamento GLPI vs. Melhores Práticas do COBIT, ITIL e ISO/IEC 20000](docs/COMPARA%C3%87%C3%83O%20COM%20AS%20MELHORES%20PR%C3%81TICAS%20DO%20COBIT%20-%20ITIL%20-%20ISO%2020000.pdf)
- [Catálogo de Serviços de TI - GLPI](docs/CATALOGO%20DE%20SERVI%C3%87OS%20DE%20TI%20-%20GLPI%2021.04.2025.pdf)
- [Catálogo ITIL e Mapeamento de SLAs](docs/Catalogo%20ITIL%2002.pdf)

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
