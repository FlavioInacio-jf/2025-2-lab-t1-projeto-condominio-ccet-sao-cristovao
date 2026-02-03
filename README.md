# Condomínio de Laboratórios de Pesquisa – CCET/UFS

Este repositório concentra **toda a documentação técnica e institucional** do **Condomínio de Laboratórios de Pesquisa do CCET (Centro de Ciências Exatas e Tecnologia) da Universidade Federal de Sergipe – UFS**.

O objetivo do condomínio é **centralizar infraestrutura, padronizar serviços de TI e facilitar o acesso público** às informações e aos sistemas desenvolvidos por cada grupo de pesquisa, mantendo ao mesmo tempo **autonomia técnica** para cada laboratório.

---

## 🌐 Site do Condomínio de Laboratórios

O site do condomínio funciona como uma **home institucional unificada**, apresentando todos os laboratórios de pesquisa vinculados.

### Características principais:

* Página inicial com descrição geral do condomínio;
* Seções resumidas para cada laboratório;
* **Âncoras e links diretos** para o site individual de cada grupo de pesquisa;
* Hospedagem em infraestrutura AWS disponibilizada pela turma;
* Cada laboratório possui seu **próprio site**, com IP dedicado, mantido de forma independente.

---

## 🧪 Laboratórios de Pesquisa

Abaixo estão listados os grupos de pesquisa integrantes do condomínio. Cada seção contém um **espaço reservado** para que o próprio laboratório descreva sua atuação, infraestrutura e sistemas.

---

### 1️⃣ Gestão da Informação e Suporte à Decisão – GISD

**Descrição técnica do laboratório:**
- O Laboratório GISD é um ambiente de pesquisa focado na investigação e desenvolvimento de metodologias para coleta, processamento, armazenamento seguro e análise de grandes volumes de dados (Big Data). O objetivo central é aplicar técnicas computacionais e algoritmos avançados para transformar dados brutos em conhecimento estratégico, otimizando processos complexos de tomada de decisão e garantindo a governança da informação.

**Principais linhas de pesquisa:**

- Sistemas de Apoio à Decisão (SAD) e Métodos Multicritério.

- Governança de Dados e Adequação à LGPD (Lei Geral de Proteção de Dados).

**Infraestrutura computacional:**

- Serviços: Ambiente virtualizado de alta performance (no Cluster do Condomínio) com orquestração via Docker.

- Banco de Dados: Servidor PostgreSQL dedicado para persistência de dados relacionais e suporte a queries analíticas complexas.

Segurança: Segmentação de rede via VLANs e controle de acesso rígido para proteção de dados sensíveis de pesquisa.
**Site do laboratório:**

* IP / Endpoint AWS: `98.91.2.44`

---

### 2️⃣ Grupo de Estudos Tectônicos

**Descrição técnica do laboratório:**

> Unidade de pesquisa especializada em geologia estrutural, mapeamento tectônico e análise de recursos minerais no estado de Sergipe.

**Principais linhas de pesquisa:**

- Mapeamento Geológico (1:25.000) e Petrografia.

- Prospecção e viabilidade de Recursos Minerais.

- Inventariação e conservação de Patrimônio Geológico.

**Infraestrutura computacional:**

>Servidor de dados geoespaciais, estações de trabalho para processamento de imagens de satélite e SIG (ArcGIS/QGIS), e integração com equipamentos geodésicos de precisão.

**Site do laboratório:**

* IP / Endpoint AWS: `3.227.88.172`

---

### 3️⃣ Construção Civil

**Descrição técnica do laboratório:**

> O laboratório atua como um hub de convergência digital para a Engenharia Civil, operando dentro da VLAN 30 da rede CCET. Ele é projetado para suportar o fluxo de trabalho colaborativo em modelos de alta complexidade. A rede fornece isolamento de tráfego para que grandes sincronizações de arquivos (processo comum em plataformas como Revit Server ou BIM 360) não sofram gargalos de latência, permitindo que múltiplos projetistas trabalhem simultaneamente no mesmo modelo central federado.

**Principais linhas de pesquisa:**

> - Modelagem da Informação da Construção (BIM): Gestão de ciclo de vida de edificações (4D, 5D e 6D) e interoperabilidade entre softwares de engenharia.

> - Gêmeos Digitais (Digital Twins): Criação de réplicas virtuais de infraestruturas físicas integradas a sensores IoT para monitoramento em tempo real.

> - Inteligência Artificial Aplicada: Otimização de cronogramas de obras e análise preditiva de patologias em estruturas através de algoritmos de visão computacional.

> - Simulação de Eficiência Energética: Análise de desempenho térmico e lumínico de materiais e projetos arquitetônicos.

**Infraestrutura computacional:**

> - Estações de Trabalho (VLAN 30): PCs de alto desempenho equipados com GPUs dedicadas para renderização em tempo real e processamento de modelos paramétricos (ex: nó Lab_IA_PVB8448).

> - Conectividade: Link dedicado ao Switch Core com priorização de pacotes para o segmento de processamento gráfico pesado.

> - Armazenamento Centralizado: Acesso direto via rede interna ao Central_Storage_NAS (VLAN 100) para backup de arquivos de nuvem de pontos (Point Cloud) e repositórios de projetos legados.

> - Segurança: Proteção por firewall de borda para colaboração externa segura com parceiros e escritórios remotos de engenharia.

**Site do laboratório:**

