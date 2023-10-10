# Machine Learning Portfolio: A brief overview

### Get in touch:
.
[<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]
[<img align="left" alt="Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]


## [Chicken Blood Vessel Segmentation](https://github.com/RGivisiez/Blood-Vessel-Segmentation):

Every day, students of pharmacy at the Federal University of Minas Gerais (UFMG) use chicken eggs to study the effects of drugs on blood vessels. Because of this, it is essential to automate, speed up, and improve the accuracy of blood vessel segmentation in chicken eggs; better segmentation guarantees reliable results with good reproducibility. This project uses machine learning algorithms to automate the process, while maintaining speed and improving accuracy.

![Chicken Egg Blood Vessel Segmentation](https://github.com/RGivisiez/Blood-Vessel-Segmentation/blob/main/images/vessel-egg.png)

-----

## [E-commerce: Identificando atrasos na entrega](https://github.com/RGivisiez/Olist-delivery-delay):

Como foi visto nos resultados do notebook [E-Commerce Seller](https://github.com/RGivisiez/Olist-sellers-K-Means/blob/main/E_Commerce_Seller.ipynb), uma baixa avaliação dos vendedores está correlacionada com o atraso da entrega. Para melhorar as avaliações dos vendedores, e também deixar o consumir mais satisfeito, iremos criar uma algoritmo que indique a possibilidade de atraso na entrega.

-----

## [E-commerce: Identificando características de bons vendedores](https://github.com/RGivisiez/Olist-sellers-K-Means):

Empresas que trabalham com marketplace agregam diversos tipos de vendedores em seus sistemas, porém nem todos eles conseguem deixar seus clientes satisfeitos. Sendo assim, é importante identificar característica de vendedores bem avaliados pelos usuários e incentivar que outros se comportem da mesma forma. Com a quantidade de dados disponível sobre os vendedores, é possível identificar de forma automatizada essas características e propor mudanças tanto por parte dos vendedores quanto por parte da empresa.

![Sellers_clusters](https://github.com/RGivisiez/Olist-sellers-K-Means/blob/c7289e289c3dca66aabdada6e6a1cbfa1ca33905/sellers_cluster.png)

-----

## [Análise de default usando o dataset do Nubank](https://github.com/RGivisiez/credit-card-risk-analysis):

O Nubank, fintech brasileira, promoveu uma competição com o intuito de buscar por novos talentos. Um dos objetivos propostos na competição foi o de criar um modelo que conseguisse prever quais clientes não iriam honrar com suas dívidas, incorrendo no que é chamado de default. Para fazer a previsões, era usado um dataset com informações sobre o cliente. Um dos grandes problemas desse tipo de dataset é seu desbalanço de classe, temos uma quantidade enorme de clientes que pagam suas dívidas e uma quantidade mínima que não pagam, isso torna a previsão difícil. 

O que você vai ver neste notebook:
  1. **Limpeza dos dados** e produção de features novas.
  2. Uso de **Pipeline** para facilitar a manipulação dos dados em diversos modelos e minimizar as chances de data leak.
  3. Como lidar com um **dataset desbalanceado**.
  4. **Escolha de métricas** para dataset desbalanceados.
  5. Conversão de features para categóricas ordenadas e para **One Hot Enconder** (OHE).
  6. Redução de skewness das features usando **log ou QuantileTransformer**.
  7. Uso de gridsearch para buscar os melhores parâmetros dos modelos.
  8. Modelos usados: **Decision Tree**, **Random Tree**, **Neural Network**, **Logistic Regression**, **Bagging**, **Random Patches**, **Adaboost** e **Voting Classifier**. 
  9. Discussão dos resultados obtidos.

-----

## [Recommendation Systems](https://github.com/RGivisiez/recommendation-systems):

Recommendation systems play an important role in filtering information before any user can consume it, whether by recommending movies to be watched or items a consumer might want. In this project, we build two recommendation systems using **Nearest Neighbor** and **Matrix Factorization**. Moreover, using the **t-SNE** algorithm, it is shown that a naive implementation of those algorithms has biases. They learn to recognize blockbuster movies from other movies as they are rated more often and with a higher rating score. That can lead to an algorithm prone to recommend more blockbuster movies than any other.

<img src="https://github.com/RGivisiez/recommendation-systems/blob/main/img/t-sne.png" alt="t-SNE" style="width:500px;"/>

-----

## [Image Generation with GANs](https://github.com/RGivisiez/WcGAN-GP-MNIST):

GAN is a machine learning model that can learn how to replicate the properties of a dataset. For example, a GAN trained in a dataset of breast cancer images learns how to generate new images similar to those seen in the dataset. Therefore, a GAN can be used to generate anonymized medical images, as they do not belong to any human, but still describe the disease characteristics. In this project, because GANs require a lot of computational resources and time, we will use two simple models to generate images of numbers.

![model2](https://github.com/RGivisiez/WcGAN-GP-MNIST/blob/main/img/model2.png)


-----

GitHub Template Photo by <a href="https://unsplash.com/@halacious?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Hal Gatewood</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

[mysite]: https://rgivisiez.github.io/
[twitter]: https://twitter.com/ronaldogivisiez/
[instagram]: https://instagram.com/ronaldo_givisiez/
[linkedin]: https://linkedin.com/in/ronaldo-givisiez/
