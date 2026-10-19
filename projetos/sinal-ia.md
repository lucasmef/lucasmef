[← Voltar ao perfil](../README.md)

# Sinal IA

## Inspeção local de metadados de imagens e vídeos

Scanner para macOS que lê metadados XMP, IPTC e estruturas C2PA e exibe as declarações de procedência encontradas nos arquivos. A análise é local, sem upload de mídia, e dispensa modelos de IA.

### Decisões técnicas

O parser impõe limites de leitura em bytes, tamanho de blocos e profundidade de estruturas. Os testes usam arquivos sintéticos e cobrem formatos, entradas inválidas e compatibilidade.

### Escopo da análise

A ferramenta apresenta as declarações registradas nos metadados. Não verifica criptograficamente as assinaturas C2PA nem determina autoria ou uso de IA a partir do conteúdo visual. A ausência de declaração nos metadados não permite concluir que a mídia foi produzida sem IA.

Os utilitários de limpeza são separados do fluxo de inspeção.

### Tecnologias

Swift · Parsing binário · XMP · IPTC · C2PA · macOS

### Código

[Consultar o código-fonte e as instruções de uso](https://github.com/lucasmef/anti-ia).

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
