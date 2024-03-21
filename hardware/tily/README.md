# Bienvenue à l'Épreuve FLAG!

## Description
🚩 Dites le mot magique "FLAG" et le trésor sera à vous! 🚩

## Instructions
1. Prêt à l'aventure? Commencez par télécharger notre carte au trésor, le fichier `docker-compose.yml`.
2. Ensuite, hissez les voiles et lancez l'épreuve en exécutant la commande suivante dans le même dossier:
```bash
docker compose up
```
3. Maintenant, ouvrez un second coffre et accédez à l'épreuve via Netcat avec:
```bash
nc localhost 4000
```

🔔 **Attention**: Votre chemin vers le trésor doit passer par le réseau exposé du conteneur Docker. Aucun raccourci ne mène au but!

🔍 Si les écueils vous barrent le chemin, demandez de l'aide à l'équipe sur Discord ou hissez le drapeau en créant un ticket! 🚩