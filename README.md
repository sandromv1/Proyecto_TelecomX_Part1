# 📊 Proyecto TelecomX - Análisis de Evasión de Clientes

## 📌 Propósito del análisis
El objetivo de este proyecto es **analizar y comprender los factores que influyen en la evasión de clientes (churn)** en una empresa de telecomunicaciones, identificando patrones y características clave que permitan desarrollar **estrategias de retención efectivas**.

Se busca:
- Detectar variables con mayor relación con la cancelación de contratos.
- Visualizar la distribución de la evasión según variables categóricas y numéricas.
- Proponer acciones estratégicas para reducir el churn.

---

## 📂 Estructura del proyecto

Proyecto_TelecomX_Part1/

│

├── Extraccion de los datos

├── Transformacion de los datos

├── Carga y analisis (Se presenta visualizaciones)

├── Informe Final


## 📈 Ejemplos de gráficos e insights obtenidos

### 🔹 Distribución general de evasión
- **26,5 %** de los clientes se dieron de baja (1 869 de 7 032).

### 🔹 Variables con mayor relación con `Dejo_Empresa`
1. **Meses_Contrato**: Clientes que se quedaron tienen una mediana de 38 meses, mientras que los que se fueron, 10 meses.
2. **Tipo_Contrato**: Mayor evasión en contratos `Month-to-month`.
3. **Servicio_Internet**: Fiber optic presenta la mayor tasa de baja (~42%).
4. **Método_Pago**: `Electronic check` muestra la tasa de evasión más alta (~45%).
5. **Servicios de soporte/seguridad**: No contar con Seguridad Online, Respaldo, Protección de Dispositivos o Soporte Técnico aumenta la probabilidad de baja.
6. **Factura_Digital**: Mayor evasión en usuarios que la utilizan (~33,6%).
7. **Cargo_Mensual**: Más alto en clientes que se dieron de baja (mediana de 79,65 vs 64,45).

### 📊 Ejemplo de gráficos
- Barras agrupadas para evasión por variable categórica.
- Boxplots para variables numéricas vs evasión.

---

## 💡 Principales conclusiones e insights
- La **antigüedad del cliente** es un factor determinante: clientes nuevos tienen mayor riesgo de baja.
- Los **contratos mensuales** concentran la mayor parte del churn.
- Determinados **servicios complementarios** están asociados a una mejor retención.
- **Métodos de pago automáticos** parecen más efectivos para reducir la evasión.
- Clientes con **factura digital** presentan una tasa de baja más alta, lo que podría indicar problemas de experiencia de usuario.

---

## 🎯 Recomendaciones estratégicas
1. **Fomentar contratos de largo plazo** mediante descuentos o beneficios.
2. **Mejorar la experiencia de clientes con Fiber optic** revisando calidad y soporte.
3. **Incentivar pagos automáticos** con promociones.
4. **Ofrecer paquetes con servicios de soporte y seguridad** incluidos para clientes de alto riesgo.

## ⚙️ Instrucciones para ejecutar el notebook
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/Proyecto_TelecomX_Part1.git
   cd Proyecto_TelecomX_Part1
