# Escenario 4: Monitorización de cambios en ruta o en fichero a través de Systemd

Ficheros inicial. Corresponden a la monitorización de un único fichero
Ficheros final. Corresponden a la monitorización de una segunda ruta

Rutas donde guardar los ficheros:

monitorizacion.service -> Colocar en ruta /etc/systemd/system/monitorizacion.service
script4.sh (inicial) -> Renombrar script4.sh y colocar en ruta /usr/local/src/script4.sh
monitorizacion.path (inicial) -> Renombrar monitorizacion.path y colocar en ruta /etc/systemd/system/monitorizacion.path
script4.sh (final) -> Renombrar script4.sh y colocar en ruta /usr/local/src/script4.sh
escenario4.path (final) -> Renombrar monitorizacion.path y colocar en ruta /etc/systemd/system/monitorizacion.path
