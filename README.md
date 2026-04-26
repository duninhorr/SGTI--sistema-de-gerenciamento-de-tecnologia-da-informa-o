# 📊 TechLevel BI & Analytics - SGTI SISTEMA DE GERENCIAMENTO DA TECNOLOGIA DA INFORMAÇÃO

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![PHP Version](https://img.shields.io/badge/php-%3E%3D%208.0-777bb4.svg)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=flat&logo=mysql&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)

O **TechLevel BI** é uma plataforma robusta de **Service Desk (ITSM)** e **Gestão de Infraestrutura**, desenvolvida para transformar dados operacionais em inteligência comercial. O sistema oferece uma visão clara dos custos de manutenção (OpEx), investimentos em ativos (CapEx) e produtividade da equipa técnica através de dashboards interativos no estilo SaaS Premium.

---

## 🚀 Funcionalidades Principais

### 📉 Dashboard Analítico (Business Intelligence)
* **Análise de Pareto**: Identificação dos setores com maior demanda de chamados.
* **Distribuição Anual**: Monitoramento do volume de manutenções por período.
* **KPIs Financeiros**: Visualização imediata do gasto total em manutenção e peças.
* **Filtros Dinâmicos**: Cruzamento de dados por Técnico, Setor, Ano e Período Customizado.

### 🎧 Service Desk (Módulo ITSM)
* Abertura de tickets com níveis de prioridade (Baixa a Urgente).
* Histórico de interações estilo chat entre usuário e técnico.
* Gestão de status em tempo real (Novo, Em Atendimento, Pendente, Solucionado).

### 💰 Gestão de Investimentos (CapEx)
* Módulo para solicitação de materiais tecnológicos.
* Controle de custos de substituição de hardware.
* Gráficos financeiros dedicados à expansão de ativos.

### 📂 Pipeline de Dados
* Importação em massa via **CSV** para alimentação de dados históricos.
* Data Lake para consulta rápida e exportação de registros.

---

## 🛠️ Stack Tecnológica

* **Backend:** PHP 8.0+ (Arquitetura Modular)
* **Banco de Dados:** MySQL com integração PDO
* **Frontend:** Bootstrap 5 (Custom Dark Mode SaaS)
* **Visualização de Dados:** Chart.js 4.4 (UMD)
* **Segurança:** Gestão de sessões e Hash de passwords (BCRYPT)

---

## 📸 Demonstração do Visual

| Dashboard Analítico | Service Desk |
| :---: | :---: |
| ![Dashboard Preview](https://via.placeholder.com/400x250?text=SaaS+Dark+Dashboard) | ![Service Desk Preview](https://via.placeholder.com/400x250?text=Service+Desk+Interface) |

---

## ⚙️ Instalação e Configuração

1.  **Clonar o repositório:**
    ```bash
    git clone [https://github.com/teu-usuario/techlevel-sgti.git](https://github.com/teu-usuario/techlevel-sgti.git)
    ```

2.  **Configurar o Banco de Dados:**
    * Importe o arquivo `database.sql` para o seu servidor MySQL.
    * Ajuste as credenciais no arquivo `db.php`.

3.  **Ambiente Local:**
    * Certifique-se de ter o módulo `PDO_MYSQL` ativado no seu PHP.
    * Inicie o servidor (Apache/Nginx).

---

## 👤 Autor

**Luis Carlos Pereira dos Santos Junior** *Systems Analyst & Full-Stack Programmer* 📍 Candeias, Bahia - Brasil.  
🎓 Graduando em Ciência de Dados pela Estácio de Sá.

---

## 📝 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---
⭐ **Se este projeto te ajudou, dá-lhe uma estrela no GitHub!**
