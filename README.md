# OpenSourceMonitoring

Template de configuração de monitoramento gratuito e de código aberto para configurar Prometheus, Node Exporter, Grafana e cAdvisor usando Docker Compose.

# Passos para criar no seu ambiente

Você precisará instalar um host de contêiner Docker no seu ambiente.
Também, instale o Docker Compose.
Depois de ter os pré-requisitos do Docker em ordem, crie a estrutura de diretórios no seu diretório inicial usando os seguintes comandos:


mkdir -p promgrafnode/prometheus && \ 
mkdir -p promgrafnode/grafana/provisioning && \ 
touch promgrafnode/docker-compose.yml && \ 
touch promgrafnode/prometheus/prometheus.yml

#  Clonar os arquivos de exemplo

Usando os arquivos de configuração exemplo docker-compose.yml e prometheus.yml, basta copiar o conteúdo para seus arquivos docker-compose.yml e prometheus.yml criados a partir dos comandos acima.

# Criar os contêineres

Depois de criar os diretórios, navegue até a pasta promgrafnode e execute o comando docker-compose up -d.
