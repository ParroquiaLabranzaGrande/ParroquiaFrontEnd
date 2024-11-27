/src
│
├── /public                 # Archivos públicos accesibles por el cliente
│   ├── /assets             # Estilos e imágenes
│   │   ├── /css            # Archivos CSS
│   │   └── /img            # Imágenes
│   ├── EnvioConfesiones.js # Lógica de envío de confesiones
│   ├── EnvioMisas.js       # Lógica de envío de misas
│   └── EnvioPartida.js     # Lógica de envío de partidas
│
├── /views                  # Archivos HTML (vistas del proyecto)
│   ├── index.html          # Página de inicio
│   ├── SuperAdmin.html     # Vista para SuperAdmin
│   ├── User.html           # Vista para Usuarios
│   ├── secretary.html      # Vista para Secretaría
│
├── /modules                # Módulos JavaScript por funcionalidad
│   ├── GestionConfesionesSuperAdmin.js
│   ├── GestionMisaSuperAdmin.js
│   ├── GestionPartidasSuperAdmin.js
│   ├── SolicitudDePartidaUser.js
│   ├── UserSolicitarConfesion.js
│   ├── UserSolicitarMisa.js
│   └── comprobation
