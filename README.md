# Urne·27

Suivi de l'élection présidentielle 2027 : sondages, soirée électorale commune par commune, calendrier des prochains scrutins.

## Données
- `data/polls.json` : sondages (une entrée par sondage, une liste de configurations testées).
- `data/duels.json` : duels de second tour (dernière mesure).
- `data/config.json` : `phase` = `sondages` ou `resultats` (ouvre le site sur la soirée électorale).
- `data/resultats/t1.json`, `t2.json` : résultats officiels le soir du vote,
  `{ "tour": 1, "maj": "ISO-8601", "communes": { "codeINSEE": [inscrits, votants, exprimes, { "idCandidat": voix }] } }`.
- `data/base.json`, `data/*.topo.json` : base de simulation modélisée et contours des communes.

Site statique, publié avec GitHub Pages.
