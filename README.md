# Segmentation of Prostate Deformations with Deep Learning

## Segmentação de Deformações da Próstata com Deep Learning

### Definição do Projeto

<div>
<img src="https://user-images.githubusercontent.com/54995990/191143197-2333b041-fbe3-4ba5-8d42-fe03ed7af36b.png" width="600px" />
</div>

A determinação do volume da próstata facilita a avaliação das deformações ou câncer da próstata e, em conjunto com outros parâmetros, pode ajudar a prever o estágio patológico da doença, oferece informações sobre o prognóstico e ajuda a prever a resposta ao tratamento. Informações sobre o tamanho, forma e localização da próstata em relação aos órgãos adjacentes também são uma parte essencial do planejamento cirúrgico para prostatectomia, radioterapia e terapias minimamente invasivas emergentes, como crioterapia e ultrassom focalizado de alta intensidade (HIFU). Neste trabalho vamos construir um modelo de IA que ao receber uma imagem de 
ressonância magnética da próstata será capaz de segmentar uma deformação e ajudar o médico a identificar algum tipo de distúrbio ou mesmo câncer.

**Referências:**

<a href="https://arxiv.org/abs/2011.07795">Deep learning in magnetic resonance prostate segmentation: A review and a new perspective</a>

<a href="https://arxiv.org/abs/1901.09462">A deep learning-based method for prostate segmentation in T2-weighted magnetic resonance 
imaging</a>

<a href="https://link.springer.com/article/10.1007/s00066-020-01607-x">Segmentation of prostate and prostate zones using deep learning</a>

<a href="https://www.sciencedirect.com/science/article/abs/pii/S1361841513001734">Evaluation of prostate segmentation algorithms for MRI: The PROMISE12 challenge</a>

Fonte de Dados:

https://promise12.grand-challenge.org/

### Etapas do Projeto

- Carregando Imagens e Máscaras
- Visualizando Imagens e Máscaras
- Modelagem da Arquitetura U-Net
- Avaliação do Modelo
