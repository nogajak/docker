up:
	docker compose up -d

down:
	docker compose down

remove:	
	docker compose rm

logs:
	docker compose logs -f

test:
	docker run -it --rm -v ./haproxy.cfg:/usr/local/etc/haproxy/haproxy.cfg:ro --network rabbitmq_network --name haproxy-syntax-check haproxy:2.6.18-alpine3.20 haproxy -c -f /usr/local/etc/haproxy/haproxy.cfg