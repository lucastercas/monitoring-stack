.PHONY: traefik grafana zabbix all

all: traefik grafana zabbix wiki

traefik:
	docker stack deploy -c traefik.yml traefik

grafana:
	docker stack deploy -c grafana.yml grafana

zabbix:
	docker stack deploy -c zabbix.yml zabbix

wiki:
	docker stack deploy -c wiki.yml wiki