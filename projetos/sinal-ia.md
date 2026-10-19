[← Voltar ao perfil](../README.md#user-content-projetos)

# Sinal IA

## Conferir o que os metadados dizem sobre uma imagem ou vídeo

Desenvolvi o Sinal IA para procurar declarações de uso de IA nos metadados de arquivos. O aplicativo roda localmente no Mac, sem enviar a mídia para um serviço externo.

### O que ele encontra

O scanner lê XMP, IPTC e estruturas C2PA e mostra as declarações encontradas. Ele não analisa a aparência da imagem nem verifica assinaturas criptográficas. Um arquivo sem declaração pode ter sido criado ou editado com IA.

Na implementação, limitei o tamanho dos blocos, o volume de leitura e a profundidade das estruturas. Os testes usam arquivos sintéticos e entradas inválidas para conferir o comportamento do parser.

Os utilitários de limpeza de metadados ficam separados da inspeção. Arrastar um arquivo para o scanner não altera seu conteúdo.

`Swift` `XMP` `IPTC` `C2PA` `Parsing binário` `macOS`

[Ver o código e os formatos aceitos](https://github.com/lucasmef/anti-ia)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
