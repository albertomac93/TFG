# Escenario 9. Máquina 1

Rutas donde almacenar los ficheros

broker0_kafka.nspawn -> /etc/systemd/nspawn/broker0_kafka.nspawn
kafka-container.service -> /etc/systemd/system/kafka-container.service
kafka-zookeeper.service -> /etc/systemd/system/kafka-zookeeper.service
notif_arranque_inicio.sh -> /usr/local/src/kafka/notif_arranque_inicio.sh
notif_arranque_fin.sh -> /usr/local/src/kafka/notif_arranque_fin.sh
zookeeper-server-start.sh -> /usr/local/src/kafka/bin/zookeeper-server-start.sh 
zookeeper-server-stop.sh -> /usr/local/src/kafka/bin/zookeeper-server-stop.sh 
