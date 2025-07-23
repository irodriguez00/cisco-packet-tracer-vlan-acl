# Diseño de Red Empresarial con Cisco Packet Tracer

Este es un proyecto propio diseñado y configurado por mí en **Cisco Packet Tracer**, simulando la infraestructura de una red empresarial segmentada y segura.

## 🔷 Descripción

El objetivo de este proyecto fue crear una red empresarial simulada con segmentación lógica mediante VLANs, políticas de acceso mediante ACLs y un servidor con servicios esenciales.

## 🖥️ Topología

- 1 Router Cisco 1941
- 2 Switches Cisco 2960
- 4 PCs:
  - Admin
  - HR
  - IT
  - Guest
- 1 Servidor (HTTP, DNS, Syslog)

## 🔷 VLANs configuradas

| VLAN | Nombre   | Dispositivos         | Red IP          | Gateway        |
|------|----------|----------------------|-----------------|----------------|
| 10   | Admin    | PC1, Servidor        | 192.168.10.0/24 | 192.168.10.1   |
| 20   | HR       | PC2                  | 192.168.20.0/24 | 192.168.20.1   |
| 30   | Guest    | PC3                  | 192.168.30.0/24 | 192.168.30.1   |
| 40   | IT       | PC4                  | 192.168.40.0/24 | 192.168.40.1   |
| 99   | Native   | (No hosts)           | —               | —              |

## 🔷 Características implementadas

✅ VLANs para segmentación lógica  
✅ Puertos trunk y VLAN nativa  
✅ ACLs para restringir tráfico entre VLANs  
✅ Servidor configurado con HTTP, DNS y Syslog  
✅ Pruebas de conectividad para validar políticas

## 💡 Aprendizajes

Durante este proyecto, fortalecí mis habilidades en:

- Diseño de redes segmentadas con seguridad básica
- Implementación de reglas de control de acceso (ACLs)
- Solución de problemas de conectividad entre VLANs
- Configuración de servicios de red en un entorno simulado

## 🛠️ **Tecnologías usadas**
- Cisco Packet Tracer
- VLANs
- ACLs
- Servicios de red: HTTP/DNS/Syslog

## 📁 Archivos

- [proyecto red.pkt](proyecto%20red.pkt) — Archivo de Cisco Packet Tracer.
- [Video demostración en YouTube](https://www.youtube.com/watch?v=X9sALeZS55Y)
  
## 📌 Autor

**Ignacio Rodriguez**  

[https://www.linkedin.com/in/ignacio-rodriguez00/](https://www.linkedin.com/in/ignacio-rodriguez00/)  
