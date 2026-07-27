# 🛡️ SAFE — Academic Business Training System

> A corporate learning platform that centralizes training, tracks employee progress, and gives managers real-time visibility — Software Engineering I project, Universidad Nacional de Colombia, 2025.

SAFE (*Sistema Académico de Formación Empresarial*) solves a real problem: organizations struggle to train employees consistently and measure the impact of that training. SAFE brings courses, roles, evaluations, and progress dashboards into one platform.

---

## ✨ Features

- 📚 **Personalized learning paths** — employees access courses and advance at their own pace
- 🔔 **Smart notifications** — timely alerts for achievements and pending tasks
- 👥 **Role-based access** — employees, HR managers, supervisors, and directors each see what they need
- 📊 **Progress dashboards** — supervisors track team performance with clear indicators
- 🔐 **User and content management** — HR admins manage users, roles, and training content

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python (Django) |
| Frontend | HTML / CSS |
| Infrastructure | Docker + Docker Compose |
| Database | Relational (via Django ORM) |
| Deployment | Cross-platform setup scripts (Windows + Linux/macOS) |

---

## 🚀 Getting Started

### Prerequisites
- [Docker](https://www.docker.com/get-started) installed on your system

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/TommyBermu/error404.git
   cd error404/Proyecto
   ```

2. Set up environment variables (if needed):
   ```bash
   cp .env.example .env
   # Edit .env with your settings
   ```

3. Run the setup script:
   ```bash
   # Windows
   ./setup.bat

   # macOS / Linux
   chmod +x setup.sh
   ./setup.sh
   ```

4. Open your browser at `http://localhost:8000`

### Demo admin account

```bash
docker compose exec -T web python manage.py ensure_default_admin
# Default credentials: username "admin" / password "Admin123!"
```

---

## 👥 Team

Developed as a university project for the **Software Engineering I** course at **Universidad Nacional de Colombia**.

| Name | Contact |
|---|---|
| Tomás Alejandro Bermúdez Guaqueta | tbermudezg@unal.edu.co |
| Daniel Alfonso Cely Infante | dcelyi@unal.edu.co |
| David Alejandro Herrera Novoa | daherreran@unal.edu.co |
| Daniel Alonso Gracia Pinto | dagraciap@unal.edu.co |
