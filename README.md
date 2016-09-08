# Traduction des Accessibility Steps de Opquast

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Sommaire

- [Présentation générale](#pr%C3%A9sentation-g%C3%A9n%C3%A9rale)
- [Le projet Opquast](#le-projet-opquast)
- [Organisation des fichiers et méthodologie de traduction](#organisation-des-fichiers-et-m%C3%A9thodologie-de-traduction)
- [Statut des traductions](#statut-des-traductions)
- [Crédits et remerciements](#cr%C3%A9dits-et-remerciements)
- [Licences](#licences)
- [Et après ?](#et-apr%C3%A8s-)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Présentation générale

Ce projet a pour objectif de **traduire collectivement les listes Accessibility Steps** ([first step](https://checklists.opquast.com/fr/accessibility-first-step/) et [second step](https://checklists.opquast.com/fr/accessibility-second-step/)) du projet Opquast, afin qu'elles puissent **profiter à un public plus large**.

Nous, chez Clever Age, avons de plus en plus de clients à l'international qui acceptent de travailler avec les référenciels de bonnes pratiques Opquast, mais sont bloqués par le contenu essentiellement français, d'où le lancement de cette initiative. Nous lançons le projet, mais notre objectif est bien que tout cela revienne à Temesis, au sein du projet Opquast.

**La première langue cible est l'anglais**, pour laquelle le travail avait déjà été initié par Aurélien Levy et Stéphane Deschamps, qui ont déjà traduit tous les titres.

D'autres langues pourraient être ajoutées par la suite si des contributeurs le proposent, mais l'objectif est de finaliser l'anglais au préalable.

## Le projet Opquast

[Le projet Opquast](http://checklists.opquast.com/fr/workshops/) (Open Quality Standards) a pour objectif de faire avancer la qualité Web à travers des outils d'évaluation, des ressources, un annuaire. Le projet a notamment pour objectif d'élaborer, de faire vivre et d'assurer la diffusion libre de référentiels publics de bonnes pratiques.

## Organisation des fichiers et méthodologie de traduction

Chaque règle est décrite dans un fichier Markdown à part, avec :

- Une partie initiale *YAML Front Matter* pour quelques méta données ;
- Un titre de premier niveau pour la description de la règle ;
- Des titres de second niveau pour les trois composantes de la fiche.

Cette structure est calquée sur celle des fiches source disponibles sur <http://checklists.opquast.com/en/workshops/>.

Les premiers fichiers ont été initialisés, vous pouvez ajouter les manquants au fur et à mesure.

Pour proposer une traduction, vous pouvez donc [ajouter ou éditer directement une fiche (un des fichiers Markdown) sur l'interface Web de Github, qui vous proposera automatiquement de créer la *pull request* correspondante](https://help.github.com/articles/editing-files-in-another-user-s-repository/).

Si vous maîtrisez l'outillage technique Git/Github, vous pouvez bien entendu faire vous-même un fork du projet, et faire des *pull requests* directement.

Attention, merci de ne proposer qu' **une seule fiche en traduction par *pull request* **. Si vous traduisez plusieurs fiches, faites autant de *pull requests*. Mélanger plusieurs propositions au sein d'une unique *pull request* rend le travail collaboratif de revue et commentaire plus compliqué. Lisez *"[The 55 Commits Syndrome](https://oncletom.io/2013/the-55-commits-syndrome/)"* pour vous en convaincre.

## Statut des traductions

Ces tableaux sont générés automatiquement à partir des fiches en Markdown, notamment la méta donnée `statut` du *YAML Front Matter*. (le script de génération reste à écrire)

<!-- START statustable -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN statustable (yet to be written) TO UPDATE -->
### Accessibility first step

| id | description                                                                                                                                                      | en          |
|----|------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| 1  | [Use a W3C-conforming DTD syntax before the html element](accessibility-first-step/en/01\ -\ Use\ a\ W3C-conforming\ DTD\ syntax\ before\ the\ html\ element.md) | in progress |
| …  | …                                                                                                                                                                | …           |

### Accessibility second step

<!-- END statustable -->


## Crédits et remerciements

Merci à l'ensemble des contributeurs Opquast qui ont participé aux appels à commentaires qui ont permis d'élaborer la présente liste. Les projets de checklist Accessibility First et Second Steps ont été conduits par Aurélien Levy, Laurent Denis et Elie Sloïm, sous la direction et à l'initiative d'Aurélien Levy. Ont également participé : Jean-Pierre Villain, Olivier Nourry, Igor Maynaud, Delphine Malassingne, Nicolas Hoffmann, Monique Brunel, Romain Gervois, Pascal Weber, Marie, Johan Ramon, Philippe Vayssière, Steven Mouret, Nathalie Rosenberg, Benjamin Ach, Claire Bizingre, Axel Roche, Regis Lapeze, Cyril Lamotte, Denis Boudreau, Arthur Rigaud, Grégory les participants à l'atelier ParisWeb 2011 et de tous les contributeurs Opquast. Le Logo Opquast a été élaboré par Aurélien Levy et Elie Sloïm. Le Logo Temesis a été produit par Emmanuel Clément.

## Licences

Les bonnes pratiques sont publiées sous [licence Creative Commons BY-SA](http://creativecommons.org/licenses/by-sa/2.0/fr/). Vous pouvez en faire ce que vous souhaitez, même dans un cadre commercial, la licence choisie vous rend en quelque sorte co-propriétaire de ces contenus. La licence vous impose en revanche de maintenir la paternité du contenu, nous vous remercions donc par avance de citer l'origine, voire de faire un lien vers le site de la société Temesis ou celui du projet Opquast. Opquast est une marque française déposée à l'INPI.

## Et après ?

Vous pouvez faire absolument ce que vous voulez de cette liste, et notamment effectuer vos audits. Nous vous conseillons toutefois vivement d'utiliser [Opquast Reporting](http://reporting.opquast.com), service en ligne proposé par Temesis pour évaluer vos sites.

