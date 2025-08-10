# IA-Project
DÉTECTION D’ANOMALIES DANS LE TRAFIC RÉSEAU (ATTAQUES_DDOS_)
L’objectif est de développer un autoencodeur LSTM capable de détecter des anomalies dans le trafic réseau, en particulier des attaques DDoS, à partir de la caractéristique Flow Packets/s du dataset CICDDoS2019. Plus précisément, nous visons à : 
Charger et prétraiter les données du dataset CICDoS2019.
Créer des séquences temporelles à partir du débit de paquets.
pour capturer les motifs temporels.
Construire et entraîner un autoencodeur LSTM pour apprendre les motifs normaux du trafic.
identifier les anomalies (possibles attaques DDoS) en se basant sur les erreurs de reconstruction.
Visualiser les résultats pour évaluer la performance de la détection.
