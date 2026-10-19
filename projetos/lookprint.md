[← Voltar ao perfil](../README.md)

# LookPrint

## Quadros úteis sem assistir ao vídeo inteiro

Desenvolvi um app nativo para macOS que encontra mudanças persistentes nas composições de roupas e acessórios de um vídeo e exporta quadros completos. O original é preservado.

### Decisões técnicas

O motor usa AVFoundation para amostragem e exportação e Vision para orientar a região de análise. Comparações temporais filtram movimento e favorecem quadros estáveis próximos do estado completo de cada composição.

### Estado e limites

É um detector baseado em regras visuais, calibrado em exemplos específicos. Não compreende moda de forma universal e exige revisão em outros enquadramentos. Os vídeos de referência não fazem parte do código.

### Tecnologias

Swift · SwiftUI · AVFoundation · Vision · macOS

### Código

[Consultar o código-fonte e as instruções de uso](https://github.com/lucasmef/print-videos).

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
