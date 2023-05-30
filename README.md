# Sharpe-ratio-Optimisation

Ce script permet d'optimiser le ratio de Sharpe d'un portefeuille, dans l'exemple le portefeuille est constitué des actions d'Apple, de Cisco, de IBM et d'Amazon et l'optimisation est appliquée à une stratégie de conservation


Le ratio de sharpe optimisé est de 0,8183 

Avec la répartition suivante : 

-Apple : 54,51%

-Amazon : 43,4%

-Cisco : 1,7%

-IBM : 0,39%

La répartition est très hétérogène et le ratio de Sharpe assez mauvais, il n'est pas recommendé de suivre cette stratégie

Le ratio de Sharpe est calculé de la manière suivante :

<img width="87" alt="Capture d’écran 2023-05-30 à 09 31 39" src="https://github.com/NFiuz5/Sharpe-ratio-Optimisation/assets/59396030/d567760e-0ca4-4ac2-b3b2-54f57f13d07a">

où R est l'espérance des rentabilités du portefeuille, r étant le référentiel de comparaison choisi (en général le taux de placement sans risque), et sigma l'écart-type du taux de rendement du portefeuille considéré.
