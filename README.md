# 🖧 Je m'entraîne : le réseau — Technologie 4e

Une page pour **réviser la séquence sur le réseau informatique** : le matériel, l'adresse IPv4, le binaire et la communication entre les appareils.

Ça marche sur ordinateur, tablette et téléphone, sans compte et sans rien installer. Tu peux t'entraîner **autant de fois que tu veux**.

---

## 📚 Les thèmes

Choisis un thème : tu as **10 questions** à chaque partie. Elles sont tirées au hasard, donc elles changent d'une partie à l'autre. Après chaque réponse, une explication t'aide à comprendre.

| Thème | Ce que tu révises |
|---|---|
| 🖧 **Le matériel** | Reconnaître les éléments d'un réseau (ordinateur, switch, routeur, serveur, borne Wi-Fi, câble RJ45) et leur rôle |
| 🏠 **L'adresse IPv4** | 4 nombres de 0 à 255, adresse possible ou impossible, partie réseau et partie machine |
| 🔢 **Le binaire** | Bits, octets, conversions, nombre de possibilités |
| 📡 **Communiquer** | Même réseau ou pas, conflit d'adresse, chemin des données, pannes |
| 🎲 **Tout mélangé** | Un peu de tout : le grand défi ! |

À la fin, tu vois ta note sur 10, ton **record** et la liste des questions **à revoir**.

## 🧮 L'atelier binaire

Pour t'entraîner aux conversions :

- **🔁 Convertisseur libre** : clique sur les bits ou tape un nombre, et vois la conversion en direct.
- **🎯 Binaire → décimal** : lis l'octet et tape sa valeur en décimal.
- **🎯 Décimal → binaire** : clique sur les bits pour écrire le nombre.
- **⏱️ Contre-la-montre** : un maximum de bonnes réponses en 60 secondes !

Plus tu enchaînes les bonnes réponses, plus les nombres deviennent grands :

| Niveau | Nombres |
|---|---|
| Niveau 1 | de 1 à 15 |
| Niveau 2 | de 16 à 63 |
| Niveau 3 | de 64 à 255 |

💡 **Besoin d'aide pour calculer ?** Clique sur **« 📋 Afficher le tableau de conversion »** : tu y vois les poids des bits (128, 64, 32, 16, 8, 4, 2, 1).

## ✍️ Rappel pour convertir

**Du binaire au décimal** : j'additionne les poids des bits qui sont à 1.

```
poids :  128  64  32  16   8   4   2   1
bits  :    0   0   1   1   0   0   1   0
                   32 + 16       +   2  = 50
```

**Du décimal au binaire** : je cherche les poids qui, additionnés, donnent mon nombre, et je mets un 1 sous chacun d'eux.

```
50 = 32 + 16 + 2   →   00110010
```

**À retenir** : 1 bit = 2 possibilités · 1 octet = 8 bits = 256 possibilités (de 0 à 255).

---

## ❓ Questions fréquentes

**Mes records disparaissent.** Ils sont enregistrés dans ton navigateur, sur l'appareil que tu utilises. Si tu changes d'appareil ou de navigateur, ou si tu es en navigation privée, tu repars de zéro. C'est normal.

**Est-ce que c'est noté ?** Non. C'est un entraînement libre : personne ne voit tes résultats.

**Je peux l'utiliser sans internet ?** Oui. Télécharge le fichier `index.html` et ouvre-le avec ton navigateur.

---

## 👩‍🏫 Pour l'enseignant·e : mettre la page en ligne

1. Créer un dépôt public sur GitHub, puis y déposer le fichier de la page **renommé en `index.html`** et ce `README.md`.
2. Aller dans **Settings → Pages**. Dans **Build and deployment**, choisir **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`. Cliquer sur **Save**.
3. Attendre une ou deux minutes : la page est disponible à l'adresse `https://<nom-utilisateur>.github.io/<nom-du-depot>/`.
4. Remplacer le lien en haut de ce README par la vraie adresse, puis la partager aux élèves (sur École Directe, par exemple).

La page tient dans un seul fichier HTML, photos comprises. Elle n'a besoin d'aucun serveur ni d'aucune base de données, et ne collecte aucune donnée sur les élèves.

---

*Technologie — 4e · Séquence Réseaux*
