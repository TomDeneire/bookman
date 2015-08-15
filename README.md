## Pacman

An old classic, written in HTML5. Visit [pacman.thisismichaelorourke.com](http://pacman.thisismichaelorourke.com) to play it live.

## Quick Install

1. Clone from GitHub and go into the directory.

        $ git clone -b gh-pages https://github.com/caleorourke/pacman.git
        $ cd pacman


2. Install Bundler.

        $ [sudo] gem install bundler


3. Install runtime dependencies.

        $ [sudo] bundle install


## Roll Your Own

1. Make a fresh clone and go into the directory.

        $ git clone https://github.com/username/mrpacman.git
        $ cd mrpacman

2. Create a new `gh-pages` branch.

        $ git checkout --orphan gh-pages

3. Copy the contents from `/pacman` to `/mrpacman`.

        $ [sudo] cp -r ~/pacman/* ~/mrpacman

4. Push your site to GitHub.

        $ git add .
        $ git commit -a -m "first commit"
        $ git push origin gh-pages

## License

<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Pacman Canvas</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://platzh1rsch.ch" property="cc:attributionName" rel="cc:attributionURL">Platzhersh</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/platzhersh/pacman-canvas" rel="dct:source">Pacman Canvas</a>.

Feel free to use, copy, or modify this code, just as long as you give some credit to the original author, [Platzhersh](http://github.com/platzhersh).
