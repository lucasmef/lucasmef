[← Voltar ao perfil](../README.md#user-content-projetos)

# LookPrint

## Extrair os looks completos de um vídeo

Criei o LookPrint para encontrar quadros em que uma composição de roupas e acessórios já está montada. O aplicativo roda no Mac, processa o vídeo localmente e exporta as imagens sem alterar o original.

### Como escolhe os quadros

O motor compara mudanças ao longo do vídeo para separar as composições. Ele procura momentos estáveis, próximos da montagem completa, e evita exportar várias imagens do mesmo estado.

Uso AVFoundation para ler e exportar os quadros e Vision para orientar a área de análise. A interface foi feita em SwiftUI, com integração ao Finder.

O detector usa regras visuais calibradas nos exemplos do projeto. Outros enquadramentos e movimentos podem exigir revisão das imagens selecionadas. Os vídeos de referência ficam fora do repositório.

`Swift` `SwiftUI` `AVFoundation` `Vision` `macOS`

[Ver o código e as instruções](https://github.com/lucasmef/print-videos)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
