[← Voltar ao perfil](../README.md#user-content-projetos)

# Rosto Natural

## Tratamento facial para vídeo

Núcleo de processamento facial em C++ para suavização de pele e correções localizadas. Máscaras e estabilização temporal controlam a aplicação do efeito ao longo dos quadros, com preservação de textura e geometria facial como critérios de validação.

### Processamento da imagem

O núcleo em C++ combina suavização em diferentes escalas com máscaras faciais. Há controles para pele, olheiras, cor e maquiagem leve. O rastreamento usa MediaPipe, com estabilização ao longo do vídeo.

O módulo de correção de cabelos rebeldes delimita a área tratada, preserva a região principal do cabelo e protege o rosto durante a reconstrução do fundo.

### Integração com o editor

O projeto tem testes do núcleo e comparações de imagens para conferir textura, contorno e alterações fora da área tratada. A implementação foi avaliada fora do Premiere; o teste completo no editor ainda está pendente.

O núcleo CPU serve de referência para o processamento em Metal. O desempenho em tempo real depende da integração final com a GPU.

`C++` `MediaPipe` `Metal` `Python` `JavaScript` `Adobe UXP`

[Ver o código e o estágio da integração](https://github.com/lucasmef/rosto-natural)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
