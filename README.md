# cassandra

плейбук для ansible 2.2, 
разворачивает cassandra кластер, в группе [cassandra] в inventory
для ubuntu 14.04, x86_64
требует прав root
запуск:
 * определить хосты в inventroy в группу cassandra
 * положить jre-8u121-linux-x64.tar.gz в cassandra-cluster/roles/cassandra/files/
 * запустить ansible-playbook -i ./hosts run.yml

PS: на jre ссыль прямой с oracle быстро не нашёл.
