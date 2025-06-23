# Projeto SOC Integrado com Wazuh, Zeek e Azure feito no GNS3 (Em Construção)

Este projeto visa a construção de um Security Operations Center (SOC) completo e funcional, com foco em segurança ofensiva e defensiva, utilizando uma arquitetura integrada entre **Wazuh**, **Zeek (Bro IDS)** e **servidores em nuvem Azure**. O objetivo é demonstrar a implementação de um ambiente de monitoramento e detecção de ameaças robusto, capaz de coletar, analisar e correlacionar eventos de segurança de forma eficaz.

## Visão Geral do Projeto

O laboratório de SOC foi montado do zero, simulando um ambiente corporativo para praticar e aplicar conceitos avançados de cibersegurança. A integração entre as ferramentas visa maximizar a visibilidade sobre o tráfego de rede e o comportamento dos endpoints, facilitando a detecção e mitigação proativa de ataques.

## Componentes Principais

* **Wazuh:** Plataforma de segurança open source unificada para detecção de intrusões (HIDS), monitoramento de integridade de arquivos (FIM), avaliação de vulnerabilidades, coleta de logs e resposta a incidentes. Utilizado como o coração do SOC para agregação e análise de dados de segurança.
* **Zeek (Bro IDS):** Poderoso framework de análise de tráfego de rede. Zeek é empregado para uma análise profunda de pacotes, gerando logs de rede detalhados e específicos (como logs HTTP, DNS, SSL) que são cruciais para a análise forense e a caça a ameaças.
* **Microsoft Azure:** Infraestrutura de nuvem utilizada para hospedar os servidores e serviços do ambiente SOC. Serão utilizados templates (como ARM templates ou Terraform, dependendo da implementação) para provisionar e gerenciar a infraestrutura de forma automatizada e escalável.
* **MITRE ATT&CK:** Framework utilizado para mapear e mitigar ameaças, aplicando táticas e técnicas de adversários para aprimorar as capacidades de detecção e resposta do SOC.
* **MITRE CAR (Cyber Analytics Repository):** Repositório de análises e detecções baseadas no ATT&CK, que serão adaptadas e implementadas no Wazuh para enriquecer as regras de detecção.
* **MITRE D3FEND:** Framework aplicado para guiar a implementação de contramedidas defensivas e melhorar a resiliência do ambiente.

## Objetivos do Projeto

* Implementar e configurar uma infraestrutura de SOC escalável no Azure.
* Integrar Wazuh para coleta e análise de logs de endpoints e rede.
* Implantar Zeek para monitoramento de tráfego de rede, gerando dados valiosos para o SIEM.
* Desenvolver e aplicar regras de detecção personalizadas no Wazuh baseadas nos frameworks MITRE ATT&CK, CAR e D3FEND.
* Simular cenários de ataque para testar a eficácia das detecções e dos playbooks de resposta a incidentes.
* Documentar todo o processo de setup, configuração e testes para facilitar a replicação e o aprendizado.

## Próximos Passos

* [ ] Implementação de SOAR (Security Orchestration, Automation and Response) para automação de resposta.
* [ ] Integração com ferramentas de Threat Intelligence.
* [ ] Criação de dashboards personalizados para visualização de segurança.

---

![image](https://github.com/user-attachments/assets/e71aed53-f17a-4fa1-97ba-fa41d3fdcc2a)
