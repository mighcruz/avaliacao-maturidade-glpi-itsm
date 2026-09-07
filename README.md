<p align="center">
  <img src="docs/BANNER1.PNG" alt="banner" width="1000">
</p>

**Natureza:** Acadêmico / Simulação Corporativa  ✔

---
## Visão Geral

Execução da avaliação técnica e operacional do GLPI como solução centralizada de Service Desk. 
O projeto validou a conformidade da plataforma com boas práticas de governança de TI por meio da estruturação de catálogo de serviços, definição de SLAs, parametrização de perfis de acesso (RBAC) e auditoria de aderência aos frameworks ITIL, COBIT e ISO/IEC 20000 em cenário de simulação corporativa.

## Contexto e Problema

Eliminar a falta de rastreabilidade, a inconsistência operacional e a baixa mensuração de desempenho causadas pelo uso de canais de suporte informais (e-mail, telefone e mensagens). Centralizar o atendimento em ferramenta governada por processos padronizados de gestão de serviços.

## Objetivos

- Avaliar funcionalidade e usabilidade do GLPI nos perfis de Solicitante, Técnico e Administrador.
- Estruturar catálogo de serviços de TI com SLAs, janelas de atendimento e fluxos de aprovação.
- Identificar lacunas de governança na configuração padrão da ferramenta.

## Escopo

- **Inclusões**: Configuração de ambiente de laboratório, definição de catálogo de serviços (Hardware, Software, Rede, Acessos), testes de usabilidade por perfil, auditoria de funcionalidades e elaboração de relatório de conformidade.
- **Exclusões**: Integração com sistemas externos de ERP, RH ou ferramentas de monitoramento em tempo real.
- **Limites**: Cenário de simulação corporativa em ambiente de laboratório, sem impacto em operações de produção.

## Atuação e Responsabilidades

- Configurar o ambiente de testes e o provisionamento de infraestrutura.
- Desenhar o catálogo de serviços e parametrizar SLAs.
- Executar testes de usabilidade nos perfis de Usuário, Técnico e Administrador.
- Redigir o relatório técnico comparativo entre funcionalidades do GLPI e requisitos de governança.

## Metodologia e Abordagem

1. Configuração do Ambiente: Provisionar o GLPI em laboratório isolado com acesso via VPN controlada.
2. Estruturação do Serviço: Definir categorias de chamados, campos obrigatórios, SLAs e janelas de atendimento.
3. Testes de Usabilidade (RBAC): Executar fluxos ponta a ponta para Usuário, Técnico e Administrador.
4. Auditoria de Conformidade: Cruzar funcionalidades do GLPI com ITIL v4, COBIT 2019 e ISO/IEC 20000.
5. Análise de Gaps e Recomendações: Mapear limitações da ferramenta e propor melhorias de processo e configuração.

## Frameworks e Boas Práticas

![GLPI](https://img.shields.io/badge/GLPI-004385?style=flat&logo=glpi&logoColor=white)
![ITIL v4](https://img.shields.io/badge/ITIL%20v4-005A9C?style=flat&logoColor=white)
![COBIT 2019](https://img.shields.io/badge/COBIT%202019-003366?style=flat&logoColor=white)
![ISO/IEC 20000](https://img.shields.io/badge/ISO%2FIEC%2020000-4A154B?style=flat&logoColor=white)

- ITIL v4: Direcionar a estruturação do Catálogo de Serviços, Gerenciamento de Incidentes, Requisições e Ativos de TI.
- COBIT 2019 (Domínio DSS): Avaliar a capacidade de gerenciar solicitações, incidentes e problemas.
- ISO/IEC 20000: Fundamentar a parametrização de Acordos de Nível de Serviço (SLA) e gestão de níveis de serviço.

## Tecnologias e Ferramentas

- Plataforma de Service Desk: GLPI (Open Source).
- Acesso e Rede: ZeroTier (VPN para laboratório).
- Documentação e Modelagem: Editores de texto e planilhas eletrônicas.


# Solução e Arquitetura

Implementação do GLPI como Service Desk estruturado com catálogo dividido em oito categorias principais (Hardware, Software, Rede, Acessos e Segurança, E-mail, Telefonia, Sistemas Corporativos e Outros). Parametrização de solicitantes, fluxos de aprovação, obrigatoriedade de campos, SLAs e janelas de atendimento para garantir rastreabilidade e padronização.

## Evidências e Entregáveis

- Catálogo de Serviços de TI: Documento com mais de vinte itens parametrizados com descrições, SLAs e regras de aprovação.
- Relatório Técnico de Avaliação: Análise comparativa de alinhamento entre GLPI, ITIL, COBIT e ISO 20000.
- Resultados de Testes de Usabilidade: Avaliação crítica da experiência de navegação e pontos de atenção em campos de abertura de chamados.
- Matriz de Recomendações: Plano de melhorias de configuração e processos.

<p align="center">
  <img src="docs/GLPI.PNG" alt="Logo GLPI" width="600">
</p>


## Resultados e Validação

- Validar o GLPI como solução robusta, escalável e de baixo custo para ITSM em pequenas e médias empresas.
- Comprovar a eficiência da ferramenta em Incidentes, Requisições e Ativos, identificando a necessidade de customização para Gestão de Mudanças complexas ou Projetos.
- Demonstrar que o sucesso da implementação depende de planejamento inicial rigoroso e treinamento contínuo de usuários.

## Aprendizados e Limitações

- Aprendizado: Ferramentas open-source exigem esforço inicial intenso de modelagem de processos; a tecnologia automatiza, mas não substitui a governança.
- Limitação: A configuração padrão do GLPI apresenta restrições para projetos complexos e CRM, demandando plugins externos ou adaptações processuais.

---

## Documentação, Evidências e Recursos

- [Relatório Técnico de Avaliação de Service Desk - GLPI](docs/REPORT%20-%20AVALIAÇÃO%20DE%20SERVICE%20DESK%20-27.04.2025.pdf)
- [Relatório Alinhamento GLPI Vs MELHORES PRÁTICAS DO COBIT E ITIL/ISO 20000
](docs/COMPARA%C3%87%C3%83O%20COM%20AS%20MELHORES%20PR%C3%81TICAS%20DO%20COBIT%20-%20ITIL%20-%20ISO%2020000.pdf)
- [Catálogo de Serviços de TI - GLPI](docs/CATALOGO%20DE%20SERVIÇOS%20DE%20TI%20-%20GLPI%2021.04.2025.pdf)
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
