# Prompt 6 — el panel que muestra lo que importa (Claude Dashboards)

**Plan:** Dashboards está en **beta** y solo está disponible en los planes de pago (Pro, Max, Ultra, Team, Enterprise). En el plan gratuito, haz solo la primera parte (elegir los números) y llévalos en una hoja de cálculo.
En Enterprise viene desactivado hasta que el dueño de la cuenta lo habilite.
**Datos:** conecta una base de datos (BigQuery, Snowflake, Databricks, Redshift, ClickHouse) o una app como
Salesforce mediante los conectores. Sin eso, puedes empezar con una hoja de cálculo adjunta.

## Primero: elige las cifras (antes de abrir el panel)
Un buen panel responde una sola pregunta: «¿estoy llegando a mi meta?».
- **Cifra de resultado** (lo que quieres lograr al final): ingresos del mes, clientes activos, consultas realizadas.
- **Cifras que impulsan el resultado** (lo que puedes cambiar hoy): propuestas enviadas, primeras consultas, pacientes que regresan.

```
Ayúdame a elegir las cifras de mi panel.
Mi objetivo para [período] es: [ej.: 120 consultas al mes].
1. Confirma cuál es la cifra de resultado.
2. Sugiere de 2 a 4 cifras que impulsen ese resultado y que pueda medir cada semana.
3. Para cada una, dime de dónde proviene el dato (qué sistema u hoja de cálculo) y con qué frecuencia actualizarlo.
Todavía no armes el panel.
```

## Después: arma el panel
```
Arma un dashboard con: [cifra de resultado] frente a la meta en la parte superior; debajo, [cifras que impulsan el resultado]
semana a semana; un gráfico por cifra, sin adornos. Usa [conector / hoja de cálculo adjunta].
En cada gráfico, indica en una frase qué cambió desde la semana pasada.
```

**Antes de compartirlo:** haz clic en cada cifra y revisa la consulta (query) que hay detrás; comprueba la fecha de
la última actualización de cada gráfico. Anthropic no ha publicado la tasa de aciertos de las consultas: revísalas siempre.
Para un análisis profundo, envía el panel a tu herramienta de BI.