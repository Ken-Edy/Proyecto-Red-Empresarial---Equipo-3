# Proyecto-Red-Empresarial---Equipo-3
Proyecto de Implementación de Red Empresarial - Conmutación y Enrutamiento (TI-203) - ITLA

# Implementación de Red Empresarial (Producto 1)
**Asignatura:** Conmutación y Enrutamiento (TI-203)  
**Institución:** Instituto Tecnológico de Las Américas (ITLA)  
**Docente:** Prof. Onel Luis Pelegrino  
**Grupo:** Equipo 3  

## Integrantes
* Kenedy Espíritu — Matrícula: 2025-2726
* Albert Bravo Maria — Matrícula: 2025-2715
* Erick Brito — Matrícula: 2025-2731
* Melvin Batista - Matrícula: 2023-0119

## Descripción del Proyecto
Diseño, despliegue y validación de una infraestructura corporativa escalable y redundante para una mediana empresa sobre PNETLab, implementando:
* **VLANs y VTP:** Segmentación por departamentos con propagación en dominio `EMPRESA-ITLA`.
* **Alta Disponibilidad L2/L3:** Agregación de enlaces EtherChannel (PAgP) y redundancia de puerta de enlace con HSRPv2.
* **Enrutamiento Dinámico:** OSPFv2 (Área 0) con propagación de ruta predeterminada hacia el ISP e interfaces pasivas.
* **Seguridad Perimetral:** Filtrado granular de tráfico con ACLs extendidas en la sucursal/datacenter.

## Plan de Direccionamiento Base
* **IPv4:** `172.20.0.0/15`
* **IPv6:** `2001:25:20::/48`

## Estructura del Repositorio
* `/topologia`: Contiene el archivo `.unl` exportado de PNETLab y el diagrama gráfico de interconexión.
* `/configs`: Scripts individuales en formato `.txt` con las configuraciones aplicadas en cada router, switch multicapa, switch de acceso y hosts VPCS.
