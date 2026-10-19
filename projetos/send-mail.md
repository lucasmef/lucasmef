[← Voltar ao perfil](../README.md)

# Send Mail

## Fila local de e-mails com controle de falhas

Desenvolvi uma CLI em Python para preparar, revisar e enviar mensagens com uma fila persistente em SQLite. As credenciais ficam no Keychain do macOS, e o transporte exige TLS.

### Decisões técnicas

O worker usa lock entre processos e identificadores estáveis para evitar duplicidade. Se a conexão cai depois de uma possível aceitação SMTP, a mensagem fica em estado incerto e não é reenviada automaticamente. O projeto também inclui cópia via IMAP e assinatura DKIM opcional.

### Estado e limites

Há testes com transporte simulado para persistência, idempotência e recuperação. Uma demonstração de software não exige enviar mensagens reais. O código é voltado a macOS e depende das versões Python documentadas.

### Tecnologias

Python · SQLite · SMTP · IMAP · Keychain · Testes automatizados

### Código

A publicação do código-fonte está em preparação. Esta página apresenta o escopo e o trabalho técnico.

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
