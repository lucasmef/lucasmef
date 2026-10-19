[← Voltar ao perfil](../README.md#user-content-projetos)

# Send Mail

## CLI de envio com fila persistente

CLI em Python para preparar, revisar e enviar e-mails no macOS. As mensagens ficam em uma fila persistente em SQLite, com credenciais no Keychain e conexão SMTP com TLS.

### Consistência da fila e recuperação de falhas

Uma conexão pode cair depois que o servidor aceitou a mensagem. Repetir o envio nesse caso pode entregar duas cópias. O Send Mail registra essa situação como incerta e aguarda uma decisão, em vez de tentar novamente por conta própria.

Identificadores estáveis evitam repetir a mesma operação, e uma trava impede dois processos de trabalhar na fila ao mesmo tempo. O histórico e os limites de execução são preservados ao retomar o trabalho.

O projeto também permite arquivar uma cópia por IMAP e usar assinatura DKIM. Os testes simulam o transporte para verificar duplicidade, persistência e recuperação sem enviar mensagens reais.

`Python` `SQLite` `SMTP` `IMAP` `Keychain`

[Ver o código e as instruções de uso](https://github.com/lucasmef/send-mail)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
