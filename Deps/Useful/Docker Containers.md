- **RabbitMq**
>docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 --hostname rabbitmq-master rabbitmq:3-management

- **Redis**
>docker run --name redis -p 6379:6379 -d redis:7-alpine


- **Limpar Cache do Banco do Redis**
>npm install redis-cli -g
>**(instala o rdcli global)**
>
>rdcli
>flushall
>![[RedisCache.png]]