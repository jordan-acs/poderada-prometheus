# Ponderada M9S7

## O que é o Prometheus?

O Prometheus é um sistema de monitoramento e alerta de código aberto projetado para monitorar ambientes de computação em nuvem e infraestruturas complexas. Ele é especialmente útil para monitorar sistemas distribuídos, como aplicações em contêineres, microsserviços e ambientes de computação em escala.

## Como o Prometheus funciona?

O Prometheus funciona coletando métricas diretamente de alvos de monitoramento, como servidores, aplicações e serviços. Ele utiliza um modelo de coleta de métricas baseado em "scraping" (raspagem), onde os alvos expõem endpoints HTTP ou exportam métricas em formatos específicos (como o formato Prometheus).
<br><br>
Os dados coletados são armazenados localmente em um banco de dados de séries temporais, onde são organizados e indexados para facilitar a consulta e análise. O Prometheus também oferece recursos avançados de consultas e expressões para filtrar, agrupar e calcular métricas de maneira eficiente.
<br><br>
Além da coleta de métricas, o Prometheus possui um sistema de regras de alerta que permite definir condições de alerta com base nos dados monitorados. Ele pode enviar notificações e alertas para sistemas externos, como o Alertmanager, para gerenciamento e escalonamento de alertas.


## Vantagens do Prometheus

* Modelo de coleta flexível: O Prometheus suporta diferentes métodos de coleta de métricas, incluindo scraping HTTP, protocolos de exposição de métricas específicos (como o formato Prometheus), e integrações com outras ferramentas e serviços.

* Armazenamento eficiente: Ele utiliza um banco de dados de séries temporais que é otimizado para armazenar e consultar grandes volumes de dados de métricas de forma eficiente.

* Consultas poderosas: O Prometheus oferece uma linguagem de consulta expressiva e poderosa (PromQL) para análise e visualização de dados, permitindo realizar consultas complexas e criar gráficos e alertas personalizados.

* Integrações: Ele possui integrações com outras ferramentas e serviços de monitoramento, como o Grafana para visualização de dados, o Alertmanager para gerenciamento de alertas, e integração com sistemas de armazenamento em nuvem.

* Comunidade ativa: Sendo uma ferramenta de código aberto, o Prometheus possui uma comunidade ativa de desenvolvedores e usuários que contribuem com melhorias, plugins e suporte.
