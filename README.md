
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
- [📊 Laptop Score 100](https://laptopsrenovadas.com/laptop-score-100/)
- [🍎 Decodificador de MacBook](https://laptopsrenovadas.com/decodificador-de-macbook/)
- [↩️ ¿La Devuelvo o Me la Quedo?](https://laptopsrenovadas.com/devuelvo-o-me-quedo-laptop-renovada/)
- [📄 Asesor de Reclamo con Evidencia](https://laptopsrenovadas.com/reclamo-laptop-renovada-amazon-renewed/)

### Documentación

- [Arquitectura y privacidad](#-arquitectura-tecnológica-y-privacidad)
- [Estructura del ecosistema](#-estructura-del-ecosistema-unificado)
- [Índice TecnoLatino](#-1-índice-oficial-de-herramientas-de-tecnolatino--67-soluciones)
- [Índice Laptops Renovadas](#-2-índice-oficial-de-herramientas-de-laptops-renovadas--39-soluciones)
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

Centraliza **67 herramientas** de software utilitario, telefonía móvil, conectividad, privacidad, ciberseguridad, IA, viajes tecnológicos, resiliencia familiar y protección de identidad digital. La Suite incorpora además protocolos interactivos de respuesta ante incidentes como llamadas sospechosas, compromiso de cuentas, SIM swap y port-out fraud.

Los resultados compatibles pueden integrarse con:

### 🧠 [Mi Tecnología](https://tecnolatino.com/mi-tecnologia/)

Un panel local que organiza herramientas, resultados y rutas de diagnóstico para reutilizar contexto técnico dentro del navegador.

Las herramientas individuales compatibles pueden registrar su actividad y la finalización de sus diagnósticos mediante la integración con Suite. Que una herramienta figure como completada significa que se terminó su evaluación dentro de TecnoLatino; no confirma automáticamente que un servicio externo haya recuperado una cuenta o resuelto un incidente.

---

### 💻 [Suite de Herramientas de Laptops Renovadas](https://laptopsrenovadas.com/herramientas/)

Unifica **39 herramientas** de control de calidad, selección, diagnóstico físico, hardware, tasación, configuración inicial, decisión de devolución y preparación de reclamos con evidencia para laptops usadas o reacondicionadas.

El ecosistema está especialmente orientado a equipos comprados en mercados como Amazon Renewed, eBay, Swappa y vendedores de hardware empresarial reacondicionado.

La suite incorpora una arquitectura de diagnóstico progresivo en la que herramientas automáticas y comprobaciones manuales pueden reutilizar evidencia técnica sin presentar como certeza aquello que el sistema operativo no pudo confirmar.

Los resultados compatibles se organizan dentro de:

### 💻 [Mi Laptop](https://laptopsrenovadas.com/mi-laptop/)

Panel local para registrar pruebas, diagnósticos, rutas de revisión, estado conocido del equipo, actividad reciente y evidencia obtenida por herramientas como Auditoría Express.

---

# 🗂️ Catálogo Forense Completo y Enlaces de Utilidad Pública

---

# 📱 1. Índice Oficial de Herramientas de TecnoLatino — 67 Soluciones

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

* **[¿Puedo Trabajar Solo Desde Mi Teléfono?](https://tecnolatino.com/puedo-trabajar-solo-desde-mi-telefono/)**  
  Evalúa si un flujo de trabajo puede sostenerse únicamente desde el celular según aplicaciones, jornada, batería, señal, datos, documentos, respaldo y necesidad real de computadora.

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

* **[Rescate del Autenticador](https://tecnolatino.com/autenticador-telefono-viejo/)**  
  Guía interactiva para recuperar el acceso cuando los códigos de autenticación quedaron en un teléfono viejo, se cambió de dispositivo o se perdió el acceso al autenticador. Ayuda a identificar sincronización disponible, códigos de respaldo y rutas alternativas de recuperación.

* **[Apple ID, iCloud y Activation Lock](https://tecnolatino.com/apple-id-icloud-activation-lock/)**  
  Guía interactiva para distinguir problemas relacionados con Apple ID o Cuenta de Apple, iCloud, Buscar y Activation Lock. Ayuda a identificar si un iPhone, iPad u otro dispositivo Apple sigue vinculado a otra cuenta y orienta hacia las vías legítimas de recuperación, desvinculación o transferencia sin intentar evadir los controles de seguridad.

* **[Recuperar Cuenta Google/Gmail](https://tecnolatino.com/recuperar-cuenta-google-gmail/)**  
  Guía interactiva para diagnosticar y organizar la recuperación de una Cuenta de Google o Gmail cuando se olvidó la contraseña, se perdió acceso al teléfono o correo de recuperación, falla la verificación en dos pasos, cambió el dispositivo habitual o existe sospecha de acceso no autorizado. Ayuda a distinguir el escenario real y orienta hacia las vías oficiales de recuperación sin solicitar contraseñas, códigos de verificación ni otros secretos de autenticación.

* **[Cuenta Microsoft / Outlook / Hotmail](https://tecnolatino.com/recuperar-cuenta-microsoft-outlook-hotmail/)**  
  Guía interactiva para recuperar acceso a una cuenta Microsoft, Outlook o Hotmail cuando se olvidó la contraseña, se perdió un método de verificación, cambió el dispositivo habitual o existe sospecha de compromiso. Organiza las vías oficiales de recuperación sin solicitar contraseñas, códigos de seguridad ni otros secretos de autenticación.

* **[Recuperar WhatsApp tomado](https://tecnolatino.com/recuperar-whatsapp-hackeado/)**  
  Protocolo guiado para recuperar una cuenta de WhatsApp tomada o comprometida. Ayuda a revisar el registro del número, dispositivos vinculados, verificación en dos pasos y métodos de recuperación, priorizando la recuperación legítima de la cuenta sin solicitar códigos de verificación ni credenciales sensibles.

* **[Separador de Identidades](https://tecnolatino.com/separar-cuentas-personales-trabajo-escuela/)**  
  Ayuda a separar cuentas personales, laborales y escolares para reducir cruces de identidad, accesos y métodos de recuperación. Organiza correos, perfiles, dispositivos y autenticación por contexto sin mezclar credenciales ni asumir que una misma cuenta debe utilizarse para todos los ámbitos.

* **[Meta: Recuperar Facebook e Instagram](https://tecnolatino.com/recuperar-facebook-instagram-hackeado/)**  
  Guía interactiva para recuperar cuentas de Facebook e Instagram comprometidas, tomadas o bloqueadas. Ayuda a identificar el escenario, proteger los métodos de recuperación y seguir las vías oficiales de Meta sin solicitar contraseñas, códigos de verificación ni intentar evadir controles de acceso.

* **[Recuperar Cuenta Amazon](https://tecnolatino.com/recuperar-cuenta-amazon/)**  
  Diagnóstico interactivo para identificar problemas de contraseña, OTP, autenticación en dos pasos, teléfono perdido, passkeys, bloqueos de seguridad, cuentas en revisión, pagos rechazados o actividad no autorizada. Distingue los escenarios y orienta hacia las vías oficiales de Amazon sin solicitar credenciales, códigos ni documentos.

* **[Protocolo SIM swap / port-out fraud](https://tecnolatino.com/sim-swap-port-out-fraud-usa/)**  
  Protocolo interactivo para actuar ante pérdida súbita de señal, cambio no autorizado de SIM/eSIM o transferencia fraudulenta del número en Estados Unidos. Organiza la respuesta entre operador, correo, bancos, mensajería y métodos de autenticación, distingue SIM swap de port-out fraud y no convierte una señal aislada en una confirmación automática de fraude.

* **[¿Te Están Espiando el Celular?](https://tecnolatino.com/me-estan-espiando-el-celular/)**  
  Diagnóstico guiado de privacidad móvil sin necesidad de instalar software adicional.

* **[Privacy Check](https://tecnolatino.com/privacy-check/)**  
  Revisión estructurada de privacidad y seguridad digital.

* **[Límite Laboral](https://tecnolatino.com/limite-laboral/)**  
  Ayuda a separar cuentas, datos y accesos personales de los recursos de trabajo cuando se utiliza o devuelve un equipo corporativo. Organiza la revisión de Microsoft 365, VPN, perfiles de trabajo, MDM y otros vínculos laborales sin asumir que una señal aislada confirma gestión activa.

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

* **[La Llave de la Escuela](https://tecnolatino.com/la-llave-de-la-escuela/)**  
  Ayuda a identificar qué cuenta corresponde usar para acceder a plataformas escolares y a separar el acceso del estudiante del portal de padres. Orienta la recuperación de acceso en entornos como Clever, ClassLink y Google Classroom sin mezclar credenciales ni roles.

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

# 💻 2. Índice Oficial de Herramientas de Laptops Renovadas — 39 Soluciones

Acceso directo a los módulos para selección, compra, diagnóstico y mantenimiento de laptops renovadas o usadas.

---

## 📊 Compra, Evaluación y Score de Decisión

* **[Laptop Score 100](https://laptopsrenovadas.com/laptop-score-100/)**  
  Evalúa una laptop renovada con una puntuación de 0 a 100 basada en precio, batería, reparabilidad, rendimiento, soporte, condición y riesgo. Separa el Score de la confianza del diagnóstico, mantiene explícitos los datos desconocidos y aplica bloqueadores críticos cuando existe evidencia de problemas graves.

El **Laptop Score 100** funciona como una capa de síntesis para comparar unidades concretas sin sustituir las herramientas especializadas de precio, riesgo, vida útil, batería, reparabilidad o revisión física.

---

## ↩️ Decisión, Devolución y Reclamo con Evidencia

* **[¿La Devuelvo o Me la Quedo?](https://laptopsrenovadas.com/devuelvo-o-me-quedo-laptop-renovada/)**  
  Ayuda a decidir si conviene conservar una laptop renovada, continuar observándola, utilizar una garantía o iniciar una devolución según fallos detectados, condición del equipo y plazo declarado.

* **[Asesor de Reclamo con Evidencia](https://laptopsrenovadas.com/reclamo-laptop-renovada-amazon-renewed/)**  
  Convierte resultados ya obtenidos en Mi Laptop en un paquete organizado para devolución o reclamo. Reutiliza evidencia como Battery Health, pantalla, teclado, bloqueos o gestión anterior y la decisión de devolución sin volver a ejecutar esas pruebas. Organiza qué presentar, qué fotografías conservar, qué información sensible no publicar, un texto base editable y el siguiente paso según el canal de compra, incluido Amazon Renewed y Marketplace.

El **Asesor de Reclamo con Evidencia** no sustituye las pruebas técnicas ni decide automáticamente que una tienda, vendedor o marketplace esté obligado a aprobar una devolución. Su función es ordenar la evidencia existente y ayudar a presentar un caso claro después de que el diagnóstico y la decisión técnica ya se hayan realizado.

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
```

Esta separación permite diferenciar el volumen lógico presentado por macOS del almacenamiento físico subyacente. Cuando un dato de salud, temperatura, S.M.A.R.T. o desgaste NVMe no está disponible, la herramienta debe conservar ese estado como desconocido, sin sustituirlo por un valor favorable.

---

# 🧠 Suites de Contexto Local

## 📱 Mi Tecnología

**URL:**  
https://tecnolatino.com/mi-tecnologia/

Organiza localmente información y resultados producidos por las herramientas de TecnoLatino.

Funciones del ecosistema:

* registro de herramientas ejecutadas;
* resultados recientes;
* rutas guiadas;
* contexto reutilizable;
* seguimiento de diagnóstico;
* exportación e importación compatible;
* almacenamiento local del navegador.

Las herramientas individuales pueden integrarse con la Suite mediante identificadores estables y señales de resultado. La finalización de un diagnóstico no implica, por sí sola, que se haya solucionado el problema externo investigado.

---

## 💻 Mi Laptop

**URL:**  
https://laptopsrenovadas.com/mi-laptop/

Centraliza el proceso de revisión y seguimiento de una laptop renovada o usada.

Incluye:

* perfil local del equipo;
* estado conocido del hardware;
* rutas de inspección;
* pruebas realizadas;
* diagnósticos guardados;
* actividad reciente;
* decisiones de compra;
* información de mejoras;
* exportación e importación de datos locales.

---

# 🧭 Filosofía de las Rutas Guiadas

Las suites no se limitan a presentar una lista estática de utilidades.

Determinadas herramientas pueden agruparse en **rutas**, donde cada prueba conduce al siguiente paso lógico del diagnóstico.

Las rutas se mantienen separadas de las herramientas independientes. Incorporar una herramienta al Hub o al catálogo de Mi Tecnología no la convierte automáticamente en un paso de una ruta.

### 📱 Compra de Celular Usado

Una ruta puede combinar:

1. IMEI.
2. Bloqueos y gestión anterior.
3. Piezas y reparaciones.
4. Salud de batería.
5. eSIM y liberación.
6. Compatibilidad de red.
7. Consumo de datos.
8. Selección de plan.
9. Portabilidad.

---

### 💻 Revisión de Laptop Renovada

La ruta de revisión puede combinar:

1. Auditoría Express.
2. Checklist general.
3. Service Tag, serial y garantía.
4. Batería.
5. Pantalla.
6. Teclado.
7. Distribución de teclado US vs Latinoamérica.
8. Webcam.
9. Micrófono.
10. Altavoces.
11. Temperatura.
12. Test de estrés CPU y estabilidad.
13. SSD / S.M.A.R.T.
14. Bloqueos y gestión anterior.
15. Decisión final: devolverla o quedársela.

---

# 🔬 Principios de Diseño del Laboratorio

El proyecto sigue varios principios técnicos:

### 1. Local-first

Siempre que sea técnicamente posible, el procesamiento ocurre en el navegador.

### 2. Privacidad por diseño

No se solicitan credenciales, contraseñas ni información sensible innecesaria para realizar un diagnóstico.

### 3. Explicabilidad

Las herramientas buscan explicar **por qué** se produce una recomendación y no limitarse a mostrar una puntuación.

### 4. Resultados reutilizables

Los resultados compatibles pueden formar parte del contexto de **Mi Tecnología** o **Mi Laptop**.

### 5. Diagnóstico progresivo

Una herramienta puede conducir a otra cuando el resultado indica que se necesita una comprobación adicional.

### 6. Interoperabilidad

Las herramientas utilizan identificadores estables y contratos de eventos dentro de sus respectivos ecosistemas.

### 7. Portabilidad

Cuando la Suite lo permite, el usuario puede exportar su información local para conservarla fuera del navegador.

### 8. Estados desconocidos explícitos

Los datos ausentes o no verificables permanecen desconocidos. `Unknown` no equivale a `false`, `Missing` no equivale a `0` y la ausencia de evidencia no equivale a una aprobación.

### 9. Herramientas y rutas independientes

Las nuevas herramientas pueden añadirse al catálogo sin modificar los pasos de rutas existentes. Los cambios de rutas requieren una decisión técnica específica, no se infieren automáticamente del registro de una herramienta.

### 10. Finalización verificable

Una herramienta individual debe registrar su finalización solamente cuando genera el resultado que le corresponde. Abrir una página, iniciar un cuestionario o hacer clic en un botón no constituye por sí solo una evaluación completada.

---

# 🔐 Nota de Seguridad

Las herramientas de este repositorio tienen fines de:

* diagnóstico;
* educación;
* análisis preventivo;
* auditoría de equipos propios o autorizados;
* privacidad;
* mantenimiento;
* evaluación de compras;
* resiliencia digital.

No están diseñadas para:

* eludir Activation Lock;
* eliminar FRP sin autorización;
* evadir MDM corporativo;
* vulnerar cuentas;
* obtener credenciales;
* romper controles de acceso;
* acceder a dispositivos ajenos.

Las herramientas relacionadas con bloqueos y gestión están diseñadas para **detectar e interpretar señales de vinculación**, no para evadirlas.

Los procedimientos de recuperación de cuentas de Apple, Google, Microsoft, WhatsApp, Meta y Amazon se orientan a procesos legítimos y canales oficiales. Una recomendación de recuperación no equivale a una verificación de identidad realizada por TecnoLatino.

---

# 🌎 Ecosistema

## TecnoLatino

* Sitio principal: https://tecnolatino.com/
* Herramientas: https://tecnolatino.com/herramientas/
* Mi Tecnología: https://tecnolatino.com/mi-tecnologia/

## Laptops Renovadas

* Sitio principal: https://laptopsrenovadas.com/
* Herramientas: https://laptopsrenovadas.com/herramientas/
* Mi Laptop: https://laptopsrenovadas.com/mi-laptop/

---

# 📊 Inventario Actual

| Ecosistema | Herramientas |
|---|---:|
| 📱 TecnoLatino | **67** |
| 💻 Laptops Renovadas | **39** |
| **Total combinado** | **106** |

Las suites **Mi Tecnología** y **Mi Laptop** son interfaces de contexto y seguimiento; no se cuentan como herramientas adicionales dentro del inventario.

Las rutas guiadas tampoco incrementan el número de herramientas públicas. Sus pasos pueden utilizar herramientas existentes, sin duplicarlas en el catálogo.

---

# 📜 Licencia

Consulta el archivo `LICENSE` del repositorio para conocer las condiciones de reutilización, distribución y modificación del código.

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas cuando respeten los principios fundamentales del proyecto:

* privacidad por diseño;
* procesamiento local cuando sea posible;
* explicabilidad;
* accesibilidad;
* seguridad;
* minimización de datos;
* ausencia de técnicas de evasión de controles de acceso.

Antes de enviar cambios, revisa la estructura del proyecto y evita introducir dependencias que obliguen a transmitir información sensible a servicios externos sin una justificación técnica clara.

---

## 🧰 Total del Laboratorio

**106 herramientas públicas**

* **67 herramientas en TecnoLatino**
* **39 herramientas en Laptops Renovadas**
* **2 suites de contexto local**
  * Mi Tecnología
  * Mi Laptop
* rutas de diagnóstico y decisión independientes del inventario de herramientas;
* procesamiento local y almacenamiento privado siempre que la función lo permite.

El objetivo del ecosistema es transformar una colección de utilidades independientes en un laboratorio técnico coherente para diagnóstico, prevención, compra informada y resiliencia digital.
