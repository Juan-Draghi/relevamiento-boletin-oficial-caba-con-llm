# Análisis automatizado del Boletín Oficial con filtrado semántico

Este proyecto permite detectar automáticamente normativa de interés publicada en el Boletín Oficial de la Ciudad Autónoma de Buenos Aires, utilizando un enfoque mixto basado en búsqueda por palabras clave y evaluación semántica asistida por un modelo de lenguaje (LLM).

## 🧩 Funcionalidad

- Extrae texto de ejemplares en PDF del Boletín Oficial.
- Busca coincidencias con una lista de términos clave.
- Evalúa si el contexto indica una acción normativa real (modificación, aprobación, derogación, etc.).
- Exporta los resultados pertinentes en un archivo Excel, listo para revisión o archivo.

## 📚 Requisitos

- Google Colab
- Cuenta en Google Cloud con acceso a Gemini API (API Key)
- Archivo Excel con términos clave (opcional)
- Archivo PDF del Boletín (subido o accedido desde Drive o URL)

## 🚀 Cómo usarlo

1. Abrí el script en Google Colab.
2. Cargá el PDF del Boletín (o configurá para usar Drive o una URL fija).
3. Indicá los términos clave o cargá el archivo `.xlsx`.
4. El script generará un Excel con los resultados pertinentes, listos para descargar.

## 🔒 Licencia

Este proyecto se distribuye bajo la licencia MIT. Puede ser reutilizado, adaptado o modificado libremente, citando al autor original.

---

# Automated Analysis of Official Gazette with Semantic Filtering

This project enables the automated detection of relevant regulations published in the Official Gazette Buenos Aires City, using a mixed approach based on keyword matching and semantic filtering powered by a Large Language Model (LLM).

## 🧩 Features

- Extracts text from Official Gazette PDF files.
- Searches for matches with a custom keyword list.
- Evaluates whether the context reflects a real normative action (modification, approval, repeal, etc.).
- Exports pertinent results to Excel for review or archiving.

## 📚 Requirements

- Google Colab
- Google Cloud account with access to Gemini API (API Key)
- Excel file with keywords (optional)
- Official Gazette PDF (uploaded, from Drive, or via URL)

## 🚀 How to Use

1. Open the script in Google Colab.
2. Upload the Gazette PDF or connect to Drive/URL.
3. Provide keyword list or upload `.xlsx` file.
4. The script will export an Excel file with filtered results ready for download.

## 🔒 License

This project is released under the MIT License. Feel free to reuse or adapt it with attribution.
