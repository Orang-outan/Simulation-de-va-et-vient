<h2>prompt</h2>
Génère le code d’une page HTML avec du CSS pour simuler le fonctionnement d’un éclairage par va et vient électrique. Une ampoule L s’allume si on clique sur switch A pour l’activer et qu’on ne clique pas sur switch B ou si on clique sur switch B et qu’on ne clique pas sur switch A, sinon l’ampoule L reste éteinte.


Caractéristiques de la simulation :
Logique XOR intégrée :
Switch A actif seul 
→
→ Ampoule allumée avec halo lumineux (#fde047 + box-shadow).
Switch B actif seul 
→
→ Ampoule allumée.
Les deux inactifs ou les deux actifs 
→
→ Ampoule éteinte.
Interactif et fluide : Les interrupteurs ont une animation de glissement fluide.
Table de vérité interactive : La ligne correspondant à l'état actuel est mise en surbrillance en temps réel grâce aux sélecteurs :has() et :not().

![alt text](image.png)