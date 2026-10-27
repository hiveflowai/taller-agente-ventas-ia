# Crea tu agente de IA para ventas en 3 preguntas

Taller de **Mexico Tech Week 2026** con Jonathan Olvera, fundador de [Hiveflow](https://hiveflow.ai).
WhatsApp, cotizaciones y CRM, sin saber programar.

> ¿Vas más rápido que el taller? Adelante: aquí está todo, paso a paso. Si te atoras, revisa [Si algo falla](#si-algo-falla).

## Lo que vas a construir

Contestando 3 preguntas, Genius (el asistente de Hiveflow) te arma:

| Pieza | Qué hace |
|---|---|
| 🤖 Agente de WhatsApp | Contesta a tus clientes en segundos, pregunta lo necesario y los califica |
| 📇 CRM | Guarda cada contacto (sin duplicados: la llave es el teléfono) |
| 🗂 Pipeline | Mueve a cada cliente: Nuevo → Calificando → Calificado → Agendado → Cerrado |
| 💬 Conversaciones | El historial de cada chat |
| 🌐 Landing con QR | Una página con el botón «Escríbenos por WhatsApp» y su QR |

## Paso a paso

### 1. Crea tu cuenta y abre Genius

👉 **[Empieza aquí](https://app.hiveflow.ai/signup?redirect=%2Fdashboard%2Fgenius%3Fplaybook%3Dwhatsapp-sales)**

Crea tu cuenta con correo o con Google. Tu cuenta nueva trae **5 USD en créditos** para usar el agente hoy.
Al entrar, Genius arranca solo con «Vende por WhatsApp con un agente IA».

> ¿Ya tienes cuenta? En esa misma página elige «Inicia sesión» y llegas al mismo lugar.

### 2. Contesta las 3 preguntas

1. **¿Cómo se llama tu negocio y qué vendes?** Nombre, giro y 3 a 5 productos o servicios.
   *Ejemplo: «Café La Juárez: cafetería de especialidad; vendemos café en grano, cursos de barismo y catering para oficinas».*
2. **¿Con qué WhatsApp contesta?** Si todavía no conectas tu número, dile a Genius que lo conectas después (ver [paso 4](#4-conecta-tu-whatsapp)).
3. **¿Qué datos necesitas de cada cliente?** Genius te propone 3 o 4 según tu giro; confírmalos o cámbialos.
   *Ejemplo: tipo de cliente (casa u oficina), cantidad, fecha en que lo necesita, colonia.*

En un par de minutos te entrega el agente, el CRM, el pipeline, las conversaciones y la landing.

### 3. Pruébalo como si fueras cliente

Abre la landing, escanea su QR con otro celular y escríbele como cliente. Mira cómo aparecen el contacto en el CRM y la tarjeta en el pipeline.

Prueba también: escríbele «quiero hablar con una persona». El agente marca **REQUIERE HUMANO** y te deja la conversación.

### 4. Conecta tu WhatsApp

En Hiveflow: **Integraciones → WhatsApp Evolution → Conectar**, escanea el QR con el WhatsApp de tu negocio (como WhatsApp Web) y después elige esa conexión en los dos nodos de WhatsApp de tu flujo («WhatsApp Entrada» y «WhatsApp Salida»).

> Usa un número de negocio. Si ese número ya tiene otro bot o agente contestando, desactívalo primero para que no contesten dos.

## ¿Ya terminaste? Haz el cotizador

En Genius escribe: **«Crea un cotizador automático»** (o abre [este link](https://app.hiveflow.ai/dashboard/genius?playbook=quote-generator)).

Te pregunta 3 cosas: qué cotizas, tu lista de precios (si no la tienes, te propone una de ejemplo) y a qué correo mandarte copia.
Te entrega un formulario público: el cliente pide su cotización y recibe el **PDF por correo** en minutos, y tú ves el trato en el CRM y en el tablero «Cotizaciones».

Usa una de las [listas de precios de ejemplo](ejemplos/listas-de-precios.md) si quieres probar rápido.

## ¿Crédito, seguros, KYC, logística o salud?

El mismo patrón sirve para precalificar créditos, armar expedientes KYC, cobrar, renovar, cotizar fletes o agendar citas. Ve [casos por industria](ejemplos/casos-por-industria.md).

## Tarea: cobranza

En Genius escribe **«Automatiza mi cobranza»**: recordatorios amables antes y después del vencimiento, sin que nadie se tenga que acordar.

## Para que el agente no invente

Un agente es tan bueno como lo que le das:

- **Lista de precios**: es lo único de donde saca precios. Si algo no está, dice «precio a confirmar».
- **Reglas**: vigencia, IVA, descuentos, tiempos de entrega, zonas de envío.
- **Qué datos pedir**: los que necesita tu equipo para cerrar.
- **Cuándo pasar a una persona**: si lo pide, se molesta o pregunta algo fuera de la lista.

Más ideas en [ejemplos/prompts.md](ejemplos/prompts.md).

## Si algo falla

| Pasa esto | Haz esto |
|---|---|
| No me llegó el WhatsApp del taller | Revisa la lada del país en el formulario, o entra directo con el link de [Empieza aquí](#1-crea-tu-cuenta-y-abre-genius) |
| Después de registrarme no veo Genius | Abre [app.hiveflow.ai/dashboard/genius?playbook=whatsapp-sales](https://app.hiveflow.ai/dashboard/genius?playbook=whatsapp-sales) |
| Genius no arrancó el playbook | Escríbele: «Vende por WhatsApp con un agente IA» |
| El agente no contesta en WhatsApp | Revisa que el flujo esté activo y que los dos nodos de WhatsApp tengan tu conexión |
| Me quedé sin créditos | Agrega créditos desde tu cuenta en app.hiveflow.ai |
| Otra cosa | Pregúntale a Genius o escríbenos en hiveflow.ai |

## Enlaces

- Hiveflow: [hiveflow.ai](https://hiveflow.ai)
- Agenda 20 minutos con Jonathan: [calendly.com/hiveflow](https://calendly.com/hiveflow/)
- Jonathan en [Instagram](https://instagram.com/johnolven), [TikTok](https://tiktok.com/@JohnOlven) y [LinkedIn](https://linkedin.com/in/johnolven)

---

Hecho con [Hiveflow](https://hiveflow.ai) para Mexico Tech Week 2026.
