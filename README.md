# ML-model

Ce projet de Machine Learning a pour objectif de prédire l'issue des matchs de Tottenham Hotspur en Premier League durant la saison 2022. En exploitant un jeu de données historique, une première version du modèle Random Forest a été développée en se basant sur des variables simples comme le lieu du match, l'adversaire ou le jour de la semaine. Face à une précision perfectible, une étape clé d'amélioration a été l'ingénierie de nouvelles caractéristiques (feature engineering). J'ai notamment calculé les moyennes glissantes sur les trois derniers matchs pour des statistiques clés (buts marqués/encaissés, tirs, etc.), permettant ainsi de capturer la "forme" récente de chaque équipe. L'intégration de ces variables a significativement augmenté la performance, faisant passer la précision du modèle de 47% à plus de 62%.

Ce projet a été inspiré par la page YouTube suivante : https://www.youtube.com/@Dataquestio

/// English Version 

The objective of this Machine Learning project is to predict the outcome of Tottenham Hotspur's matches in the 2022 Premier League season. Using a historical dataset, an initial version of the Random Forest model was developed based on simple variables such as match venue, opponent, or day of the week. As the initial precision had room for improvement, a key enhancement step was feature engineering. Specifically, I calculated 3-match rolling averages for key statistics (goals for/against, shots, etc.) to capture each team's recent "form". Integrating these features significantly increased the model's performance, raising its precision score from 47% to over 62%. 

This project was inspired by the following YouTube page: https://www.youtube.com/@Dataquestio
