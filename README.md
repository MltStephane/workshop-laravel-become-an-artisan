### 🛠️ Préparation au Workshop : **« Laravel : devenez un artisan du code »** 🖥️

Dans le cadre de votre participation au Workshop du **14 décembre**, il est essentiel de venir équipé d'un ordinateur personnel sur lequel le **starter Laravel** est déjà installé **et opérationnel**. 🚀

---

## 1️⃣ Créer une application Laravel

L'installation du **starter Laravel** peut être réalisée de plusieurs façons. Choisissez la méthode qui vous convient le mieux :

- 🐳 **Installation via Docker :** Rendez-vous à la section **1.1. Laravel Sail**.
- ⚙️ **Installation manuelle (WAMP ou équivalent) :** Passez à la section **1.2. Laravel Installer**.
- 🌟 **Installation simplifiée via Herd :** Consultez la section **1.3. Laravel Herd**.

---

### **1.1. Laravel Sail 🐋 (recommandé pour Docker)**

Laravel Sail est un outil officiel qui fournit un environnement de développement local basé sur Docker. Il simplifie la configuration d'un environnement complet (**PHP**, **MySQL**, **Redis**, etc.) sans installation manuelle. ✅

#### 📚 Documentation officielle :
- [Pour macOS](https://laravel.com/docs/11.x#sail-on-macos) 🍎
- [Pour Linux](https://laravel.com/docs/11.x#sail-on-linux) 🐧
- [Pour Windows](https://laravel.com/docs/11.x#sail-on-windows) 🪟

> ⚠️ **Conseil :** Pour le workshop, utilisez les services par défaut proposés par Sail, sans modifications.

---

### **1.2. Laravel Installer ⚙️ (recommandé pour une installation manuelle)**

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

💡 **Pas encore prêt ?** Pas de souci ! Le site [php.new](https://php.new/) offre une solution rapide pour configurer un environnement Laravel-ready. ⚡

> 🌟 **Astuce :** [php.new](https://php.new/) est soutenu par une agence très active dans l’écosystème Laravel, ce qui garantit sa fiabilité.

---

### **1.3. Laravel Herd 🐎 (recommandé pour une installation simplifiée)**

Laravel Herd est une solution légère et rapide, particulièrement adaptée aux utilisateurs de **macOS** et **Windows**. Développé en partenariat avec [Beyond Code](https://beyondco.de/), Herd offre un environnement de développement préconfiguré. 🖥️

#### 📚 Documentation officielle :
- [Installation pour macOS et Windows](https://herd.laravel.com/docs/windows/1/getting-started/installation)

---

### ✅ Checklist avant le workshop :
1. **Vérifiez que votre starter Laravel est fonctionnel.** 🕵️‍♂️  
   - Accédez à votre projet via un navigateur en local. 🌐  
   - Testez les commandes basiques (`php artisan serve` ou `./vendor/bin/sail up`). 💻  
2. **Apportez votre ordinateur le jour J.** 💼  
3. **En cas de problème d'installation, contactez l’organisateur avant le 12 décembre.** 📩

Nous avons hâte de vous voir au workshop et de vous accompagner dans votre aventure Laravel ! 🌟🎉
