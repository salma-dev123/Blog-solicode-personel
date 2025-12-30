---
marp: true
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
color: #5B2C6F
style: |
  img {
    max-width: 80%;
    max-height: 65vh;
    display: block;
    margin: 1em auto;
    object-fit: contain;
    border: 1px solid #ddd;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
---

<!-- Page de garde -->
# Présentation Blog Solicode - Sprint 2
### Gestion des articles
**Présentée par : Salma Akajou**  
**Encadré par : M. ESSARRAJ FOUAD**

---

## Introduction

Dans le sprint précédent, on a déjà travaillé sur le **front office** du blog (page accueil, page articles, page détail article).  
Dans ce **Sprint 2**, on a intégré le **back office/admin**, pour la **gestion des articles** : ajout, édition, upload d’images et vidéos.

---

## Travail à faire

- Développer le formulaire pour **ajouter et éditer les articles**  
- Permettre l’**upload de fichiers** (images et vidéos)  
- Mettre en place la **gestion des articles** côté admin  

---

## Méthodologie : Scrum

![Scrum](images_presentation/scrum.png)

**J’ai travaillé par Scrum :**  
- Organisation du travail en sprints courts  
- Suivi régulier des tâches  
- Priorisation et révision à chaque sprint  

---

## Méthodologie : Design Thinking

![Design Thinking](images_presentation/design_thinking.png)

**J’ai travaillé par Design Thinking :**  
- Conception centrée sur l’utilisateur  
- Prototypage de la maquette avant développement  
- Tests et ajustements de l’interface  

---

## Fonctionnalités principales

![Use Cases Admin](images_presentation/admin_use_cases.png)

---

## Labs réalisés

**Lab  : Upload fichiers et médias (Images & Vidéos)**

- Gestion de l’upload dans Laravel  
- Stockage sécurisé et enregistrement des chemins dans la base de données
- Prévisualisation des fichiers dans l’interface admin  

---

## Maquette réalisée

![Maquette Form Article](images_presentation/maquettes_form_article.png)

**Validation de maquette avec : la formatrice Mme Fatine Chehab**

---

## Diagramme de classe

![Diagramme de Classe](images_presentation/diagram_class.png)

---

## Technologies utilisées

**Frontend :**  
- Blade (Laravel)  
- Preline  
- Tailwind CSS  

**Backend :**  
- Laravel 12  
- PHP  
- Architecture globale : **N-tiers** et **MVC**

---

## Prochain Sprint

- Ajout de la section **commentaires**  
- Gestion des **utilisateurs**  
- Gestion des **catégories**
