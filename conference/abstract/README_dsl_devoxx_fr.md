# Conference Session

# How to create a fluent API DSL with lambda builders? 

en_US : With the dOOv framework, we are trying to solve a common problem with software: 
performance vs. readability vs. type-safety. Since Java 8, lambdas offer the 
ability to compose functions at runtime with high performance. We built a 
fluent API using lambdas to write validation and mapping logic with a DSL. It 
enables the written application rules to be introspected and profiled by 
visiting the DSL abstract syntax tree at runtime. During this session we will 
discuss how the framework is designed, the issues that we encountered 
generating the natural language output, failure cause analysis, and AST 
rewriting.

# Comment créer son propre langage avec un fluent API et un lambda builder ?

fr_FR : Avec le framework dOOv, nous adoptons une nouvelle approche pour résoudre un problème
récurrent dans nos applications: conjuguer performance, lisibilité et typage fort.
Depuis Java 8, les lambdas permettent de composer des fonctions avec d'excellentes performances à l'exécution.
dOOv fournit une fluent API qui permet d'écrire la logique d'une application avec un DSL 'pur Java' 
et construit des lambdas pour l'exécution.
Il devient possible de parcourir l'arbre de syntaxe du DSL lors de l'exécution et d'effectuer dynamiquement
des réécritures. Pendant la session, nous présenterons le fonctionnement du framework,
les problèmes rencontrés pour générer du langage naturel, l'instrumentation du code écrit en DSL et 
la réécriture des arbres de syntaxe pour les afficher sous forme canonique.

## Status 

TO_SUBMIT

# Hands-On-Labs

# Getting Started with custom DSLs using the dOOv framework

en_US : Have you heard a lot about the advantages of DSLs but don't know where to 
start? In this session, we will be modernizing a webshop application,
which has validation rules with BeanValidation and implements 
business logic and mapping code with plain old Java. Using dOOv, 
attendees will generate a Java-based DSL and migrate incrementally the 
logic and mapping code of the application. First, attendees will use 
dOOv to rewrite BeanValidation rules and discover the benefits of a 
strongly-typed fluent API to express constraints of a model.
Then we will migrate the application logic and the mapping code to ensure 
the compliance and governance of the partner exchanges. Finally, we will 
evaluate the performance and flexibility gains.

# Adopter une approche DDD en Java avec le framework dOOv

fr_FR : 
Avez-vous toujours voulu expérimenter avec l'approche DDD sur votre projet 
mais vous ne savez pas par où commencer ?  
Dans cette session, nous allons vous montrer comment moderniser à l'aide d'un
DSL 'pur Java', une application de e-commerce qui utilise des règles de validation
écrites avec BeanValidation et une logique métier écrite en Java.
Nous utiliserons le framework dOOv pour réécrire la partie BeanValidation et nous
découvrirons les bénéfices du fluent API fortement typé de dOOv.
Nous migrerons ensuite l'intégralité de la logique métier et du code de mapping en
permettant l'audit rapide de toute la logique en langage naturel.
Nous terminerons par la mise en place de tests de performance avec JMH sur le code migré.

## Status

TO_SUBMIT

# Conference Session

# Java genetic street art

fr_FR : Peut-on générer, faire s'affronter et sélectionner des sets de règles dynamiques
pour dessiner comme Banksy ?

Le framework dOOv permet de générer des DSL 'pur java' en partant d'un modèle objet.
Il permet de muter dynamiquement un programme écrit avec ce DSL pendant son exécution et facilite
l'écriture d'algorithmes génétiques en Java sans sacrifier en performance.

Nous allons vous le prouver en apprenant à reproduire quelques graphes de Banksy !

Dans cette présentation, nous allons utiliser dOOv pour contruire un DSL permettant d'exprimer des contraintes sur des pixels,
puis appliquer à ces règle des sélections, des mutations et des reproductions : en bref un algorithme génétique. 

Yes, Java can do street art !

en_GB : Can a dynamic ruleset compete with Banksy ?

The dOOv framework generates pure java DSL from any object model. It allows us to mutate programs written with the DSL during
execution.
It enables design and develop of genetic algorithms in a way more expressive fashion without compromising on performances.

We are going to prove it by learning to draw some works from Bansky!

In this talk, we are going to use dOOv to build a DSL expressing constraints on pixels, 
and then apply to those rules selections, mutations and breeding : a genetic optimisation algorithm.

Yes, Java can do street art!

## Status

TO_SUBMIT

## Private message for committee

Website: http://doov.org
Github: https://github.com/lesfurets/dOOv
Slides: http://doov.org/dsl_to_go_beyond_bean_validation_english.html



en_US : We developed dOOv to migrate our 500 business validation rules to a format that
would be easy to write and to export in a human readable form. We open-sourced
our project and present it in conferences because domain object validation is a
recurrent and important problem in our work, so it might help others. We like
to get feedback on dOOv, discuss about usage and future improvements.

fr_FR : Nous avons développé dOOv pour migrer plus de 500 règles métiers de filtrage dans un
format qui permette une maintenance aisée et une relecture efficace par des utilisateurs
hors de l'équipe de développement. Le projet est open source, nous le faisons évoluer depuis
plus de 2 ans.
En 2018, nous avons intégré un grand nombre de retours et d'améliorations lors de la
présentation du projet dans différentes conférences.
La validation et le mapping d'objet métier est un problème récurrent dans notre travail et
nous espérons que d'autres équipes pourrons bénéficier de l'expérience accumulée.
