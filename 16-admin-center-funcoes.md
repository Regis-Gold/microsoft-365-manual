Na guia **Funções** do **Microsoft 365 Admin Center**, podemos gerenciar permissões administrativas por meio do **controle de acesso baseado em função (RBAC)**. Essa guia permite configurar quem tem acesso a recursos críticos e quais ações podem ser executadas.

---

### **1. Funções Internas (Built-in Roles)**  
- **Visualizar funções padrão**:  
  - Lista de funções pré-definidas pela Microsoft (ex: **Administrador Global**, **Administrador de Teams**, **Administrador de Licenças**).  
  - Detalhes das permissões associadas a cada função (ex: "Administrador de Segurança" pode gerenciar políticas de segurança).  
- **Atribuir/Remover funções**:  
  - Adicionar ou remover usuários/grupos de funções específicas.  
  - Limitar o escopo de atuação (ex: restringir um administrador a gerenciar apenas usuários de um departamento).  

---

### **2. Funções Personalizadas (Custom Roles)**  
- **Criar funções personalizadas**:  
  - Definir permissões granulares combinando ações específicas (ex: permitir "resetar senhas" sem acesso a configurações de segurança).  
  - Escolher serviços afetados (ex: Exchange Online, Azure AD, SharePoint).  
- **Editar ou Excluir funções**:  
  - Modificar permissões de funções personalizadas existentes.  
  - Excluir funções não utilizadas.  

---

### **3. Grupos de Funções (Role Groups)**  
- **Criar grupos de funções**:  
  - Combinar múltiplas funções (internas ou personalizadas) em um único grupo para facilitar a atribuição (ex: grupo "Suporte Técnico" com funções de resetar senhas e gerenciar licenças).  
- **Gerenciar membros**:  
  - Adicionar/remover usuários ou grupos de segurança a um grupo de funções.  

---

### **4. Privileged Identity Management (PIM)**  
- **Ativação Just-in-Time**:  
  - Configurar elevação temporária de privilégios (ex: permitir que um usuário atue como "Administrador Global" por 2 horas).  
  - Exigir aprovação para ativação de funções sensíveis.  
- **Revisões de acesso**:  
  - Agendar revisões periódicas para verificar se as atribuições de função ainda são necessárias.  

---

### **5. Auditoria de Atribuições**  
- **Ver histórico de alterações**:  
  - Auditoria de quem atribuiu/removeu funções ou grupos de funções.  
  - Acessar logs detalhados no **Centro de Conformidade** (link integrado).  

---

### **6. Delegar Permissões Administrativas**  
- **Delegação granular**:  
  - Permitir que usuários gerenciem funções específicas sem acesso total (ex: delegar apenas a função "Administrador de Usuários").  
- **Escopo administrativo**:  
  - Restringir administradores a um conjunto específico de usuários ou grupos (ex: somente usuários do departamento de RH).  

---

### **7. Configurações de Segurança Relacionadas**  
- **Exigir MFA para funções administrativas**:  
  - Forçar autenticação multifator para qualquer usuário com funções privilegiadas.  
- **Alertas de risco**:  
  - Configurar notificações para atividades suspeitas envolvendo contas administrativas (ex: login incomum).  

---

### **8. Relatórios de Atribuição**  
- **Exportar lista de funções**:  
  - Gerar relatórios em CSV/PDF com todas as atribuições de funções e grupos.  
- **Verificar sobreposições de permissões**:  
  - Identificar conflitos entre funções internas e personalizadas.  

---

### **Observações Importantes:**  
1. **Pré-requisitos**:  
   - **Azure AD Premium P2** é necessário para usar **Privileged Identity Management (PIM)**.  
   - Funções personalizadas exigem licenças **Microsoft 365 Enterprise E5** ou **Azure AD Premium**.  

2. **Acesso Crítico**:  
   - A função **Administrador Global** não pode ser restrita por escopo e tem acesso irrestrito a todo o tenant.  

3. **Boas Práticas**:  
   - Use o **Princípio do Menor Privilégio** para minimizar riscos de segurança.  
   - Revise regularmente atribuições de funções com **Revisões de Acesso**.  

---

### **Ações Rápidas na Interface:**  
- **Pesquisar funções** por nome ou descrição.  
- **Filtrar funções** por categoria (ex: "Administração", "Segurança").  
- **Ver usuários atribuídos** a uma função em tempo real.  

---

Essas opções permitem controlar rigorosamente quem tem acesso administrativo, reduzindo riscos de segurança e garantindo conformidade com políticas internas. Para configurações avançadas (ex: políticas de acesso condicional), você será redirecionado ao **Azure AD** ou **Centro de Segurança**.