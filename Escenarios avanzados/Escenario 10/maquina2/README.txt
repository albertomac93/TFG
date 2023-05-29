# Escenario 10. Máquina 2

Rutas donde almacenar los ficheros

kafka-broker.service (inicial) -> Renombrar kafka-broker.service y colocar en ruta /etc/systemd/system/kafka-broker.service
kafka-broker.service (final) -> Renombrar kafka-broker.service y colocar en ruta /etc/systemd/system/kafka-broker.service
notif_arranque_inicio.sh -> /usr/local/src/kafka/notif_arranque_inicio.sh
notif_arranque_fin.sh -> /usr/local/src/kafka/notif_arranque_fin.sh
kafka-server-start.sh -> /usr/local/src/kafka/bin/kafka-server-start.sh 
kafka-server-stop.sh -> /usr/local/src/kafka/bin/kafka-server-stop.sh
server.properties -> /usr/local/src/kafka/config/server.properties
