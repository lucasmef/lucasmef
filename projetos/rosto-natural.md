[← Voltar ao perfil](../README.md#user-content-projetos)

# Rosto Natural

## Tratamento facial para vídeo

Desenvolvo o Rosto Natural para suavizar a pele e ajustar detalhes do rosto, preservando textura e sem alterar intencionalmente a geometria facial. O tratamento precisa acompanhar o movimento sem ficar oscilando entre os quadros.

### Processamento da imagem

O núcleo em C++ combina suavização em diferentes escalas com máscaras faciais. Há controles para pele, olheiras, cor e maquiagem leve. O rastreamento usa MediaPipe, com estabilização ao longo do vídeo.

Também trabalho em um tratamento localizado de cabelos rebeldes. Ele separa a área a corrigir do cabelo que deve ser preservado e protege o rosto durante a reconstrução do fundo.

### Integração com o editor

O projeto tem testes do núcleo e comparações de imagens para conferir textura, contorno e alterações fora da área tratada. A implementação foi avaliada fora do Premiere; o teste completo no editor ainda está pendente.

O núcleo CPU serve de referência para o processamento em Metal. O desempenho em tempo real depende da integração final com a GPU.

`C++` `MediaPipe` `Metal` `Python` `JavaScript` `Adobe UXP`

[Ver o código e o estágio da integração](https://github.com/lucasmef/rosto-natural)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
