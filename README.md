# SkinLesion-Classification

### Definição do Projeto

A dermoscopia é um dispositivo de observação óptica, pelo qual examinamos os detalhes das estruturas minúsculas das lesões de pele melanocítico. Os médicos geralmente usam dermoscopia para fazer um diagnóstico de nevo benigno e melanoma maligno. 

**Classificação da lesão da pele**

O câncer de pele é o câncer mais comum em todo o mundo, com o melanoma sendo a forma mais mortal. A dermoscopia é uma modalidade de imagem da pele que tem demonstrado melhora para o diagnóstico de câncer de pele em comparação com a inspeção visual sem ajuda. No entanto, os médicos devem receber treinamento adequado para que essas melhorias sejam realizadas. Para tornar a expertise mais amplamente disponível, a International Skin Imaging Collaboration (ISIC) desenvolveu o ISIC Archive, um repositório internacional de imagens dermoscópicas, tanto para fins de treinamento clínico, quanto para apoiar pesquisas técnicas para análises algorítmicas automatizadas, hospedando os Desafios ISIC. 

Abaixo temos varias imagens positivas para Basal cell carcinoma (BCC), Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) (BKL), Melanoma (MEL) e Melanocytic nevus (NV).

<div>
<img src="https://user-images.githubusercontent.com/54995990/162527309-aa0980d0-4082-4631-b217-6451cfe109d1.png" width="1000px" />
</div>

**Referências:**

<a href="https://www.dermatologyadvisor.com/home/topics/skin-cancer/deep-learning-models-for-skin-cancer-detection/">Deep Learning Models for Skin Cancer Detection</a>

<a href="https://www.nature.com/articles/s41598-019-56522-8">An intuitive explanation of dermoscopic structures by digitally reconstructed pathological horizontal top-down view images</a>

<a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6562065/">kin cancer detection by deep learning and sound analysis algorithms: A prospective clinical study of an elementary dermoscope</a>

<a href="https://www.cancer.org/cancer/melanoma-skin-cancer/detection-diagnosis-staging.html">Early Detection, Diagnosis, and Staging</a>

<a href="https://www.nature.com/articles/nature21056">Dermatologist-level classification of skin cancer with deep neural networks</a>

**Base de Imagens**

A base de dados 25.331 imagens que estão disponíveis para treinamento em 8 categorias diferentes. A meta desse dataset é o desafio ISIC 2019, que consiste na classificação de imagens dermoscópicas entre nove categorias de diagnóstico diferentes:

- Melanoma (MEL)
- Melanocytic nevus (NV)
- Basal cell carcinoma (BCC)
- Actinic keratosis (AK)
- Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) (BKL)
- Dermatofibroma (DF)
- Vascular lesion (VASC)
- Squamous cell carcinoma (SCC)
- None of the others (UNK)

Porém, nosso intuido é o aprendizado, não iremos utilizar todas as classes, pelo motivo de os dados estarem bastante desbalanceados, com poucas amostras para diversas classes, por conta disso iremos utilizar apenas as classes: Basal cell carcinoma (BCC); Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis) (BKL); Melanoma (MEL); e Melanocytic nevus (NV).

Fonte de Dados:

https://challenge2019.isic-archive.com/

### Etapas do Projeto

**Primeira Etapa:**

- Carregando e Compreendendo os Dados
- Limpeza e Transformação dos Dados
- Limpeza e Transformação das Imagens
- Balanceamento de Classe para Classificação Multiclasse
- Preparação das Amostras de Teste
- Preparação das Amostras de Treino
- Redimensionamento das Imagens (treino/teste)
- Visualização das Imagens
- Divisão em Dados de Treino, Validação e Teste
- Normalização



