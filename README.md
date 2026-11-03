# Mi primer laboratorio seguro de ciberseguridad

**Checkpoint · Curso de Ciberseguridad, Coderhouse**
Autora: Denise Romero

## Contenido

- [`Reporte-Laboratorio-Seguro-CIA_Romero_Denise.pdf`](Reporte-Laboratorio-Seguro-CIA_Romero_Denise.pdf): Reporte Técnico de Configuración de Laboratorio, con capturas de evidencia y la justificación de cada paso según la tríada CIA (Confidencialidad, Integridad y Disponibilidad).

## Resumen del laboratorio

| Punto de la consigna | Qué se hizo | Pilar CIA |
|---|---|---|
| 1. La Fundación: red aislada | VM en VirtualBox con red en modo NAT, configurada antes del primer arranque | Confidencialidad |
| 2. Usuarios | Usuario estándar `usuario1`, sin pertenecer al grupo `sudo` | Integridad y Confidencialidad |
| 3. Capa Linux: permisos y actualizaciones | Permisos revisados con `ls -l`, sistema actualizado con `sudo apt update && sudo apt upgrade` | Integridad, Disponibilidad y Confidencialidad |
| 4. Snapshot inicial | Instantánea "Clean Install - Hardening applied" con la VM apagada | Disponibilidad e Integridad |

**Entorno:** VirtualBox sobre macOS (Intel) · Ubuntu Server 24.04 LTS
