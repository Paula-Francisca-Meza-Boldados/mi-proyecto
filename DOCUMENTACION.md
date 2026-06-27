# Documentacion Monitorizacion - Grafana

## Configuracion Grafana
- Data source: Prometheus conectado en http://172.17.0.1:9090
- Dashboard: mi-dashboard configurado con metricas en tiempo real

## Metricas monitoreadas
- Metrica: up{instance="localhost:5000", job="mi-app"}
- Estado: aplicacion corriendo correctamente

## Incidentes detectados
- No se detectaron incidentes de seguridad durante el monitoreo
- La aplicacion se mantuvo estable durante todo el periodo

## Acciones tomadas
- Monitoreo continuo configurado con intervalo de 15 segundos
- Dashboard actualizado en tiempo real
