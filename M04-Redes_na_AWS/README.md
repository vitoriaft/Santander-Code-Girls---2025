# Módulo 04 — Redes na AWS

Este módulo apresenta os principais serviços de **rede, segurança e distribuição de conteúdo na AWS**, mostrando como eles se conectam para criar infraestruturas escaláveis e seguras na nuvem.

---

## Atividades do módulo

1. **Introdução à Amazon VPC**  
2. **Entendendo o que é uma Subnet na Amazon VPC**  
3. **Introdução ao Security Group na AWS**  
4. **Explorando os Fundamentos do Route 53 na AWS**  
5. **Introdução à Distribuição de Conteúdo com Amazon CloudFront**  
6. **Entendendo o que é o Amazon Elastic Load Balancer (ELB)**  

---

## Objetivo do módulo

- Entender como funcionam as redes virtuais na AWS.  
- Criar e configurar **VPCs**, **Subnets** e **Security Groups**.  
- Compreender o funcionamento de **DNS (Route 53)** e **CDN (CloudFront)**.  
- Aplicar **balanceamento de carga (ELB)** para escalabilidade e alta disponibilidade.

---

##  Diagrama — Representação das Redes na AWS

Usuário 
↓
Amazon CloudFront (CDN)
↓
Amazon Route 53 (DNS)
↓
Elastic Load Balancer (Distribuição de Tráfego)
↓
Amazon VPC (Rede Virtual Privada)
├── Subnet Pública → Instâncias EC2 (Front-end)
└── Subnet Privada → Bancos de Dados / Aplicações Internas
↓
Security Groups
