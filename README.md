# Commands
    docker build -t express_node .
----
    docker run --name express_node_container -v D:\docker\node-app:/app -d -p 4000:4000 express_node
----
    docker exec -it express_node_container bash
