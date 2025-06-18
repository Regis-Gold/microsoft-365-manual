Na guia **"Equipes"** do Microsoft Teams, os **administradores** (com permissões via *Microsoft 365 Admin Center* ou *Teams Admin Center*) têm acesso a opções exclusivas de gerenciamento que não estão disponíveis para usuários comuns.

---

### **Opções Exclusivas para Administradores na Guia "Equipes"**  
#### **1. Gerenciamento Centralizado de Todas as Equipes**  
- **Visão Global:**  
  - Lista completa de todas as equipes da organização, incluindo ocultas ou arquivadas.  
- **Filtros Avançados:**  
  - Filtrar por status (*Ativa*, *Arquivada*), tipo (*Pública*, *Privada*, *MSOwned*), ou data de criação.  

#### **2. Ações em Massa**  
- **Seleção Múltipla:**  
  - Aplicar ações simultâneas em várias equipes (ex.: arquivar, restaurar, excluir).  
- **Exportar Dados:**  
  - Gerar relatórios em CSV com detalhes (proprietários, membros, status).  

#### **3. Configurações Avançadas por Equipe**  
Ao clicar em uma equipe específica → **"⋯" (Mais opções)**:  
- **Editar Equipe como Admin:**  
  - Alterar tipo (Pública/Privada), adicionar/remover proprietários **sem ser membro**.  
- **Gerenciar Membros em Lote:**  
  - Adicionar/remover múltiplos usuários via lista ou grupos do Active Directory.  
- **Políticas de Expiração:**  
  - Definir renovação automática (ex.: equipe expira após 180 dias se inativa).  

#### **4. Templates de Equipe**  
- **Aplicar Templates Pré-Definidos:**  
  - Usar modelos padronizados (ex.: "Projeto", "Incidente Crítico") com canais, apps e políticas pré-configuradas.  
- **Criar Templates Personalizados:**  
  - Desenvolver modelos específicos para a organização (via *Teams Admin Center*).  

#### **5. Políticas de Conformidade e Governança**  
- **Política de Nomenclatura:**  
  - Impor prefixos/sufixes obrigatórios no nome das equipes (ex.: `GRP_ProjetoX`).  
- **Restrições de Criação:**  
  - Limitar criação de equipes a grupos específicos (ex.: apenas líderes de departamento).  
- **Retenção de Dados:**  
  - Aplicar políticas de retenção/exclusão automática de mensagens e arquivos.  

#### **6. Auditoria e Monitoramento**  
- **Logs de Atividade:**  
  - Acessar histórico de modificações (ex.: quem adicionou membros, alterou configurações).  
- **Relatórios de Uso:**  
  - Ver métricas de engajamento (mensagens por canal, atividade de arquivos) por equipe.  

#### **7. Recuperação e Restauração**  
- **Restaurar Equipes Excluídas:**  
  - Recuperar equipes apagadas (até 30 dias após exclusão).  
- **Arquivamento:**  
  - Colocar equipes inativas em "modo arquivo" (bloqueia edições, mantém dados).  

---

### **Como Acessar?**  
- **Pré-requisito:**  
  - Permissões de **Administrador Global**, **Administrador do Teams** ou **Administrador de Serviços do Teams** no *Microsoft 365 Admin Center*.  
- **Localização:**  
  - Abra o Teams → Guia **"Equipes"** → Botão **"Gerenciar equipes"** (visível apenas para admins).  

---

### **Resumo das Opções Exclusivas para Admins:**  
| **Recurso**                     | **Funcionalidade**                                  |  
|---------------------------------|-----------------------------------------------------|  
| **Gerenciamento em Massa**      | Ações simultâneas em múltiplas equipes              |  
| **Edição Forçada**              | Modificar qualquer equipe sem ser membro            |  
| **Templates Personalizados**    | Padronizar estrutura de equipes                     |  
| **Políticas de Nomenclatura**   | Impor regras de nomes (ex.: `DEP_Marketing`)        |  
| **Expiração Automática**        | Renovar/excluir equipes inativas automaticamente    |  
| **Restauração de Equipes**      | Recuperar equipes excluídas                         |  
| **Relatórios de Auditoria**     | Rastrear alterações e atividade                     |  

---

### **⚠️ Importante:**  
- Essas opções **não aparecem para usuários comuns**, mesmo que sejam "proprietários" de uma equipe.  
- Configurações como *políticas de nomenclatura* ou *restrição de criação* são definidas no **Teams Admin Center**, mas aplicadas e monitoradas na guia "Equipes".