# 📈 Automatización de Análisis de Acciones con Python

Este proyecto permite automatizar la recolección, análisis y envío de datos financieros sobre acciones bursátiles.

## 🔧 ¿Qué hace?

- Solicita al usuario el código de una acción y un rango de fechas.
- Obtiene datos desde **Yahoo Finanzas** usando `yfinance`.
- Calcula el valor máximo, mínimo y promedio de los precios de cierre.
- Genera un gráfico con `matplotlib`.
- Envía automáticamente los resultados por correo electrónico usando `pyautogui` y `Gmail`.

## 🛠️ Tecnologías utilizadas

- Python
- yfinance
- matplotlib
- pyautogui
- pyperclip

## 📩 Resultado

El usuario recibe por correo un resumen con los datos de la acción y un gráfico adjunto, sin necesidad de hacer el proceso manualmente.

---

Proyecto desarrollado por Oscar Junca.
