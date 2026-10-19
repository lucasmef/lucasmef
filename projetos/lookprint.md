[← Voltar ao perfil](../README.md)

# LookPrint

## Extração de quadros de vídeos de moda

Desenvolvi um aplicativo nativo para macOS que identifica mudanças persistentes nas composições de roupas e acessórios em um vídeo. O aplicativo exporta quadros completos e preserva o arquivo original.

### Decisões técnicas

O motor usa AVFoundation na amostragem e na exportação, e Vision para orientar a região analisada. A comparação entre quadros filtra movimentos e prioriza imagens estáveis, próximas do estado completo de cada composição.

### Estágio atual e limitações

O detector usa regras visuais, com calibração restrita aos exemplos usados no desenvolvimento. Outros enquadramentos exigem revisão dos resultados. Os vídeos de referência não estão incluídos no repositório.

### Tecnologias

Swift · SwiftUI · AVFoundation · Vision · macOS

### Código

[Consultar o código-fonte e as instruções de uso](https://github.com/lucasmef/print-videos).

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
