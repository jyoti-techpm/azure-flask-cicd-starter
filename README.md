# Azure Flask Web App – CI/CD Deployment via GitHub

This project demonstrates a simple Python Flask web application deployed to **Azure App Service** using **GitHub Actions** for continuous deployment.

## 🔧 Tech Stack

- **Python Flask** – lightweight web framework
- **Azure App Service** – scalable PaaS to host the app
- **GitHub Actions** – CI/CD automation
- **gunicorn** – production-ready WSGI server
- **Azure Monitor & Application Insights** (coming soon)

## 🌐 Live Demo

Access the deployed application here:  
👉 [https://jyoti-flask-app-e6bkbsh2hqddcwcf.canadacentral-01.azurewebsites.net](https://<your-app-name>.azurewebsites.net)

## 🚀 How It Works

1. Code is pushed to GitHub
2. GitHub triggers Azure Deployment Center
3. Azure installs Python packages from `requirements.txt`
4. Azure uses `gunicorn app:app` to launch Flask app
5. App is live within seconds!

## 📁 File Structure



## 💼 Author

**Jyotirmayee Ramaraju**  
Senior Technical Project Manager | Cloud & AI Advocate  
[GitHub](https://github.com/jyoti-techpm) | [LinkedIn](https://linkedin.com/in/jyotirmayee-ramaraju-75142958)

---

## 📌 Next Enhancements

- [ ] Add Azure Monitor + Application Insights
- [ ] Integrate Azure DevOps CI/CD pipeline (YAML)
- [ ] Add Blob Storage or Azure B2C integration
