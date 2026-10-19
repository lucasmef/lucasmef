[← Voltar ao perfil](../README.md)

# Proxies Maker

## Previews leves para consultar vídeos

Ferramenta local para gerar versões pequenas de vídeos com Swift, Python e FFmpeg, preservando os arquivos originais. Inclui integração com o Finder e uma variante experimental com VideoToolbox.

### Decisões técnicas

Trabalhei em fila de conversão, acompanhamento de progresso, tratamento de subpastas e validação de saída. Há teste que gera mídia sintética para verificar conversão e integridade de áudio.

### Estado e limites

O FFmpeg precisa ser preparado conforme a documentação. A variante acelerada depende de hardware e não tem fallback de codificação por software. Os resultados são previews; a adequação como proxy de edição depende do uso.

### Tecnologias

Swift · Python · FFmpeg · VideoToolbox · macOS

### Código

[Consultar o código-fonte e as instruções de uso](https://github.com/lucasmef/proxies-maker).

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
