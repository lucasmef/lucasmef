[← Voltar ao perfil](../README.md)

# Proxies Maker

## Geração de versões leves de vídeos no macOS

Ferramenta local para converter vídeos em arquivos menores, preservando os originais. Reúne componentes em Swift e Python, usa FFmpeg e oferece integração com o Finder. Inclui uma variante experimental com VideoToolbox.

### Decisões técnicas

Trabalhei na fila de conversão, no acompanhamento de progresso, no processamento de subpastas e na validação dos arquivos gerados. Um teste gera mídia sintética para verificar a conversão e a integridade do áudio.

### Estágio atual e limitações

A execução depende da preparação do FFmpeg descrita na documentação. A variante com VideoToolbox depende do hardware e não oferece codificação alternativa por software. Os arquivos gerados servem para pré-visualização; seu uso como proxies de edição precisa ser avaliado conforme o fluxo de trabalho.

### Tecnologias

Swift · Python · FFmpeg · VideoToolbox · macOS

### Código

[Consultar o código-fonte e as instruções de uso](https://github.com/lucasmef/proxies-maker).

[Conversar comigo](https://www.linkedin.com/in/lucasmef) · [Voltar ao perfil](../README.md)
