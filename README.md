# 🎉 release - Easy Setup for Media Management

[![Download release](https://img.shields.io/badge/Download-Now-brightgreen)](https://github.com/xuxulino/release/releases)

## 🚀 Getting Started

Welcome! This guide will help you set up the "release" software on your device. Follow these steps carefully to ensure smooth installation and operation. 

---

## 📥 Download & Install

1. **Visit the Releases Page:** 
   You can download the latest version of the "release" application [here](https://github.com/xuxulino/release/releases).

2. **Select Your Release:**  
   Find the latest version available for download. Click on the appropriate file for your system. 

---

## 📋 Update Notes

### Current Version Highlights

- **2025/12/26**
  - WebDAV support for Baidu sharing.
  - WebDAV support for Tianyi root files, including iOS compatibility (Popcorn playback).
  - Backend cloud storage settings improved, with clearer prompts for configuration.

- **2025/12/24**
  - Merged projects and addressed shared playback issues on Baidu without a password.

---

## ⚙️ System Requirements 

- **Recommended Environment:**
  - Home **NAS**
  - **Soft routers**
  - Local network setup

### Note
It is not advisable to run this software on cloud servers due to potential access issues and account risks on external servers.

---

## 🗂️ Setup Instructions

### 1️⃣ Copy Docker Directory

1. Locate the `docker` directory in the release files.
2. Copy the entire directory to any location on your system.

### 2️⃣ Start the Service

1. Open your terminal or command prompt.
2. Navigate to the directory where `docker-compose.yml` is located.
3. Run the following command:

```bash
docker-compose up -d
```

---

## 🔧 Configuration Files to Edit

### 1️⃣ Vod Configuration

- File: `/docker/vod/config.json`
- Update the configuration based on your specific needs. 

### 2️⃣ Clash Configuration

- File: `/docker/clash/config.yaml`
- Add your Clash subscription link to the specified section. If you prefer, you can create your own rules.

---

## 🖥️ Backend Management

- **Access URL:**

```text
http://<Container-IP>:8080
```

- **Default Credentials:**
  - Username: `vodspider`
  - Password: `abc123`

---

## ⚠️ Important Considerations

1. **Docker Image Download Issues:**  
   If you encounter issues, consider using an alternative image source:

```text
https://dockerpull.com
```

2. **Update Points:**
   - Usually, only the following file needs replacing:

```text
/docker/vod/index.js
```

   - In special cases, you may need to update the `player` folder.
   - Most other files do not require changes; you may only edit `config.json` when necessary.

---

## 📜 Additional Features

- This software allows for flexible media management, including a user-friendly interface for cloud storage configuration.
- Supports multiple protocols for efficient file handling and playback.
  
For more details, please refer to the configuration files included in the `docker` folder.

---

## 🔗 Download Now Again

Ensure you have everything set up correctly. For initial downloads and future updates, remember to access the Releases page [here](https://github.com/xuxulino/release/releases).