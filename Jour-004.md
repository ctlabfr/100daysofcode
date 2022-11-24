# Sytem Design, classes utilitaires en CSS 

## Objectifs du jour
- Continuer le cours [Create a Design System with CSS](https://www.youtube.com/watch?v=lRaL-8qZ0mM) & [Github du cours](https://github.com/kevin-powell/space-tourism)

## Ce que j'ai réalisé aujourd'hui
- Finalisation de la typographie des titres
- Mise en place de classes utilitaires pour gérer les espacements

## Ce que j'ai appris aujourd'hui
``` css
/* fichier css */
.flow > * + * {
/* Ce style s'appliquera à tous les enfants directs d'une balise à l'exception du premier*/
}
``` 
Cette déclaration n'étant pas des plus explicites on peut la remplacer par l'équivalent suivant
``` css
/* fichier css */
.flow > *:not(:first-child) {

}
``` 

- Découverte des sélecteurs CSS  [:where](https://developer.mozilla.org/en-US/docs/Web/CSS/:where)  et  [:is]()

- Découverte de l'agorithme [Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity) utilisé par les navigateurs pour déterminer quel style appliquer

## Ressources

[Toutes les ressources de mon 100daysofcode](Ressources.md)