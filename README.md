# Placa Control Fuentes y Carga - Hardware y PCB 🚀

Este repositorio contiene el diseño completo de la placa de circuito impreso (PCB) desarrollado en **KiCad 10** para el sistema de **Control de Fuentes y Gestión de Carga de Baterías**.

---

## 📌 Características del Diseño
* **Gestión de Energía:** Monitoreo y conmutación inteligente entre fuentes de alimentación principales y sistemas de respaldo por batería.
* **Etapa de Carga Integrada:** Circuito de control dedicado para la recarga segura, regulación de corriente y protección térmica del banco de baterías.
* **Supervisión Analógica:** Divisores de tensión de precisión y sensores de corriente dispuestos para la telemetría de voltajes críticos.
* **Protección de Entrada:** Fusibles rearmables, diodos de protección contra inversión de polaridad y supresores de transitorios (TVS).

---

## 🛠️ Especificaciones Técnicas de Fabricación
Configuración sugerida basada en las reglas de diseño (DRC) aplicadas en KiCad 10:

| Parámetro | Configuración Sugerida |
| :--- | :--- |
| **Capas (Layers)** | 2 Capas |
| **Grosor de la Placa** | 1.6 mm |
| **Grosor del Cobre** | 1 oz / 2 oz (Recomendado para pistas de alta corriente en etapas de carga) |
| **Acabado Superficial** | HASL (with lead) o ENIG |

---

## 👥 Desarrollado por
* **Damian Granzella** - *Ingeniería de Hardware* - [edgranzella](https://github.com)
