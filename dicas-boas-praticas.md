# Boas Práticas de Monitoramento no Azure

## 🔐 Segurança e Controle

- Monitore **eventos administrativos** como exclusão, criação e alteração de VMs
- Ative logs em **todas as regiões e recursos sensíveis**
- Crie alertas para **operações de risco**

## 📉 Custo e Performance

- Monitore uso de **CPU, disco e rede** para dimensionar corretamente a VM
- Configure alertas para **escalar automaticamente** quando necessário

## 📊 Logs e Análise

- Use **Log Analytics** para cruzar dados históricos e gerar relatórios
- Configure **dashboards no Azure Monitor** para visualizar saúde geral

## 🚨 Alertas Inteligentes

- Configure alertas para:
  - Exclusão de recursos
  - Falhas de login
  - Queda de disponibilidade
- Utilize **Grupos de Ações** para distribuir alertas corretamente (infra, dev, etc)

## 💡 Dica Extra

- Combine o Azure Monitor com **Azure Policy** para bloquear ações indesejadas
- Use **Workbooks** para visualizar e customizar relatórios no Azure
