🕒 Horloge Analogique JavaScript

📄 Description

Ce script crée une horloge analogique en temps réel. Les aiguilles des secondes, minutes et heures bougent de façon fluide grâce à JavaScript et CSS.

⚡ Étapes d’implémentation
	1.	Sélection des éléments DOM
	•	On récupère les aiguilles (secondhand, minutehand, hourhand) pour pouvoir les faire tourner.
	2.	Fonction setDate()
	•	Récupère l’heure actuelle (Date()) et calcule l’angle de rotation de chaque aiguille.
	•	Applique les transformations CSS pour faire tourner les aiguilles.
	3.	Mise à jour automatique avec setInterval()
	•	Appelle setDate() toutes les secondes pour que l’horloge reste à jour.
	•	Appel initial pour afficher immédiatement l’heure correcte au chargement de la page.

💡 Points clés
	•	Conversion des secondes, minutes et heures en degrés pour la rotation.
	•	Progression fluide des aiguilles grâce à la prise en compte des fractions (minutes/secondes pour heures, secondes pour minutes).
	•	Utilisation de DOM + CSS transform pour l’animation visuelle.

🎯 Résultat

Une horloge analogique précise et fluide, qui se met à jour chaque seconde.