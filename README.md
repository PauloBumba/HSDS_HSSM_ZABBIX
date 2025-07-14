# 📡 Zabbix Monitoring Stack – Instalador Completo com Docker 🐳

Um ambiente completo de monitoramento com **Zabbix**, **MySQL**, **Portainer**, **Grafana** e mais — tudo rodando via **Docker** com facilidade, robustez e estilo.

---

## 📦 Serviços Instalados

| Serviço         | Porta | Descrição                                      |
|-----------------|-------|-----------------------------------------------|
| Zabbix Web      | 80    | Interface de monitoramento                    |
| Zabbix Server   | 10051 | Recebe dados dos agentes                      |
| Zabbix Agent    | 10050 | Monitora o próprio host/container             |
| MySQL           | 3306  | Banco de dados do Zabbix                      |
| Portainer       | 9443  | Gerenciamento visual de containers Docker     |
| Grafana         | 3000  | Dashboards de visualização avançada (opcional)|

---

## 🚀 Como usar

### 🧱 Pré-requisitos

- Docker e Docker Compose instalados.
- Sistema operacional: Linux, macOS, ou Windows com Docker Desktop.
- Acesso à porta 80 (ou 8080), 9443, 3000, etc.

### 🧪 Subir o ambiente

```bash
docker-compose up -d
