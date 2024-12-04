Dans le cadre de votre participation au Workshop du **14 décembre**, il est essentiel de venir équipé d'un ordinateur personnel sur lequel le **starter Laravel** est déjà installé **et opérationnel**. 🚀

---

## 1. Créer une application Laravel

L'installation du **starter Laravel** peut être réalisée de plusieurs façons.

Choisissez la méthode qui vous convient le mieux :

- 🐳 **Installation via Docker :** Rendez-vous à la section **1.1. Laravel Sail**.
- ⚙️ **Installation manuelle (WAMP ou équivalent) :** Passez à la section **1.2. Laravel Installer**.
- 🌟 **Installation simplifiée via Herd :** Consultez la section **1.3. Laravel Herd**.

---

### **1.1. Laravel Sail 🐋**

Laravel Sail est un outil officiel qui fournit un environnement de développement local basé sur Docker. Il simplifie la configuration d'un environnement complet (**PHP**, **MySQL**, **Redis**, etc.) sans installation manuelle.

#### 📚 Documentation officielle :

- [Pour macOS](https://laravel.com/docs/11.x#sail-on-macos)
- [Pour Linux](https://laravel.com/docs/11.x#sail-on-linux)
- [Pour Windows](https://laravel.com/docs/11.x#sail-on-windows)

> ⚠️ **Conseil :** Pour le workshop, utilisez les services par défaut proposés par Sail, sans modifications.

Ensuite, lancez le projet

```bash
cd mon-projet
./vendor/bin/sail up
```

Une fois les containers lancés, dans un nouveau terminal, lancez :

```bash
./vendor/bin/sail npm install
./vendor/bin/sail artisan migrate
./vendor/bin/sail run dev
```

---

### **1.2. Laravel Installer ⚙️**

Si vous préférez travailler sans Docker et disposez déjà de **PHP**, **Composer**, et **Node.js** sur votre machine, vous pouvez installer Laravel directement en ligne de commande. 🖱️

#### 🚀 Étapes principales :

1. Installez Laravel via Composer :
    ```bash
    composer global require laravel/installer
    ```
2. Créez une nouvelle application Laravel :

    ```bash
    laravel new mon-projet
    ```

3. Lancez l'application

```bash
cd mon-projet
npm install && npm run build
composer run dev
```

💡 **Pas de PHP, Composer ni Node.js ? ?** Pas de souci ! Le site [php.new](https://php.new/) offre une solution rapide pour configurer un environnement Laravel-ready. ⚡


---

### **1.3. Laravel Herd 🐎 **

Laravel Herd est une solution légère et rapide, particulièrement adaptée aux utilisateurs de **macOS** et **Windows**. Développé en partenariat avec [Beyond Code](https://beyondco.de/), Herd offre un environnement de développement préconfiguré. 🖥️

#### 📚 Documentation officielle :

- [Installation pour macOS et Windows](https://herd.laravel.com/docs/windows/1/getting-started/installation)

PS : je ne suis pas en mesure d'utiliser Herd, je ne pourrais pas vous aider si vous choisissez cette méthode.

---

Nous avons hâte de vous voir au workshop et de vous accompagner dans votre aventure Laravel ! 🌟🎉
