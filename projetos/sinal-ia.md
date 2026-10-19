[← Voltar ao perfil](../README.md#user-content-projetos)

# Sinal IA

## Parser de metadados XMP, IPTC e C2PA

Scanner macOS de declarações de uso de IA em metadados de imagens e vídeos. Processamento local, sem envio da mídia a serviços externos.

### O que ele encontra

O scanner lê XMP, IPTC e estruturas C2PA e mostra as declarações encontradas. Ele não analisa a aparência da imagem nem verifica assinaturas criptográficas. Um arquivo sem declaração pode ter sido criado ou editado com IA.

O parser aplica limites ao tamanho dos blocos, ao volume de leitura e à profundidade das estruturas. Os testes usam arquivos sintéticos e entradas inválidas para conferir o comportamento do parser.

Os utilitários de limpeza de metadados ficam separados da inspeção. Arrastar um arquivo para o scanner não altera seu conteúdo.

`Swift` `XMP` `IPTC` `C2PA` `Parsing binário` `macOS`

[Ver o código e os formatos aceitos](https://github.com/lucasmef/anti-ia)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
