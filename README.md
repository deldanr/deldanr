# Hola, soy Daniel Eldan 👋

Construyo productos de software con IA que salen a producción: reservas para pymes, detección de incendios forestales con visión artificial, plataformas para municipios y tutores conversacionales con voz y video. Fundador de [Emersys](https://emersys.cl), en Chile 🇨🇱.

[![Sitio](https://img.shields.io/badge/me.emersys.cl-03102C?style=for-the-badge&logo=googlechrome&logoColor=white)](https://me.emersys.cl)
[![Email](https://img.shields.io/badge/deldanr@gmail.com-A90429?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deldanr@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-deldanr-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/deldanr)

## 🚀 Productos

| | Producto | Qué resuelve | Estado |
|---|---|---|---|
| 📅 | [**Reserly**](https://reserly.cl) | Agenda online para negocios de servicios: reservas, clientes y servicios en un solo panel. | 🟢 Producción |
| 🔥 | [**FireLink · GuaitaIA**](https://firelink.cl) | Detecta columnas de humo en las imágenes de cámaras forestales y avisa al equipo por correo, Telegram o push. Un agente liviano (Docker o Raspberry Pi) conecta cámaras RTSP/ONVIF sin abrir puertos. | 🟡 Beta |
| 🇭🇷 | [**JezikApp**](https://jezikapp.com) | Croata para la diáspora con IA conversacional: chat, corrección de pronunciación por voz y videollamada con un tutor virtual, organizado por situaciones reales (ciudadanía, trámites, entrevistas). | 🟡 Piloto cerrado |
| 🧱 | [**ParrillApp 3D**](https://parrillapp3d.com) | Modelador 3D en el navegador para diseñar quinchos y parrillas con bloques de hormigón y calcular materiales y mortero. | 🟢 Producción |
| 🗳️ | **Gestión Ciudadana** | SaaS multi-municipio de participación ciudadana: reportes urbanos georreferenciados, consultas y votaciones con verificación de identidad, y juntas de vecinos (asistencia con QR, tesorería, botón de pánico). | 🟡 En desarrollo |
| 🎭 | **live-agent** | Motor propio de avatar conversacional en tiempo real (video y voz sincronizados por WebRTC), pensado para reemplazar el servicio externo de avatar de JezikApp. | 🔵 I+D |

Más proyectos y contexto en [me.emersys.cl](https://me.emersys.cl).

## 📈 Algunos resultados

- **JezikApp:** la primera respuesta hablada del tutor bajó de **~6,1 s a ~2,5 s**. El modelo responde por oraciones en streaming, la síntesis de voz se hace oración por oración sobre conexiones persistentes y el audio se reproduce en cola estricta.
- **FireLink:** la detección corre con un modelo de visión **cuantizado a INT8**, y el agente de captura usa **solo conexiones salientes**, así que se instala en la red de un cliente sin tocar su firewall.

## 🤖 Qué hago con IA

- **Voz y video en tiempo real:** tutores conversacionales que encadenan reconocimiento de voz → LLM → síntesis de voz → avatar, con streaming de punta a punta para que la conversación no tenga pausas.
- **Agentes:** agentes con herramientas (MCP, function calling), orquestación de varios agentes y flujos con aprobación humana.
- **RAG:** ingesta, chunking, embeddings, búsqueda híbrida y evaluación de respuestas sobre documentos propios.
- **Visión artificial:** detección de objetos en video de cámaras, con modelos optimizados para inferencia en CPU y en el borde.
- **Clasificación con probabilidades:** modelos que puntúan texto para enrutar, moderar o priorizar, dejando la decisión final en código.

## 🛠️ Cómo trabajo

**Desarrollo agéntico:** paso rápido de una idea a un producto o servicio desplegado, con metodologías de trabajo agéntico múltiple, entornos aislados y metas que conversan entre sí. Trabajo **asistido** cuando corresponde, dirigiendo yo los milestones que así lo requieren, o **autónomo**, con agentes supervisores que se alinean a mis convenciones de trabajo, a los requerimientos del cliente y a los estándares actuales de producto y servicio.

## 💻 Stack

- **Lenguajes:** Python · TypeScript · Rust · Ruby · SQL
- **Web y móvil:** React · Next.js · Vite · Tailwind · FastAPI · Node/Express · NestJS · Rails · React Native/Expo · PWA
- **IA:** LLMs · agentes y MCP · reconocimiento de voz (STT) · síntesis de voz (TTS) · avatares en tiempo real · embeddings y búsqueda vectorial · evals
- **Visión:** YOLO · ONNX Runtime · cuantización INT8
- **Tiempo real:** WebRTC · LiveKit · SSE · WebSockets
- **Datos:** PostgreSQL · PostGIS · Supabase · Redis · pandas · scikit-learn
- **Plataforma:** Docker · Vercel · Cloudflare · GitHub Actions · VPS Linux · inferencia en GPU

## 📦 Código abierto

- [**apa-unab**](https://github.com/deldanr/apa-unab): skill para generar documentos Word en formato APA 7 según la guía de la UNAB.