* IP / Endpoint AWS: `18.206.233.81`

---

### 4️⃣ Engenharia e Energia – LABENGE

**Descrição técnica do laboratório:**

> Laboratório voltado ao desenvolvimento de pesquisas aplicadas nas áreas de engenharia e energia, com foco em sistemas térmicos, eficiência energética, refrigeração e soluções tecnológicas voltadas a contextos industriais e comunidades isoladas. O LABENGE atua integrando modelagem matemática, simulação computacional, prototipagem e análise experimental.

**Principais linhas de pesquisa:**

- Sistemas de Refrigeração e Ciclos Termodinâmicos Alternativos.

- Eficiência Energética e Otimização de Sistemas Térmicos.

- Desenvolvimento de Protótipos de Engenharia Aplicada.

- Tecnologias Energéticas para Comunidades Isoladas e Sustentabilidade.

**Infraestrutura computacional:**

> Servidor para simulação e armazenamento de dados experimentais, estações de trabalho para modelagem e análise numérica (MATLAB, Octave, Python), softwares de simulação termodinâmica e ferramentas CAD/CAE. A infraestrutura suporta também hospedagem de sistemas web para divulgação de projetos, repositórios de dados e documentação técnica.

**Site do laboratório:**

* IP / Endpoint AWS: `52.90.126.112`

---

### 5️⃣ Argumentação, Inclusão e Educação Matemática

**Descrição técnica do laboratório:**

> Grupo criado em 2013, vinculado ao DMA/UFS. Ele produz reflexões e práticas sobre usos da argumentação no ensino de matemática.

**Principais linhas de pesquisa:**

> Possui três linhas voltadas ao estudo e às práticas dos usos da argumentação no ensino de matemática, com foco nos níveis fundamental e médio e investigação sobre ensino superior.

**Infraestrutura computacional:**

> O condomínio de laboratórios contará com uma infraestrutura computacional composta por servidor de uso compartilhado, equipamentos de rede, estações de trabalho, notebooks e computadores, assim garantindo suporte às atividades de pesquisa, ensino e desenvolvimento tecnológico.

**Site do laboratório:**

* IP / Endpoint AWS: `http://100.52.71.56`
---

### 6️⃣ Geoplan – Geoecologia e Planejamento Territorial

**Descrição técnica do laboratório:**

> O GEOPLAN (Grupo de Pesquisa em Geoecologia e Planejamento Territorial), certificado pelo CNPq desde 2006, dedica-se à investigação da dinâmica biofísica de ambientes naturais e modificados. O laboratório atua como um centro avançado de processamento de geoinformação, integrando dados ambientais massivos para subsidiar o planejamento territorial, gestão de bacias hidrográficas e políticas públicas de saúde e meio ambiente.

**Principais linhas de pesquisa:**

> - **Geografia da Saúde:** Mapeamento de riscos e condicionantes socioambientais (Esquistossomose/Dengue) na Grande Aracaju (ex: Projetos PVD5115 e PVD3270).
> - **Planejamento Territorial:** Zoneamento de Unidades de Conservação e mapeamento de uso do solo (ex: RPPN em Glória/SE - PVJ6561).
> - **Geobiodiversidade:** Análise de serviços ecossistêmicos e patrimônio hidrológico.
> - **Geotecnologias:** Uso de WebGIS e bancos de dados espaciais para gestão ambiental e cooperação internacional (UFS/Coimbra).

**Infraestrutura computacional:**

> O laboratório conta com infraestrutura "Enterprise" para suportar o tráfego pesado de imagens de satélite e ortofotos. O núcleo é composto por um servidor rodando banco de dados **PostGIS** e containers **Docker**. A conectividade é garantida por Switch Core de alta densidade, assegurando mobilidade e performance para modelagem SIG.

**Site do laboratório:**

* IP / Endpoint AWS: `3.238.250.177`

---

## 📁 Estrutura do Repositório

Este repositório armazena os seguintes materiais:

* 📊 **Planilha de orçamento**
  Contém os custos estimados da infraestrutura, com **links para registros de atas e decisões administrativas**.

* 🗺️ **Documento PDF – Mapa Físico**
  Planta física do condomínio de laboratórios, incluindo:
  * Sala de servidores;
  * Laboratórios individuais;
  * Cabeamento estruturado;
  * Pontos de rede e Wi‑Fi.

* 🧾 **Lista de dispositivos**
  Relação de equipamentos utilizados no condomínio, como:
  * Switches (L2/L3);
  * Access Points;
  * Servidores;
  * Racks;
  * Equipamentos específicos de cada laboratório.

---

## 🏗️ Visão Geral da Infraestrutura

* Arquitetura em **modelo de condomínio**, com infraestrutura compartilhada e segmentação lógica;
* Switches gerenciáveis por laboratório;
* VLANs para isolamento de tráfego;
* Servidor(es) central(is) para serviços comuns (web, banco de dados, backup, autenticação);
* Autonomia para cada laboratório conectar seus próprios dispositivos e servidores internos.

---

## 📌 Observações Finais

* Cada laboratório é responsável por manter **atualizada sua própria seção** neste README;
* As informações aqui descritas servem como **documentação técnica e institucional**;
* Este repositório pode ser utilizado como base para auditorias, apresentações acadêmicas e evolução futura da infraestrutura.

---

**Condomínio de Laboratórios de Pesquisa – CCET/UFS**
*UFS – Universidade Federal de Sergipe*
