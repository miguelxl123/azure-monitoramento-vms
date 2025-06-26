# Criando Alertas de Eventos Críticos no Azure

Este guia ensina como configurar alertas para eventos críticos, como a exclusão de uma máquina virtual no Azure.

---

## 🛑 Alerta para Exclusão de VM

### Etapas:

1. Vá até **Azure Monitor > Alerts**
2. Clique em **"New alert rule"**
3. Em *Resource*, selecione sua **Subscription**
4. Em *Condition*, clique em **"Add condition"**
5. Escolha a opção: **"Administrative Activity Log"**
6. Selecione **"Operation name = Delete Virtual Machine"**
7. Defina o grupo de ação:
   - Enviar e-mail para responsável
   - Webhook para automação
8. Nomeie e crie a regra de alerta

---

## 📨 Opções de Ação

- E-mail
- SMS (dependendo do plano)
- Webhook (para automações com Logic Apps, por exemplo)
- Notificação via App do Azure

---

## 📎 Exemplo de Alerta

| Nome do Alerta         | Ação                         | Condição                      |
|------------------------|------------------------------|-------------------------------|
| `Excluir VM alerta`    | E-mail para admin             | Operation = Delete VM         |
| `Uso Alto de CPU`      | Notificação App + E-mail      | CPU > 90% por 5 min           |
