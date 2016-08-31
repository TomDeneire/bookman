## Pacman
An old classic written in HTML5. Play [Pacman](http://pacman.thisismichaelorourke.com) live.

## Quick Install
Clone from GitHub and go into the directory.

```
$ git clone -b gh-pages https://github.com/caleorourke/pacman.git
$ cd pacman
```

Install Bundler.

```
$ [sudo] gem install bundler
```

Install runtime dependencies.

```
$ [sudo] bundle install
```

## Roll Your Own
Make a fresh clone and go into the directory.

```
$ git clone https://github.com/username/mrpacman.git
$ cd mrpacman
```

Create a new `gh-pages` branch.

```
$ git checkout --orphan gh-pages
```

Copy the contents from `/pacman` to `/mrpacman`.

```
$ [sudo] cp -r ~/pacman/* ~/mrpacman
```

Push your site to GitHub.

```
$ git add .
$ git commit -a -m "first commit"
$ git push origin gh-pages
```
