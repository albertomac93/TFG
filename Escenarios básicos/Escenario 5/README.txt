# Escenario 5: Control del uso de CPU y memoria a partir de cgroups para servicio Systemd

Fichero inicial. Corresponde al servicio inicial sin slice configurado
Ficheros final. Corresponde al servicio final con slice configurado

Rutas donde guardar los ficheros:

escenarioCgroups.service(inicial) -> Renombrar escenarioCgroups.service y colocar en ruta /etc/systemd/system/escenarioCgroups.service
generate_load.sh -> Colocar en ruta /etc/systemd/system/generate_load.sh
escenarioCgroups.service(final) -> Renombrar escenarioCgroups.service y colocar en ruta /etc/systemd/system/escenarioCgroups.service
