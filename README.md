<div align="center">

# 🎮 Customer Data Dashboard

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![Reflex](https://img.shields.io/badge/reflex-0.5.3-purple.svg)](https://reflex.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

> 🚀 A modern, interactive dashboard for managing and visualizing customer data, built with Reflex and PostgreSQL.

<!-- ![Dashboard Preview](assets/dashboard-preview.png) -->

## 💫 Features

- 📊 Real-time data visualization with stunning charts
- 🔐 Enterprise-grade security & data management
- 📱 Sleek responsive design for all devices
- ⚡️ Lightning-fast live updates
- 🎨 Beautiful customizable themes
- 📈 Advanced data analytics & insights
- 🤖 AI-powered data predictions
- 🌐 Multi-language support
- 🔍 Smart search functionality
- 🎯 Intuitive user interface

## ⚡️ Quick Start

### 🛠 Prerequisites

```bash
# 🔍 Check Python version (3.9 or higher required)
python --version

# 📦 Check pip version
pip --version
```

<!-- ### 🚄 One-Line Installation

```bash
# 🎯 Clone and install in one command
git clone https://github.com/YourUsername/dashboard.git && cd dashboard && python -m venv venv && source venv/bin/activate && pip install -r requirements.txt
``` -->

### 🎯 Step-by-Step Installation

1. **📥 Clone the repository**
   ```bash
   git clone https://github.com/elkenzi/dashboard.git
   cd dashboard
   ```

2. **🔮 Create and activate virtual environment**
   ```bash
   # 🌟 Create venv
   python -m venv venv

   # ✨ Activate venv (choose based on your OS)

   # 🍎 macOS/Linux:
   source venv/bin/activate
   # 🪟 Windows:
   .\venv\Scripts\activate
   ```

3. **📦 Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **⚙️ Set up environment**
   ```bash
   # 📝 Copy example env file
   cp .env.example .env
   # ✏️ Edit .env with your settings
   ```

5. **🎮 Initialize the app**
   ```bash
   reflex init
   reflex db migrate
   ```

6. **🚀 Launch the app**
   ```bash
   reflex run
   ```

   🎉 Visit `http://localhost:3000` in your browser and watch the magic happen! ✨

<!-- ## 📚 Documentation

### 🗂 Project Structure
```
dashboard/
├── 📂 .github/         # GitHub Actions workflows
├── 🎨 assets/         # Static assets
├── 🎯 dashboard/      # Main application code
├── 🧪 tests/         # Test files
├── 📝 .env.example   # Example environment variables
├── 📋 .gitignore     # Git ignore rules
├── 📖 README.md      # This file
└── 📦 requirements.txt # Python dependencies
```

<!-- markdown-table 
### 🔐 Environment Variables
| Variable | Description | Default |
|----------|-------------|---------|
| 🔗 DATABASE_URL | Database connection string | sqlite:///reflex.db |
| 🐞 DEBUG | Debug mode | False |
| 🔑 SECRET_KEY | App secret key | None |
-->
<!-- ## 🧪 Development -->

<!-- ### 🎯 Code Guide

```bash
# 📦 Install dev dependencies
pip install -r requirements.txt

# ✨ Format code
black .

# 🔍 Run lints
flake8 .

# 🎯 Type checking
mypy .

# 🧪 Run tests
pytest
```

### 🗃 Database Management

```bash
# ✨ Create new migration
reflex db migrate

# 🚀 Apply migrations
reflex db upgrade

# ⏮ Rollback
reflex db downgrade
```

## 🚀 Deployment

### 🤖 GitHub Actions (CI/CD)

This repository includes GitHub Actions workflows for:
- 🧪 Automated testing
- ✨ Code quality checks
- 🚀 Deployment to production

### 🎯 Manual Deployment

1. **📦 Prepare for deployment**
   ```bash
   # 🏗 Build the project
   reflex export
   ```

2. **🗃 Set up production database**
   ```bash
   # 🐘 Example with PostgreSQL
   export DATABASE_URL="postgresql://user:password@host:5432/dbname"
   ```

3. **🚀 Deploy to your platform of choice**
   - [🔷 Deploy to Vercel](docs/deploy-vercel.md)
   - [💜 Deploy to Heroku](docs/deploy-heroku.md)
   - [🌊 Deploy to DigitalOcean](docs/deploy-digitalocean.md)

## 🔧 Troubleshooting

### ❗️ Common Issues

<details>
<summary>🔌 Database Connection Error</summary>

```bash
# 🔍 Check database connection
python -c "from dashboard.db import check_connection; check_connection()"
```
- 🔍 Verify DATABASE_URL format
- 🔑 Check database credentials
- ⚡️ Ensure database server is running
</details>

<details>
<summary>📦 Import Errors</summary>

- ✅ Verify virtual environment is activated
- 🔄 Reinstall dependencies: `pip install -r requirements.txt`
- 🧹 Clear Python cache: `find . -type d -name "__pycache__" -exec rm -r {} +`
</details> --> 

## 🤝 Contributing

1. 🔱 Fork the repository
2. 🌿 Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. ✨ Commit your changes (`git commit -m '✨ Add some AmazingFeature'`)
4. 🚀 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🎯 Open a Pull Request

<!-- See [📋 CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines. -->

## 📜 License

This project is licensed under the MIT License - see the [📄 LICENSE](LICENSE) file for details.

## 💝 Acknowledgments

- 💎 [Reflex](https://reflex.dev/) for the amazing framework
- 🌟 [Contributors](../../graphs/contributors) who participated in this project

---
⭐️ Star us on GitHub — it helps us reach more developers! 🚀

<p align="center">
  <a href="https://github.com/moelkenzi/PyDashboard">
    <img src="https://img.shields.io/github/stars/moelkenzi/PyDashboard?style=social" alt="GitHub stars">
  </a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=60&section=footer" width="100%" />
  <br/>
  <sub>
    <img src="https://raw.githubusercontent.com/khoa083/khoa/main/Khoa_ne/img/Rainbow.gif" width="60%" height="2px">
  </sub>
  <br/>
  <sub>Made with 💖 and ☕️ by</sub>
  <br/>
  <a href="https://github.com/moelkenzi">
    <img src="https://img.shields.io/badge/moelkenzi-%23121011.svg?style=for-the-badge&logo=github&logoColor=white&color=000000" alt="moelkenzi" />
  </a>
  <br/>
  <a href="https://twitter.com/moelkenzi">
    <img src="https://img.shields.io/badge/Follow-%23000000.svg?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X" />
  </a>
  <br/>
  <sub>
    <img src="https://raw.githubusercontent.com/khoa083/khoa/main/Khoa_ne/img/Rainbow.gif" width="60%" height="2px">
  </sub>
</div>