# Contexto del proyecto — Rolando

Este archivo se lee automáticamente al iniciar Claude Code en esta carpeta. Contiene el contexto de negocio y técnico necesario para construir apps y herramientas consistentes con el resto del proyecto. No hace falta repetirlo en cada sesión.

## Quién soy / negocio

Coach de estrategia y organización certificado P.R.O.F.I.T., basado en Monclova, Coahuila, México. Ayudo a dueños de empresa a institucionalizar su negocio — delegar, construir capacidad de decisión en su equipo, clarificar visión, e implementar sistemas de control (KPIs, dashboards). Mi diferenciador frente a consultores de puro proceso: combino institucionalización organizacional con liderazgo consciente (mente-cuerpo-espíritu).

**Framework:** PROFIT (Profit & Cash, Revenue & Marketing, Operations, Finance & KPIs, Innovation & Leadership, Team), en tres etapas: Visión, Velocidad, Valor.

**Oferta insignia:** El Fundador Libre — cohorte grupal de 6 meses para dueños con 5-50 empleados y facturación aprox. $500K-$5M USD anuales, atrapados en la operación de su propio negocio.

**Avatar del cliente:** dueño de empresa, 40-44 años, gastos personales crecientes, maneja el negocio prácticamente solo, dolor central: "si no estoy yo, todo se cae." Dolores secundarios: fragilidad operativa por personal clave, falta de claridad de rentabilidad, escalar sin estructura, sacrificio de vida personal.

**Meta actual:** crecer a 6-8 clientes activos de forma constante.

## Convenciones técnicas (para que las nuevas apps sean consistentes)

- Stack preferido para mini-apps y prototipos: HTML/CSS/JS puro en un solo archivo, sin frameworks pesados, para poder desplegar fácil en GitHub Pages e instalar como PWA en celular.
- Persistencia de datos: localStorage para prototipos rápidos. Si se necesita sync real (multi-dispositivo, backend), evaluarlo aparte antes de construir — no asumir que hace falta desde el inicio.
- Mobile-first siempre. El usuario final típico revisa esto desde el celular, no desde escritorio.
- Idioma: español de México en toda la interfaz y copys.
- Entregables: guardar en carpeta de salida clara, evitar dependencias externas innecesarias.

## Tono y voz para copys dentro de las apps

- Tuteo siempre. Nunca "usted".
- Directo pero cálido — como "hablando en serio, entre cuates", no como corporativo ni como gurú motivacional.
- Evitar: emojis decorativos, gamificación infantil, frases tipo "sigue tus sueños", intensificadores como "definitivamente" o "absolutamente", el patrón "X no es Y — es Z" con em-dash.
- Si hay mensajes de cierre o de refuerzo, mejor una pregunta directa al usuario que una frase de aliento genérica.
- Preferir lenguaje cualitativo sobre cifras falsamente precisas cuando no hay dato duro detrás.
- Este tono aplica al copy de la interfaz (botones, mensajes, onboarding). Para contenido más largo tipo posts o textos de marketing, se define aparte con más detalle — no asumir que este resumen basta para eso.

## Proyectos ya existentes (contexto, no repetir desde cero)

- **CRM interactivo:** app HTML standalone desplegada en GitHub Pages, instalable como PWA. 5 pantallas: Dashboard, Contactos (Red), Pipeline, Actividad, Agenda. Incluye dictado por voz, recordatorios codificados por urgencia, generador de mensajes con IA. Datos en localStorage; sync real con Google Sheets pendiente.
- **Kit de El Fundador Libre:** diagnóstico PROFIT+LIBRE en Excel bilingüe, Plan de Liberación en Word, brochure de ventas en PDF, Life Assessment en Excel, dashboard de seguimiento de cohorte en Excel, diagnóstico Vida Balance en Word.

## Notas al construir

- Cuando se generen gráficas con openpyxl (Excel), reconstruir los objetos de gráfica desde cero en la misma operación de guardado — parchar archivos cargados suele fallar.
- Antes de proponer una app nueva, considerar si conviene como producto independiente o como imán/embudo hacia El Fundador Libre — ambos son válidos, pero cambia el diseño (qué se da gratis, qué empuja a agendar una llamada).
