# Links Cortos

![Ícono de tijera](/linkTijera.png)

**Links Cortos** es un servicio HTTP que te permite generar URLs breves y personalizadas a partir de enlaces largos con una sola petición. Ideal para compartir en redes sociales, correos electrónicos o integrarlo en tus propias aplicaciones.

---

## 🔧 Características

- Generación de enlaces cortos en un solo `POST`  
- Playground interactivo para probar la API desde el navegador  
- Respuesta completa con metadatos:  
  - `id` (número): identificador interno  
  - `urlOriginal` (string): la URL larga enviada  
  - `code` (string): código alfanumérico generado  
  - `localDateTime` (string): fecha y hora de creación (ISO 8601)  
  - `clickCount` (número): número de accesos al enlace corto  
  - `urlShort` (string): la URL completa y acortada  
- Sin ánimo de lucro · App con propósito educativo y demostrativo

---

## 🛠️ Tecnologías

- **Backend**: Spring Boot, Java, H2 (perfil `local`)  
- **Frontend**: Astro + Tailwind CSS  
- **Formato**: JSON over HTTP

---

## 🚀 Instalación y ejecución

1. Clona este repositorio y entra en él:  
   ```bash
   git clone https://github.com/tu-usuario/links-cortos.git
   cd links-cortos
