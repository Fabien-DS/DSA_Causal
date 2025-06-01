# Formation DSA de l'IRM
# Introduction à la causalité

Ce repo contient les exercices pour le module d'Introduction à la causalité proposé par Fabien FAIVRE dans le cadre de la formation Data Science pour l'Actuaire de l'Institut Risk Management de l'Institut des Actuaires

Prérequis :
- avoir installé ['uv'](https://github.com/astral-sh/uv)
- avoir installé libgraph-dev : sous Ubuntu :
- `sudo apt install graphviz libgraphviz-dev graphviz-dev pkg-config`
- puis ajouté pygraphviz : `uv add --config-settings="--global-option=build_ext" \
              --config-settings="--global-option=-I/opt/local/include/" \
              --config-settings="--global-option=-L/opt/local/lib/" \
              pygraphviz`
  [source](https://github.com/astral-sh/uv/issues/7992)
L'utilisation de se répertoire suppose que ['uv'](https://github.com/astral-sh/uv) a déjà été installé sur la machine de l'utilisateur. Après avoir cloné le repo, en se mettant à la racine de ce dernier, utiliser la commande `uv run --with jupyter jupyter lab` pour lancer une session jupyter lab avec le bon environnement.
