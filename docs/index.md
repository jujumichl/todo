<style>
.code-box {
  position: relative;
  background: #2d2d2d;
  color: #f8f8f2;
  padding: 1em;
  border-radius: 5px;
  font-family: monospace;
  margin: 1em 0;
  overflow-x: auto;
}

.code-label {
  position: absolute;
  top: 0;
  left: 0;
  background: #ffcc00;
  color: #000;
  font-size: 0.75em;
  font-weight: bold;
  padding: 2px 6px;
  border-bottom-right-radius: 5px;
}
</style>

# SOMMAIRE
* [Sur la borne interactive](#-sur-la-borne-interactive)
* [Statistiques téléphonie](#-statistiques‑téléphonie)
* [🤖 IA](#‑ia)
  * [Projet Naaro](#‑projet‑naaro)
* [Portail Travaux (Projet Carto)](#‑portail‑travaux‑(projet‑carto))
* [🌐 Recherche & veille informatique](#‑recherche--veille‑informatique)
* [🛑 Application carte de stationnement (à créer entièrement)](#‑application‑carte‑de‑stationnement‑à‑créer‑entièrement)
* [🗺️ Carte mentale sur le château](#‑carte‑mentale‑sur‑le‑château)
* [📝 Demande de changement du formulaire de remboursement lors des déplacements](#demande-de-changement-du-formulaire-de-remboursement-lors-des-déplacements)
* [🧾 Documentation personnelle](#‑documentation‑personnelle)

---

## 🔹 Sur la borne interactive

<input type="checkbox" checked> Dupliquer la page `Borne DEE`  
<input type="checkbox" checked> Supprimer portail agent, borne état civil et cimetière  
<input type="checkbox" checked> Renommer la page : CCAS

## 🔹 Statistiques téléphonie

<input type="checkbox" checked> Tester l'import des stats (aucun problème détecté)  
📁 [Fichier importé](./../Desktop/Export%20complet%20Mois%20pour%20portail%2021-10-25%2014'44'221736139987542%2002332.xls)  
<input type="checkbox" checked> Ne conserver que les numéros à 4 chiffres  
<input type="checkbox" checked> Supprimer fichiers inutiles  

## 🤖 IA

### 🔸 Projet Naaro

<input type="checkbox" checked> Lire la démo + site public  
<input type="checkbox" checked> Résumer le fonctionnement  
<input type="checkbox" checked> Évaluer les possibilités d'IA privée    

#### ✅ Tâches réalisables :
* Analyse de marché
* Chatbot
* Traitement de formulaires
* Gestion de plannings / données

#### ❌ Tâches non retenues :
* Suivi des demandes en ligne
* Saisie de factures
* Vérification de pièces comptables
* Rapprochements bancaires
* Rédaction de courriers types

## 🔸 Portail Travaux (Projet Carto)

<input type="checkbox" checked> Lire les fichiers de contexte  
<input type="checkbox" checked> Lister les ajouts envisageables  
<input type="checkbox"> Faire le schéma des BDD (en attente)  

## 🌐 Recherche & veille informatique

<input type="checkbox" checked> Recherche IA privée interne  
  <input type="checkbox" checked> Comprendre l’IA nationale  
  <input type="checkbox" checked> Lister des IA privées (perf, coût…)  

## 🛑 Application carte de stationnement (à créer entièrement)

* ✅ À maintenir :
  * Version PHP / Symfony
  * Base de données ?
  * Git
  * DevOps

* 📌 Fonctions clés :
  * RGPD ~
  * Contrat de maintenance
  * Inventaire réseau
  * Ajout / modification / suppression
  * Tirage au sort
  * Décisions / contrôles
  * Intégration au portail global

NB : Portail carto ODP : Open web/literalis

## 🗺️ Carte mentale sur le château

* Objectif : version simplifiée demandée

appli sur les tablettes
Plan interactif qui a des num et qui lance du contenu video quand on clique sur un num

Vrai appli indépendante sans wifi, un peu aléatoire le wifi c'est pour ça que l'on veux un appli sans.

s:/informatique/carteInteractive c'est ce qu'on veux améliorer

rien d'ajout, appli plus intuitive et ergonomique. 
une fois lancer, bloquer sur l'appli pour pas qu'on puisse en sortir.

A voir avec la géolocalisation pour l'ajouter et gérer quand on est déconnecter d'internet pour passer en mode déconnecter 

## 📝Demande de changement du formulaire de remboursement lors des déplacements
Demande de changement sur le formulaire de remboursement lors de déplacements.  

Besoin : Ajouter une periode afin d'éviter que les personnes envoie 2 formulaire avec la date de début a la date de fin et ajouter un pop-up de confirmation lors de l'envoie du formulaire car il est arrivé que certaine personne ne soit pas sur que le formulaire a bien été envoyer.  

Ajout :  
- Changement de l'entrer nommé date en 2 champ qui seront nommé du et au afin de délimiter une date car certaine fois il arrive que cela dure sur plusieurs jours

- Ajout d'un pop up de confirmation d'envoie du formulaire

## 🧾 Documentation personnelle  
🔍 Trouver le contrôleur ou la vue liée à un `path()` Symfony

<div class="code-box">
<div class="code-label">bash</div>
<pre><code>
php bin/console debug:route
</code></pre>
</div>
