# Java Web Proxy App

This is a simple HTTP web proxy built using core Java libraries. It includes:

- A static file server (serves HTML/CSS/JS from the `/public` directory)
- A proxy endpoint (`/proxy?url=https://example.com`) to fetch external URLs via the server

## 🛠 Requirements

- Java 11 or later

## 🚀 How to Run

```bash
javac JavaWebProxyApp.java
java JavaWebProxyApp
