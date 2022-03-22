<p align="center">
    <img height="100px" src="Images/Markdown.png">
</p>
<div align="center">
    <h2>Apprendre le Markdown par @colasnaudi</h2>
    <h4>Édition GitHub</h4>
</div>

## Table des matières
<!--ts-->
   * [Titres](#titres)
   * [Style de texte](#style-de-texte)
      * [Gras](##gras)
      * [Italique](##italique)
      * [Gras et Italique](##gras-et-italique)
      * [Bloc-notes](##bloc-notes)
      * [Monospaced](##monospaced)
      * [Souligné](##souligné)
      * [Rayé](##rayé)
      * [Boxed](##boxed)
      * [Subscript](##subscript)
      * [Superscript](##superscript)
   * [Mise en avant de la syntaxe](#mise-en-avant-de-la-syntaxe)
   * [Alignements](#alignements)
      * [Gauche](##gauche)
      * [Centre](##centre)
      * [Droit](##droit)
      * [Aligner du texte au centre](##aligner-du-texte-au-centre)
   * [Tableaux](#tableaux)
      * [Tableau html](##tableau-html)
      * [Autre tableau](##autres-tableaux)
      * [Double tableau](##double-tableau)
      * [Tableau sur plusieurs lignes](##tableau-sur-plusieurs-lignes)
   * [Liens](#liens)
   * [Images](#images)
   * [GIF](#gif)
   * [Listes](#listes)
      * [Liste ordonnée](##liste-ordonnée)
      * [Liste sur plusieurs niveaux](##liste-sur-plusieurs-niveaux)
      * [Liste à puces](##liste-à-puces)
      * [Case à cocher](##case-à-cocher)
   * [Règles horizontale](#règles-horizontale)
   * [Divers](#divers)
<!--te-->

# Titres

```
# Titres 1
## Titres 2
### Titres 3
#### Titres 4
##### Titres 5
```

# Titres 1
## Titres 2
### Titres 3
#### Titres 4
##### Titres 5

```
<h1>Titres 1</h1>
<h2>Titres 2</h2>
<h3>Titres 3</h3>
<h4>Titres 4</h4>
<h5>Titres 5</h5>
```

<h1>Titres 1</h1>
<h2>Titres 2</h2>
<h3>Titres 3</h3>
<h4>Titres 4</h4>
<h5>Titres 5</h5>

Titres 1
=
Titres 2
-

# Style de texte

```
Mise en gars
**Ceci est un texte avec un style.**
__Ceci est un texte avec un style.__
<strong>Ceci est un texte avec un style.</strong>

Italique
*Ceci est un texte avec un style.*
_Ceci est un texte avec un style._
<em>Ceci est un texte avec un style.</em>

Gras et italique
**_Ceci est un texte avec un style._**
<strong><em>Ceci est un texte avec un style.</em></strong>
```

## Gras

**Ceci est un texte avec un style.**

__Ceci est un texte avec un style.__

<strong>Ceci est un texte avec un style.</strong>


## Italique

*Ceci est un texte avec un style.*

_Ceci est un texte avec un style._

<em>Ceci est un texte avec un style.</em>

## Gras et italique

**_Ceci est un texte avec un style._**

<strong><em>Ceci est un texte avec un style.</em></strong>

## Bloc-notes

```
> Ceci est un texte avec un style.
> Ceci est un texte avec un style.
> 
> Ceci est un texte avec un style.
> 
> Ceci est un texte avec un style.
> Ceci est un texte avec un style.
>> Ceci est un texte avec un style.
>>> Ceci est un texte avec un style.
> **The quick brown fox** *jumps over the lazy dog.*
```

> Ceci est un texte avec un style.

> Ceci est un texte avec un style.
> 
> Ceci est un texte avec un style.
> 
> Ceci est un texte avec un style.

> Ceci est un texte avec un style.
>> Ceci est un texte avec un style.
>>> Ceci est un texte avec un style.

> **Ceci est un texte** *avec un style.*

```
Monospaced
<samp>Ceci est un texte avec un style.</samp>

Souligné
<ins>Ceci est un texte avec un style.</ins>

Rayé
~~Ceci est un texte avec un style.~~
```

## Monospaced

<samp>Ceci est un texte avec un style.</samp>

## Souligné

<ins>Ceci est un texte avec un style.</ins>

## Rayé

~~Ceci est un texte avec un style.~~


## Boxed
```
Boxed
<table><tr><td>Ceci est un texte avec un style.</td></tr></table>
```

<table><tr><td>Ceci est un texte avec un style.</td></tr></table>

## Subscript
```
Subscript <sub>Ceci est un texte avec un style.</sub>
```

Subscript <sub>Ceci est un texte avec un style.</sub>

## Superscript
```
Superscript <sup>Ceci est un texte avec un style.</sup>
```
Superscript <sup>Ceci est un texte avec un style.</sup>



# Mise en avant de la syntaxe

Une énumération est un type défini par l'utilisateur qui se compose d'un jeu de constantes intégrales nommées, appelées énumérateurs. Il se note `enum`.


```
enum Mois = {Janvier, Février, Mars, Avril, Mai, Juin, Juillet, Août, Septembre, Octobre, Novembre, Decembre};
```


```cpp
enum Mois = {Janvier, Février, Mars, Avril, Mai, Juin, Juillet, Août, Septembre, Octobre, Novembre, Decembre};
```

# Alignements
## Gauche
```
<p align="gauche">
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100" border="10"/>
</p>
```

<p align="left">
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100" border="10"/>
</p>

## Centre
```
<p align="centre">
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100" border="10"/>
</p>
```

<p align="center">
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100" border="10"/>
</p>

## Droit
```
<p align="droit">
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100" border="10"/>
</p>
```

<p align="right">
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100" border="10"/>
</p>

## Aligner du texte au centre
```
<h3 align="center"> Ce texte est aligné au centre. </h3>
```

<h3 align="center"> Ce texte est aligné au centre. </h3>


# Tableaux

## Tableau html
```
<table>
<tr>
<td width="33%"">
Ceci est un texte avec un style.
</td>
<td width="33%">
Ceci est un texte avec un style.
</td>
<td width="33%">
Ceci est un texte avec un style.
</td>
</tr>
</table>
```

<table>
<tr>
<td width="33%"">
Ceci est un texte avec un style.
</td>
<td width="33%">
Ceci est un texte avec un style.
</td>
<td width="33%">
Ceci est un texte avec un style.
</td>
</tr>
</table>

## Autres tableaux

```
| Défaut | Aligné à gauche | Aligné au centre | Aligné à droite |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |


| Défaut    | Aligné à gauche | Aligné au centre | Aligné à droite |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |


Défaut    | Aligné à gauche | Aligné au centre | Aligné à droite
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999 
999999999  | 999999999  | 999999999    | 999999999  
99999999   | 99999999   | 99999999     | 99999999   
9999999    | 9999999    | 9999999      | 9999999 
```

| Défaut | Aligné à gauche | Aligné au centre | Aligné à droite |
| - | :- | :-: | -: |
| 9999999999 | 9999999999 | 9999999999 | 9999999999 |
| 999999999 | 999999999 | 999999999 | 999999999 |
| 99999999 | 99999999 | 99999999 | 99999999 |
| 9999999 | 9999999 | 9999999 | 9999999 |


| Défaut    | Aligné à gauche | Aligné au centre | Aligné à droite |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |


Défaut    | Aligné à gauche | Aligné au centre | Aligné à droite
---------- | :--------- | :----------: | ----------:
9999999999 | 9999999999 | 9999999999   | 9999999999 
999999999  | 999999999  | 999999999    | 999999999  
99999999   | 99999999   | 99999999     | 99999999   
9999999    | 9999999    | 9999999      | 9999999 

## Double tableau
```
<table>
<tr>
<th>Titre 1</th>
<th>Titre 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>
```

<table>
<tr>
<th>Titre 1</th>
<th>Titre 2</th>
</tr>
<tr>

<td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td><td>

| A | B | C |
|--|--|--|
| 1 | 2 | 3 |

</td></tr> </table>

## Tableau sur plusieurs lignes
```
| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |
```

| A | B | C |
|---|---|---|
| 1 | 2 | 3 <br/> 4 <br/> 5 |

# Liens

```
[The-Ultimate-Markdown-Cheat-Sheet](https://github.com/lifeparticle/Markdown-Cheatsheet)
```

[The-Ultimate-Markdown-Cheat-Sheet](https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet)

```
[The-Ultimate-Markdown-Cheat-Sheet][reference text]

[The-Ultimate-Markdown-Cheat-Sheet][1]

[Markdown-Cheat-Sheet]

[reference text]: https://github.com/lifeparticle/Markdown-Cheatsheet
[1]: https://github.com/lifeparticle/Markdown-Cheatsheet
[Markdown-Cheat-Sheet]: https://github.com/lifeparticle/Markdown-Cheatsheet
```

[The-Ultimate-Markdown-Cheat-Sheet][reference text]

[The-Ultimate-Markdown-Cheat-Sheet][1]

[Markdown-Cheat-Sheet]

[reference text]: https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet
[1]: https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet
[Markdown-Cheat-Sheet]: https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet


```
[Example of a relative link](rl.md)
```

[Example of a relative link](rl.md)


Visit https://github.com/

# Images

```
![alt text](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

![alt text](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

```
![alt text][image]

[image]: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
```
![alt text][image]

[image]: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png

```
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"/>
```

<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100" border="10"/>

# GIF
<iframe src="https://giphy.com/embed/yjI5G3pE3NH3O" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/adult-swim-rick-and-morty-yjI5G3pE3NH3O"></a></p>

# Listes

## Liste ordonnée
```
1. Un
2. Deux
3. Trois
```

1. Un
2. Deux
3. Trois

## Liste sur plusieurs niveaux
```
1. Premier niveau
    1. Deuxième niveau
        - Troisième niveau
            - Quatrième niveau
2. Premier niveau
    1. Deuxième niveau
3. Premier niveau
    1. Deuxième niveau
```

1. Premier niveau
    1. Deuxième niveau
        - Troisième niveau
            - Quatrième niveau
2. Premier niveau
    1. Deuxième niveau
3. Premier niveau
    1. Deuxième niveau
    

```
- Premier niveau
    - Deuxième niveau
        - Troisième niveau
            - Quatrième niveau
- Premier niveau
    - Deuxième niveau
- Premier niveau
    - Deuxième niveau
```

- Premier niveau
    - Deuxième niveau
        - Troisième niveau
            - Quatrième niveau
- Premier niveau
    - Deuxième niveau
- Premier niveau
    - Deuxième niveau

## Liste à puces
```
* 1
* 2
* 3

+ 1
+ 2
+ 3


- 1
- 2
- 3
```

* 1
* 2
* 3

+ 1
+ 2
+ 3


- 1
- 2
- 3


```
<ul>
<li>Premier item</li>
<li>Deuxième item</li>
<li>Troisième item</li>
<li>Quatrième item</li>
</ul>
```

<ul>
<li>Premier item</li>
<li>Deuxième item</li>
<li>Troisième item</li>
<li>Quatrième item</li>
</ul>

## Case à cocher
```
- [x] Résoudre Bug 24
- [ ] Ajouter la documentation
- [ ] Ajouter des tests unitaires
```

- [x] Résoudre Bug 24
- [ ] Ajouter la documentation
- [ ] Ajouter des tests unitaires


# Règles horizontale
```
--- ou
*** ou
___
```

---

***

___


# Divers

```
\*   Asterisque
\\   Anti-slash
\`   Accent grave
\{}  Accolades
\.   Point
\!   Point d'exclammation
\#   HashTag ou dièze
\-   Tiret
\()  Parentheses
\+   Plus
\[]  Crochets
\_   Underscore
```

\*   Asterisque
\\   Anti-slash
\`   Accent grave
\{}  Accolades
\.   Point
\!   Point d'exclammation
\#   HashTag ou dièze
\-   Tiret
\()  Parentheses
\+   Plus
\[]  Crochets
\_   Underscore