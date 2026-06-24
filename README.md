<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1BA0D7,100:0D47A1&height=220&section=header&text=Networking%20Lab&fontSize=55&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=David%20Lopez%20%7C%20ASIR%20%7C%20CCNA%201%20%E2%9C%85&descSize=20&descAlign=50&descAlignY=60&descColor=c0e0ff" alt="Redes Banner" width="100%">

**Configuracion de equipos Cisco, diseño de topologias, enrutamiento, switching y networking real en homelab.**

[![Cisco](https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white)](https://www.netacad.com/)
[![CCNA 1](https://img.shields.io/badge/CCNA_1-Certificado_✅-04222E?style=flat-square&logo=cisco&logoColor=white)](#)
[![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)](#)

</div>

<br/>

## 🎯 Sobre este repositorio

Laboratorio personal y portafolio de **Administracion de Redes** como parte de mi formacion en **ASIR**.

**Certificacion CCNA 1 obtenida** — los conceptos aqui practicados en simulador los aplico en mi homelab real con +15 servicios Docker accesibles por subdominios, reverse proxy, DNS local y monitorizacion de red.

<br/>

## 📂 Estructura del Laboratorio

<table>
<tr>
<td width="50%" valign="top">

### 🏗️ Topologias y Diseño
- Red jerarquica (Core, Distribucion, Acceso)
- VLSM y Subnetting aplicados a casos reales

### 🔀 Switching (Capa 2)
- Switches Cisco: seguridad de puertos, SSH
- **VLANs** y Router-on-a-Stick
- STP y EtherChannel

</td>
<td width="50%" valign="top">

### 🗺️ Routing (Capa 3)
- Enrutamiento estatico y rutas por defecto
- Enrutamiento dinamico (OSPF, RIPv2)
- ACLs estandar y extendidas

### 🛠️ Servicios de Red
- Servidores **DHCP** y **DNS**
- **NAT / PAT**

</td>
</tr>
</table>

<br/>

## 🏠 Networking real — Homelab

<div align="center">

Los conceptos de este repositorio los aplico en mi infraestructura real:

</div>

<br/>

<details>
<summary><b>🌐 Ver diagrama de red</b></summary>
<br/>

```
Internet ──► Router ──► UGREEN NAS (Docker)
                              │
                              ├── Pi-hole (DNS local + ad-blocking)
                              ├── Nginx Proxy Manager (reverse proxy)
                              │     └── Wildcard SSL por subdominios
                              ├── Uptime Kuma (monitorizacion)
                              └── +15 servicios por subdominios HTTPS
```

</details>

<br/>

<div align="center">

| Concepto | Aplicacion real en el homelab |
| :--- | :--- |
| 🛡️ **DNS** | Pi-hole como servidor DNS local, filtrando publicidad |
| 🔀 **Reverse Proxy** | Nginx Proxy Manager redirigiendo subdominios a puertos |
| 🔐 **SSL/TLS** | Certificado wildcard para HTTPS en todos los servicios |
| 🔢 **Subnetting** | Red local con IP fija asignada al NAS |
| 📊 **Monitorizacion** | Uptime Kuma + Prometheus/Grafana para metricas |
| 🔌 **Port Forwarding** | Puertos redirigidos al NAS para acceso externo |

</div>

<br/>

## 🚀 Como explorar mis practicas

> Cada practica incluye: archivo `.pkt` para Cisco Packet Tracer, documento `.txt` con comandos aplicados, y diagrama exportado cuando la topologia es compleja.

<br/>

<div align="center">

*"Una red bien diseñada es aquella en la que el administrador puede dormir tranquilo."*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1BA0D7,100:0D47A1&height=100&section=footer" width="100%"/>

**[⬅️ Volver a mi perfil principal](https://github.com/davidlpizano/davidlpizano)**

</div>
