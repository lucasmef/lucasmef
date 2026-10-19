[← Voltar ao portfólio](../README.md#user-content-projetos)

# Rosto Natural

## Tratamento local de pele e cabelo em vídeo

Desenvolvo o Rosto Natural para tratar pele e cabelos em vídeos com processamento local. O objetivo é preservar a textura e o contorno do rosto e manter o efeito estável entre quadros, sem alterar a geometria facial.

A integração com o Adobe Premiere Pro está em desenvolvimento.

### Processamento de imagem

O núcleo em C++ combina suavização em diferentes escalas com máscaras faciais. Os controles permitem ajustar pele, olheiras e cor, além de aplicar maquiagem leve. O rastreamento usa MediaPipe, com estabilização temporal para reduzir mudanças bruscas no tratamento.

O processamento de cabelos rebeldes separa a região a tratar da massa principal do cabelo e protege o rosto durante a reconstrução do fundo.

### Decisões técnicas

| Desafio | Abordagem do projeto |
| :--- | :--- |
| Preservar detalhes da pele | Suavização com controle de textura e comparação com as imagens de referência. |
| Respeitar os limites do rosto | Máscaras internas e proteção do contorno. |
| Acompanhar o movimento | Estabilização das detecções ao longo dos quadros. |
| Preparar o processamento em GPU | Núcleo CPU de referência e shader Metal com a mesma matemática facial. |

### Estágio atual e validação

O projeto reúne testes do núcleo e comparações de imagens para avaliar textura, contorno e alterações fora da área tratada. Esses resultados orientam a calibração do efeito.

O processamento foi validado fora do editor. Restam etapas de compilação e o teste completo dentro do Premiere. O desempenho em tempo real depende da integração final com a GPU.

### Tecnologias

`C++` `MediaPipe` `Metal` `Python` `JavaScript` `Adobe UXP`

### Código-fonte

[Consultar o repositório e as instruções de uso](https://github.com/lucasmef/rosto-natural).

### Contato

Para conversar sobre o processamento de imagem e a integração com o Premiere, [fale comigo pelo LinkedIn](https://www.linkedin.com/in/lucasmef) ou [envie um e-mail sobre o Rosto Natural](mailto:lucasmef@gmail.com?subject=Conhecer%20o%20projeto%20Rosto%20Natural).

<!-- Adicionar demonstração pública somente com mídias autorizadas e após confirmar o link. -->

---

[Ver o Voz Neural →](./voz-neural.md) · [Voltar ao portfólio](../README.md)
