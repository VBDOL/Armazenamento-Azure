# 🚀 Dominando o Armazenamento na Azure

## 📌 Introdução
Este repositório documenta os principais conceitos explorados no laboratório **Dominando o Armazenamento na Azure**, incluindo criação, configuração e gerenciamento de **contas de armazenamento**, além de redundância, segurança, transferência de dados e otimização de custos.

## 📚 O que aprendi

### 🏗️ Criação e Configuração de Contas de Armazenamento
- O nome da conta de armazenamento deve ser **globalmente exclusivo**.
- Pode ser criada via **Portal do Azure, CLI, PowerShell** ou **ARM Templates**.
- O armazenamento pode ser configurado em diferentes **camadas** (Standard/Premium).
- Modelos de **redundância** garantem proteção contra falhas.

### 🔄 Modelos de Redundância
O **Azure Storage** oferece várias opções para garantir alta disponibilidade:
- LRS (Locally Redundant Storage) → Replicação dentro do mesmo datacenter, com durabilidade de **11 noves**.
- ZRS (Zone-Redundant Storage) → Replicação entre zonas dentro da mesma região.
- GRS (Geo-Redundant Storage) → Replicação entre regiões geográficas diferentes.
- GZRS (Geo-Zone-Redundant Storage) → Combina zoneamento e replicação geográfica.

### 📦 Transferência de Dados
Quando é necessário mover grandes volumes de dados, algumas opções são:
- Azure Data Box → Melhor para transferências acima de **60TB**, usando dispositivos físicos.
- AzCopy → Ferramenta de linha de comando para copiar blobs e arquivos rapidamente.
- ExpressRoute → Solução de **conexão privada** para transferência de grandes volumes de dados.

### 🛡️ Governança e Segurança
O gerenciamento eficaz de **recursos de armazenamento** no Azure inclui:
- Azure Policy → Define regras e conformidade para garantir governança.
- Marcas do Azure → Organiza recursos logicamente através de **tags**.
- Bloqueios de Recursos → Protege contra alterações acidentais ou exclusões indevidas.

### 💰 Otimização de Custos
- Calculadora de Preços do Azure → Estima os custos associados às configurações selecionadas.
- Calculadora de TCO (Total Cost of Ownership) → Compara custos de infraestrutura local e nuvem.
- Instâncias Reservadas → Redução de custos ao se comprometer com serviços por períodos de **1 ou 3 anos**.

## 🔗 Link do Repositório
[Adicionar link do repositório GitHub aqui]

## 🎯 Conclusão
Este laboratório consolidou o conhecimento sobre **armazenamento na nuvem**, aprimorando práticas de **governança, custos e segurança** no Azure. Os conceitos aprendidos permitem a criação de soluções eficientes e escaláveis para diferentes necessidades empresariais.

---

🔥 **Feito com dedicação para aprimorar habilidades no Microsoft Azure!** 🚀
