[← Voltar ao perfil](../README.md#user-content-projetos)

# LookPrint

## Seleção e exportação de quadros no macOS

Aplicativo macOS para identificar quadros com composições completas de roupas e acessórios em vídeos de moda. Processamento local e exportação de imagens sem alteração do vídeo original.

### Como escolhe os quadros

O motor compara mudanças ao longo do vídeo para separar as composições. Ele procura momentos estáveis, próximos da montagem completa, e evita exportar várias imagens do mesmo estado.

AVFoundation realiza a leitura e exportação dos quadros; Vision orienta a área de análise. Interface em SwiftUI, com integração ao Finder.

O detector usa regras visuais calibradas nos exemplos do projeto. Outros enquadramentos e movimentos podem exigir revisão das imagens selecionadas. Os vídeos de referência ficam fora do repositório.

`Swift` `SwiftUI` `AVFoundation` `Vision` `macOS`

[Ver o código e as instruções](https://github.com/lucasmef/print-videos)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
