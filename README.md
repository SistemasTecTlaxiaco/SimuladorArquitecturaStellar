# Stellar Network Explorer 🌌

![Stellar Network Simulator](https://img.shields.io/badge/Tec%20de%20Tlaxiaco-Ingenier%C3%ADa%20en%20Sistemas-004D40?style=for-the-badge) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

**Stellar Network Explorer** es un laboratorio interactivo de una sola página (SPA) diseñado con fines educativos. Sirve como un simulador visual para enseñar y comprender la arquitectura, el consenso (SCP) y el ecosistema de activos digitales de la blockchain de Stellar.

Desarrollado para estudiantes y entusiastas de **Ingeniería en Sistemas** y tecnologías descentralizadas (Web3).

---

## 🚀 Características Principales

La aplicación se divide en tres módulos de aprendizaje interactivo:

### 1. 🌐 Red de Nodos (Simulador de Topología y Consenso)
* **Canvas Interactivo (Drag & Drop):** Diseña tu propia red arrastrando y soltando nodos en el lienzo.
* **Tipos de Nodos Reales:** Coloca Validadores Completos, Validadores Básicos, Nodos RPC, Watchers, Archivers y nodos Galexie.
* **Flujo de Transacciones Realista:** Simula cómo una transacción viaja desde un nodo periférico, busca el Gateway (Nodo RPC) más cercano, y se distribuye a la red core.
* **Ola de Consenso (SCP):** Visualiza la propagación del *Federated Byzantine Agreement (FBA)* a través de *Quórum Slices* dinámicos mediante animaciones.

### 2. 💎 Activos Digitales (Simulación de Billetera y DEX)
* **Gestión de Cuenta:** Genera llaves públicas y simula saldos en **XLM** (Lumens).
* **Emisión de Tokens:** Crea y emite activos digitales personalizados (Stablecoins, Commodities, Tokens Educativos).
* **Líneas de Confianza (Trustlines):** Aprende la mecánica de seguridad de Stellar que requiere explícitamente "confiar" en un activo antes de recibirlo, simulando la reserva de XLM necesaria.
* **Exchange Descentralizado (DEX):** Interactúa con un libro de órdenes en memoria (*Orderbook*) generando posturas de Compra/Venta On-Chain.

### 3. 📚 Guía de Conceptos
Un glosario nativo de tarjetas de aprendizaje (Flashcards) que explican conceptos fundamentales y avanzados del protocolo de forma digerible (SCP, FBA, Finalidad, Trustlines, etc.).

---

## 🛠️ Instalación y Uso

Este proyecto es extremadamente ligero. No requiere dependencias de Node.js, compiladores ni servidores complejos. Todo está autocontenido usando HTML, CSS y Vanilla JavaScript nativo.

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/SistemasTecTlaxiaco/SimuladorArquitecturaStellar.git
    ```
2.  **Abrir el simulador:**
    Simplemente haz doble clic en el archivo `index.html` o ábrelo en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).
    
    *Opcional para desarrollo:* Puedes usar extensiones como *Live Server* en VSCode o iniciar un servidor web local:
    ```bash
    # Usando Python (si estÃ¡ instalado)
    python -m http.server 5500
    ```

---

## 📐 Tecnologías Utilizadas

*   **Estructura:** HTML5 Semántico.
*   **Estilos:** CSS3 nativo (Variables CSS, Grid, Flexbox, UI/UX moderno, Glassmorphism).
*   **Lógica y Gráficos:** JavaScript ES6 (Vanilla JS), `Canvas API` nativa para el renderizado a 60fps de la red.
*   **Fuentes:** Google Fonts (Inter, JetBrains Mono).

---

## 🎓 Enfoque Pedagógico

Este simulador está pensado para ayudar a visualizar lo abstracto. En lugar de explicar la "Finalidad del Ledger" o el enrutamiento de RPC a Validadores sólo con texto, los estudiantes pueden:
1.  *Tocar* la topología.
2.  *Desencadenar* animaciones.
3.  *Experimentar* con las reglas de negocio de la blockchain (reservas fraccionarias por Trustline).

---

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - Siéntete libre de bifurcar, modificar y utilizar este simulador para potenciar el ecosistema educativo.
