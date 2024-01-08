Ce projet explore en profondeur les différentes étapes d'un projet d'analyse de données utilisant SQL et Power BI 
pour en ressortir des insights pertinents sur les données RH de l'entreprise.
Le très beau Dashboard construit présente les indicateurs RH essentiels tels que le taux de rotation des employés, 
la diversité, l'efficacité du recrutement et les évaluations de performance. 
Ces données permettent aux RHs et aux managers de prendre des décisions éclairées et de planifier de façon stratégique les effectifs.




------------------------------------------------------------------------------------------------------
Questions
------------------------------------------------------------------------------------------------------

-- 1) Quelle est la répartition de l'âge au sein de l'entreprise ?
-- 2) Quelle est la répartition des genres au sein de l'entreprise ?
-- 3) Comment varie la répartition des genres selon les départements et les titres de poste ?
-- 4) Quelle est la répartition des origines ethniques au sein de l'entreprise ?
-- 5) Quelle est la durée moyenne d'emploi au sein de l'entreprise ?
-- 6) Quel département a le taux de rotation le plus élevé ?
-- 7) Quelle est la distribution de la durée de service pour chaque département ?
-- 8) Combien d'employés travaillent en télétravail pour chaque département ?
-- 9) Quelle est la répartition des employés dans différents États ?
-- 10) Comment les titres de poste sont-ils répartis au sein de l'entreprise ?
-- 11) Comment le nombre d'embauches d'employés a-t-il varié au fil du temps ?

------------------------------------------------------------------------------------------------------
Insights
------------------------------------------------------------------------------------------------------

-- 1) Il y a plus d'employés masculins que d'employées féminines ou non conformes.

-- 2) Les genres sont répartis de manière assez équitable dans les différents départements. Globalement, il y a légèrement plus d'employés masculins.

-- 3) Les employés âgés de 21 à 30 ans sont les moins nombreux dans l'entreprise. La plupart des employés ont entre 31 et 50 ans. 
De manière surprenante, le groupe d'âge 50+ compte le plus grand nombre d'employés dans l'entreprise.

-- 4) Les employés caucasiens constituent la majorité dans l'entreprise, suivis par les métis, les noirs, les asiatiques, les hispaniques et les Amérindiens.

-- 5) La durée moyenne d'emploi est de 7 ans.

-- 6) L'audit a le taux de rotation le plus élevé, suivi du service juridique, de la recherche et développement, et de la formation. 
Les domaines du développement commercial et du marketing ont les taux de rotation les plus bas.

-- 7) Les employés ont tendance à rester dans l'entreprise pendant 6 à 8 ans. L'ancienneté est assez uniformément répartie dans les différents départements.

-- 8) Environ 25 % des employés travaillent à distance.

-- 9) La plupart des employés se trouvent dans l'Ohio (14 788), suivis de loin par la Pennsylvanie (930) et l'Illinois (730), l'Indiana (572), 
le Michigan (569), le Kentucky (375) et le Wisconsin (321).

-- 10) Il y a 182 titres de poste dans l'entreprise, avec le poste de Research Assistant II comptant le plus d'employés (634), tandis que les postes de Assistant Professor, 
Marketing Manager, Office Assistant IV, Associate Professor et VP of Training and Development n'ont qu'un employé chacun.

-- 11) Le nombre d'embauches d'employés a augmenté au fil des ans.

1) Création de la base de données rh

'''sql
SELECT column1, column2
FROM your_table
WHERE condition = 'example';
'''
