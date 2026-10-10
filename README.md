# 🧰 Suite de Auditoría Forense de Hardware, Ciberseguridad Local y Resiliencia Digital

[![Licencia](https://shields.io)](https://opensource.org)
[![Privacidad](https://shields.io)](#-arquitectura-tecnológica-y-privacidad)
[![Ecosistema](https://shields.io)](#-estructura-del-ecosistema-unificado)

Un repositorio público e indexable que centraliza herramientas interactivas, recolectores locales, scripts de diagnóstico y utilidades web avanzadas para la auditoría técnica de dispositivos móviles, laptops reacondicionadas, ciberseguridad ciudadana, conectividad y resiliencia digital.

La mayor parte del procesamiento técnico se realiza directamente en el navegador o en el propio dispositivo mediante recolectores locales. Cuando una herramienta necesita consultar información externa —por ejemplo red, DNS, compatibilidad o servicios públicos— se limita a los datos necesarios para ejecutar esa función.

---

## 📌 Menú del Ecosistema

### Suites principales

- [📱 Suite de Herramientas de TecnoLatino](https://tecnolatino.com/herramientas/)
- [🧠 Mi Tecnología](https://tecnolatino.com/mi-tecnologia/)
- [💻 Suite de Herramientas de Laptops Renovadas](https://laptopsrenovadas.com/herramientas/)
- [💻 Mi Laptop](https://laptopsrenovadas.com/mi-laptop/)

### Laptops Renovadas — herramientas destacadas

- [⚡ Auditoría Express de Laptop](https://laptopsrenovadas.com/auditoria-express-laptop/)
- [🔐 Verificador de Bloqueos y Gestión Anterior](https://laptopsrenovadas.com/verificar-bloqueos-gestion-laptop/)
- [🚀 Primer Arranque de tu Laptop Renovada](https://laptopsrenovadas.com/primer-arranque-laptop-renovada-latino/)
- [✅ Checklist de Laptop Usada](https://laptopsrenovadas.com/checklist-de-laptop-usada/)
- [💾 Analizador de Salud SSD y S.M.A.R.T.](https://laptopsrenovadas.com/analizador-salud-ssd-smart/)
- [🔋 Battery Health](https://laptopsrenovadas.com/battery-health/)
- [🍎 Decodificador de MacBook](https://laptopsrenovadas.com/decodificador-de-macbook/)
- [↩️ ¿La Devuelvo o Me la Quedo?](https://laptopsrenovadas.com/devuelvo-o-me-quedo-laptop-renovada/)

### Documentación

- [Arquitectura y privacidad](#-arquitectura-tecnológica-y-privacidad)
- [Estructura del ecosistema](#-estructura-del-ecosistema-unificado)
- [Índice TecnoLatino](#-1-índice-oficial-de-herramientas-de-tecnolatino--55-soluciones)
- [Índice Laptops Renovadas](#-2-índice-oficial-de-herramientas-de-laptops-renovadas--37-soluciones)
- [Mejoras recientes de Auditoría Express](#-auditoría-express-multiplataforma--windows--macos)
- [Suites de contexto local](#-suites-de-contexto-local)
- [Rutas guiadas](#-filosofía-de-las-rutas-guiadas)
- [Principios de diseño](#-principios-de-diseño-del-laboratorio)
- [Nota de seguridad](#-nota-de-seguridad)
- [Inventario actual](#-inventario-actual)

---

## 🔒 Arquitectura Tecnológica y Privacidad

A diferencia de plataformas tradicionales que requieren cuentas permanentes o perfiles centralizados, este ecosistema prioriza una arquitectura **local-first**, la minimización de datos y la soberanía digital:

* **Sin cuenta obligatoria:** Las suites principales pueden utilizarse sin crear una cuenta de usuario.
* **Persistencia local:** El historial técnico y el contexto de las suites se almacenan principalmente en el navegador mediante tecnologías como `IndexedDB`.
* **Portabilidad:** Los módulos compatibles permiten exportar, importar o borrar los datos técnicos locales.
* **Procesamiento local:** Diagnósticos, cálculos y análisis compatibles se ejecutan directamente en el dispositivo del usuario.
* **Recolectores locales:** Cuando una auditoría requiere información del sistema operativo, puede utilizar scripts de solo lectura que generan evidencia estructurada localmente.
* **Minimización de datos:** Las herramientas están diseñadas para solicitar solamente la información necesaria para producir el diagnóstico.
* **Resultados reutilizables:** Las suites **Mi Tecnología** y **Mi Laptop** permiten que distintas herramientas compartan contexto técnico local sin obligar al usuario a repetir información innecesariamente.
* **Evidencia cruzada:** Cuando una herramienta ya obtuvo una señal técnica útil, otras herramientas compatibles pueden reutilizarla como contexto sin convertirla automáticamente en una comprobación manual completada.
* **Estados desconocidos explícitos:** La ausencia de evidencia no se interpreta automáticamente como un resultado favorable. Un dato desconocido permanece desconocido hasta que pueda comprobarse.
* **Sin transmisión implícita:** Los recolectores locales de Auditoría Express están diseñados para funcionar sin enviar por iniciativa propia los resultados a servicios remotos.
* **Privacidad por diseño:** No se pretende recopilar credenciales, contraseñas, cuentas completas, perfiles MDM completos ni identificadores organizacionales innecesarios.

---

## 🧭 Estructura del Ecosistema Unificado

El laboratorio se divide en dos grandes suites de diagnóstico y decisión que funcionan de manera complementaria.

### 📱 [Suite de Herramientas de TecnoLatino](https://tecnolatino.com/herramientas/)

Centraliza **55 herramientas** de software utilitario, telefonía móvil, conectividad, privacidad, ciberseguridad, IA, viajes tecnológicos, resiliencia familiar y protección de identidad digital.

Los resultados compatibles pueden integrarse con:

### 🧠 [Mi Tecnología](https://tecnolatino.com/mi-tecnologia/)

Un panel local que organiza herramientas, resultados y rutas de diagnóstico para reutilizar contexto técnico dentro del navegador.

---

### 💻 [Suite de Herramientas de Laptops Renovadas](https://laptopsrenovadas.com/herramientas/)

Unifica **37 herramientas** de control de calidad, selección, diagnóstico físico, hardware, tasación, configuración inicial y auditoría de laptops usadas o reacondicionadas.

El ecosistema está especialmente orientado a equipos comprados en mercados como Amazon Renewed, eBay, Swappa y vendedores de hardware empresarial reacondicionado.

La suite incorpora una arquitectura de diagnóstico progresivo en la que herramientas automáticas y comprobaciones manuales pueden reutilizar evidencia técnica sin presentar como certeza aquello que el sistema operativo no pudo confirmar.

Los resultados compatibles se organizan dentro de:

### 💻 [Mi Laptop](https://laptopsrenovadas.com/mi-laptop/)

Panel local para registrar pruebas, diagnósticos, rutas de revisión, estado conocido del equipo, actividad reciente y evidencia obtenida por herramientas como Auditoría Express.

---

# 🗂️ Catálogo Forense Completo y Enlaces de Utilidad Pública

---

# 📱 1. Índice Oficial de Herramientas de TecnoLatino — 55 Soluciones

Acceso directo a los módulos del laboratorio web de TecnoLatino.

---

## 🖥️ Hardware y Rendimiento de PC

* **[TechCheck](https://tecnolatino.com/techcheck/)**  
  Diagnóstico general de problemas en PC, laptop, Android y iPhone.

* **[Verificador Windows 11](https://tecnolatino.com/verificador-windows-11/)**  
  Comprueba si el hardware de una computadora cumple los requisitos relevantes de Windows 11.

* **[Decodificador de Procesadores](https://tecnolatino.com/decodificador-de-procesadores/)**  
  Interpreta nomenclaturas y generaciones de procesadores Intel y AMD.

* **[RAM Calculator](https://tecnolatino.com/ram-calculator/)**  
  Calcula cuánta memoria RAM puede necesitar un usuario según aplicaciones y perfil de uso.

* **[Storage Calculator](https://tecnolatino.com/storage-calculator/)**  
  Estima cuánto almacenamiento conviene según documentos, fotografías, aplicaciones, juegos y otros usos.

* **[¿Cuántas Fotos Caben?](https://tecnolatino.com/cuantas-fotos-caben/)**  
  Convierte una capacidad de almacenamiento en una estimación de fotografías, videos y otros archivos.

* **[Consumo Eléctrico de tu PC](https://tecnolatino.com/consumo-electrico-de-tu-pc/)**  
  Estima el consumo eléctrico y costo diario, mensual y anual de una computadora.

* **[¿Reparar o Comprar?](https://tecnolatino.com/reparar-o-comprar/)**  
  Ayuda a decidir si conviene reparar un dispositivo o sustituirlo según costo, antigüedad y contexto.

---

## 📱 Telefonía, IMEI, Celulares Usados y Conectividad Móvil

* **[Verificador de IMEI](https://tecnolatino.com/verificador-de-imei/)**  
  Analiza la estructura e información disponible de la identidad IMEI de un celular.

* **[¿Cuántos Años le Quedan a tu Celular?](https://tecnolatino.com/cuantos-anos-le-quedan-a-tu-celular/)**  
  Estima el horizonte de soporte y actualizaciones de seguridad de smartphones.

* **[Calculadora de Datos Móviles](https://tecnolatino.com/calculadora-de-datos-moviles/)**  
  Estima cuántos GB mensuales puede necesitar una línea móvil.

* **[¿Contrato vs Prepago?](https://tecnolatino.com/costo-real-contrato-celular-vs-prepago/)**  
  Compara costos y condiciones de planes de contrato frente a opciones prepago.

* **[¿Tu Celular Tiene eSIM y Está Liberado?](https://tecnolatino.com/mi-telefono-tiene-esim-y-esta-liberado/)**  
  Ayuda a comprobar compatibilidad con eSIM y requisitos relacionados con el desbloqueo del dispositivo.

* **[¿Mi Celular Funciona en Estados Unidos?](https://tecnolatino.com/mi-celular-funciona-en-estados-unidos/)**  
  Evalúa compatibilidad de un celular con redes y operadores de Estados Unidos.

* **[Portabilidad Numérica en Estados Unidos](https://tecnolatino.com/portabilidad-numerica-estados-unidos/)**  
  Guía interactiva para evaluar los requisitos antes de transferir un número entre operadores.

* **[¿Qué Plan Celular Me Conviene en Estados Unidos?](https://tecnolatino.com/mejor-plan-celular-estados-unidos/)**  
  Asesor para comparar necesidades de datos, líneas, cobertura, presupuesto y uso internacional.

* **[¿Este Celular Sigue Vinculado a Otro Dueño o Empresa?](https://tecnolatino.com/verificar-bloqueos-gestion-celular/)**  
  Auditoría guiada de Activation Lock, FRP, MDM y otras señales de gestión o propiedad anterior.

* **[Auditor de Piezas y Reparaciones del Celular](https://tecnolatino.com/auditor-piezas-reparaciones-celular/)**  
  Ayuda a revisar componentes reemplazados, reparaciones anteriores y funciones críticas antes de comprar un celular usado.

* **[Analizador Avanzado de Salud de Batería del Celular](https://tecnolatino.com/analizador-salud-bateria-celular/)**  
  Interpreta capacidad, ciclos, desgaste y otros indicadores disponibles de la batería de un smartphone.

---

## 🌐 Redes, WiFi y Conectividad Doméstica

* **[Internet Calculator](https://tecnolatino.com/internet-calculator/)**  
  Calcula qué velocidad de Internet puede necesitar un hogar según personas, dispositivos, actividades simultáneas y necesidades de descarga/subida, incluyendo gaming, streaming y videollamadas.

* **[Test de Velocidad de Internet](https://tecnolatino.com/test-de-velocidad/)**  
  Mide parámetros relevantes del rendimiento de una conexión a Internet.

* **[¿Cuál es Mi IP?](https://tecnolatino.com/cual-es-mi-ip/)**  
  Muestra la dirección IP pública y explica información relacionada con la conexión.

* **[Tiempo de Descarga](https://tecnolatino.com/tiempo-de-descarga/)**  
  Calcula cuánto puede tardar en descargarse un archivo según tamaño y velocidad disponible.

* **[Diagnóstico DNS de un Dominio](https://tecnolatino.com/diagnostico-dns/)**  
  Ayuda a revisar configuración DNS y registros relevantes de un dominio.

* **[Optimizador de WiFi para tu Casa](https://tecnolatino.com/optimizador-de-wifi-para-tu-casa/)**  
  Diagnóstico guiado para identificar obstáculos, ubicación deficiente del router y problemas de cobertura doméstica.

* **[¿Funciona con tu Smart Home? Verificador de Compatibilidad](https://tecnolatino.com/compatibilidad-smart-home/)**  
  Cruza ecosistema, protocolo e infraestructura para comprobar compatibilidad con Matter, Thread, Alexa, Google Home, Apple Home, SmartThings, Zigbee y Z-Wave.

---

## 🛡️ Ciberseguridad, Privacidad y Contención de Fraudes

* **[ScamCheck](https://tecnolatino.com/scamcheck/)**  
  Analiza mensajes sospechosos, SMS y señales frecuentes de estafa.

* **[Protocolo de Llamada Sospechosa](https://tecnolatino.com/protocolo-llamada-sospechosa/)**  
  Protocolo interactivo para responder a llamadas que dicen provenir de bancos, gobierno, inmigración, familiares, soporte técnico u otras fuentes sensibles. Ayuda a decidir cuándo colgar, verificar por un canal independiente, proteger cuentas y documentar lo ocurrido sin compartir datos innecesarios.

* **[Mapa de Identidad de mi Número](https://tecnolatino.com/mapa-identidad-mi-numero/)**  
  Evalúa cuántas áreas de la vida digital dependen de un mismo número telefónico y calcula por separado la dependencia del número y la resiliencia de recuperación. Organiza banca y 2FA, mensajería, trabajo, escuela y métodos alternativos de recuperación sin solicitar el número real.

* **[¿Te Están Espiando el Celular?](https://tecnolatino.com/me-estan-espiando-el-celular/)**  
  Diagnóstico guiado de privacidad móvil sin necesidad de instalar software adicional.

* **[Privacy Check](https://tecnolatino.com/privacy-check/)**  
  Revisión estructurada de privacidad y seguridad digital.

* **[Verificador de Contraseñas Filtradas](https://tecnolatino.com/contrasenas-filtrada/)**  
  Ayuda a comprobar exposición de credenciales mediante técnicas diseñadas para minimizar la divulgación de la contraseña.

* **[Generador de Contraseñas](https://tecnolatino.com/generador-de-contrasenas/)**  
  Genera contraseñas aleatorias y configurables.

* **[Verificar Sitio Web](https://tecnolatino.com/verificar-sitio-web/)**  
  Ayuda a evaluar señales de confianza y riesgo antes de interactuar con un sitio web.

* **[LinkCheck — Analizador de Enlaces](https://tecnolatino.com/linkcheck-analizador-de-enlaces/)**  
  Examina URLs y características relevantes antes de abrir enlaces potencialmente sospechosos.

* **[Analizador de Cabeceras de Correo](https://tecnolatino.com/analizar-cabeceras-correo/)**  
  Interpreta encabezados técnicos de correo electrónico para investigar rutas, autenticación y posibles señales de suplantación.

* **[Verificador de Archivos por Hash](https://tecnolatino.com/verificar-hash-archivo/)**  
  Calcula y compara firmas criptográficas para comprobar integridad de archivos.

* **[Metadatos de Fotos — EXIF](https://tecnolatino.com/metadatos-de-fotos/)**  
  Examina localmente metadatos disponibles dentro de fotografías.

* **[¿Me Están Espiando el WiFi de Casa?](https://tecnolatino.com/me-estan-espiando-el-wifi/)**  
  Diagnóstico guiado de seguridad inalámbrica y señales de acceso no autorizado.

---

## 🤖 Productividad, IA, Finanzas, Viajes y Resiliencia Familiar

* **[Constructor de Prompts](https://tecnolatino.com/constructor-de-prompts/)**  
  Ayuda a estructurar instrucciones más claras y útiles para sistemas de inteligencia artificial.

* **[Desintoxicador de Textos de IA](https://tecnolatino.com/desintoxicador-de-textos-de-ia/)**  
  Ayuda a revisar textos sintéticos y reducir patrones de redacción excesivamente robóticos.

* **[Traductor de Códigos de Error](https://tecnolatino.com/traductor-codigos-de-error/)**  
  Interpreta códigos de error y los convierte en explicaciones y próximos pasos comprensibles.

* **[Explícame esta Factura](https://tecnolatino.com/explicame-esta-factura/)**  
  Ayuda a interpretar cargos y conceptos de facturas de celular o Internet.

* **[Generador de Código QR Gratis](https://tecnolatino.com/generador-codigo-qr/)**  
  Genera códigos QR para enlaces, WiFi, WhatsApp y otros usos.

* **[¿Le Sirve Allá?](https://tecnolatino.com/le-sirve-alla-compatibilidad-aparatos/)**  
  Evalúa compatibilidad eléctrica y tecnológica de dispositivos cuando se utilizarán en otro país.

* **[Armador de Vuelos USA ↔ Latinoamérica](https://tecnolatino.com/armador-de-vuelos/)**  
  Herramienta para organizar y comparar alternativas de rutas aéreas entre Estados Unidos y Latinoamérica.

* **[eSIM vs Roaming vs Chip Local](https://tecnolatino.com/esim-vs-roaming-chip-local/)**  
  Compara alternativas de conectividad móvil para viajes internacionales.

* **[¿Puedo Llevar Esto en el Avión?](https://tecnolatino.com/puedo-llevar-esto-en-el-avion/)**  
  Guía interactiva sobre dispositivos electrónicos, baterías y equipaje tecnológico.

* **[Plan de Emergencia Digital Familiar](https://tecnolatino.com/plan-de-emergencia-digital-familiar/)**  
  Ayuda a organizar acceso de emergencia, recuperación de cuentas y continuidad digital familiar.

* **[Checklist para Preparar tu Celular Antes de Venderlo](https://tecnolatino.com/checklist-preparar-celular-antes-de-vender/)**  
  Organiza los pasos que conviene completar antes de vender, regalar, enviar o reciclar un smartphone.

* **[Cómo Recuperar una Cuenta Hackeada](https://tecnolatino.com/recuperar-cuenta-hackeada/)**  
  Flujo de recuperación y contención para cuentas comprometidas, bloqueadas o sin acceso.

* **[Cómo Proteger tus Datos con la Regla 3-2-1-1-0](https://tecnolatino.com/regla-3-2-1-1-0-copias-seguridad/)**  
  Guía para construir una estrategia de copias de seguridad resistente a pérdida, fallos y ransomware.

* **[Test de Mouse](https://tecnolatino.com/test-de-mouse/)**  
  Comprueba botones, clics y rueda de desplazamiento del mouse.

* **[Test de Mecanografía](https://tecnolatino.com/test-de-mecanografia/)**  
  Mide velocidad de escritura y palabras por minuto.

* **[Mi Celular en Casa](https://tecnolatino.com/mi-celular-en-casa/)**  
  Diagnóstico de dependencia digital del hogar, conectividad, privacidad, seguridad, fraude y continuidad cuando el teléfono es una pieza crítica de la vida familiar.

---

# 💻 2. Índice Oficial de Herramientas de Laptops Renovadas — 37 Soluciones

Acceso directo a los módulos para selección, compra, diagnóstico y mantenimiento de laptops renovadas o usadas.

---

## 🆕 Auditoría Express Multiplataforma — Windows + macOS

La evolución de **Auditoría Express** incorpora soporte nativo para Windows y macOS dentro de una misma herramienta y sin aumentar artificialmente el inventario público de la Suite.

### 🪟 Windows

Utiliza un recolector local de PowerShell de solo lectura para obtener evidencia estructurada sobre:

* procesador;
* memoria;
* batería;
* almacenamiento;
* S.M.A.R.T.;
* seguridad;
* señales de gestión;
* información técnica compatible con el diagnóstico posterior.

### 🍎 macOS

Utiliza un recolector local nativo para macOS basado en herramientas incluidas por Apple, como:

* `system_profiler`;
* `sysctl`;
* `ioreg`;
* `diskutil`;
* `profiles`;
* `fdesetup`;
* utilidades de seguridad disponibles en el sistema.

El recolector macOS puede obtener, cuando el propio sistema expone la información:

* modelo técnico del Mac;
* nombre amigable del equipo;
* Apple Silicon o arquitectura Intel;
* chip/procesador;
* memoria unificada o memoria disponible;
* versión y build de macOS;
* ciclos de batería;
* capacidad máxima;
* condición de batería;
* SSD físico subyacente al contenedor APFS;
* capacidad física y capacidad utilizable;
* S.M.A.R.T.;
* desgaste NVMe cuando está disponible;
* temperatura del almacenamiento;
* FileVault;
* SIP;
* estado local de inscripción MDM;
* información local relacionada con ADE, anteriormente conocido como DEP;
* estado de Activation Lock únicamente cuando macOS expone evidencia concluyente.

### 🔎 Principio de evidencia conservadora

Auditoría Express no transforma automáticamente una ausencia de datos en una conclusión favorable.

Por ejemplo:

* `Activation Lock desconocido` no significa desactivado.
* `MDM no inscrito actualmente` no significa que el equipo nunca haya estado administrado.
* una consulta local que no indique ADE no descarta por sí sola una asignación organizacional externa;
* un dato no disponible no se convierte en `0`, `false` o “sin riesgo”.

### 💾 SSD físico y NVMe

En macOS, la herramienta intenta resolver la relación:

```text
APFS Container
      ↓
Physical Store
      ↓
Whole Disk
      ↓
SSD físico
