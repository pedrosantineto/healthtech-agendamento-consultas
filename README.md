# 🏥 Sistema de Marcação de Consultas e Plano de Saúde

Sistema completo para agendamento de consultas médicas online, busca de rede credenciada, gestão de solicitações de planos e emissão de boletos/extratos financeiros.

## 🚀 Módulos do Sistema
- **Portal do Paciente:** Busca de médicos por especialidade, agendamento de consultas e gestão do perfil.
- **Módulo Financeiro:** Emissão de 2ª via de faturas, histórico de pagamentos e coparticipação.
- **Gestão do Plano:** Solicitação de migração/troca de plano de saúde.
- **Painel Administrativo (Backoffice):** Cadastro da rede credenciada (médicos, clínicas) e aprovação de solicitações.

## 🛠️ Tecnologias Utilizadas
- **Frontend:** [Ex: React / Flutter]
- **Backend:** [Ex: Node.js / Java Spring Boot / Python]
- **Banco de Dados:** [Ex: PostgreSQL / MySQL]
- **Qualidade & Testes:** [Ex: SonarQube, Jest, Appium]

## 📋 Documentação
Os artefatos de Engenharia de Software (Diagramas UML, Especificação de Requisitos e Checklist ISO/IEC 25010) estão armazenados na pasta [`/docs`](./docs).

## 🔀 Estratégia de Branches (GitFlow)
- `main`: Código estável pronto para produção.
- `develop`: Código em integração com as últimas funcionalidades desenvolvidas.
- `feature/*`: Novas funcionalidades (ex: `feature/busca-medicos`).
- `fix/*`: Correção de bugs (ex: `fix/erro-download-boleto`).
