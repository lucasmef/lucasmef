[← Voltar ao perfil](../README.md#user-content-projetos)

# Send Mail

## Uma fila de e-mails que pode ser retomada

Desenvolvi o Send Mail para preparar, revisar e enviar mensagens pelo terminal do Mac. A fila fica em SQLite, as credenciais no Keychain e a conexão com o servidor de e-mail usa TLS.

### O que acontece quando um envio falha

Uma conexão pode cair depois que o servidor aceitou a mensagem. Repetir o envio nesse caso pode entregar duas cópias. O Send Mail registra essa situação como incerta e aguarda uma decisão, em vez de tentar novamente por conta própria.

Identificadores estáveis evitam repetir a mesma operação, e uma trava impede dois processos de trabalhar na fila ao mesmo tempo. O histórico e os limites de execução são preservados ao retomar o trabalho.

O projeto também permite arquivar uma cópia por IMAP e usar assinatura DKIM. Os testes simulam o transporte para verificar duplicidade, persistência e recuperação sem enviar mensagens reais.

`Python` `SQLite` `SMTP` `IMAP` `Keychain`

[Ver o código e as instruções de uso](https://github.com/lucasmef/send-mail)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
