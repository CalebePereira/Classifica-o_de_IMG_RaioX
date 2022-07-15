# Classifica-o_de_IMG_RaioX
Modelo treinado usando TensorFlow para classificar se está ou não com Pneumonia a partir de imagens de Raio-X

## Dataset

O conjunto de dados é organizado em 3 pastas (train, test, val) e contém subpastas para cada categoria de imagem (Pneumonia/Normal). São 5.863 imagens de Raio-X (JPEG) e 2 categorias (Pneumonia/Normal).

Imagens de radiografia de tórax (anterior-posterior) foram selecionadas a partir de coortes retrospectivas de pacientes pediátricos de um a cinco anos de idade do Guangzhou Women and Children's Medical Center, Guangzhou. Todas as radiografias de tórax foram realizadas como parte do atendimento clínico de rotina dos pacientes.

Disponível em: 
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download

## Modelos
Foram treinados modelos de Aprendizagem profunda.

VGG16: O teste apresentou uma precisão de 86%
Modelo treinado com 40 épocas e taxa de aprendizagem 0.0005

RESNET

EFFICIENTNET
