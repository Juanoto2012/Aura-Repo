<p align="center">
  <a href="https://aura-repo.infinityfreeapp.com/">
    <img src="https://aura-repo.infinityfreeapp.com/logo.png" width="120" alt="Aura Repo Logo">
  </a>
</p>

<h1 align="center">🗄️ Aura Repo | Catálogo Libre</h1>

<p align="center">
  <strong>El núcleo de datos y el motor del catálogo de software libre.</strong><br>
  Curado por IA • Escaneado con VirusTotal • Vibe-Coded
</p>

<p align="center">
  <a href="https://aura-repo.infinityfreeapp.com/">
    <img src="https://img.shields.io/badge/Sitio_Web-aura--repo-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Sitio Web">
  </a>
  <a href="https://github.com/Juanoto2012/Aura-Repo/issues">
    <img src="https://img.shields.io/badge/Añadir_App-RFP-000000?style=for-the-badge&logo=github&logoColor=white" alt="Submit App">
  </a>
  <img src="https://img.shields.io/github/v/release/Juanoto2012/Aura-Repo?style=for-the-badge&color=000000" alt="Version">
</p>

---

## 📖 Acerca de este Repositorio

Este repositorio actúa como el **Backend "Serverless"** de [Aura Repo](https://aura-repo.infinityfreeapp.com/). Contiene el archivo maestro `apps.json`, el cual alimenta dinámicamente la interfaz de nuestra tienda. 

Nuestra misión es ofrecer un repositorio de Android moderno y pragmático que permita aplicaciones de IA y conectividad total, manteniendo la seguridad mediante análisis de malware automatizados.

##😉 Usa nuestro badge personalizado en tu repositorio o sitio web 

<a href="https://aura-repo.infinityfreeapp.com/?appid=your_app_ide">
  <img src="https://aura-repo.infinityfreeapp.com/badge.png" alt="Get it on Aura Repo" width="322">
</a>

## 📄 El Archivo Maestro (`apps.json`)

El archivo `apps.json` contiene la base de datos de todas las aplicaciones listadas. Si eres desarrollador, asegúrate de que tu entrada siga este esquema:

```json
{
  "id": "com.ejemplo.app",
  "name": "Nombre de la App",
  "developer": "Tu Nombre",
  "icon_url": "[https://link-al-icono.png](https://link-al-icono.png)",
  "short_desc": "Descripción breve para el banner.",
  "description": "Descripción completa de la aplicación.",
  "version": "1.0.0",
  "size": "15 MB",
  "license": "GPL-3.0",
  "category": "Herramientas",
  "download_url": "[https://github.com/usuario/repo/releases/download/v1/app.apk](https://github.com/usuario/repo/releases/download/v1/app.apk)",
  "repo_url": "[https://github.com/usuario/repo](https://github.com/usuario/repo)",
  "screenshots": ["url1.jpg", "url2.jpg"],
  "featured": true,
  "timestamp": "2026-04-03T12:00:00Z"
}
