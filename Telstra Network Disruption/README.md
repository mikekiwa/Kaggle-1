# Predict service faults on Australia's largest telecommunications network

In their first recruiting competition, Telstra is challenging Kagglers to predict the severity of service disruptions on their network. Using a dataset of features from their service logs, you're tasked with predicting if a disruption is a momentary glitch or a total interruption of connectivity.
Telstra is on a journey to enhance the customer experience - ensuring everyone in the company is putting customers first. In terms of its expansive network, this means continuously advancing how it predicts the scope and timing of service disruptions. Telstra wants to see how you would help it drive customer advocacy by developing a more advanced predictive model for service disruptions and to help it better serve its customers.
This challenge was crafted as a simulation of the type of problem you might tackle as a member of the team at Telstra.

Kagglers who stand out will be considered for data science roles in Telstra's Big Data team in Telstra’s absolute discretion. Highly-ranked participants will combine technical expertise and intuition in data science problems with a keen business sense and an effortless ability to work with technical and non-technical staff to turn data into real changes that impact customers. Highly-ranked participants will be considered by Telstra for interviews for employment, based on their work in the Competition and ability to meet the selection criteria for any suitable open job vacancy in Melbourne and Sydney, Australia. Participation in this Competition is not a recruitment process and Kaggle does not provide Telstra with recruitment services.

Link: https://www.kaggle.com/c/telstra-recruiting-network

#Remarques
Classification Supervisé sur 3 classes. 6 fichiers csv dont un pour les données d'apprentissage + un pour les données de test. Plusieurs possibilités de jointures de ces fichiers. La métric utilisée ici est la 'mlogloss' (qualité des probabilités de chaque classes).

Remarque 1: La consolidation de l'ensemble des fichiers nous amène, avec le XGBOOST, à un score 0.53XX. Le résultat final est de 0.39XX. Le but ici était de traiter le principe de feature engineering. Le score final obtenu est de 0.49XX.

Remarque 2:Le One Hot Encoding de la variable 'location' peut être utilisé pour intégrer les méta variables (probabilités) à l'aide du regression logistique.
