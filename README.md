# Cobranca_emails_AppScript
<p>
  Integração de Planilhas Google, Google Drive, Gmail e AppScript para envios automáticos de e mails de cobrança todo dia 05 de cada mês.
  O código verificar condições na planilha e envia e mails apenas para o que possuem "NÃO" na coluna R e os que estão com "E mail enviado ao fornecedor sobre entrega/ interesse de entrega" na coluna V, enviando mensagem para o e mail da coluna U com o nome presente na coluna B, empenho da coluna A e valor da coluna C.
</p>
<H2>
  <b>Etapas:</b>
</H2>
<ol> 
  <li>Criar base de dados : Google Sheets (Planilhas Google) criada com extração de dados via Python (PDFQuery) 
  <li>Inserir o código da function enviarEmailsEmMassaComConfirmacao2023agendado no AppScript vinculado à planilha
  <li> Utilizar Triggers (Acionadores do AppScript) e programar envio para todo dia 05 de cada mês
</ol> 
<img src="https://github.com/RenataVerasVenturim/Cobranca_emails_AppScript/assets/129551549/e1af9756-2ad3-49a4-b442-0cf8830597fa">
<i>
  Triggers
</i>
<p>
  <img src="https://github.com/RenataVerasVenturim/Cobranca_emails_AppScript/assets/129551549/fa833bc2-c6a8-4b91-a936-6ccd7d994a7e">
<i>
  Um dos e mails enviados
</i>
</p>
