# UPTIME

El comando `uptime` muestra cuánto tiempo ha estado encendido el sistema y la carga promedio durante ese tiempo.

## Ejemplo de uso
```bash
uptime
```
La salida del comando puede verse así:
```bash
14:36 up 2 days, 6:45, 4 users, load averages: 0.29 0.24 0.18
```
Muestra la hora actual del sistema. `14:36`
La segunda muestra el tiempo transcurrido desde que se inició el sistema. `up 2 days, 6:45`
El número de usuarios conectados. `4 users`
La [carga promedio del sistema]() en los últimos 1, 5 y 15 minutos. `load averages: 0.29 0.24 0.18`

| Opcion | Acción |
| ----------- |-------------|
| **-p** | Muestra el tiempo transcurrido desde que se inició el sistema de forma más bonita |
| **-h** | Imprime un texto de explicación del comando |
| **-s** | Muestra el tiempo transcurrido desde que se inició el sistema en formato `yyyy-mm-dd HH:MM:SS` |
| **-V** | Muestra la version |
