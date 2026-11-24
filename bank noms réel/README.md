# Bank noms réel

Copies des banques audio dont le véhicule réel est explicitement identifiable dans le chemin FMOD `event:/cars/<vehicule>/...` du fichier INI.

Les originaux de `sounds/banks/` ne sont pas modifiés. Les copies conservent les octets d'origine ; seuls leurs noms sont normalisés d'après les événements du INI.

## Paires renommées

- `ruf_yellowbird.bank` + `ruf_yellowbird.ini`
- `bmw_m3_e92.bank` + `bmw_m3_e92.ini`
- `porsche_cayenne.bank` + `porsche_cayenne.ini`
- `corvette_c7_stingray.bank` + `corvette_c7_stingray.ini`
- `mazda_mx5_cup.bank` + `mazda_mx5_cup.ini`
- `ferrari_laferrari.bank` + `ferrari_laferrari.ini`
- `ferrari_812_superfast.bank` + `ferrari_812_superfast.ini`
- `toyota_ae86.bank` + `toyota_ae86.ini`
- `toyota_gt86.bank` + `toyota_gt86.ini`
- `toyota_celica_st185.bank` + `toyota_celica_st185.ini`
- `mazda_rx7_spirit_r.bank` + `mazda_rx7_spirit_r.ini`
- `mercedes_sls_gt3.bank` + `mercedes_sls_gt3.ini`
- `mercedes_amg_gt3.bank` + `mercedes_amg_gt3.ini`
- `ford_mustang_2015.bank` + `ford_mustang_2015.ini`
- `nissan_370z.bank` + `nissan_370z.ini`
- `porsche_991_turbo_s.bank` + `porsche_991_turbo_s.ini`
- `abarth500.bank` + `abarth500.ini`
- `nissan_skyline_r34.bank` + `nissan_skyline_r34.ini`

## Sources en double

- `nytcadilext` et `nyttoycrown` pointent tous deux vers Porsche Cayenne et ont les mêmes fichiers : une seule paire `porsche_cayenne`.
- `nythondacrx` et `nytnis200sx` pointent tous deux vers Toyota AE86 et ont les mêmes fichiers : une seule paire `toyota_ae86`.

## Non renommés

Ces INI utilisent des GUID FMOD sans nom de véhicule lisible. Ils sont laissés de côté plutôt que renommés au hasard : `nytaudis4`, `nytbmwe87`, `nytbmwe92`, `nytbugattiveyr`, `nytchevcor09`, `nytchopper`, `nytfordcvlx98`, `nytfordmus73`, `nytgtrr35`, `nytlambo2005`, `nytlambo2011`, `nytlexuslfa`, `nytmercc63`, `nytquattro10`, `nytrollsphant7`, `nytscde39`, `nytscde39stock`, `nytsupra`, `nytsuzukig1`.

Le nom du véhicule vient des événements FMOD du INI, pas d'une identification par écoute.
