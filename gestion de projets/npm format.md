# npm run format 

## Cette commande sert à formatter avec prettier tous vos fichiers de votre projet react ou autre !

Pour le faire vous allez devoir rajouter ce code dans votre package.json de votre dossier qui contient vos .CSS, .js et .jsx:
```
    "format": "prettier --write \"./src/**/*.{js,jsx,css}\""
```


pour pouvez aussi rajouter ça au package.json à l'accueil de votre projet:
```
    "format": "cross-env-shell \"cd ./frontend && npm run format\""
```

Voilà ! 😉