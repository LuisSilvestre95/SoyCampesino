# 📂 LISTADO COMPLETO DE ARCHIVOS MULTIMEDIA REQUERIDOS

## Estructura de Carpetas

```
diego-campesino/
├── index.html
├── img/
│   ├── logo-partido.png
│   ├── portada.jpg
│   ├── diego-hero.png
│   ├── historia.jpg
│   ├── testimonio1.mp4
│   ├── testimonio1.jpg
│   ├── testimonio2.mp4
│   ├── testimonio2.jpg
│   ├── testimonio3.mp4
│   ├── testimonio3.jpg
│   ├── video1.jpg
│   ├── video2.jpg
│   ├── video3.jpg
│   └── video4.jpg
```

---

## 📋 TABLA DE ARCHIVOS REQUERIDOS

| # | Nombre del Archivo | Formato | Tamaño Recomendado | Ubicación | Descripción |
|---|---|---|---|---|---|
| 1 | `logo-partido.png` | PNG (Transparente) | 500x500px mín. | `img/` | Logo del partido Alianza Verde o tu movimiento |
| 2 | `portada.jpg` | JPG | 1920x1080px mín. | `img/` | Imagen de fondo para el Hero (sección principal) |
| 3 | `diego-hero.png` | PNG (Transparente) | 800x1000px mín. | `img/` | Tu foto oficial sin fondo para el Hero |
| 4 | `historia.jpg` | JPG | 1920x1080px mín. | `img/` | Foto para la sección "De la Tierra a la Política" |
| 5 | `testimonio1.mp4` | MP4 (Video) | 1080p o 4K | `img/` | **Video MP4** del primer testimonio (9:16 vertical) |
| 6 | `testimonio1.jpg` | JPG | 1080x1920px mín. | `img/` | Captura/thumbnail del primer video |
| 7 | `testimonio2.mp4` | MP4 (Video) | 1080p o 4K | `img/` | **Video MP4** del segundo testimonio (9:16 vertical) |
| 8 | `testimonio2.jpg` | JPG | 1080x1920px mín. | `img/` | Captura/thumbnail del segundo video |
| 9 | `testimonio3.mp4` | MP4 (Video) | 1080p o 4K | `img/` | **Video MP4** del tercer testimonio (9:16 vertical) |
| 10 | `testimonio3.jpg` | JPG | 1080x1920px mín. | `img/` | Captura/thumbnail del tercer video |
| 11 | `video1.jpg` | JPG | 1080x1920px mín. | `img/` | Captura de alta resolución del video de Instagram |
| 12 | `video2.jpg` | JPG | 1080x1920px mín. | `img/` | Captura de alta resolución del video de TikTok |
| 13 | `video3.jpg` | JPG | 1080x1920px mín. | `img/` | Captura de alta resolución del video de Facebook |
| 14 | `video4.jpg` | JPG | 1080x1920px mín. | `img/` | Captura de alta resolución del video de YouTube |

---

## 🎬 DETALLES IMPORTANTES

### Testimonios (Videos MP4)
- **Formato**: MP4 (H.264 codec recomendado)
- **Resolución**: 1080p (1920x1080) o 4K (3840x2160)
- **Aspecto**: 9:16 (vertical, como un Reel)
- **Duración**: 15-30 segundos recomendado
- **Audio**: Sin sonido (muted) - Los videos se reproducen silenciados automáticamente
- **Características**: 
  - Se reproducen automáticamente en loop
  - Sin sonido para no molestar
  - Al pasar el cursor, aparece un ícono de play

### Imágenes JPG (Thumbnails)
- **Formato**: JPG (comprimido para carga rápida)
- **Resolución**: Mínimo 1080x1920px (para simular 4K)
- **Aspecto**: 9:16 (vertical)
- **Uso**: Se muestran como fallback si el video no carga

### Logo y Fotos PNG
- **Formato**: PNG con fondo transparente
- **Resolución**: Alta (mínimo 500x500px para logo)
- **Uso**: Se integran sin bordes blancos

---

## 📌 NOTAS CRÍTICAS

1. **Videos MP4**: Los videos deben estar en formato MP4 con codec H.264 para máxima compatibilidad.
2. **Tamaño de Archivo**: Intenta mantener cada video MP4 por debajo de 10MB para carga rápida.
3. **Compresión**: Usa herramientas como FFmpeg o HandBrake para comprimir videos sin perder calidad.
4. **Nombres Exactos**: Los nombres de los archivos deben ser exactamente como se muestran aquí (minúsculas, sin espacios).
5. **Carpeta img/**: Todos los archivos deben estar en la carpeta `/home/ubuntu/diego-campesino/img/`.

---

## 🔧 COMANDO PARA VERIFICAR ARCHIVOS

Una vez que tengas todos los archivos en la carpeta `img/`, ejecuta este comando para verificar:

```bash
ls -lh /home/ubuntu/diego-campesino/img/
```

Deberías ver 14 archivos en total.

---

## 📱 FORMATOS RECOMENDADOS POR SECCIÓN

| Sección | Archivos | Formato |
|---|---|---|
| **Identidad** | logo-partido.png | PNG (Transparente) |
| **Hero** | portada.jpg, diego-hero.png | JPG + PNG |
| **Historia** | historia.jpg | JPG |
| **Testimonios** | testimonio1-3.mp4, testimonio1-3.jpg | MP4 + JPG |
| **Reels Virales** | video1-4.jpg | JPG |

---

**¡Con estos 14 archivos, tu página web estará 100% lista para el lanzamiento!** 🥔🌱
