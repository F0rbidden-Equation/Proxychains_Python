# Proxychains_Python

# Présentation des différents types de serveurs proxy

## Introduction
Dans le domaine des réseaux informatiques, un serveur proxy agit comme un intermédiaire entre un client et un serveur. Il permet de faire transiter le trafic réseau à travers lui, offrant ainsi divers avantages tels que l'anonymat, l'accès restreint à certains contenus, la mise en cache, etc.

Dans cette documentation, nous allons explorer les différents types de serveurs proxy les plus couramment utilisés et comment les déployer à l'aide de proxychains avec du code Python.

## Proxy HTTP
Le proxy HTTP est l'un des types de serveurs proxy les plus courants. Il agit comme un intermédiaire entre un client et un serveur HTTP, permettant de filtrer et de contrôler les requêtes et les réponses HTTP. Les proxies HTTP sont souvent utilisés pour la mise en cache, le filtrage de contenu et l'anonymat en ligne.

## Proxy SOCKS
Le proxy SOCKS est un protocole de proxy plus général qui prend en charge les connexions TCP et UDP. Contrairement aux proxies HTTP, les proxies SOCKS n'inspectent pas spécifiquement les requêtes ou les réponses HTTP, mais ils permettent de rediriger le trafic réseau de manière transparente. Les proxies SOCKS sont couramment utilisés pour le contournement des pare-feu et l'anonymat.

## Proxy Transparent
Un proxy transparent fonctionne de manière similaire à un proxy HTTP, mais il agit de manière transparente, c'est-à-dire qu'il n'exige aucune configuration spécifique du client. Le client n'est pas conscient de l'existence du proxy, car toutes les requêtes sont automatiquement redirigées vers le proxy. Les proxies transparents sont généralement utilisés pour le filtrage du contenu et le contrôle d'accès.

## Proxy Reverse
Un proxy reverse est utilisé pour rediriger le trafic des clients vers des serveurs situés en aval. Il agit comme un intermédiaire entre les clients et les serveurs, masquant la véritable adresse IP du serveur. Les proxies inverses sont souvent utilisés pour la répartition de charge, la mise en cache et la sécurisation des serveurs web.

## Déploiement de proxychains avec Python
Maintenant que nous avons une vue d'ensemble des différents types de serveurs proxy, nous allons explorer comment déployer proxychains à partir de code Python.

Proxychains est un outil qui permet de chaîner les connexions à travers plusieurs proxies, offrant ainsi une superposition de proxy. Il peut être utilisé pour acheminer le trafic à travers différents types de serveurs proxy, ce qui peut s'avérer utile dans certaines situations.
