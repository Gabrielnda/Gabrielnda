# Olá, sou Gabriel Assis 👋

Profissional de Tecnologia da Informação, integrante da equipe de infraestrutura, com atuação em **Blue Team, monitoramento de segurança e análise de incidentes**.

No dia a dia, trabalho com análise de logs em **SIEM**, triagem e investigação de e-mails suspeitos (*phishing*, *spoofing* e *malware*), além de atividades relacionadas à proteção de endpoints e à segurança da infraestrutura.

Atualmente, também estou aprofundando meus conhecimentos em **DevSecOps e segurança de aplicações**, com foco em **automação de testes de segurança em pipelines CI/CD**, identificação de vulnerabilidades antes da entrada em produção e centralização de resultados para análise e tratamento.

---

## Áreas de atuação e estudo

- **Blue Team / SOC:** monitoramento, análise de alertas, investigação e resposta inicial a incidentes.
- **Segurança de e-mail:** análise de ameaças, autenticação de mensagens e identificação de tentativas de phishing.
- **Segurança de redes e endpoints:** análise de tráfego, eventos e indicadores de comprometimento.
- **DevSecOps / AppSec:** estudos e laboratórios de integração de testes automatizados ao ciclo de desenvolvimento de software.

---

## Projetos

| Projeto | Descrição | Link |
| :--- | :--- | :--- |
| **SOC HomeLab** | Implementação e monitoramento de um ambiente de segurança para estudos e análises de eventos. | [Acessar repositório](https://github.com/Gabrielnda/SOC_HomeLab.git) |
| **Security Pipeline Lab** *(em desenvolvimento)* | Laboratório de pipeline CI/CD voltado à automação de testes de segurança e à gestão centralizada de vulnerabilidades. | Documentação e repositório em preparação |

### Security Pipeline Lab — DevSecOps

Laboratório para compreender e implementar um processo de **validação automatizada de segurança em aplicações**, usando uma aplicação de teste e ferramentas integradas a uma pipeline.

**Fluxo de referência:**

```text
Código / repositório
        │
        ▼
      Jenkins
  (orquestração)
        │
        ├── Semgrep CE   → SAST (análise estática)
        ├── Gitleaks     → detecção de segredos
        ├── Trivy        → dependências e imagens de contêiner
        └── OWASP ZAP    → DAST (testes dinâmicos)
        │
        ▼
    Relatórios dos scanners
        │
        ▼
     DefectDojo
(centralização e acompanhamento de achados)
        │
        ▼
  Triagem e tratamento de vulnerabilidades
```

O laboratório aborda **orquestração de etapas no Jenkins**, integração com scanners, organização de relatórios e definição de critérios de avaliação dos achados. As integrações e políticas de bloqueio são parte da evolução do projeto e **não representam uma implantação concluída em produção**.

---

## Ferramentas e tecnologias

### Frameworks e referências

<div>
  <img alt="OWASP" src="https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white" />
  <img alt="MITRE ATT&CK" src="https://img.shields.io/badge/MITRE%20ATT%26CK-3595F9?style=for-the-badge&logoColor=white" />
  <img alt="ISO 27001:2022" src="https://img.shields.io/badge/ISO%2027001%3A2022-FFFFFF?style=for-the-badge&logoColor=004C97" />
</div>

### Análise de redes

<div>
  <img alt="Wireshark" src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img alt="Suricata" src="https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge&logoColor=white" />
  <img alt="Zeek" src="https://img.shields.io/badge/Zeek-777BB4?style=for-the-badge&logoColor=white" />
</div>

### Endpoint e XDR

<div>
  <img alt="Sophos" src="https://img.shields.io/badge/Sophos-337AB7?style=for-the-badge&logoColor=white" />
</div>

### SIEM / SOC e monitoramento

<div>
  <img alt="Wazuh" src="https://img.shields.io/badge/Wazuh-3595F9?style=for-the-badge&logoColor=white" />
  <img alt="Zabbix" src="https://img.shields.io/badge/Zabbix-D40000?style=for-the-badge&logo=zabbix&logoColor=white" />
</div>

### CI/CD e automação de segurança

<div>
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img alt="OWASP ZAP" src="https://img.shields.io/badge/OWASP%20ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white" />
  <img alt="DefectDojo" src="https://img.shields.io/badge/DefectDojo-343A40?style=for-the-badge&logoColor=white" />
  <img alt="Semgrep" src="https://img.shields.io/badge/Semgrep-FF5A5F?style=for-the-badge&logoColor=white" />
  <img alt="Trivy" src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logoColor=white" />
  <img alt="Gitleaks" src="https://img.shields.io/badge/Gitleaks-555555?style=for-the-badge&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</div>

### Linguagens e tecnologias

<div>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</div>

---

> **Objetivo profissional:** aprofundar minha atuação em segurança defensiva e evoluir em práticas de **DevSecOps**, conectando monitoramento, identificação de vulnerabilidades e automação de processos de segurança.
