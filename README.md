# ⚙️ API Rust :

[![Rust badge](https://img.shields.io/badge/Language-Rust-brown
)](https://www.rust-lang.org/fr)
[![Actix badge](https://img.shields.io/badge/Library-Actix-green)
](https://actix.rs/docs/application)

### 📌 Sommaire :

I. [Prérequis](#🔧-prérequis)

II. [Routes](#​📋​-routes)

III. [Utilisation](#💻-utilisation)



### 🔧 Prérequis :
- Avoir [Rust](https://www.rust-lang.org/fr) d'installé sur la machine.

### ​📋 Routes :

#### `/ping`
Renvoie le header de la requête dans au format `JSON`.

#### `/*`
Toutes les routes restante renvoie un status 404 avec un contenu vide.

### 💻 Utilisation :

Avant de commencer, vous devez :

- Clonner le repo : 
```bash
git clone https://github.com/Tenlutshy/wik-dps-tp01.git
```

- Configurer le port sur lequel écoutera l'API (`8080` par défaut)

- Naviguer jusqu'au projet
```bash
cd wik-dps-tp01
```

- Démarrer l'API
```rs
cargo run
```

**✅ Vous pouvez maintenant accéder à votre API**

http://0.0.0.0:8080