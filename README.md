# 🛡️ CyberArch Black — Mapa Visual y Juegos de Ciberataques en Arquitectura de Seguridad (UNIR)

Aplicación web interactiva en un único archivo autónomo ([`index.html`](file:///c:/Users/elcas/Desktop/APP_Antigravity/Juego_Ciberataques_Arquitectura/index.html)), diseñada específicamente para **iPhone 11** en **Estilo Black (OLED `#030407`)** y con **control de tamaño de letra en tiempo real (`A-`, `A`, `A+`, `A++`)** para estudiar de noche sin gafas.

---

## ✨ ¿Qué puede hacer el programa?

### 1. 🗺️ Parte 1: Mapa Visual de Ciberataques por Categorías
- **Esquema Interactivo de Capas**: Muestra de un vistazo las 4 grandes áreas de la arquitectura de seguridad:
  1. 🌐 **Redes** (*ARP Spoofing / MITM, DDoS SYN Flood, DNS Cache Poisoning, Packet Sniffing Pasivo*).
  2. 💻 **Sistemas Operativos** (*Buffer Overflow en Pila, Rootkit de Kernel / Bootkit UEFI, Volcado LSASS & Pass-the-Hash, Side-Channel Spectre/Meltdown*).
  3. 🗄️ **Servicios (Web, Bases de Datos, Cloud, Directorio Activo)** (*Inyección SQL, Cross-Site Scripting XSS, SSRF a Metadatos Cloud, Kerberoasting*).
  4. 🎣 **Correo, Ingeniería Social y Malware** (*Spear Phishing y Whaling, Phishing Masivo Evilginx, Ransomware de Doble Extorsión, Troyano RAT / C2*).
- **Filtro Especial `⭐ Selección Tarea UNIR (2+2+2)`**: Filtra automáticamente los **6 ciberataques clave** exigidos en la pauta de la actividad (2 de Redes, 2 de Sistemas Operativos y 2 de Servicios).
- **Recuadros con Diagramas SVG Integrados**: Cada ataque incluye su propio esquema gráfico vectorial (`SVG`) que ilustra cómo entra el atacante y qué componente compromete, acompañado de una descripción corta, qué propiedad vulnera (*Autenticación, Autorización, Confidencialidad, Integridad o Disponibilidad*) y su defensa principal.

---

### 2. ❓ Parte 2: Juego Test de Preguntas y Respuestas (3 Vidas)
- **Orden 100% Aleatorio y Sin Repetición**: Utiliza el algoritmo *Fisher-Yates* para barajar tanto las 18 preguntas del banco como el orden de las 4 opciones (`A, B, C, D`) en cada partida.
- **Sistema de 3 Vidas (`❤️❤️❤️`) y Puntuación con Racha**:
  - Cada acierto suma puntos más una bonificación por racha consecutiva (`🔥`).
  - Cada fallo resta una vida y muestra la explicación técnica detallada.
  - Si pierdes las 3 vidas (`💀`), la partida termina y debes pulsar **Volver a empezar**, reordenándose todas las preguntas.

---

### 3. 🕵️ Parte 3: Simulador de Casos Reales en Doble Fase (Complicado, 3 Vidas)
- **14 Casos Técnicos con Logs Reales**: Presenta el síntoma en la arquitectura y una línea de telemetría/log real (*switches, netstat, kernel traps, WAF, Active Directory, SMTP, EDR*) sin repetirse.
- **Doble Decisión Encadenada por Caso**:
  - **Fase 1 (Identificar el Ataque)**: Primero debes diagnosticar qué ciberataque exacto está ocurriendo.
  - **Fase 2 (Dar la Solución)**: Una vez identificado el ataque, debes elegir la mitigación arquitectónica exacta.
- **Respuestas Mezcladas con Otros Casos Reales**: Para evitar respuestas evidentes, las opciones incorrectas se extraen dinámicamente de los demás casos reales de la base de datos (con la misma complejidad y longitud técnica).
- **3 Vidas y Puntuación**: Si pierdes las 3 vidas en cualquiera de las dos fases, aparece la pantalla de *Sistema Comprometido* y debes **volver a empezar** desde cero con los casos mezclados.

---

### 4. 🌙 Estilo Black (OLED) y Accesibilidad Nocturna sin Gafas (iPhone 11)
- **Fondo Negro Puro (`#030407`)**: Evita el deslumbramiento en habitaciones oscuras y ahorra batería en pantallas móviles.
- **Botones `A-`, `A`, `A+`, `A++` en la Barra Superior**: Aumentan instantáneamente el tamaño de todas las fuentes, recuadros y botones de la aplicación, guardando tu preferencia en la memoria del navegador (`localStorage`).
- **Navegación Inferior para el Pulgar**: Las 3 secciones están fijas en la parte inferior de la pantalla del iPhone para cambiar cómodamente con una sola mano.
