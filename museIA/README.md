# 🏛️ Le Musée de l'IA

> Un musée vivant, construit à plus de 20 mains en 2 heures,
> pendant la formation **Git & GitHub** du club.
> Statut : 🚧 en construction — ouverture prévue aujourd'hui.

## 🗺️ La carte du musée

Chaque salle = une branche Git. Chaque équipe construit sa salle dans son atelier,
puis tout est fusionné dans `main`, la vitrine officielle.

| Salle (branche)    | Époque              | Ce qu'on y expose                    |
|--------------------|---------------------|--------------------------------------|
| `origines`         | 1943 → 1980         | Les premières machines qui rêvent    |
| `essor`            | 1980 → 2010         | L'IA quitte le laboratoire           |
| `deep-learning`    | 2010 → 2020         | La révolution des neurones profonds  |
| `llm`              | 2020 → aujourd'hui  | L'ère des grands modèles de langage  |

## 🎮 Les règles du jeu

1. `git clone` ce dépôt, puis rejoins la salle de ton équipe :
   `git switch origines` (ou `essor`, `deep-learning`, `llm`)
2. Crée ton **cartel** (la fiche d'une œuvre de musée) :
   fichier nommé `<salle>-<ton-pseudo>.md` — ex. `origines-sara.md`
3. Copie le modèle ci-dessous et remplis-le avec **une seule œuvre du menu**
   (chaque œuvre n'est exposée qu'une fois — premier arrivé, premier servi !)
4. Photographie ton travail :
   `git add <fichier>` → `git commit -m "ton message"` → `git push`
   *(si le push est refusé : `git pull` d'abord, puis re-`push`)*
5. À la fin, chaque salle fusionne vers `main` via une **Pull Request**,
   relue par une équipe voisine. Bienvenue au musée. 🎉

## 🖼️ Le modèle de cartel (à copier-coller)

```markdown
# 💡 <Nom de l'œuvre> — <année>

**Inventeur(s) :** <nom(s)>

**Pourquoi c'est une pièce de musée :** <1 ou 2 phrases : ce que ça a changé>
```

## 🌟 Un cartel d'exemple (le mien — ne le recopiez pas !)

# 💡 Le Perceptron — 1958

**Inventeur :** Frank Rosenblatt

**Pourquoi c'est une pièce de musée :** la première machine capable d'*apprendre*
à reconnaître des formes à partir d'exemples. L'ancêtre direct de tous les
réseaux de neurones que vous utiliserez dans votre carrière d'ingénieur IA.

## 🧭 Le menu des œuvres

#### Salle `origines` — 1943 → 1980
- 1943 — Le neurone formel (McCulloch & Pitts)
- 1950 — Le test de Turing
- 1956 — La conférence de Dartmouth : le mot "intelligence artificielle" naît
- 1966 — ELIZA, le premier chatbot
- 1969 — Le livre qui déclenche le premier "hiver de l'IA"

#### Salle `essor` — 1980 → 2010
- 1980 — Les systèmes experts (XCON)
- 1986 — La rétropropagation popularisée
- 1997 — Deep Blue batit le champion du monde d'échecs
- 2002 — Le Roomba : l'IA entre dans nos maisons
- 2005 — Stanley gagne le DARPA Grand Challenge (voiture autonome)

#### Salle `deep-learning` — 2010 → 2020
- 2012 — AlexNet : le big bang du deep learning
- 2014 — Les GANs : des réseaux qui imaginent
- 2016 — AlphaGo bat le champion de Go
- 2017 — "Attention Is All You Need" : le Transformer naît
- 2019 — GPT-2 : des textes presque humains

#### Salle `llm` — 2020 → aujourd'hui
- 2020 — GPT-3 : la taille change tout
- 2021 — AlphaFold résout le repliement des protéines
- 2022 — ChatGPT ouvre l'IA au grand public
- 2023 — GPT-4 et les modèles multimodaux
- À vous — proposez la pièce qui marquera 2024-2026 !

*(Une œuvre hors menu ? Propose-la à l'animateur pour validation.)*