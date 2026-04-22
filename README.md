# Calculadora Calorica React

Aplicacion web para estimar el consumo calorico diario usando la formula de Mifflin-St Jeor.

## Que hace

- Calcula la tasa metabolica basal (TMB)
- Estima las calorias de mantenimiento segun actividad
- Ajusta un objetivo diario para perder grasa, mantener o ganar masa muscular
- Usa React en el navegador mediante modulos ESM

## Estructura

- `index.html`: punto de entrada de la app
- `src/main.js`: arranque de React
- `src/App.js`: interfaz y logica de calculo
- `src/styles.css`: estilos de la aplicacion

## Como ejecutarla en local

Al ser una app estatica, basta con servir la carpeta con un servidor simple:

```bash
cd /Users/samuelgonzalezbarchin/Documents/mifflin-react
python3 -m http.server 4174
```

## Formula utilizada

- Hombres: `10 x peso + 6.25 x altura - 5 x edad + 5`
- Mujeres: `10 x peso + 6.25 x altura - 5 x edad - 161`


