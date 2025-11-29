# Tutorial sobre models de regressió bayesians amb Bambi

## Abans de començar

Abans de començar és recomanable crear un ambient virtual per a executar
el codi del tutorial. Una de les dependències és PyMC, que en la versió
bàsica per defecte necessita accés a compiladors de C i per tant és millor instal·lar
a través de conda/mamba.

Si no teniu conda/mamba disponible al vostre ordinador, instal·leu [miniforge](https://github.com/conda-forge/miniforge).

Per tal de crear l'ambient virtual i instal·lar-hi totes les dependències, cloneu aquest repositori
i executeu la instrucció de conda mostrada:

```bash
conda env create -f environment.yml
```

Un cop instal·lat, activeu l'ambient amb `conda activate pyday-bambi`.

## Per tal de seguir el tutorial

Obrir la llibreta de Jupyter que hi ha en aquest repositori. Els primers exemples
ja són allà i només cal executar, després hi haureu d'experimentar amb models vosaltres mateixos.

Un cop acabat el tutorial intentaré publicar també la versió amb notes i comentaris que
s'hagin fet durant la sessió.
