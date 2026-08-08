# Gestão Orçamentária - Business-Intelligence
Uma solução de Business Intelligence concebida para acompanhar a execução orçamentária e financeira de contratos públicos, consolidando informações de orçamento, execução da despesa, contratos e restos a pagar em um modelo analítico único para apoio à tomada de decisão.
# Gestão Orçamentária — Business Intelligence

Uma solução de Business Intelligence desenvolvida para transformar informações dispersas sobre orçamento, contratos e execução financeira em uma visão integrada para apoio à tomada de decisão.

> 🔗 Dashboard público disponível:
>
> https://app.powerbi.com/view?r=eyJrIjoiNmY3NmEyNTEtOGNhOS00ZDEwLWJjZDEtNjBkYTQ4MjQ3N2I0IiwidCI6IjNhNzhiMGNkLTdjOGUtNDkyOS04M2Q1LTE5MGE2Y2MwMTM2NSJ9

---

# O problema

O acompanhamento da execução orçamentária era realizado a partir de diversas planilhas e consultas em diferentes sistemas.

Responder perguntas aparentemente simples exigia consolidar manualmente informações sobre:

- orçamento autorizado;
- reservas orçamentárias;
- contratos;
- empenhos;
- liquidações;
- pagamentos;
- Restos a Pagar.

Além do tempo gasto, a atualização das informações dependia de processos repetitivos e estava sujeita a inconsistências.

---

# A solução

Foi desenvolvido um modelo analítico capaz de consolidar essas informações em um único ambiente de Business Intelligence.

A solução passou a oferecer acompanhamento praticamente em tempo real da situação orçamentária da Secretaria, permitindo analisar desde indicadores executivos até detalhes operacionais de cada contrato.

Entre as principais funcionalidades estão:

- acompanhamento da execução orçamentária;
- monitoramento da execução financeira dos contratos;
- controle dos Restos a Pagar;
- indicadores executivos;
- consultas operacionais self-service;
- filtros cruzados entre todos os indicadores;
- consolidação automática de diferentes bases de dados.

---

# Arquitetura da Solução

O projeto foi estruturado em quatro camadas principais.

```text
                Fontes de Dados
                        │
                        ▼
             Power Query (ETL)
                        │
                        ▼
          Modelo Analítico (Power BI)
                        │
                        ▼
      Dashboards Executivos e Operacionais
```

Cada atualização percorre esse fluxo, garantindo consistência entre os dados importados e os indicadores apresentados aos usuários.

---

# Indicadores

O painel disponibiliza indicadores relacionados a toda a execução orçamentária, incluindo:

- Dotação Inicial
- Dotação Atual
- Reserva Orçamentária
- Empenhado
- Liquidado
- Pago
- Saldo Disponível
- Restos a Pagar Inscritos
- Restos a Pagar Pagos
- Restos a Pagar Cancelados
- Restos a Pagar Pendentes
- Execução dos Contratos de Publicidade

---

# Tecnologias

- Power BI
- Power Query (M)
- DAX
- Excel
- Modelagem de Dados

---

# Meu papel

Atuei durante todas as etapas do projeto:

- levantamento das regras de negócio;
- definição dos indicadores;
- consolidação das bases de dados;
- modelagem do modelo analítico;
- desenvolvimento das transformações em Power Query;
- construção das medidas em DAX;
- desenvolvimento dos dashboards;
- validação junto às áreas usuárias.

---

# Resultados

A solução passou a ser utilizada diariamente pelas áreas de orçamento e finanças como ferramenta de apoio à gestão.

Os principais ganhos observados foram:

- redução do tempo gasto na consolidação de informações;
- maior confiabilidade dos indicadores;
- visão integrada da execução orçamentária;
- acompanhamento contínuo dos contratos;
- maior transparência sobre os Restos a Pagar.

---

# Aprendizados

Este projeto representou um importante passo na minha evolução em Business Intelligence.

Durante seu desenvolvimento aprofundei conhecimentos em:

- modelagem de dados;
- construção de indicadores financeiros;
- DAX;
- Power Query;
- integração de diferentes bases de dados;
- visualização de informações para apoio à decisão.

Grande parte da experiência adquirida aqui foi posteriormente aplicada em projetos de automação de processos e no desenvolvimento de sistemas utilizando Python, Django e PostgreSQL.

---

# Observações

Este repositório documenta a arquitetura e as decisões adotadas no desenvolvimento da solução.

O código-fonte e as bases de dados não são disponibilizados por conterem informações relacionadas ao ambiente institucional.
