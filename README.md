---
editor_options: 
  markdown: 
    wrap: 72
---

# ECN3950

Données immigration : <https://www.trade.gov/i-94-arrivals-program>

# Question de recherche détaillée

## Question de recherche

L'émergence de friction commerciale lors l'arrivé du gouvernement Trump
a suscité plusieurs réactions polarisantes dans les médias. Scott
Kennedy, un expert de la Chine au Centre d'études stratégiques et
internationales a déclaré : « Ce sont des pertes inutiles. Et ces
victimes inutiles seront les entreprises dont les exportations seront
éliminées et les consommateurs qui paieront plus et auront moins de
choix. » Dès lors, une amplitude d'études et de chercheurs ont tenté de
trouver l'impact multidimensionnel des tarifs de Trump. Une sanction
importante que le gouvernement républicain a imposée est un tarif
douanier de 10% sur des milliers de produits chinois. Le montant de
cette taxe a atteint un total 200 milliards de dollars. Notre recherche
s'intéresse à rapprocher l'effet de cette taxe au tourisme. Autrement
dit, on cherche à savoir, ici, si cette sanction à un effet sur le
tourisme (Beech, 2018). Formellement, il est possible d'écrire cette
question comme ceci : Quel est l'impact de cette sanction économique sur
le nombre d'immigrants et de touristes chinois en territoire américain ?

## Pourquoi cette question ?

Cette question est intéressante, car selon notre revue de littérature,
le tourisme peut avoir un effet relativement significatif sur le PIB.
Ainsi, s'il est démontré que les sanctions économiques ont des effets
négatifs sur le tourisme, cela pourrait faire évoluer l'argumentaire
contre le protectionnisme et les guerres économiques. En effet, si nous
découvrons que la sanction étudiée à des effets négatifs sur le nombre
de visiteurs chinois aux États-Unis, nous allons pouvoir utiliser les
résultats des études discutés ci-bas pour estimer l'effet précis de la
sanction sur la portion touristique du PIB. Notre hypothèse principale
se base justement sur l'argumentaire ci-dessus. Nous croyons que la
sanction en question (Beech, 2018) aura un effet négatif, toutefois
léger, sur le nombre de touristes chinois arrivant aux États-Unis.
Parallèlement, cet effet négatif se répercutera sur l'économie des É-U.
La plupart des études sur les sanctions se concentrent sur l'aspect
commercial de celles-ci. Nous croyons que les effets des sanctions
économiques sont plutôt multidimensionnelset c'est pourquoi nous croyons
que notre question de recherche est autant intéressante qu'importante à
étudier, ainsi représentant l'importance et l'intérêt économique de
segmenter et d'étudier l'effet des sanctions sur un seul aspect.

# Méthodologie de recherche

## Données

Concernant les données utilisées, nous allons utiliser les données
officielles du Department of Commerce , qui recense de façon mensuelle
l'ensemble des touristes venus aux É-U selon le pays de provenance et
l'année. Ces données vont de janvier 2000 à novembre 2022. De plus, pour
approfondir notre analyse, nous utiliserons également les données sur
l'immigration internationale américaine. Ce jeu de données a été trouvé
dans la base de données du Department of Homeland Security . En
revanche, ces données ne sont que disponibles annuellement. Il est à
noter que les données migratoires sont divisibles par État ainsi que par
type d'immigration. Il sera ainsi possible de pousser l'analyse plus
loin en cas de besoin.

## Méthodologie

Pour évaluer la causalité, nous allons utiliser la régression par
discontinuité. L'équation étudiée sera, à moins de changement sous cette
forme.

enter_t=B_0+B_1 t+B_2 〖sanction〗\_t

Où enter_t est le nombre de touristes ou d'immigrants à t temps et où
sanction est une variable binaire pour le mois ou l'année de la
sanction.

Nous allons également tester la régression Différence-en-Différence si
les données s'y prêtent (tendance similaire entre la Chine et d'autres
pays). Dans le cas échéant, l'équation serait sous cette forme :

enter\_(t,i)=B_0+B_1 t+B_2 〖sanction〗*(t,i)+B_3
after〖sanction〗*(t,i)

Où after〖sanction〗\_(t,i) est une variable binaire pour après la
sanction sur la Chine. Pour les autres variables, elles sont similaires
sauf du fait qu'elles dépendent dorénavant du pays et du temps.

RDD : <https://scholar.harvard.edu/files/dell/files/ecta8121_0.pdf>
<https://eml.berkeley.edu/~webfac/cromer/e211_sp07/card.pdf>
<https://academic.oup.com/qje/article/114/2/533/1844228>
<https://onlinelibrary.wiley.com/doi/full/10.1111/1468-2354.t01-1-00055>
Guide RDD :
<https://www.sciencedirect.com/science/article/pii/S0304407607001091#bib7>

Taches :
1. Finir régression
2. Stat descriptive
3. GGplot
4.
