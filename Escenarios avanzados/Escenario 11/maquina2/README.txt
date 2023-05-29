# Escenario 11. Máquina 2

Rutas donde almacenar los ficheros

broker1kafka.nspawn -> /etc/systemd/nspawn/broker1kafka.nspawn
kafka-container.service -> /etc/systemd/system/kafka-container.service
kafka-broker.service -> /etc/systemd/system/kafka-broker.service
notif_arranque_inicio.sh -> /usr/local/src/kafka/notif_arranque_inicio.sh
notif_arranque_fin.sh -> /usr/local/src/kafka/notif_arranque_fin.sh
kafka-server-start.sh -> /usr/local/src/kafka/bin/kafka-server-start.sh 
kafka-server-stop.sh -> /usr/local/src/kafka/bin/kafka-server-stop.sh
server.properties -> /usr/local/src/kafka/config/server.properties
