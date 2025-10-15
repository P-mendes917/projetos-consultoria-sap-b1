# 🧩 Projetos de Consultoria SAP Business One


Repositório contendo o portfólio de projetos desenvolvidos em **C# / .NET** com foco em **integrações e add-ons para o SAP Business One**, abrangendo automações, portais, APIs RESTful e soluções corporativas.

Os projetos foram implementados em diferentes empresas de consultoria SAP, atendendo diversos segmentos de negócio, com uso de tecnologias modernas e práticas avançadas de integração e arquitetura.

#### Note: The original source codes and repositories are the property of the company and cannot be publicly shared. The information provided here is generic, focusing on my technical contributions.
---

## 🏢 Empresa: **Neocantra**


### 🌐 **Portais**

#### 🔸 Portal de Canais  
Portal interno para que os canais da consultoria visualizassem a tabela de preços das licenças SAP Business One ofertadas.  
**🔧 Tecnologias:** C#, .NET Framework 4.8, Gvince Framework.

---

## 🏢 Empresa: **B2Finance**


### ⚙️ **Serviços**

#### 🔸 Serviço de Rateio CTe  
Realiza o rateio do valor do CTe conforme os centros de custo do LCM da nota de saída.  
**🔧 Tecnologias:** C#, .NET Framework 4.8, SAP DI API.

#### 🔸 Serviço de E-mails  
Envio automático de e-mails de cobrança de faturas vencidas e a vencer.  
**🔧 Tecnologias:** C#, .NET 7, SMTP.

#### 🔸 Serviço de Inserção de Documentos Aprovados  
Realiza a inserção automática de esboços de documentos aprovados em fluxos de aprovação.  
**🔧 Tecnologias:** C#, .NET 8, B1SLayer.

---

### 🔗 **APIs**

#### 🔸 Integração SAP Ariba  
Integra esboços de pedidos de venda do SAP Business One com o sistema de compras **SAP Ariba**.  
**🔧 Tecnologias:** C#, .NET 7, B1SLayer, SAP HANA Core 2.

#### 🔸 Integração SAP e Sistema Kisense  
Integra notas de saída do SAP com o sistema de gestão de energia **Kisense**.  
**🔧 Tecnologias:** C#, .NET 6, Service Layer, SAP HANA.

#### 🔸 Integração SAP e Sistema Flash Expense  
Integra notas de entrada do SAP com o sistema de gestão de despesas **Flash Expense**.  
**🔧 Tecnologias:** C#, .NET 6, Service Layer.

#### 🔸 Integração SAP e Sistema Varitus  
Integra notas e XMLs do sistema **Varitus** para o SAP Business One (tabelas independentes).  
**🔧 Tecnologias:** C#, .NET 6, HANA, Service Layer.

#### 🔸 Integração SAP e Sistema FM Logistic  
Integra pedidos de venda, lista de picking e recebimento de mercadorias a partir de arquivos `.txt` do sistema **FM Logistic**.  
**🔧 Tecnologias:** C#, .NET 6, File Processing, Service Layer.

#### 🔸 Integração SAP e HubSpot  
Notifica a API do **HubSpot** sobre novos pedidos de venda ou atualizações.  
**🔧 Tecnologias:** C#, .NET 7, Service Layer, HubSpot API.

#### 🔸 API de Parceiros de Negócios (PNs)  
Criação e atualização de parceiros de negócio no SAP Business One via API RESTful.  
**🔧 Tecnologias:** C#, .NET 6, Service Layer.

#### 🔸 API de Boleto e Nota Fiscal  
Retorna o **Base64** do PDF do boleto e da nota fiscal de saída a partir do `DocEntry`.  
**🔧 Tecnologias:** C#, .NET 6, Service Layer.

#### 🔸 API de Pagamentos  
Disponibiliza o status de pagamento das notas fiscais de saída dos clientes.  
**🔧 Tecnologias:** C#, .NET 7, B1SLayer, HANA.

---

### 🧩 **Add-ons**

#### 🔸 Add-on de Seleção de Lote  
Seleção automática de lotes conforme a regra **FEFO (First Expired, First Out)**.  
**🔧 Tecnologias:** C#, DI API, UI API.

