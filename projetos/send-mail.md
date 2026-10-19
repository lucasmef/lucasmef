[← Voltar ao perfil](../README.md)

# Send Mail

## Fila local de e-mails com controle de falhas

Desenvolvi uma CLI em Python para preparar, revisar e enviar e-mails com uma fila persistente em SQLite. As credenciais ficam no Keychain do macOS, e o transporte exige TLS.

### Decisões técnicas

O worker usa bloqueio entre processos e identificadores estáveis para reduzir o risco de envios duplicados. Se a conexão cai após uma possível aceitação pelo servidor SMTP, a mensagem fica em estado incerto e não é reenviada automaticamente. O projeto também inclui cópia via IMAP e assinatura DKIM opcional.

### Estágio atual e validação

Há testes com transporte simulado para persistência, idempotência e recuperação. A aplicação é voltada ao macOS e depende das versões de Python indicadas na documentação.

### Tecnologias

Python · SQLite · SMTP · IMAP · Keychain · Testes automatizados

### Código

[Consultar o código-fonte e as instruções de uso](https://github.com/lucasmef/send-mail).

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
