# Vue.js Template avec Tailwind CSS et Font Awesome

Un template Vue.js 3 prêt à l'emploi avec Tailwind CSS et Font Awesome pré-configurés pour démarrer rapidement vos projets.

## 🚀 Fonctionnalités

- **Vue.js 3** - Framework JavaScript moderne
- **Tailwind CSS v4** - Framework CSS utilitaire
- **Font Awesome** - Icônes vectorielles
- **Vue Router** - Routage côté client
- **Pinia** - Gestion d'état moderne pour Vue
- **Vite** - Build tool ultra-rapide
- **ESLint & Prettier** - Formatage et linting du code

## 📦 Installation

### 1. Cloner le repository

```bash
git clone <votre-repo-url>
cd VpsDashboard
```

### 2. Installer les dépendances

```bash
npm install
```

### 3. Installer Font Awesome (optionnel)

```bash
npm install @fortawesome/fontawesome-free
# ou
npm install @fortawesome/vue-fontawesome @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons
```

### 4. Démarrer le serveur de développement

```bash
npm run dev
```

## 🛠️ Commandes disponibles

```bash
# Serveur de développement
npm run dev

# Build pour la production
npm run build

# Preview du build de production
npm run preview

# Formatage du code
npm run format
```

## 📁 Structure du projet

```
VpsDashboard/
├── public/           # Fichiers statiques
├── src/
│   ├── assets/       # CSS, images, etc.
│   ├── components/   # Composants Vue réutilisables
│   ├── router/       # Configuration des routes
│   ├── stores/       # Stores Pinia
│   ├── views/        # Pages/Vues principales
│   ├── App.vue       # Composant racine
│   └── main.js       # Point d'entrée
├── index.html        # Template HTML
├── package.json      # Dépendances et scripts
├── tailwind.config.js # Configuration Tailwind
└── vite.config.js    # Configuration Vite
```

## 🎨 Utilisation de Tailwind CSS

Tailwind CSS est déjà configuré. Vous pouvez utiliser les classes utilitaires directement :

```vue
<template>
  <div class="bg-blue-500 text-white p-4 rounded-lg">
    <h1 class="text-2xl font-bold">Hello Tailwind!</h1>
  </div>
</template>
```

## 📚 Ressources

- [Documentation Vue.js](https://vuejs.org/)
- [Documentation Tailwind CSS](https://tailwindcss.com/)
- [Documentation Font Awesome](https://fontawesome.com/)
- [Documentation Vite](https://vitejs.dev/)

## 📝 Licence

Ce projet est sous licence MIT.

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou une pull request.
