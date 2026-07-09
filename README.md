# busqueda-inmobiliaria-ia
¿Qué es esto?
Sistema automatizado de búsqueda inmobiliaria desarrollado como Trabajo Final de la Diplomatura en IA Aplicada a Entornos Digitales de Gestión (FCE-UBA, Cohorte 2026).
¿Para qué sirve?
Ayuda a tasadores inmobiliarios a encontrar propiedades que cumplan criterios específicos de sus clientes, buscando de forma automática en los principales portales inmobiliarios de Argentina: Zonaprop, Argenprop y MercadoLibre Inmuebles.
El sistema resuelve un problema real: cuando un tasador recibe una consulta específica (por ejemplo, departamento de 3 ambientes en Canning con pileta), debe buscar manualmente en múltiples portales, lo que consume mucho tiempo y puede hacer perder potenciales clientes al no poder responder rápidamente.
¿Cómo funciona?
1.	El tasador completa un formulario con los criterios de búsqueda: zona, habitaciones, comodidades, precio máximo y tipo de operación
2.	Una IA (Groq/Llama 3.3) transforma esos criterios en búsquedas optimizadas
3.	El sistema busca automáticamente en los 3 portales usando SerpAPI
4.	La IA resume los resultados encontrados
5.	El tasador recibe hasta 6 enlaces de propiedades directamente en Telegram
Herramientas utilizadas
•	n8n — automatización del flujo de trabajo
•	Groq / Llama 3.3 — modelo de IA gratuito para generación y resumen
•	SerpAPI — búsquedas en Google (plan gratuito)
•	Telegram — notificaciones al celular via bot
Estado del proyecto
Primera versión funcional completada. Pendiente de prueba en campo real con la usuaria final.
Próximos pasos
•	Probar el sistema con la tasadora en su flujo de trabajo real
•	Ajustar parámetros de búsqueda según necesidades detectadas
•	Incorporar más portales inmobiliarios
•	Agregar fotos y descripciones de propiedades en las notificaciones
•	Desarrollar un catálogo que se renueve automáticamente
Autora
Alejandra Magalí Micheli — Diplomatura en IA Aplicada a Entornos Digitales de Gestión, FCE-UBA 2026

