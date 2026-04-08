# 💻 BashCeption - Virtualisation & Bash Scripting

## 📌 Description du projet

Ce projet a pour objectif de découvrir :

* la **virtualisation**
* l’utilisation de **Linux**
* la maîtrise du **shell Bash**
* l’automatisation via des **scripts**
* les bases de **Git**

Le projet consiste à créer un environnement virtualisé avec plusieurs systèmes d’exploitation et à développer des scripts Bash pour automatiser différentes tâches système.

---

## 🎯 Objectifs

* Installer et configurer une machine virtuelle
* Mettre en place un dual boot (Windows / Debian)
* Comprendre le fonctionnement du shell Linux
* Manipuler les commandes système
* Créer des scripts Bash
* Automatiser des tâches
* Utiliser Git et GitHub

---

## 🧪 Environnement

* OS hôte : Windows
* Virtualisation : VMware Workstation
* OS invités :

  * Windows 10
  * Debian
  * Manjaro

---

## 🖥️ Virtualisation

* Création d’une machine virtuelle (50 Go)
* Installation de Windows
* Partitionnement du disque
* Installation de Debian (Dual Boot avec GRUB)
* Communication réseau entre machines (ping)

---

## 🌐 Réseau

Tests réalisés :

```bash
ping VM_host
ping VM_debian
ping VM_manjaro
```

👉 Vérification de la connectivité entre :

* machine hôte
* machine virtuelle Debian
* machine virtuelle Manjaro

---

## 🧠 Commandes Linux

Exemples de commandes utilisées :

```bash
ls
ls -la
cat fichier
head fichier
tail fichier
```

Gestion des utilisateurs :

```bash
sudo useradd
sudo groupadd
sudo chmod
sudo chown
```

---

## 🔁 Redirections & Pipes

```bash
echo "texte" > fichier.txt
wc -l fichier.txt
ls -a | wc -l
```

---

## ⚙️ Scripts Bash réalisés

### 📜 1. Premier script

```bash
echo "i'm a script"
```

📌 Fichier : `myfirstscript.sh` 

---

### 🔄 2. Mise à jour système

```bash
sudo apt update && sudo apt upgrade -y
```

📌 Fichier : `myupdate.sh` 

---

### ➕ 3. Addition de deux nombres

```bash
resultat=$(( $1 + $2 ))
```

📌 Fichier : `add.sh` 

---

### 📂 4. Copie de fichier avec arguments

```bash
cat "$contenu" > "$nouveauFichier"
```

📌 Fichier : `argument.sh` 

---

### 🔀 5. Conditions (Hello / Bye)

```bash
if [ "$1" == "Hello" ]; then
```

📌 Fichier : `hello_bye.sh` 

---

### 🧮 6. Calculatrice Bash

```bash
resultat=$(echo "$nombre1 $operation $nombre2" | bc)
```

📌 Fichier : `my_calculator.sh` 

---

### 🔁 7. Boucle

```bash
for ((i = 1; i <= 10; i++))
```

📌 Fichier : `myloop.sh` 

---

## 🚀 Exécution des scripts

```bash
chmod +x script.sh
./script.sh
```

Exemples :

```bash
./add.sh 2 3
./hello_bye.sh Hello
./my_calculator.sh 2 + 3
```

---

## 🧰 Outils utilisés

* Linux (Debian, Manjaro)
* Bash
* VMware
* Git / GitHub

---

## 📈 Compétences développées

* Administration système
* Virtualisation
* Scripting Bash
* Automatisation
* Réseau
* Git

---

## 📌 Conclusion

Ce projet m’a permis de :

* comprendre la virtualisation et les OS
* maîtriser les commandes Linux
* créer des scripts Bash fonctionnels
* automatiser des tâches système

Il constitue une base essentielle pour :
👉 DevOps
👉 Administration système
👉 Cybersécurité

---

## 👨‍💻 Auteur

**Alaa Kaid Ahmed**
