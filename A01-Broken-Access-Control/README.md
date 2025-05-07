## 🧠 Descripción
Broken Access Control ocurre cuando los usuarios pueden actuar fuera de sus permisos intencionados. Por ejemplo, acceder a archivos o recursos a los que no deberían tener acceso, como `/etc/passwd` en sistemas Linux.

## ⚙️ Entorno de pruebas

- Kali Linux como atacante
- Metasploitable2 como víctima
- Conectividad establecida entre ambas VMs
- IP de la víctima: `192.168.X.X` *(reemplazar por la real)*

## 🔍 Escaneo inicial

Se utilizó el siguiente comando Nmap para detectar servicios y puertos abiertos:

```bash
nmap -sS -sV -O 192.168.X.X


> Autor: Jerson Giraldo  
> Proyecto: OWASP Top 10 Lab  
> Año: 2025
