# Rede de Segmentação Semântica UNet com Acurácia de 88%

Bem-vindo ao repositório da Rede de Segmentação Semântica utilizando a arquitetura UNet! Este projeto oferece uma implementação ousada de uma rede de segmentação semântica usando a popular arquitetura UNet. A rede é treinada para realizar a segmentação precisa de objetos em imagens, permitindo identificar áreas de interesse e separá-las do fundo.

## Sobre o Projeto

Neste projeto, criamos uma rede de segmentação semântica usando a arquitetura UNet. A UNet é uma arquitetura de rede neural convolucional profundamente conectada, projetada especificamente para tarefas de segmentação de imagens. Ela possui uma arquitetura única, composta por um "encoder" que captura características das imagens e um "decoder" que reconstrói a segmentação da imagem original.

## Detalhes do Código

O código fornecido realiza diversas etapas, incluindo:

- Carregamento de checkpoints do modelo.
- Cálculo de métricas como IoU, Dice Score, Recall, FPR e FNR.
- Preparação e configuração de parâmetros, como taxa de aprendizado e tamanho do lote.
- Treinamento da rede com otimizador Adam e suporte a treinamento em precisão mista.
- Validação da rede e cálculo das métricas de desempenho.
- Visualização das previsões geradas em imagens.

## Resultados e Métricas

Durante o treinamento e a validação, a rede alcançou uma notável acurácia de 88%. Além disso, diversas métricas de desempenho, como IoU, Dice Score, Recall, FPR e FNR, são calculadas e registradas  no Wandb. Essas métricas fornecem uma avaliação completa da eficácia da rede de segmentação.

## Como Usar

1. Clone este repositório para o seu ambiente local.
2. Ajuste os diretórios de imagem e máscara nos parâmetros do código.
3. Personalize as transformações de treinamento e validação conforme necessário.
4. Execute o código para treinar a rede e validar seu desempenho.

## Visualizações e Contribuição

Este repositório também oferece a possibilidade de visualizar as previsões geradas pela rede. Além disso, você pode contribuir com melhorias, correções ou recursos adicionais para a implementação.

## Contato

Sinta-se à vontade para entrar em contato [Linkedin](www.linkedin.com/in/eduardo-lawson-da-silva-32b8a4224) para tirar dúvidas ou fornecer feedback. Espero que este projeto inspire você a explorar o poder da segmentação semântica com a arquitetura UNet!

Divirta-se explorando e criando! 🚀
