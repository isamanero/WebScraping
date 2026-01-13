# 🌐 Web Scraping Académico – Ejemplos de Práctica 📊

Bienvenid@ a este repositorio de **web scraping**, desarrollado **exclusivamente con fines académicos**. Aquí encontrarás tres ejemplos prácticos de extracción, limpieza y enriquecimiento de datos, usando técnicas controladas y responsables. ⚠️ No se deben utilizar con fines comerciales ni masivos.

---

## 📚 Ejemplos incluidos

1. **📱 Scraping de smartphones**  
   - Extrae nombre y precio de móviles desde una página de tecnología.  
   - Permite realizar scrapes en diferentes fechas para **comparar precios** y analizar **tendencias temporales**.

2. **🐟 Scraping de zonas FAO de pesca**  
   - Asocia las zonas FAO numéricas de un CSV con sus correspondientes **zonas marinas** (ej. FAO 27 → Atlántico Norte).  
   - Ejemplo de **enriquecimiento de datos** añadiendo información contextual.

3. **🎬 Scraping de películas de Pixar**  
   - Gestión de **valores nulos** en un CSV: se buscan fechas de estreno faltantes en fuentes confiables y se completan los registros.  
   - Ejemplo de **limpieza y enriquecimiento de datasets** mediante scraping eficiente.

---

## 📂 Estructura del repositorio

├─ files/ ← CSVs originales y usados en los notebooks

├─ img/ ← Imágenes usadas (IA) de forma estética en los notebooks

├─ Notebooks/ ← Tres notebooks:

   │ ├─ WS_smartphones.ipynb
   
   │ ├─ WS_FAO.ipynb
   
   │ └─ WS_Pixar.ipynb
└─ README.md ← Este archivo

---

## ⚙️ Librerías utilizadas

- **Selenium** 🚀: Ideal para interactuar con páginas dinámicas, hacer clicks, scroll y navegación avanzada.  
- **BeautifulSoup** 🍵: Ideal para parsear HTML estático y extraer información de forma rápida y sencilla.  

**Mini-esquema de uso:**

| Librería       | Mejor uso | Ventaja principal                        |
|----------------|-----------|-----------------------------------------|
| Selenium 🚀    | Páginas dinámicas, JavaScript | Permite simular navegador completo |
| BeautifulSoup 🍵 | HTML estático                | Rápido y simple para extraer contenido |

---

## ⚠️ Nota importante

Todos los scrapes se realizaron de forma **ética y responsable**, únicamente con **propósitos educativos**.
---

¡Disfruta explorando el mundo del **web scraping académico**! 🌟


