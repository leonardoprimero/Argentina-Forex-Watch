# Argentina Forex Watch 🇦🇷💱

> Herramienta automatizada para seguir de cerca la evolución del mercado cambiario argentino.

Argentina Forex Watch nace como una necesidad práctica: tener a mano una caja de herramientas para analizar el tipo de cambio en Argentina desde diferentes ángulos. Este proyecto incluye scripts en Python para obtener datos del Banco Central, del Matba-Rofex y de los mercados financieros, y genera gráficos e informes automáticos listos para ser enviados por correo.

---

## 📊 ¿Qué incluye?

### 📈 Análisis de tasas implícitas
Estudio de la curva de futuros de dólar, calculando la tasa implícita en base a los precios del Matba-Rofex. Esto permite estimar la expectativa del mercado respecto a la devaluación futura.

![Tasa Implícita](https://raw.githubusercontent.com/leonardoprimero/Argentina-Forex-Watch/refs/heads/main/rateImpl.png)

---

### 💱 Diferentes tipos de cambio
Comparación visual entre los distintos tipos de cambio vigentes en Argentina: oficial, solidario, MEP, CCL, y más. Incluye valores implícitos calculados a través de Cedears y ADRs.

![Tipos de Cambio](https://github.com/leonardoprimero/Argentina-Forex-Watch/blob/main/Exchanges.png?raw=true)

---

### 📉 Seguimiento general del mercado
Una visión global y simplificada del mercado cambiario argentino a través de una infografía que resume el estado de las cotizaciones en tiempo real y su relación con variables claves del mercado.

![Resumen General](https://raw.githubusercontent.com/leonardoprimero/Argentina-Forex-Watch/refs/heads/main/ArgentinaFX.png)

---

## 🧰 Scripts incluidos

- `bcra.py`: Descarga datos del BCRA y analiza agregados monetarios.
- `futuresCurve.py`: Analiza la curva de futuros y calcula tasas implícitas.
- `Exchanges.py`: Calcula y grafica diferentes tipos de cambio (oficial + impuestos, Cedears, ADR).
- `spotRofex.py`: Scrapea el sitio del Matba-Rofex para obtener el spot del dólar.
- `forexReport.py`: Envío automatizado de reportes por correo.
- `templateReport.py`: Plantilla en HTML/CSS lista para usar en informes.
- `credentials.py`: Archivo donde se cargan las credenciales del mail.

---

## ⚙️ Instalación

```bash
pip install -r requirements.txt
```

---

## 📬 Notas

- Los archivos `.xlsx`, `.csv` e imágenes se generan automáticamente al ejecutar los scripts.
- Este proyecto es ideal tanto para uso personal como para estudios contables que necesiten reportes rápidos y personalizados del mercado.

---

**Desarrollado por Leonardo Caliva · [@leonardoprimero](https://github.com/leonardoprimero)**
