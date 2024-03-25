Projet de Sniper de Jetons pour Avalanche

Ce projet Node.js est conçu pour "sniper" (acheter rapidement) des jetons sur la blockchain Avalanche en utilisant le routeur TraderJoe.

## Fonctionnalités

- Configurer les paramètres tels que la clé privée, le montant à échanger, le gaz et le slippage
- Interagir avec le contrat intelligent du routeur TraderJoe pour échanger AVAX contre le jeton cible
- Utiliser la bibliothèque ethers.js pour les interactions avec la blockchain Avalanche
- Recevoir l'entrée du jeton cible à partir de la ligne de commande

## Procédure

1. Installer les dépendances (ethers.js et prompt-sync)
2. Configurer les paramètres tels que les clés privée/publique, le montant AVAX, le gaz et le slippage
3. Définir les adresses des contrats AVAX et du routeur TraderJoe
4. Créer une instance du fournisseur Avalanche et du portefeuille avec la clé privée
5. Instancier le contrat du routeur TraderJoe avec l'ABI appropriée
6. Saisir l'adresse du jeton cible à partir de la ligne de commande
7. Appeler la fonction `swapExactAVAXForTokens` du routeur pour échanger AVAX contre le jeton cible
8. Attendre la confirmation de la transaction sur la blockchain
