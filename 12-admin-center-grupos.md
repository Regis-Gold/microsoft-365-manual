Na guia **Grupos** do **Microsoft 365 Admin Center**, podemos encontrar opções para gerenciar diferentes tipos de grupos, as configurações, membros e políticas. Abaixo temos uma descrição detalhada das principais funcionalidades disponíveis nessa guia:

---

### **1. Tipos de Grupos Gerenciáveis**  
- **Grupos do Microsoft 365** (antigos "Grupos do Office 365"):  
  - Criar grupos para colaboração (inclui caixa de correio, site do SharePoint, bloco de notas do OneNote e equipe do Teams).  
  - Editar nome, descrição, privacidade (público/privado) e endereço de email.  
  - Gerenciar membros (adicionar/remover usuários ou convidados).  
  - Habilitar/desabilitar a opção de **Teams** vinculado ao grupo.  

- **Grupos de distribuição**:  
  - Criar listas de email para comunicação em massa.  
  - Definir se membros externos podem enviar emails para o grupo.  
  - Configurar aprovação de mensagens (moderação).  

- **Grupos de segurança**:  
  - Gerenciar acesso a recursos (ex: SharePoint, aplicativos).  
  - Associar licenças em massa a membros do grupo.  

- **Grupos de segurança habilitados para email** (Mail-enabled Security Groups):  
  - Combina funcionalidades de grupos de segurança e de distribuição.  

---

### **2. Ações Específicas por Grupo**  
- **Adicionar grupo**: Escolher o tipo (Microsoft 365, distribuição, segurança, etc.) e configurar parâmetros iniciais.  
- **Editar grupo**:  
  - Alterar tipo de grupo (se permitido).  
  - Adicionar/remover proprietários e membros.  
  - Configurar **assinatura de email** (para grupos de distribuição).  
  - Ativar/desativar **acesso externo** (permitir que convidados sejam membros).  
- **Excluir grupo**: Remove o grupo (pode ser restaurado dentro de 30 dias).  
- **Restaurar grupo**: Recupera grupos excluídos recentemente.  
- **Renomear grupo**: Atualizar nome e endereço de email.  

---

### **3. Configurações de Associação**  
- **Membros**:  
  - Adicionar/remover usuários ou grupos aninhados.  
  - Definir **membros dinâmicos** (grupos de segurança com regras baseadas em atributos do Azure AD, como departamento ou localização).  
- **Proprietários**:  
  - Designar usuários responsáveis por gerenciar o grupo.  
  - Limitar o número de proprietários.  

---

### **4. Políticas e Compliance**  
- **Política de expiração**:  
  - Definir tempo de expiração para grupos do Microsoft 365 (ex: 180 dias).  
  - Renovar grupos automaticamente se houver atividade.  
- **Política de nomenclatura**:  
  - Aplicar prefixos/sufixos padrão (ex: "GRP_*" ou "Sales_*").  
  - Bloquear palavras específicas em nomes de grupos.  
- **Classificação de sensibilidade**:  
  - Atribuir rótulos de sensibilidade (ex: "Confidencial", "Público") para controlar acesso.  

---

### **5. Configurações de Convidados (Guest Access)**  
- **Permitir convidados**: Habilitar/desabilitar a adição de usuários externos ao grupo.  
- **Restrições de domínio**: Bloquear convites para domínios específicos.  
- **Aprovação de convidados**: Exigir aprovação do proprietário para adicionar convidados.  

---

### **6. Ações em Massa**  
- **Selecionar múltiplos grupos**:  
  - Excluir vários grupos simultaneamente.  
  - Atribuir políticas de expiração em massa.  
- **Exportar lista de grupos**: Gerar CSV com detalhes (nome, tipo, proprietários, etc.).  

---

### **7. Recursos Vinculados**  
- **Gerenciar Teams**: Para grupos do Microsoft 365 vinculados a uma equipe, redireciona para o **Teams Admin Center**.  
- **Gerenciar SharePoint**: Acessar o site do SharePoint associado ao grupo.  
- **Relatórios de atividade**: Ver métricas de uso (ex: mensagens no Teams, arquivos no SharePoint).  

---

### **8. Configurações Específicas para Grupos do Microsoft 365**  
- **Caixa de correio compartilhada**: Converter um grupo em caixa de correio compartilhada (via **Exchange Admin Center**).  
- **Arquivo morto**: Preservar dados do grupo após exclusão (configurar retenção).  
- **Preferências de email**:  
  - Permitir que membros externos enviem emails para o grupo.  
  - Habilitar cópias de email para proprietários/membros.  

---

### **9. Aprovação de Solicitações**  
- **Política de associação**:  
  - Exigir aprovação para ingressar em grupos públicos.  
  - Definir approvers (proprietários ou usuários específicos).  

---

### **Observações Importantes:**  
- Algumas configurações avançadas (ex: regras de associação dinâmica, políticas de acesso condicional) exigem acesso ao **Azure Active Directory**.  
- Grupos de distribuição clássicos devem ser gerenciados via **Exchange Admin Center**.  
- A restauração de grupos excluídos só é possível dentro de **30 dias**.  

Essas opções permitem gerenciar colaboração, segurança e comunicação de forma centralizada, garantindo conformidade com políticas organizacionais.