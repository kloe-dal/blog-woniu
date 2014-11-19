#L'atelier Meteor
J'ouvre [Meteor Discover](http://fr.discovermeteor.com/) comme un apprenti ouvre la porte de l'atelier dans lequel il se forme. J'espère y réaliser ma maquette afin de devenir [aspirant](https://fr.wikipedia.org/wiki/Compagnons_du_Devoir). Meteor c'est un atelier de développement. On y trouve un ensemble d'outils, une architecture et des bibliothèques. Étant basé sur Node JS, la langue officielle est le Java-Script, coté client comme coté serveur. Cette particularité fait de lui un Framework imprégné par l’événementiel. Meteor semble adéquat pour la fabrication de ma première application web.
###S'installer
On entre dans l'atelier par le terminal. C'est par cette porte que l'on ouvre Meteor :

`meteor create projet` 

Une nouvelle porte apparaît, c'est dans cette pièce que nous allons construire notre projet :

`cd projet` 

Nous nous emparons de l'outil bootstrap :

`meteor add bootstrap`

On s'organise :

- */server* exécuté que par le serveur

- */client* exécuté par le client

*Tous les autres fichiers sont exécutés coté server comme coté client!*

- */public* données statiques (png, jpg....)

- */lib* chargé en premier

- *main.* est chargé en dernier

La mise en place est faite, les outils sont sortis et prêt à être utilisés. C'est sur cette base que le projet va se construire. La machine est lancée, l'atelier Meteor est en action,  il reste cependant à savoir comment piloter l'engin...

