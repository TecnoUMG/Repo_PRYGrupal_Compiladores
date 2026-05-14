# 📘 LinguaCore - Simulador de Compilador Traductor Inglés-Español

**Proyecto Grupal de Compiladores 2026**  
*Universidad Mariano Gálvez de Guatemala*  
*Facultad de Ingeniería en Sistemas de Información y Ciencias de la Computación*  
*Catedrática: Inga. M.A. Sheyla Esquivel*  
*Campus Jutiapa – 2026*

---

## 🚀 Descripción General

**LinguaCore** es un simulador de compilador diseñado para traducir oraciones entre inglés y español (y viceversa), aplicando los principios fundamentales de la construcción de compiladores. A diferencia de traductores estadísticos o neuronales convencionales, LinguaCore no solo traduce, sino que **analiza y valida la estructura gramatical** del texto antes de generar la salida.

El sistema realiza un análisis profundo en tres fases:
1.  **Análisis Léxico:** Tokenización y clasificación de palabras (sustantivos, verbos, adjetivos, etc.) mediante expresiones regulares.
2.  **Análisis Sintáctico:** Validación de la estructura de la oración utilizando gramáticas BNF y generación de árboles de derivación.
3.  **Análisis Semántico:** Verificación de concordancia (género/número) y validez lógica.

Solo si la entrada está libre de errores críticos, el motor de síntesis genera la traducción final. Si existen errores, se reportan detalladamente en una tabla transversal.

> **Slogan:** *"Where language meets logic"*  
> **Concepto:** Una herramienta de traducción inteligente que garantiza precisión gramatical.

---

## 🛠️ Especificaciones Técnicas y Entorno

Para ejecutar este proyecto correctamente, asegúrese de cumplir con los siguientes requisitos de software y versiones. El proyecto ha sido desarrollado bajo estándares modernos de Python.

### ✅ Versiones Requeridas

| Componente | Versión Mínima Recomendada | Notas |
| :--- | :--- | :--- |
| **Python** | `3.13` o superior | Compatible con Windows, Linux y macOS. |
| **pip** | `21.0` o superior | Gestor de paquetes de Python. |
| **Git** | `2.30` o superior | Para clonar el repositorio y control de versiones. |
| **Node.js** | `18.x` (Opcional) | Solo si se utiliza la versión Web con Flask + React/Vue (si aplica). |

### 📦 Librerías y Dependencias

El proyecto utiliza las siguientes librerías externas. Instálelas ejecutando el comando indicado en la terminal desde la raíz del proyecto:

```bash
pip install -r requirements.txt
