landig


ChatGPT Plus
markdown
Copiar
Editar
# Links Cortos

**¿Qué es la API Links Cortos?**  
Genera URLs breves y personalizadas a partir de enlaces largos con una sola petición HTTP. Ideal para compartir en redes, correos o en tus propias aplicaciones.

---

## Playground  
1. Pega tu URL larga en el campo “Pega tu URL larga”.  
2. Haz clic en **Cortar**.  
3. Tu enlace corto aparecerá listo para copiar.

---

## Endpoint principal

### POST `/shorten`

- **Headers**: `Content-Type: application/json`  
- **Body**:
  ```json
  { "url": "https://ejemplo.com/enlace-muy-largo" }


### Respuesta (200 OK)
    {
    "id": 42,
    "urlOriginal": "https://ejemplo.com/enlace-muy-largo",
    "code": "hG12Sa",
    "localDateTime": "2025-05-16T12:00:00",
    "clickCount": 20,
    "urlShort": "https://linkscortos-1.onrender.com/hG12Sa"
    }
