[← Voltar ao perfil](../README.md#user-content-projetos)

# Voz Neural

## Tratamento de voz para vídeos

Processamento local de voz com redução de ruído, ajustes de timbre e controle de nível. Calibração para voz feminina falada e exportação de um novo WAV, preservando a gravação original.

### Cadeia de processamento

O RNNoise ajuda a identificar os trechos de voz, e o DeepFilterNet faz parte da redução de ruído. Depois, o processamento de sinal ajusta a presença e o nível da fala, com transições graduais entre voz e ambiência.

A saída usa dois canais idênticos para evitar a queda de nível que pode ocorrer ao centralizar um clipe mono em uma faixa estéreo no editor.

### Integração com o Premiere

A integração em desenvolvimento usa um painel UXP e uma ponte em C++. O fluxo previsto processa os clipes selecionados e insere o resultado em outra faixa, na posição original, preservando a mídia de origem.

Python e NumPy servem de referência numérica para a integração com o painel. Versões fixadas e comparações de hashes ajudam a detectar diferenças na saída.

O núcleo funciona localmente. A integração com o Premiere continua em desenvolvimento, e a calibração descrita no projeto se limita à voz feminina falada.

`Python` `NumPy` `DeepFilterNet` `RNNoise` `C++` `Adobe UXP`

[Ver o código e as dependências](https://github.com/lucasmef/voz-neural)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
