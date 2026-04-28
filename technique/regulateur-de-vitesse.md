# 🚀 Régulateur de vitesse

## Régulateur de vitesse

Sur certains **Cherokee 4.0L Limited**, le boîtier jaune sous la colonne de direction pilote le régulateur de vitesse.

Il permet d’ajuster son comportement sur trois points :

* la vitesse mémorisée lors de l’enclenchement
* la plage de fonctionnement
* la tolérance de variation autour de la consigne

***

<figure><img src="../.gitbook/assets/image (1).png" alt="Boîtier de régulateur de vitesse" width="188"><figcaption></figcaption></figure>

{% hint style="info" %}
Avant tout réglage, notez la position d’origine des vis.\
Vous pourrez revenir facilement au point de départ.
{% endhint %}

### Les 3 réglages du boîtier

{% tabs %}
{% tab title="A — Centering adjustment" %}
Ce réglage ajuste l’écart entre la vitesse réelle du véhicule et la vitesse prise en compte par le calculateur au moment où vous activez le régulateur.

Bien réglé, le véhicule garde la même allure quand vous enclenchez le régulateur.\
Il ne doit ni accélérer, ni ralentir de quelques km/h.

Si la vitesse bouge au moment de l’activation, corrigez ce réglage :

* vers le **+** si la vitesse prise en compte est trop basse
* vers le **-** si elle est trop haute
{% endtab %}

{% tab title="B — Low speed adjustment" %}
Ce réglage détermine la plage de vitesse dans laquelle le régulateur peut fonctionner.

Le régulateur ne s’active qu’au-dessus d’une vitesse minimale.\
Il cesse aussi d’être disponible au-dessus d’une vitesse maximale.

Cette plage reste fixe.\
Si vous abaissez le seuil d’activation, vous abaissez aussi la limite haute.

Exemples de principe :

* plage de **80 à 170 km/h**
* plage de **50 à 140 km/h**

Ces valeurs sont données à titre d’illustration.
{% endtab %}

{% tab title="C — Sensitivity adjustment" %}
Ce réglage agit sur la tolérance de variation de vitesse quand le régulateur est actif.

Il ajuste la marge admise autour de la vitesse de consigne, notamment :

* en montée
* en descente
* sur route légèrement vallonnée

En augmentant la tolérance, la vitesse varie davantage autour de la consigne.\
En la réduisant, le régulateur corrige plus vite.
{% endtab %}
{% endtabs %}

### Comment vérifier un bon réglage

Le test le plus simple consiste à rouler à vitesse stabilisée, puis à activer le régulateur.

Si le véhicule :

* accélère légèrement, le centrage n’est pas bon
* ralentit légèrement, le centrage n’est pas bon
* garde exactement son allure, le réglage est correct

### Si le régulateur ne fonctionne plus

La panne est en général soit **mécanique**, soit **électrique**.

{% columns %}
{% column %}
#### Panne mécanique

Contrôlez d’abord les éléments dans le compartiment moteur :

* le **poumon** commandé par dépression
* le câble entre le poumon et le papillon
* les durites de dépression

Vérifiez aussi la vanne de mise à l’air liée à la pédale de frein.\
Si le poumon est continuellement mis à l’air, le régulateur ne peut pas rester enclenché.
{% endcolumn %}

{% column %}
#### Panne électrique

Contrôlez ensuite les éléments électriques :

* le boîtier électronique jaune sous le tableau de bord côté conducteur
* le commodo
* les contacteurs de pédale de frein

Sur les Cherokee 4.0L, la panne vient souvent des fils internes du commodo.
{% endcolumn %}
{% endcolumns %}

### Les contacteurs sur la pédale de frein

Vous avez **deux contacteurs** sur la pédale de frein.

#### Contacteur supérieur

Tout en haut de la pédale, peu visible, se trouve un ensemble avec :

* un connecteur **2 fils**
* une durite caoutchouc
* une vanne de mise à l’air

Quand vous appuyez sur le frein, cette vanne met à l’air le poumon du régulateur.\
Le régulateur se désenclenche alors immédiatement.

Si cette vanne laisse le poumon à l’air en permanence, le régulateur ne fonctionne plus.

{% hint style="info" %}
À ce niveau, le contacteur électrique désenclenche aussi le **lock-up** du convertisseur.\
Le lock-up est l’embrayage qui supprime le glissement du convertisseur.
{% endhint %}

#### Contacteur inférieur

En bas de la pédale se trouve le contacteur avec **connecteur 3 fils**.

Il gère :

* les feux stop
* la déconnexion électrique du régulateur

S’il fonctionne mal, le régulateur peut se couper immédiatement ou refuser de s’activer.

### Point faible fréquent : le commodo

Sur de nombreux Cherokee 4.0L, la panne vient des fils très fins à l’intérieur du commodo.

Avec le temps, les rotations répétées pour les essuie-glaces fatiguent les soudures.\
Un fil peut finir par se couper au niveau du raccord.

<details>

<summary>Réparation du commodo — opération délicate</summary>

Le démontage demande beaucoup de précaution.\
La partie cylindrique en bout de commodo doit être ouverte très doucement au niveau du plan de joint.

Une fois ouverte, vous trouverez 3 ou 4 fils très fins.\
Si un seul fil est dessoudé, il est souvent possible de repérer son emplacement et de le ressouder.

Au remontage, utilisez seulement quelques très petites gouttes de colle cyano.\
Évitez tout débordement.

</details>

### En bref

Le boîtier de régulateur permet d’ajuster :

* le centrage de la vitesse mémorisée
* la plage d’activation
* la sensibilité de correction

En cas de panne, contrôlez d’abord la dépression, puis les contacteurs de frein, puis le commodo et le boîtier électronique.
