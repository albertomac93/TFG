# Escenario 10. Máquina 1

Rutas donde almacenar los ficheros

kafka-zookeeper.service (inicial) -> Renombrar kafka-zookeeper.service y colocar en ruta /etc/systemd/system/kafka-zookeeper.service
kafka-zookeeper.service (final) -> Renombrar kafka-zookeeper.service y colocar en ruta /etc/systemd/system/kafka-zookeeper.service
notif_arranque_inicio.sh -> /usr/local/src/kafka/notif_arranque_inicio.sh
notif_arranque_fin.sh -> /usr/local/src/kafka/notif_arranque_fin.sh
zookeeper-server-start.sh -> /usr/local/src/kafka/bin/zookeeper-server-start.sh 
zookeeper-server-stop.sh -> /usr/local/src/kafka/bin/zookeeper-server-stop.sh 
