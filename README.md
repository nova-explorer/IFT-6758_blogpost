# IFT6758 Blog Post A-09

Blog Post pour le projet de IFT-6758

bundle exec jekyll serve

TODO:
- Edit
    - README.md
    - about.md
        - Voir si plus de détails sont pertinents
    - _config.yml
        - maybe some links?
    - Essayer d'ajuster la largeur du texte? le wrapping du code fait pas super beau

- Questions:
    - 4
        - 4.1 Possibilité de le mettre en markdown, le formattage du paragraphe est juste pas centré
    - 5
        - 5.2 Pas changé en html interactif puisque je pense que c'est intéressant de voir les trois graphiques côte-à-côte
    - 6
        - 6.1
        - 6.2 <br>
          La shot map est un outil efficace pour identifier les équipes qui ont réussi au cours d'une saison donnée. D'une manière générale, ces diagrammes permettent           d'identifier les zones de la glace offensive dans lesquelles une équipe est déficiente ou forte en matière de tirs. D'une manière générale, il est possible d'interpréter les équipes qui se sont distinguées au cours d'une saison donnée. Les équipes qui ont un plus grand nombre de zones rouges ont une plus grande probabilité de gagner des matchs, statistiquement parlant, étant donné qu'elles font plus de tentatives que la moyenne.
        - 6.3 <br>
          Colorado Avalanche au cours de la saison 2016-17 a affiché de petites zones où ils ont tiré plus que la ligue (minimalement), plutôt, la plupart de la glace offensive est couverte en bleu. Ces données peuvent indiquer que l'Avalanche n'a pas pris beaucoup de tirs au cours de cette saison, ce qui diminue ses chances de réussite. En revanche, les chiffres des tirs de la saison 2020-21 sont bien meilleurs, avec moins de zones bleues et plus de zones où les tirs sont supérieurs à ceux de la ligue. Notamment, à partir d'une distance de 10 pieds du côté droit du filet, ils ont obtenu de très bons résultats par rapport à la ligue. En augmentant leur nombre de tirs dans une zone où le score est si élevé, ils sont en bonne position pour réaliser une bonne saison. <br>
Compte tenu de toutes ces données et informations, il n'est pas surprenant d'apprendre que l'Avalanche du Colorado a terminé premier de sa division en 2020-21 tout en accumulant plus de points au total que n'importe quelle autre équipe de la ligue. À l'inverse, ils ont été de loin l'équipe la moins performante de la ligue lors de la saison 2016-17, récoltant 21 points de moins que l'équipe la deuxième moins bien placéee.
        - 6.4 <br>
          Comme dans l'étude sur l'Avalanche du Colorado, un tracé bleu foncé permet d'expliquer la faiblesse des Sabres de Buffalo, tandis que des tracés moins bleus et plus rouges pour le Lightning de Tamba Bay expliquent leur succès. Sur les trois saisons de 2018 à 2020, les Sabres affichent une large zone où ils tirent moins que la moyenne du côté droit de la glace offensive et n'affichent aucune zone où ils ont des chiffres de tir supérieurs à ceux de la ligue. Le Lightning, en revanche, présente moins de zones bleues et plus de zones rouges au cours de ces trois années, notamment lors de la saison 2020-21 où il tire plus que la ligue sur une grande partie du milieu de la patinoire offensive. Étant donné que Tamba Bay a remporté la Coupe Stanley lors des saisons 2019-20 et 2020-21, il n'est pas surprenant de voir ce type de tracés. <br>
          Les cartes des tirs sont assez descriptives étant donné que, statistiquement parlant, les équipes qui attaquent plus et tirent plus que la moyenne marqueront plus de buts et gagneront plus de matchs. Cependant, comme pour la plupart des statistiques, tout doit être pris avec un grain de sel. Le hockey est un sport complexe et de nombreux facteurs définissent une équipe performante. Par exemple, un bon gardien de but peut augmenter considérablement la force d'une équipe. Si une équipe a des shot maps qui ne sont pas très attrayantes (beaucoup de bleu et peu de rouge), cela ne suffit pas pour conclure que cette équipe s'est mal comportée au cours d'une saison donnée. Même si elle est faible sur le plan offensif, une équipe peut très bien gagner des matchs en étant forte sur le plan défensif et en ne concédant pas beaucoup de buts (un gardien de but fort aide dans ce domaine).


# Instructions pertinentes telles que copiées dans le README du template

## Installation

### Ubuntu

1. Install Ruby (I'm using v3.2.5)

```bash
sudo apt install ruby-full
```

2. Once installed, add the following to your `.bashrc` or whatever terminal startup script you may use:

```bash
export GEM_HOME="$HOME/.gem"
export PATH="$HOME/.gem/bin:$PATH"
```

3. Install bundler:

```bash
gem install jekyll bundler
```

4. Install dependencies:

From within this repository's root directory, run:

```
bundle install
```

### MacOS and Windows

Mac and Windows users can find relevant guides for installing Jekyll here:

- [Windows guide](https://jekyllrb.com/docs/installation/windows/)
- [MacOS guide](https://jekyllrb.com/docs/installation/macos/)

Additionally, you will need to do a few steps in Windows before serving you are able to serve your page locally. The steps below are Windows only, and you won't need them if you're on a Linux based machine.

### Windows Specific Steps:

Before running these, you'd want to make sure your Ruby and Jekyll installations are functional.

1. From within the repository's root directory, run:

```
bundle add webrick
```

2. Open the `gemfile` present in the root directory of the repository, and add the following line at the end of the file:

```
gem 'wdm', '>= 0.1.0'
```

3. Run the following command in the same directory:

```
gem install wdm
```

You should be able to serve the page locally on Windows after these steps.

## Serving the Page Locally

Once you've installed jekyll and all of the dependencies, you can now serve the webpage on your local machine for development purposes using the `jekyll serve` command, using bundle to handle any dependencies.
In your terminal, from the directory containing the Jekyll project run:

```bash
bundle exec jekyll serve
```

You should see something along the lines of:

```
> bundle exec jekyll serve
Configuration file: /home/USER/ift6758-blog-template/_config.yml
            Source: /home/USER/ift6758-blog-template
       Destination: /home/USER/ift6758-blog-template/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 0.661 seconds.
 Auto-regeneration: enabled for '/home/USER/ift6758-blog-template'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
```

If you see this, you've successfully served your web page locally!
You can access it at server address specified, in this case `http://127.0.0.1:4000/`.
