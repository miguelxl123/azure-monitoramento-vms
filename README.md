# azure-monitoramento-vms
Documentação sobre monitoramento de recursos no Azure com foco em VMs – Desafio DIO AZ-104

# Monitoramento de Recursos no Microsoft Azure – Foco em Máquinas Virtuais

Este repositório contém um guia teórico e prático sobre como configurar o monitoramento de recursos no Azure, com ênfase em máquinas virtuais (VMs). O conteúdo foi desenvolvido a partir das atividades do Bootcamp Microsoft AZ-104 (DIO), com o objetivo de auxiliar no entendimento, organização e documentação de ações preventivas e corretivas em ambientes de nuvem.

## 📌 Objetivo

Demonstrar como manter visibilidade, controle e resposta proativa sobre eventos críticos no ambiente Azure, como a **exclusão acidental de uma VM**, através de:

- Monitoramento com Azure Monitor e Log Analytics
- Alertas personalizados
- Atividade de recursos (Resource Logs)
- Dicas de melhores práticas

## 📁 Arquivos

- [`guia-monitoramento.md`](./guia-monitoramento.md) – Explicação teórica e técnica do processo de monitoramento
- [`alertas-eventos.md`](./alertas-eventos.md) – Como configurar alertas para eventos críticos (exclusão de VM, por exemplo)
- [`dicas-boas-praticas.md`](./dicas-boas-praticas.md) – Dicas de boas práticas em monitoramento

## 📚 Referências

- [Documentação Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/)
- [Log Analytics no Azure](https://learn.microsoft.com/pt-br/azure/azure-monitor/logs/log-analytics-overview)
- [Alertas do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/alerts/alerts-overview)

## 🖼️ Imagens
- ![Alert setup no Azure Monitor](./images/alert-setup.png)
- ![Tela de métricas no Azure Monitor](./images/log-alert-rule-multiple-dimensions.png)
- ![Criação de alertas via Activity Log / Log Analytics](./images/log-alert-rule.png)
- ![Visão geral dos alertas do Azure Monitor](./images/alerts.png)

