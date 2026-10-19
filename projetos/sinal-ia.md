[← Voltar ao perfil](../README.md)

# Sinal IA

## Inspecionar declarações de procedência sem enviar mídia

Scanner local para imagens e vídeos no macOS. Lê metadados XMP, IPTC e estruturas C2PA para apresentar declarações encontradas e suas limitações. Não faz upload nem precisa de modelo de IA.

### Decisões técnicas

O parser limita bytes lidos, tamanho de blocos e profundidade de estruturas. O projeto inclui fixtures sintéticas e testes de formatos, entradas inválidas e compatibilidade.

### Estado e limites

É um scanner de metadados, não um detector visual de IA nem um validador criptográfico C2PA. A ausência de declaração não prova ausência de IA. Os utilitários de limpeza são separados da inspeção.

### Tecnologias

Swift · Parsing binário · XMP · IPTC · C2PA · macOS

### Código

[Consultar o código-fonte e as instruções de uso](https://github.com/lucasmef/anti-ia).

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
