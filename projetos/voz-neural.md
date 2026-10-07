[← Voltar ao portfólio](../README.md#projetos)

# Voz Neural

## Menos ruído, espaço para a voz.

Uma gravação pode ter a fala nítida em um trecho e perder presença no seguinte. Desenvolvo o Voz Neural para tratar áudio localmente, com foco em voz feminina falada para vídeos curtos.

O projeto combina redução de ruído com processamento de timbre e nível. O núcleo funciona como um processador de arquivos WAV; a integração com o Adobe Premiere Pro está em desenvolvimento.

### Como o áudio é tratado

O RNNoise identifica os trechos de voz, e o DeepFilterNet participa da redução de ruído. Uma etapa de processamento de sinal ajusta a presença e o nível da fala, com transições graduais entre voz e ambiência.

A saída padrão usa dois canais idênticos. Essa escolha busca evitar a queda de nível que pode ocorrer ao centralizar um clipe mono em uma faixa estéreo no editor.

### Levar o fluxo para o Premiere

Estou desenvolvendo um painel UXP com uma ponte nativa em C++. O fluxo foi desenhado para processar cada clipe selecionado separadamente e inserir o resultado em uma nova faixa, na posição original, sem sobrescrever a mídia de origem.

Mantive o processamento em Python e NumPy como referência também nessa integração. Reescrever os cálculos em outra linguagem poderia mudar o resultado numérico; a ponte chama o mesmo processamento já usado nos testes locais.

### O que verifico

| Decisão | Motivo |
| :--- | :--- |
| Fixar versões do processamento | Reproduzir o resultado dos arquivos de referência. |
| Comparar amostras e hashes da saída | Detectar mudanças numéricas no áudio gerado. |
| Preservar os arquivos originais | Permitir comparar o tratamento e voltar à gravação de origem. |
| Processar um clipe por vez | Manter cada resultado associado ao trecho selecionado. |

### Estágio e limites

O núcleo está preparado para uso local. A integração ao Premiere segue em desenvolvimento. A calibração é específica para voz feminina falada; música e outros perfis de voz não fazem parte da validação descrita aqui.

### Tecnologias

`Python` `NumPy` `DeepFilterNet` `RNNoise` `C++` `Adobe UXP`

### Conheça o trabalho

Esta apresentação não inclui gravações de referência nem arquivos de clientes. Para conversar sobre o processamento e a integração com o editor, [fale comigo pelo LinkedIn](https://www.linkedin.com/in/lucasmef) ou [envie um e-mail sobre o Voz Neural](mailto:lucasmef@gmail.com?subject=Conhecer%20o%20projeto%20Voz%20Neural).

<!-- Adicionar demonstração pública somente com áudios autorizados e após confirmar o link. -->

---

[Ver o Rosto Natural →](./rosto-natural.md) · [Voltar ao portfólio](../README.md)
