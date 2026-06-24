<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=1BA0D7&height=200&section=header&text=Networking%20Lab&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=David%20Lopez%20%7C%20ASIR%20%7C%20CCNA%201%20%E2%9C%85&descSize=20&descAlign=50&descAlignY=62&descColor=ffffff" alt="Redes Banner">

**Configuración de equipos Cisco, diseño de topologías, enrutamiento, switching y networking real en homelab.**

[![Cisco](https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://www.netacad.com/)
[![CCNA](https://img.shields.io/badge/CCNA_1-Certificado_✅-04222E?style=for-the-badge&logo=cisco&logoColor=white)](#)
[![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)](#)

</div>

---

## 🎯 Sobre este repositorio

Este repositorio es mi laboratorio personal y portafolio de **Administración de Redes**. Aquí documento mis prácticas, configuraciones y resoluciones de problemas en entornos de red simulados y reales como parte de mi formación en **ASIR** (Administración de Sistemas Informáticos en Red).

**Certificación CCNA 1 obtenida** — los conceptos aquí practicados en simulador los aplico en mi homelab real con +15 servicios Docker accesibles por subdominios, reverse proxy, DNS local y monitorización de red.

---

## 📂 Estructura del Laboratorio

El repositorio está organizado por tecnologías y conceptos de red:

### 1. 🏗️ Topologías Base y Diseño (Packet Tracer)
- Diseños de red jerárquica (Core, Distribución, Acceso).
- Ejercicios de VLSM y Subnetting aplicados a casos reales.

### 2. 🔀 Switching y Capa 2
- Configuración inicial de Switches Cisco (Seguridad de puertos, contraseñas, SSH).
- Creación y enrutamiento de **VLANs** (Router-on-a-Stick).
- Protocolos de redundancia y prevención de bucles (STP, EtherChannel).

### 3. 🗺️ Routing y Capa 3
- Enrutamiento estático puro y rutas por defecto.
- Primeros pasos con enrutamiento dinámico (OSPF, RIPv2).
- Listas de Control de Acceso (ACLs) estándar y extendidas.

### 4. 🛠️ Servicios de Red
- Configuración de servidores **DHCP** y **DNS** en simulador.
- Traducción de Direcciones de Red (**NAT / PAT**).

---

## 🏠 Networking real — Homelab

Los conceptos de este repositorio los aplico en mi infraestructura real:

```
Internet ──► Router 192.168.1.1 ──► UGREEN NAS 192.168.1.3
                                         │
                                         ├── Pi-hole (DNS local + ad-blocking)
                                         ├── Nginx Proxy Manager (reverse proxy)
                                         │     └── Wildcard SSL *.dlplab.es
                                         ├── Uptime Kuma (monitorización de red)
                                         └── +15 servicios por subdominios HTTPS
```

| Concepto de red | Aplicación real en el homelab |
| :--- | :--- |
| **DNS** | Pi-hole como servidor DNS local para toda la red, filtrando publicidad |
| **Reverse Proxy** | Nginx Proxy Manager redirigiendo subdominios a puertos internos |
| **SSL/TLS** | Certificado wildcard `*.dlplab.es` para cifrado HTTPS en todos los servicios |
| **Subnetting** | Red local 192.168.1.0/24 con IP fija en el NAS |
| **Monitorización** | Uptime Kuma comprobando disponibilidad + Prometheus/Grafana para métricas de red |
| **Port forwarding** | Puertos 80/443 redirigidos al NAS para acceso externo |

---

## 🚀 Cómo explorar mis prácticas

La mayoría de prácticas incluyen:
1. Un archivo `.pkt` (Cisco Packet Tracer) para visualizar y probar la red.
2. Un documento o script `.txt` con los comandos relevantes aplicados a cada equipo.
3. Un pequeño diagrama exportado en imagen (cuando la topología es compleja).

---

<div align="center">

*"Una red bien diseñada es aquella en la que el administrador puede dormir tranquilo."*

**[⬅️ Volver a mi perfil principal](https://github.com/davidlpizano/davidlpizano)**

</div>
