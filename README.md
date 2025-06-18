<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Alumnos CONALEP CCNA</title>
<style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #006633;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .leyenda {
      background-color: #e0f7e0;
      padding: 10px;
      text-align: center;
      font-style: italic;
      margin-top: 10px;
    }
    section {
      padding: 20px;
    }
    h2 {
      color: #006633;
    }
    .descargas, .pdfs {
      margin-top: 15px;
    }
    a.descargar {
      display: block;
      margin-bottom: 10px;
      color: #006633;
      text-decoration: none;
      font-weight: bold;
    }
    iframe {
      width: 100%;
      height: 500px;
      border: 1px solid #ccc;
      margin-top: 10px;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #ddd;
      font-size: 0.9em;
      margin-top: 40px;
    }
</style>
</head>
<body>
<header>
<h1>Alumnos CONALEP CCNA</h1>
</header>
<div class="leyenda">
    Página diseñada para jóvenes estudiantes de CONALEP inscritos en la carrera de redes y telecomunicaciones.
</div>
<section>
<h2>Descarga de Prácticas (Packet Tracer)</h2>
<div class="descargas">
<a class="descargar" href="1.0.5-packet-tracer-.pka" download>Descargar Práctica - Exploración de Modo Lógico y Físico</a>
<a class="descargar" href="2.2.13-packet-tracer-.pka" download>Descargar Práctica - Configuración OSPFv2 Punto a Punto</a>
<a class="descargar" href="2.3.11-packet-tracer-.pka" download>Descargar Práctica - Determine el DR y el BDR</a>
<a class="descargar" href="2.4.11-packet-tracer-.pka" download>Descargar Práctica - Modificar OSPFv2 Área Única</a>
<a class="descargar" href="2.5.3-packet-tracer-.pka" download>Descargar Práctica - Propagar Ruta Predeterminada en OSPFv2</a>
<a class="descargar" href="2.6.6-packet-tracer-.pka" download>Descargar Práctica - Verificar OSPFv2 Área Única</a>
<a class="descargar" href="5.1.8-packet-tracer-.pka" download>Descargar Práctica - ACL IPv4 estándar numeradas</a>
<a class="descargar" href="5.1.9-packet-tracer-.pka" download>Descargar Práctica - ACL IPv4 estándar con nombre</a>
<a class="descargar" href="5.2.7-packet-tracer-.pka" download>Descargar Práctica - Configurar y Modificar ACL IPv4</a>
<a class="descargar" href="5.4.12-packet-tracer-.pka" download>Descargar Práctica - ACL extendidas: Escenario 1</a>
<a class="descargar" href="5.4.13-packet-tracer-.pka" download>Descargar Práctica - ACL extendidas: Escenario 2</a>
<a class="descargar" href="6.2.7-packet-tracer-.pka" download>Descargar Práctica - Investigar operaciones NAT</a>
<a class="descargar" href="6.4.5-packet-tracer-.pka" download>Descargar Práctica - Configurar NAT estática</a>
<a class="descargar" href="6.5.6-packet-tracer-.pka" download>Descargar Práctica - Configuración de NAT dinámica</a>
<a class="descargar" href="6.6.7-packet-tracer-.pka" download>Descargar Práctica - Configurar PAT</a>
<a class="descargar" href="7.6.1-packet-tracer-.pka" download>Descargar Práctica - Conceptos de WAN</a>
<a class="descargar" href="10.1.5-packet-tracer-.pka" download>Descargar Práctica - Usar CDP para mapear una red</a>
<a class="descargar" href="10.2.6--packet-tracer-.pka" download>Descargar Práctica - Usar LLDP para mapear una red</a>
<a class="descargar" href="10.3.4-packet-tracer-.pka" download>Descargar Práctica - Configuración y verificación del NTP</a>
<a class="descargar" href="10.6.10-packet-tracer-.pka" download>Descargar Práctica - Copias de Respaldo de Archivos de Configuración</a>
<a class="descargar" href="10.6.12-packet-tracer-.pka" download>Descargar Práctica - Usar TFTP y Flash para administrar archivos (Modo físico)</a>
<a class="descargar" href="10.6.13-packet-tracer-.pka" download>Descargar Práctica - Recuperación de Contraseña (Modo físico)</a>
<a class="descargar" href="10.7.6-packet-tracer-.pka" download>Descargar Práctica - Actualizar imagen IOS con TFTP</a>
<a class="descargar" href="10.8.1-packet-tracer-.pka" download>Descargar Práctica - Configurar CDP, LLDP y NTP</a>
<a class="descargar" href="11.5.1-packet-tracer-.pka" download>Descargar Práctica - Comparar dispositivos de capa 2 y 3</a>
<a class="descargar" href="12.5.13-packet-tracer-.pka" download>Descargar Práctica - Resolución de problemas de redes empresariales</a>
<a class="descargar" href="12.6.1-packet-tracer-.pka" download>Descargar Práctica - Documentar la red</a>
<a class="descargar" href="12.6.2-packet-tracer-.pka" download>Descargar Práctica - Usar documentación para resolver problemas</a>
</div>
</section>
<section>
<h2>Visualización de Apuntes en PDF</h2>
<div class="pdfs">
<label for="seleccionPDF">Selecciona un archivo PDF:</label>
<select id="seleccionPDF" onchange="cargarPDF()">
<option value="">-- Selecciona un archivo --</option>
<option value="1.0.5-packet-tracer-.pdf">Exploración de Modo Lógico y Físico</option>
<option value="2.2.13-packet-tracer-.pdf">Configuración OSPFv2 Punto a Punto</option>
<option value="2.3.11-packet-tracer-.pdf">Determine el DR y el BDR</option>
<option value="2.4.11-packet-tracer-.pdf">Modificar OSPFv2 Área Única</option>
<option value="2.5.3-packet-tracer-.pdf">Propagar Ruta Predeterminada en OSPFv2</option>
<option value="2.6.6-packet-tracer-.pdf">Verificar OSPFv2 Área Única</option>
<option value="3.8.8-lab-.pdf">Laboratorio - Explorar tráfico DNS</option>
<option value="5.1.8-packet-tracer-.pdf">ACL IPv4 estándar numeradas</option>
<option value="5.1.9-packet-tracer-.pdf">ACL IPv4 estándar con nombre</option>
<option value="5.2.7-packet-tracer-.pdf">Configurar y Modificar ACL IPv4 estándar</option>
<option value="5.4.12-packet-tracer-.pdf">ACL extendidas: Escenario 1</option>
<option value="5.4.13-packet-tracer-.pdf">ACL extendidas: Escenario 2</option>
<option value="6.2.7-packet-tracer-.pdf">Investigar operaciones NAT</option>
<option value="6.4.5-packet-tracer-.pdf">Configurar NAT estática</option>
<option value="6.5.6-packet-tracer-.pdf">Configuración de NAT dinámica</option>
<option value="6.6.7-packet-tracer-.pdf">Configurar PAT</option>
<option value="7.5.11-lab-.pdf">Lab - Investigación de tecnologías de acceso a Internet de banda ancha</option>
<option value="7.6.1-packet-tracer-.pdf">Conceptos de WAN</option>
<option value="10.1.5-packet-tracer-.pdf">Usar CDP para mapear una red</option>
<option value="10.2.6-packet-tracer-.pdf">Usar LLDP para mapear una red</option>
<option value="10.3.4-packet-tracer-.pdf">Configuración y verificación del NTP</option>
<option value="10.4.10-lab-.pdf">Investigación de software de monitoreo de red</option>
<option value="10.6.10-packet-tracer-.pdf">Copias de Respaldo de Archivos de Configuración</option>
<option value="10.6.11-lab-.pdf">Lab - Usar Tera Term para Administrar los Archivos de Configuración</option>
<option value="10.6.12-packet-tracer-.pdf">Usar TFTP y Flash para administrar archivos (Modo físico)</option>
<option value="10.6.13-lab-.pdf">Lab - Recuperación de Contraseña</option>
<option value="10.6.13-packet-tracer-.pdf">Recuperación de Contraseña (Modo físico)</option>
<option value="10.7.6-packet-tracer-.pdf">Actualizar imagen IOS con TFTP</option>
<option value="10.8.1-packet-tracer-.pdf">Configurar CDP, LLDP y NTP</option>
<option value="10.8.2-lab-.pdf">Lab - Configurar CDP, LLDP y NTP</option>
<option value="11.5.1-packet-tracer-.pdf">Comparar dispositivos de capa 2 y capa 3</option>
<option value="12.5.13-packet-tracer-.pdf">Resolución de problemas de redes empresariales</option>
<option value="12.6.1-packet-tracer-.pdf">Desafío - Documentar la red</option>
<option value="12.6.2-packet-tracer-.pdf">Desafío - Usar documentación para resolver problemas</option>
<option value="13.6.1-lab-.pdf">Instalación de Linux en VM y exploración de la GUI</option>
</select>
<iframe id="visorPDF" src=""></iframe>
</div>
</section>
<footer>
    © 2025 | Proyecto educativo para estudiantes CONALEP - CCNA
</footer>
<script>
    function cargarPDF() {
      const seleccion = document.getElementById("seleccionPDF");
      const visor = document.getElementById("visorPDF");
      const archivo = seleccion.value;
      visor.src = archivo;
    }
</script>
</body>
</html>
