[← Voltar ao portfólio](../README.md#projetos)

# Voz Neural

## Processamento local de voz para vídeo

Desenvolvo o Voz Neural para reduzir ruído e ajustar timbre e nível em gravações de voz feminina falada para vídeos curtos. O núcleo processa arquivos WAV localmente. A integração com o Adobe Premiere Pro está em desenvolvimento.

### Processamento de áudio

O RNNoise identifica trechos de voz. O DeepFilterNet atua na redução de ruído, e o processamento de sinal ajusta presença e nível da fala. As transições entre voz e ambiência são graduais.

A saída padrão contém dois canais idênticos. Essa configuração busca evitar a queda de nível que pode ocorrer ao centralizar um clipe mono em uma faixa estéreo do editor.

### Integração com o Premiere

Estou desenvolvendo um painel UXP com uma ponte nativa em C++. O fluxo prevê processar cada clipe selecionado e inserir o resultado em uma nova faixa, na posição original, preservando os arquivos de origem.

Mantive Python e NumPy como referência para o processamento numérico. A ponte chama o mesmo processamento usado nos testes locais para preservar os resultados da implementação de referência.

### Validação

| Decisão | Motivo |
| :--- | :--- |
| Fixar versões do processamento | Reproduzir o resultado dos arquivos de referência. |
| Comparar amostras e hashes da saída | Detectar mudanças numéricas no áudio gerado. |
| Preservar os arquivos originais | Permitir comparar o tratamento e voltar à gravação de origem. |
| Processar um clipe por vez | Manter cada resultado associado ao trecho selecionado. |

### Estágio atual e limitações

O núcleo está preparado para uso local. A integração ao Premiere segue em desenvolvimento. A calibração é específica para voz feminina falada. Música e outros perfis de voz estão fora do escopo de validação descrito no projeto.

### Tecnologias

`Python` `NumPy` `DeepFilterNet` `RNNoise` `C++` `Adobe UXP`

### Código-fonte

[Consultar o repositório e as instruções de uso](https://github.com/lucasmef/voz-neural).

### Contato

Para conversar sobre o processamento de áudio e a integração com o Premiere, [fale comigo pelo LinkedIn](https://www.linkedin.com/in/lucasmef) ou [envie um e-mail sobre o Voz Neural](mailto:lucasmef@gmail.com?subject=Conhecer%20o%20projeto%20Voz%20Neural).

<!-- Adicionar demonstração pública somente com áudios autorizados e após confirmar o link. -->

---

[Ver o Rosto Natural →](./rosto-natural.md) · [Voltar ao portfólio](../README.md)
