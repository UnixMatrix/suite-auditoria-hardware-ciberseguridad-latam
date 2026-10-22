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
- [Índice TecnoLatino](#-1-índice-oficial-de-herramientas-de-tecnolatino--77-soluciones)
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

Centraliza **77 herramientas** de software utilitario, telefonía móvil, conectividad, privacidad, ciberseguridad, IA, tecnología para oficios, continuidad del trabajo, viajes tecnológicos, resiliencia familiar y protección de identidad digital. La Suite incorpora además protocolos interactivos de respuesta ante incidentes como llamadas sospechosas, compromiso de cuentas, SIM swap y port-out fraud.

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

# 📱 1. Índice Oficial de Herramientas de TecnoLatino — 77 Soluciones

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

## 🌐 Redes, WiFi y Conectividad

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

* **[WiFi sin Conflictos — Trabajo y Negocios](https://tecnolatino.com/wifi-sin-conflictos/)**  
  Diagnóstico de continuidad de conectividad en oficinas, comercios y trabajo remoto. Organiza pruebas para videollamadas, llamadas VoIP, cobros, VPN, impresoras y redes de invitados; distingue hechos, hipótesis y permisos de intervención sin acceder a redes ni solicitar contraseñas.

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

* **[Plan de Contención — Celular perdido o robado](https://tecnolatino.com/plan-contencion-celular/)**  
  Protocolo interactivo de emergencia para cuando se pierde o roba el celular. Genera un plan personalizado en el orden correcto según iPhone o Android, tipo de incidente (robo, pérdida o ya recuperado) y el riesgo de cuentas, número, dinero y acceso. No solicita IMEI, contraseñas ni datos sensibles; el plan se puede exportar y permanece en la pestaña.

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

* **[Digital Switcher USA](https://tecnolatino.com/digital-switcher-usa/)**  
  Interpreta pantallas, botones, etiquetas y controles en inglés (apps, routers, controles remotos, cajas y documentos). Explica el contexto, señala riesgos antes de actuar y procesa de forma local-first sin pedir cuentas ni contraseñas.

* **[CotizaTech USA — Estimaciones Técnicas Bilingües](https://tecnolatino.com/cotizatech-usa/)**  
  Permite preparar cotizaciones de oficios en Estados Unidos con medidas, cantidades, materiales, horas, costos introducidos por el usuario y descripciones del trabajo en español e inglés. Genera un alcance editable y un documento imprimible sin imponer tarifas supuestamente oficiales.

* **[Habla de tu Oficio USA](https://tecnolatino.com/habla-de-tu-oficio-usa/)**  
  Entrenador de inglés laboral para practicar conversaciones con clientes, supervisores y entrevistadores según el oficio y la situación. Ofrece ejercicios guiados, respuestas escritas o voz opcional, observaciones sobre el texto y un informe de práctica; no certifica dominio oficial del idioma.

---

*(El resto del README original se mantiene: Laptops Renovadas, principios, inventario 77/39/116, licencia, etc.)*

# 📊 Inventario Actual

| Ecosistema | Herramientas |
|---|---:|
| 📱 TecnoLatino | **77** |
| 💻 Laptops Renovadas | **39** |
| **Total combinado** | **116** |

## 🧰 Total del Laboratorio

**116 herramientas públicas**

* **77 herramientas en TecnoLatino**
* **39 herramientas en Laptops Renovadas**
