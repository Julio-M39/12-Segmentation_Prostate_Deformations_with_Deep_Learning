# Segmentation of Prostate Deformations with Deep Learning

## Segmentação de Deformações da Próstata com Deep Learning

OBS: Caso o Github não renderize o arquivo .ipynb use os links abaixo:

- <a href="https://nbviewer.org/github/Julio-M39/12-Segmentation_Prostate_Deformations_with_Deep_Learning/blob/main/Segmenta%C3%A7%C3%A3o%20de%20Deforma%C3%A7%C3%B5es%20da%20Pr%C3%B3stata.ipynb">Clique aqui!</a> 

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

### Resultados

| DICE   | IOU     | Sensibilidade | Especificidade | Acurácia | AUC | Precisão | Fscore |
| ------ | ------- | ------------- | -------------- | -------- | --- | -------- | ------ |
|  91 %  |   84 %  | 92 %          | 100 %          | 100 %    | 96 %| 91 %     | 91 %   |

**Resultados Visuais**

Na imagem abaixo podemos ver os resultados visuais para a segmentação de deformações na próstata.

<div>
<img src="https://user-images.githubusercontent.com/54995990/192004341-b2f87cdd-39f2-44e8-9ccc-0ea9f98ea471.png" width="600px" />
</div>