#### 🔸 Add-on Importador de LCM  
Importação de lançamentos contábeis manuais a partir de planilhas Excel.  
**🔧 Tecnologias:** C#, Service Layer, UI API.

#### 🔸 Add-on de Folha de Pagamento  
Integração com sistemas de folha de pagamento via arquivos `.txt`, permitindo geração e importação de LCM/Pré-LCM.  
**🔧 Tecnologias:** C#, DI API, UI API, Service Layer.

#### 🔸 Add-on de Gestão de Orçamento  
Gestão orçamentária com base nas regras americanas de exercício contábil (Nov/2024).  
**🔧 Tecnologias:** C#, DI API, UI API.

#### 🔸 Add-on de Item Alternativo  
Auxilia na escolha de itens alternativos em pedidos de venda e compra, exibindo informações de estoque.  
**🔧 Tecnologias:** C#, DI API, UI API.

#### 🔸 Add-on de Fluxo de Caixa  
Geração do fluxo de caixa por conta contábil e centro de custo em um período específico.  
**🔧 Tecnologias:** C#, DI API, UI API.

#### 🔸 Add-on de Encerramento de Período  
Realiza o fechamento de períodos contábeis agrupados por centro de custo.  
**🔧 Tecnologias:** C#, DI API, UI API.

#### 🔸 Add-on de Integração de Estoque  
Integra quantidades de estoque internacional dos itens do SAP.  
**🔧 Tecnologias:** C#, Service Layer, DI API.

#### 🔸 Add-on de Cálculo de Juros  
Calcula juros com base na condição de pagamento e aplica o valor na nota como despesa adicional.  
**🔧 Tecnologias:** C#, DI API, UI API.

#### 🔸 Add-on Mala Direta  
Automatiza o envio de e-mails de faturamento, cobrança e comunicações preventivas com templates customizados.  
**🔧 Tecnologias:** C#, DI API, UI API.

#### 🔸 Add-on Replicante  
Replica contas contábeis entre diferentes bases do SAP Business One.  
**🔧 Tecnologias:** C#, DI API.

#### 🔸 Add-on de Gestão Inteligente de Documentos  
Realiza inserção de notas fiscais de entrada a partir de PDFs, com integração OCR e IA para extração e mapeamento de dados.  
**🔧 Tecnologias:** C#, .NET 7, OCR API, SQL Server, Service Layer.

---

## 🏢 Empresa: **NEXX Consulting**


### 🌐 **Portais**

#### 🔸 Portal de Apontamentos  
Portal para controle e registro de apontamentos de horas e tarefas internas.  
**🔧 Tecnologias:** Angular 19, TypeScript.

---

### ⚙️ **Serviços**

#### 🔸 Integração SAP e Sistema SAWLUZ  
Integra pedidos e cotações de vendas com o sistema logístico **SAWLUZ** via arquivos `.txt`.  
**🔧 Tecnologias:** C#, .NET 8, File System Integration, Service Layer.

#### 🔸 Integração SAP e Sistema CORPEM  
Integra itens, notas de saída, pedidos e devoluções entre SAP e **CORPEM**.  
**🔧 Tecnologias:** C#, .NET 8, Service Layer, SAP HANA.

#### 🔸 Integração SAP e Salesforce  
Integra parceiros, itens, formas e condições de pagamento, lista de preços, estoque e pedidos entre SAP e **Salesforce**.  
**🔧 Tecnologias:** C#, .NET 8, Service Layer, Salesforce API.

---

### 🔗 **APIs**

#### 🔸 Integração Salesforce e SAP  
API bidirecional para sincronização de parceiros, pedidos e estoque entre **Salesforce** e SAP Business One.  
**🔧 Tecnologias:** C#, .NET 8, REST API, Salesforce SDK.

#### 🔸 API CrystalReports  
API para geração e impressão de relatórios **Crystal Reports** em PDF sob demanda.  
**🔧 Tecnologias:** C#, .NET 8, Crystal Reports SDK.

---



## 📚 **Tecnologias Principais Utilizadas**


**Linguagens:**  
> C#, TypeScript  

**Frameworks:**  
> .NET Framework 4.8, .NET 6, .NET 7, .NET 8, Angular 19  

**SAP B1 APIs:**  
> DI API, UI API, Service Layer, B1SLayer  

**Bancos de Dados:**  
> SAP HANA, SQL Server  
