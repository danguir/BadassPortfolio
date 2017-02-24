# Creation de siteweb sur github


1. creation projet sur [github](http://github.com/new)
1. Open terminal

    $ cd C:/wamp64/www
    $ foundation new

1. cd typeformExo

    $ git init
    $ git add .
    $ git commit -m 'message initial'
    $ git remote add origin https://github.com/danguir/typeformExo.git
    $ git push -u origin master


## Lancer foundation (compiler les fchiers scss en css)

    $ npm start

## Ajouter un typeforme et le lancer en ligne
    $ git commit m- 'update index add typeform link'
    $ git push
    $ git branch gh-pages (create a branch)
    $ git checkout nonbranche (go to nonbranche)
