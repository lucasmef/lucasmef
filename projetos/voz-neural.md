[← Voltar ao perfil](../README.md#user-content-projetos)

# Voz Neural

## Tratamento de voz para vídeos

Desenvolvo o Voz Neural para reduzir ruído e ajustar timbre e nível em gravações de voz feminina falada. O processamento roda localmente e gera um novo arquivo WAV, preservando a gravação original.

### Como trato o áudio

O RNNoise ajuda a identificar os trechos de voz, e o DeepFilterNet faz parte da redução de ruído. Depois, o processamento de sinal ajusta a presença e o nível da fala, com transições graduais entre voz e ambiência.

A saída usa dois canais idênticos para evitar a queda de nível que pode ocorrer ao centralizar um clipe mono em uma faixa estéreo no editor.

### Integração com o Premiere

Estou desenvolvendo um painel UXP com uma ponte em C++. A ideia é processar cada clipe selecionado e inserir o resultado em outra faixa, na posição original, sem substituir a mídia de origem.

Mantive Python e NumPy como referência para não mudar o resultado numérico ao ligar o processamento ao painel. Versões fixadas e comparações de hashes ajudam a detectar diferenças na saída.

O núcleo funciona localmente. A integração com o Premiere continua em desenvolvimento, e a calibração descrita no projeto se limita à voz feminina falada.

`Python` `NumPy` `DeepFilterNet` `RNNoise` `C++` `Adobe UXP`

[Ver o código e as dependências](https://github.com/lucasmef/voz-neural)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
