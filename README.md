# Automacao-de-operacoes-de-Email-com-UiPath
Automação no UiPath para verificar, catalogar e responder o "recibo" de Emails.

Requisitos:
1. Estar logado em uma conta de Email do Outlook
2. Criar uma pasta de catálogo de email no Outlook para cada nome:
  - microsoft
  - amazon
  - ebay
3. Baixar os pacotes do UiPath (se for o caso):
  - UiPath.UIAutomation.Activities (v22.4.5)
  - UiPath.System.Activities (v22.4.1)
  - UiPath.Mail.Activities (v1.15.2)


Descrição:
A automação verifica o assunto de cada Email na caixa de entrada, cataloga em sua respectiva
pastas e responde ao remetente com a mensagem "recebido!".
