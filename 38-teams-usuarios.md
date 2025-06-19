Na guia **"Usuários"** do Microsoft Teams (acessível **apenas para administradores** com permissões adequadas), você encontra funcionalidades avançadas de gerenciamento de contas, licenças e políticas.

---

### **📍 Como Acessar?**  
- **Pré-requisito**:  
  - Permissões de **Administrador Global**, **Administrador de Teams** ou **Administrador de Utilizadores** no [Microsoft 365 Admin Center](https://admin.microsoft.com).  
- **Localização**:  
  - Painel lateral esquerdo do Teams → Guia **"Usuários"** (visível apenas para admins).  

---

### **🔧 Opções Exclusivas para Administradores na Guia "Usuários":**  
#### **1. Gerenciamento Centralizado de Usuários**  
- **Filtros Avançados**:  
  - Buscar usuários por nome, e-mail, departamento ou status (*Ativo*, *Bloqueado*).  
- **Ações em Massa**:  
  - Selecionar múltiplos usuários para aplicar ações simultâneas (ex.: atribuir licenças, resetar senha).  

#### **2. Edição de Perfis**  
- **Modificar Propriedades**:  
  - Editar informações como:  
    - Nome, cargo, departamento.  
    - Número de telefone, localização.  
    - Foto do perfil (em massa via PowerShell).  
- **Definir Manager (Gestor)**:  
  - Vincular usuários a um gestor para hierarquia organizacional.  

#### **3. Atribuição de Licenças**  
- **Atribuir/Remover Licenças**:  
  - Licenças do Microsoft 365 (ex.: Teams Premium, E5).  
  - Licenças de add-ons (ex.: Audio Conferencing, Power BI).  
- **Verificar Uso de Licenças**:  
  - Monitorar licenças atribuídas vs. disponíveis.  

#### **4. Controle de Acesso e Segurança**  
- **Reset de Senha**:  
  - Forçar redefinição de senha (com notificação por e-mail).  
- **Bloquear/Desbloquear Acesso**:  
  - Impedir login no Teams e serviços Microsoft 365.  
- **Forçar Logoff**:  
  - Desconectar sessões ativas do usuário.  

#### **5. Políticas de Teams**  
- **Aplicar Políticas Personalizadas**:  
  - **Políticas de Reunião**: Restringir gravações, lobby, compartilhamento de tela.  
  - **Políticas de Mensagens**: Limitar edição/exclusão de mensagens, GIFs, memes.  
  - **Políticas de Aplicativos**: Bloquear apps específicos (ex.: Trello, Adobe).  

#### **6. Grupos e Filiação**  
- **Adicionar/Remover de Grupos**:  
  - Grupos do Microsoft 365, Grupos de Segurança ou Teams existentes.  
- **Criar Grupos Diretamente**:  
  - Iniciar novo grupo com usuários selecionados.  

#### **7. Auditoria e Relatórios**  
- **Logs de Atividade**:  
  - Ver histórico de ações do usuário (ex.: logins, chamadas, compartilhamentos).  
- **Relatórios de Uso**:  
  - Acessar dados de atividade no Teams (mensagens, reuniões, minutos em chamadas).  

#### **8. Delegação de Funções**  
- **Adicionar Proprietários de Equipe**:  
  - Designar usuários como "proprietários" de equipes específicas.  
- **Atribuir Funções de Admin**:  
  - Promover para funções limitadas (ex.: Administrador de Suporte).  

---

### **⚙️ Ações por Usuário (Menu "⋯")**  
Ao clicar em um usuário → **"⋯" (Mais opções)**:  
| **Opção**                  | **Descrição**                                      |  
|----------------------------|---------------------------------------------------|  
| **Editar perfil**          | Alterar detalhes do usuário (cargo, departamento). |  
| **Resetar senha**          | Gerar senha temporária.                           |  
| **Gerenciar licenças**     | Adicionar/remover licenças do M365.               |  
| **Bloquear sign-in**       | Impedir acesso a todos os serviços.               |  
| **Ver grupos**             | Listar grupos aos quais o usuário pertence.        |  
| **Aplicar políticas**      | Atribuir políticas de comunicação/reunião.        |  

---

### **🚫 Limitações Importantes:**  
- **Não substitui o Admin Center**:  
  - Ações complexas (ex.: criar políticas personalizadas, fluxos de trabalho) exigem o [Teams Admin Center](https://admin.teams.microsoft.com) ou [Microsoft 365 Admin Center](https://admin.microsoft.com).  
- **Permissões Granulares**:  
  - Algumas opções dependem do tipo de perfil de admin (ex.: resetar senha exige "Administrador de Suporte").  

---

### **Resumo das Opções Exclusivas:**  
| **Recurso**                  | **Finalidade**                                  | **Onde Configurar?**       |  
|------------------------------|-----------------------------------------------|---------------------------|  
| Atribuição de licenças       | Gerenciar produtos Microsoft 365 por usuário. | Guia "Usuários" do Teams  |  
| Reset de senha               | Redefinir credenciais sem acesso ao M365 Admin| Guia "Usuários" do Teams  |  
| Bloquear sign-in             | Revogar acesso emergencial.                   | Guia "Usuários" do Teams  |  
| Políticas de Teams           | Restringir funcionalidades por usuário.       | Guia "Usuários" do Teams  |  
| Auditoria de atividade       | Monitorar ações individuais.                 | Teams Admin Center (web) |  

> **📌 Nota**: Para recursos avançados (ex.: políticas de retenção, conformidade com GDPR), use sempre o **Teams Admin Center** via navegador.