# Guia Teórico: Monitoramento de Recursos com Azure Monitor

## 🎯 Objetivo

Permitir que administradores tenham visibilidade total sobre os recursos da nuvem, identifiquem comportamentos anômalos, e criem alertas sobre atividades críticas, como:

- Uso elevado de CPU
- Falhas de disco
- **Exclusão acidental de VMs**
- Reinicializações automáticas

## 🧩 Ferramentas Utilizadas

- **Azure Monitor**: serviço principal para análise de desempenho e atividade.
- **Log Analytics**: consulta detalhada dos dados.
- **Activity Log (Log de Atividade)**: rastreia eventos como criação, modificação e exclusão de recursos.

## 📊 Principais Métricas para VMs

- CPU Percentage
- Disk Read/Write Operations
- Available Memory
- Network In/Out

## 🛠 Exemplo de Configuração de Monitoramento

1. Acesse o **Azure Portal**
2. Vá até a **máquina virtual** desejada
3. Clique em **"Monitoramento" > "Métricas"**
4. Escolha a métrica desejada (ex: % CPU)
5. Configure um **gráfico ou alerta**

---

## 🔎 Visibilidade de Eventos Críticos

Para monitorar a exclusão de uma VM:

1. Acesse o serviço **Activity Log**
2. Filtro por **"Delete"**
3. Verifique quem executou a ação, quando e qual recurso foi afetado

Esses dados podem ser usados em alertas e automações (Ex: enviar e-mail ao administrador).
