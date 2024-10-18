# Gestion de logs

## Collecte, analyse et gestion centralisée des logs
- **Propriétaires** : Splunk, Datadog, IBM QRadar
- **Open Source** :
  - [Graylog](https://www.graylog.org/) (Plateforme open source pour la collecte, l'analyse et la gestion des logs avec interface web intuitive)
  - [ELK Stack](https://www.elastic.co/what-is/elk-stack) (Suite composée de Elasticsearch, Logstash, et Kibana pour la gestion des logs, l'analyse et la visualisation)
  - [Fluentd](https://www.fluentd.org/) (Collecteur de logs open source, compatible avec plusieurs plateformes)
  - [Loki](https://grafana.com/oss/loki/) (Système de gestion de logs développé par Grafana, conçu pour l'efficacité et l'intégration avec Prometheus)

## Surveillance des événements et détection d'intrusions (SIEM)
- **Propriétaires** : Splunk Enterprise Security, IBM QRadar, ArcSight
- **Open Source** :
  - [Wazuh](https://wazuh.com/) (Plateforme open source de gestion des logs, SIEM et détection des menaces, avec intégration Elasticsearch)
  - [OSSIM](https://cybersecurity.att.com/products/ossim) (SIEM open source d'AlienVault pour la gestion centralisée des événements de sécurité)
  - [Prelude](https://www.prelude-siem.org/) (SIEM open source modulaire pour la gestion des incidents et la détection d'intrusions)
  - [Security Onion](https://securityonion.net/) (Distribution open source pour la détection des menaces, la surveillance du réseau et la gestion des logs)

## Collecte et routage des logs
- **Propriétaires** : LogRhythm, Splunk Forwarders
- **Open Source** :
  - [Rsyslog](https://www.rsyslog.com/) (Collecteur de logs puissant et flexible, largement utilisé pour les systèmes Linux/Unix)
  - [Fluentd](https://www.fluentd.org/) (Solution de collecte et routage des logs, utilisée pour agréger les logs de différentes sources)
  - [Logstash](https://www.elastic.co/logstash) (Outil open source pour collecter, transformer, et envoyer des logs vers des systèmes d'analyse comme Elasticsearch)
  - [Syslog-ng](https://www.syslog-ng.com/) (Collecteur de logs avancé et flexible, avec des fonctionnalités de filtrage et de transformation)

## Monitoring et visualisation des logs
- **Propriétaires** : Splunk, Datadog, Loggly
- **Open Source** :
  - [Kibana](https://www.elastic.co/kibana) (Interface de visualisation pour Elasticsearch, utilisée pour l'analyse et la présentation des logs)
  - [Grafana](https://grafana.com/) (Outil de visualisation open source, qui peut être utilisé avec Loki pour afficher et analyser les logs)
  - [Piwik PRO Analytics](https://piwik.pro/) (Outil de visualisation de données, incluant la gestion des logs)
  - [GoAccess](https://goaccess.io/) (Outil open source léger pour la visualisation en temps réel des logs d'accès web)

## Archivage et gestion des logs à long terme
- **Propriétaires** : AWS CloudWatch, Splunk Archiving
- **Open Source** :
  - [Elasticsearch](https://www.elastic.co/elasticsearch/) (Moteur de recherche et de stockage distribué pour indexer et archiver des quantités massives de logs)
  - [Logrotate](https://linux.die.net/man/8/logrotate) (Outil pour la gestion et la rotation des logs sur les systèmes Unix/Linux)
  - [TimescaleDB](https://www.timescale.com/) (Extension de PostgreSQL pour gérer des séries temporelles, utilisée pour archiver les logs et les données historiques)

## Outils de gestion des logs spécifiques aux environnements conteneurisés
- **Propriétaires** : Datadog, Logz.io
- **Open Source** :
  - [Promtail](https://grafana.com/docs/loki/latest/clients/promtail/) (Client pour récupérer et envoyer les logs des conteneurs Docker vers Loki)
  - [Fluent Bit](https://fluentbit.io/) (Collecteur de logs léger pour les environnements conteneurisés comme Kubernetes)
  - [Vector](https://vector.dev/) (Plateforme open source de collecte et transformation des logs, conçue pour les environnements modernes)
  - [Filebeat](https://www.elastic.co/beats/filebeat) (Agent léger pour collecter et transférer les logs des conteneurs et systèmes dans l'ELK Stack)

