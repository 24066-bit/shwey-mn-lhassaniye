# شوي من الحسانية — Shwey mn lHassaniye

> "shwey mn lhassaniye" signifie "un peu de hassaniya" en hassaniya mauritanien

## 9ssetne

Ce dataset est né d'un projet de guide touristique IA pour Nouakchott.
En voulant y intégrer un chatbot capable de traduire quelques phrases
en hassaniya, j'ai réalisé qu'il n'existait presque aucune ressource
disponible. Trouver les traductions a été un vrai défi.

C'est pourquoi j'ai décidé de partager ce que j'ai collecté ,et
j'invite tout le monde à contribuer. Le hassaniya est parlé par plus
de 3 millions de personnes en Mauritanie et dans les régions limitrophes,
mais il est quasi-absent des ressources NLP existantes.

**Même une seule phrase peut faire la différence.**

Aujourd'hui c'est "shwey" (un peu) , mais j'aimerais qu'un jour
ce soit "yasser" (beaucoup) 😉

## Ce dataset n'est qu'une base qui peut servir pour

- La traduction automatique hassaniya-français
- Les applications touristiques et culturelles
- L'apprentissage du hassaniya par les non-arabophones
- La recherche NLP sur les langues à faibles ressources
- Tout ce que vous pourrez imaginer ... et même plus !

## Contenu

| Source | Entrées | Description |
|---|---|---|
| Fatimetou Nemane | 407 | Expressions authentiques — locutrice native |
| ahmed02mk/amthal-hassaniya | 319 | Proverbes hassaniya |
| Hassan-IA/DAH | 100 | Phrases trilingues |
| mendeley/projectHA | 43 | Expressions quotidiennes |
| **TOTAL** | **869** | |

## Format

```json
{
  "hassaniya": "sbah lkhayr",
  "français": "Bonjour",
  "categorie": "salutation",
  "exemple": "On dit 'sbah lkhayr'. La réponse est 'sbah nour'.",
  "source": "Fatimetou Nemane "
}
```

## Catégories

37 catégories : salutations, famille, émotions, santé, nourriture,
transport, hôtel, shopping, tourisme, religion, couleurs, jours, mois,
corps humain, animaux, lieux, proverbes, et plus encore.

## Comment contribuer ?

1. Fork ce repo
2. Ajoute tes expressions dans `shwey_mn_lhassaniye.json`
3. Respecte le format JSON ci-dessus
4. Fais une Pull Request

**Règles importantes — Hassaniya pur (pas du darija) :**

| Darija | Hassaniya mauritanien |
|---|---|
| والو | شي |
| ماقدرت | ماكديت |
| فلوس | الفظة |
| نستنى | انحاني |
| مزيان | زين |

## Citation

```bibtex
@dataset{shwey_mn_lhassaniye_2026,
  author = {Fatimetou Nemane},
  title = {Shwey mn lHassaniye — Hassaniya Mauritanian Dataset},
  year = {2026},
  url = {https://github.com/24066-bit/shwey-mn-lhassaniye}
}
```

## Auteur

**Fatimetou Ahmed Mahmoud (Fatimetou Nemane)**
Étudiante SID4 — École Supérieure Polytechnique, Nouakchott, Mauritanie
Projet Sederni — NLP pour langues à faibles ressources

---
*4e la shwey w inshAllah dor y3oud yasser* 😉🌍
