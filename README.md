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
        - 6.2
        - 6.3
        - 6.4

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