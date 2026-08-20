<div align="center">

# 👋 Привет, я Alexandru (Sansik)

### ☁️ Cloud Infrastructure · 🐧 Linux · 🌐 Web & Game Hosting · 🛠️ DevOps

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=700&lines=Building+PulsarX+Cloud;Linux+%26+Server+Administration;Cloud+Infrastructure+%26+DevOps;Web+%26+Game+Hosting;CS2+%2F+CS%3AGO+Tools+Developer" alt="Typing SVG" />

</div>

---

# ☁️ PulsarX Cloud

<div align="center">

### **Self-Service Cloud Platform for Linux mini-VPS**

**Provision → Deploy → Manage → Monitor**

[![Website](https://img.shields.io/badge/Website-pulsarx.cloud-A855F7?style=for-the-badge&logo=cloudflare&logoColor=white)](https://pulsarx.cloud)

</div>

**PulsarX Cloud** — собственная облачная платформа для аренды изолированных Linux mini-VPS.

Пользователь регистрируется, выбирает конфигурацию и операционную систему, после чего платформа автоматически создаёт готовый сервер на инфраструктуре PulsarX.

### ⚡ Возможности

- 🚀 **Self-Service Provisioning** — сервер создаётся автоматически
- 🐧 **Linux Instances** — Debian / Ubuntu
- 📦 **Incus Containers** — изолированные Linux-инстансы
- 📊 **Live Monitoring** — CPU / RAM / Disk / Network
- 🌐 **Web Hosting** — домены и reverse proxy
- 🔐 **Security** — firewall, rate limiting, Fail2Ban, SSH hardening
- 📧 **Email Automation** — verification, credentials, password reset
- 💾 **Off-site Backups** — автоматические резервные копии
- 🛡️ **Resource Isolation** — CPU / RAM / storage limits
- 👨‍💻 **Admin Panel** — управление пользователями и инстансами

### 🏗️ Архитектура

```text
                    ┌─────────────────┐
                    │      User       │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │  pulsarx.cloud  │
                    │      Nginx      │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │    FastAPI      │
                    │     Backend     │
                    └──────┬───┬──────┘
                           │   │
                 ┌─────────┘   └─────────┐
                 ▼                       ▼
        ┌─────────────────┐     ┌─────────────────┐
        │   PostgreSQL    │     │      Incus      │
        │     Database    │     │    Instances    │
        └─────────────────┘     └────────┬────────┘
                                         │
                              ┌──────────┼──────────┐
                              ▼          ▼          ▼
                           Server 1   Server 2   Server 3
```

### 🛠️ PulsarX Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Incus](https://img.shields.io/badge/Incus-333333?style=for-the-badge&logo=linuxcontainers&logoColor=white)
![Nginx](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---

# 🧰 Стек и инструменты

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Nginx](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Incus](https://img.shields.io/badge/Incus-333333?style=for-the-badge&logo=linuxcontainers&logoColor=white)
![Pterodactyl](https://img.shields.io/badge/Pterodactyl-04032D?style=for-the-badge&logo=pterodactyl&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

# 🖥️ Infrastructure & Hosting

### 🐧 Linux & DevOps

- Administration of Debian/Linux servers
- VPS deployment and configuration
- Nginx reverse proxy
- HTTPS / Let's Encrypt
- SSH hardening
- UFW / nftables
- Fail2Ban
- systemd
- Bash automation
- Server monitoring
- Automated backups
- Infrastructure security

### 🌐 Web Hosting

- VPS-based hosting
- Reverse proxy architecture
- Domain routing
- SSL certificates
- Isolated application environments
- Self-service deployment systems

### 🎮 Game Hosting

- Pterodactyl deployment
- Wings / Daemon configuration
- CS2 / CS:GO server hosting
- Server automation
- Performance optimization

---

# 📌 Другие проекты

## 🌐 Web

<div align="center">

[![FlorarieCarpineni](https://github-readme-stats.vercel.app/api/pin/?username=Dany0443&repo=FlorarieCarpineni&theme=radical)](https://github.com/Dany0443/FlorarieCarpineni)

[![debian_send](https://github-readme-stats.vercel.app/api/pin/?username=Sansikkkk&repo=debian_send&theme=radical)](https://github.com/Sansikkkk/debian_send)

</div>

**`debian_send`** — сайт для временной отправки и обмена файлами.

---

## 🛠️ Utilities

<div align="center">

[![PasswordGen](https://github-readme-stats.vercel.app/api/pin/?username=Sansikkkk&repo=PasswordGen&theme=radical)](https://github.com/Sansikkkk/PasswordGen)

[![debian_cs2server](https://github-readme-stats.vercel.app/api/pin/?username=Sansikkkk&repo=debian_cs2server&theme=radical)](https://github.com/Sansikkkk/debian_cs2server)

</div>

**`PasswordGen`** — генератор безопасных паролей.

**`debian_cs2server`** — инструменты для развёртывания CS2-серверов на Debian.

---

## 📱 Mobile

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

[![CheckQuest](https://github-readme-stats.vercel.app/api/pin/?username=Sansikkkk&repo=checkquest&theme=radical)](https://github.com/Sansikkkk/checkquest)

</div>

**`CheckQuest`** — мобильное приложение на Dart + Flutter для сканирования чеков, OCR и анализа покупок.

---

# 📊 GitHub статистика

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sansikkkk&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sansikkkk&layout=compact&theme=radical&hide_border=true" width="38%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sansikkkk&theme=radical&hide_border=true" width="60%" />

</div>

---

# 📫 Связь со мной

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/WJTdev)

[![PulsarX Cloud](https://img.shields.io/badge/PulsarX_Cloud-pulsarx.cloud-A855F7?style=for-the-badge&logo=cloudflare&logoColor=white)](https://pulsarx.cloud)

</div>

<div align="center">

⭐ **Если мои проекты вам полезны — поставьте звезду!** ⭐

</div>
