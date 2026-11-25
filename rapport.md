# Rapport : Analyse d'une transaction Bitcoin sur TestNet4

## 1. Introduction

Bitcoin est une monnaie numérique décentralisée créée en 2009. Elle permet aux utilisateurs d'effectuer des transactions directement entre eux, sans avoir besoin d'une banque ou d'un intermédiaire.

TestNet4 est un réseau de test de Bitcoin utilisé par les développeurs et les étudiants pour expérimenter les transactions sans utiliser de vrais bitcoins.

L'objectif de ce travail est d'étudier le fonctionnement d'une transaction Bitcoin sur TestNet4 et de comprendre ses principaux éléments.

## 2. Fonctionnement d'une transaction Bitcoin

Une transaction Bitcoin représente un transfert de bitcoins d'un utilisateur vers un autre.

Chaque transaction est enregistrée dans la blockchain après sa validation par le réseau.

Le processus comprend plusieurs étapes :
- Création de la transaction.
- Sélection des fonds disponibles.
- Définition du destinataire.
- Calcul des frais.
- Diffusion de la transaction sur le réseau.
- Confirmation par les mineurs.

## 3. Les Inputs (Entrées)

Les Inputs représentent les sorties de transactions précédentes utilisées pour financer une nouvelle transaction.

Ils indiquent l'origine des bitcoins utilisés.

Chaque Input fait référence à une sortie précédente non dépensée, appelée UTXO.

## 4. Les Outputs (Sorties)

Les Outputs représentent les destinations des bitcoins transférés.

Une transaction peut contenir :
- Une sortie destinée au destinataire.
- Une sortie de monnaie (Change) retournée à l'expéditeur.

Les Outputs précisent le montant envoyé et les conditions de dépense.

## 5. Les frais de transaction (Fees)

Les frais de transaction représentent la rémunération accordée aux mineurs pour inclure une transaction dans un bloc.

Ils correspondent à la différence entre la valeur totale des Inputs et celle des Outputs.

**Formule :**

Frais = Total des Inputs - Total des Outputs

## 6. Les confirmations

Une confirmation signifie qu'une transaction a été incluse dans un bloc de la blockchain.

Plus le nombre de confirmations augmente, plus la transaction est considérée comme sécurisée.

La première confirmation apparaît lorsque la transaction est intégrée dans un bloc.

## 7. Les UTXO (Unspent Transaction Outputs)

UTXO signifie Unspent Transaction Output, c'est-à-dire une sortie de transaction non dépensée.

Les UTXO représentent les fonds disponibles qu'un utilisateur peut utiliser dans une nouvelle transaction.

Lorsqu'un UTXO est utilisé comme Input, il est consommé et de nouveaux Outputs sont créés.

## 8. Le rôle de TestNet4

TestNet4 est un environnement de test du réseau Bitcoin.

Il permet de :
- Tester les transactions Bitcoin.
- Comprendre le fonctionnement de la blockchain.
- Expérimenter sans utiliser de bitcoins réels.
- Apprendre à utiliser les outils Bitcoin.

## 9. Conclusion

Cette étude nous a permis de comprendre les principaux composants d'une transaction Bitcoin sur TestNet4.

Nous avons étudié les Inputs, les Outputs, les frais de transaction, les confirmations et les UTXO.

TestNet4 constitue un environnement pratique pour apprendre et expérimenter le fonctionnement de Bitcoin sans risque financier.

## 10. Sources

- https://bitcoin.org/
- https://developer.bitcoin.org/
- https://en.bitcoin.it/wiki/Transaction
