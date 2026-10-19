[← Voltar ao perfil](../README.md#user-content-projetos)

# Voz Neural

## Tratamento de voz para vídeos

Ferramenta de processamento local de voz que reduz ruído e ajusta timbre e nível. A calibração é voltada à voz feminina falada. O resultado é exportado para um novo WAV, preservando a gravação original.

### Cadeia de processamento

O RNNoise identifica os trechos de voz, e o DeepFilterNet atua na redução de ruído. Depois, o processamento de sinal ajusta a presença e o nível da fala, com transições graduais entre voz e ambiência.

A saída usa dois canais idênticos para evitar a queda de nível que pode ocorrer ao centralizar um clipe mono em uma faixa estéreo no editor.

### Integração com o Premiere

A integração em desenvolvimento usa um painel UXP e uma ponte em C++. O fluxo previsto processa os clipes selecionados e insere o resultado em outra faixa, na posição original, preservando a mídia de origem.

Python e NumPy servem de referência numérica para a integração com o painel. Versões fixadas e comparações de hashes ajudam a detectar diferenças na saída.

O núcleo funciona localmente; a integração com o Premiere continua em desenvolvimento.

`Python` `NumPy` `DeepFilterNet` `RNNoise` `C++` `Adobe UXP`

[Ver o código e as dependências](https://github.com/lucasmef/voz-neural)

[LinkedIn](https://www.linkedin.com/in/lucasmef) · [E-mail](mailto:lucasmef@gmail.com) · [Voltar ao perfil](../README.md)
