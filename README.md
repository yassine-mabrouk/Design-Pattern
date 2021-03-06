# design pattern
## 1) Generality
### 1.1 Definition
software design pattern is a general, reusable solution to a commonly occurring problem within a given context in software design.
## 2) Implementation and demonstration
### Remarks
 - you will find a simple description for each example in the class demo for each design pattern
### 2.1 design pattern Strategy
- Catégorie :
    - Comportement
- Definition:
    - Strategy is a behavioral design pattern that lets you define a family of algorithms, put each of them into a separate class, and make their objects interchangeable.
- description of examples (implementations)
    - Example 1 :simple implementation design pattern  decorator
    - Example 2 : choose dynamic strategy
   
### 2.2 design pattern Observer
- Catégorie :
    - Comportement
- Definition:
    - Le pattern Observer définit une relation entre les objets de type un à plusieurs, de façon que, lorsqu’un objet change d’état, tous ce qui en dépendent en soient informés et soient mis à jour automatiquement
- examples:
    - Example 1 :Observable / Observers
    - Example 2 :weather Channel
### 2.3 design pattern Decorator
- Catégorie :
  - Structure 
- Définition
   - Organiser les objets en structure arborescente afin de représenter une hiérarchie.
   - Permettre à la partie cliente de manipuler un objet unique et un objet composé de la
- examples:
  - Example 1 : simple implementation design pattern decorator
  - Example 2 : StarbuzzCoffee
  
### 2.4 design pattern Composite
- Catégorie :
  - Structure
- Définition
  - Organiser les objets en structure arborescente afin de représenter une hiérarchie.
  - Permettre à la partie cliente de manipuler un objet unique et un objet composé de la même manière.
  - Le Design Pattern permet d'isoler l'appartenance à un agrégat
- examples:
  - Example 1 : file system
### 2.5 design pattern Adapter
- Catégorie :
  - Structure
- Objectif
  - Convertir l'interface d'une classe dans une autre interface comprise par la partie cliente.
  - Permettre à des classes de fonctionner ensemble, ce qui n'aurait pas été possible à cause de leurs interfaces incompatibles.
- Résultat :
  - Le Design Pattern permet d'isoler l'adaptation d'un sous-systèm
- examples:
  - Example 1 :computer ==> Connect ==>Devices
### 2.6 design pattern Proxy
- Catégorie :
  -  Structure
- Objectif
  - Fournir un intermédiaire entre la partie cliente et un objet pour contrôler les accès à ce dernier
- Résultat :
  -  Le Design Pattern permet d'isoler le comportement lors de l'accès à un objet.
- examples:
  - Example 1 :Proxy de cache et proxy de security
### 2.7 design pattern Template Method
- Catégorie :
  - Comportement
- Objectif du pattern
  - Définir le squelette d'un algorithme en déléguant certaines étapes à des sous-classes.
- Résultat :
  - Le Design Pattern permet d'isoler les parties variables d'un algorithme.
- Raisons d’utilisation :
  - Une classe possède un fonctionnement global, mais les détails de son algorithme doivent être spécifiques à ses sous-classes.

### 2.8 design pattern State
- Catégorie :
  - Comportement
- Objectif
  - Changer le comportement d'un objet selon son état interne.
- Résultat :
  - Le Design Pattern permet d'isoler les algorithmes propres à chaque état d'un objet.
  
## 3) Source
for more details consult the following sources
- demo video  [Design pattern course and demo ](https://youtu.be/paXdEHMKmh8)
- definition [Software design pattern](https://en.wikipedia.org/wiki/Software_design_pattern)
### Enjoy !!