[← Voltar ao portfólio](../README.md#projetos)

# Rosto Natural

## Suavizar a imagem sem apagar a expressão.

Em vídeo, suavizar a pele não basta. O tratamento precisa preservar textura, respeitar o contorno do rosto e acompanhar o movimento sem oscilar entre quadros. Desenvolvo o Rosto Natural com esse objetivo, sem alterar a geometria facial.

É um projeto de processamento local de imagem, com integração ao Adobe Premiere Pro em desenvolvimento.

### O que estou construindo

O núcleo em C++ combina suavização em diferentes escalas com máscaras faciais. Os controles permitem ajustar pele, olheiras e cor, além de aplicar maquiagem leve. O rastreamento usa MediaPipe, com estabilização temporal para reduzir mudanças bruscas no tratamento.

Há também um processamento localizado para cabelos rebeldes. Ele separa a região a tratar da massa principal do cabelo e protege o rosto durante a reconstrução do fundo.

### Escolhas técnicas

| Desafio | Abordagem do projeto |
| :--- | :--- |
| Preservar detalhes da pele | Suavização com controle de textura e comparação com as imagens de referência. |
| Respeitar os limites do rosto | Máscaras internas e proteção do contorno. |
| Acompanhar o movimento | Estabilização das detecções ao longo dos quadros. |
| Preparar o processamento em GPU | Núcleo CPU de referência e shader Metal com a mesma matemática facial. |

### Validação e estágio atual

O projeto reúne testes do núcleo e comparações de imagens que verificam textura, contorno e alterações fora da área tratada. Essa avaliação orienta a calibração do efeito.

A implementação foi validada fora do editor. Ainda faltam etapas de compilação e o teste completo dentro do Premiere. O desempenho em tempo real também depende da integração final com a GPU; não apresento o projeto como um plugin já concluído.

### Tecnologias

`C++` `MediaPipe` `Metal` `Python` `JavaScript` `Adobe UXP`

### Conheça o trabalho

Esta página apresenta a proposta e as decisões técnicas, sem publicar mídias de referência ou o código do projeto. Para conversar sobre o desenvolvimento, [fale comigo pelo LinkedIn](https://www.linkedin.com/in/lucasmef) ou [envie um e-mail sobre o Rosto Natural](mailto:lucasmef@gmail.com?subject=Conhecer%20o%20projeto%20Rosto%20Natural).

<!-- Adicionar demonstração pública somente com mídias autorizadas e após confirmar o link. -->

---

[Ver o Voz Neural →](./voz-neural.md) · [Voltar ao portfólio](../README.md)
