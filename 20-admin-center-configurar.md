Na guia **Configurar** do **Microsoft 365 Admin Center**, podemos encontrar opções para ajustar configurações globais da organização, personalizar comportamentos padrão e habilitar/desabilitar serviços específicos. Essa guia concentra-se em configurações organizacionais que impactam **todos os usuários ou serviços**.

---

### **1. Perfil da Organização**  
- **Editar informações da organização**:  
  - Atualizar nome, endereço, telefone e contato técnico.  
  - Definir idioma padrão e fuso horário.  
- **Configurar região geográfica de dados**:  
  - Especificar a localização de armazenamento de dados (ex: SharePoint, OneDrive).  

---

### **2. Segurança Básica**  
- **Proteções de segurança padrão**:  
  - Habilitar/desabilitar **Autenticação Multifator (MFA)** para todos os usuários.  
  - Forçar redefinição de senha periódica.  
- **Bloquear autenticação legada**:  
  - Impedir protocolos antigos (ex: POP3, IMAP) para aumentar a segurança.  

---

### **3. Serviços e Suplementos**  
- **Gerenciar serviços integrados**:  
  - Habilitar/desabilitar serviços como **Microsoft Bookings**, **Forms**, **Sway** ou **Planner**.  
  - Restringir criação de formulários ou reservas a grupos específicos.  
- **Aplicativos do Office na web**:  
  - Ativar/desativar acesso a aplicativos como **Power Automate** ou **Power Apps** para usuários finais.  

---

### **4. Domínios Personalizados**  
- **Adicionar/verificar domínios**:  
  - Associar domínios personalizados (ex: `suaempresa.com`) ao Microsoft 365.  
  - Configurar registros DNS (MX, TXT, CNAME) para validação.  
- **Gerenciar domínios existentes**:  
  - Renovar ou remover domínios não utilizados.  

---

### **5. Relacionamento com Parceiros**  
- **Adicionar parceiros de suporte (CSP)**:  
  - Delegar acesso administrativo a provedores de serviços em nuvem.  
  - Revogar permissões de parceiros.  

---

### **6. Configurações de Dispositivos Móveis**  
- **Acesso básico a dispositivos**:  
  - Permitir ou bloquear sincronização de emails/arquivos em dispositivos não gerenciados.  
  - Definir requisitos mínimos de sistema operacional (ex: iOS 14+).  

---

### **7. Personalização da Marca**  
- **Personalização da página de login**:  
  - Adicionar logotipo, cores corporativas e texto personalizado à tela de login do Azure AD.  
  - Configurar mensagens legais (ex: termos de uso) exibidas durante o login.  
- **Tema do Admin Center**:  
  - Alterar cores e logotipo exibido no painel administrativo.  

---

### **8. Configurações de Colaboração**  
- **Compartilhamento externo**:  
  - Definir padrões globais para compartilhamento no **SharePoint**, **OneDrive** e **Teams**.  
  - Bloquear domínios específicos (ex: `concorrente.com`).  
- **Criação de grupos**:  
  - Restringir a criação de grupos a administradores ou usuários selecionados.  

---

### **9. Configurações de Acessibilidade**  
- **Modo de alto contraste**:  
  - Ativar tema escuro ou ajustar contraste para melhorar a legibilidade do Admin Center.  

---

### **10. Preferências de Lançamento**  
- **Canais de atualização**:  
  - Escolher entre **Canal Padrão** (atualizações imediatas) ou **Canal Empresarial** (atualizações semestrais).  
  - Definir grupos piloto para testar novas funcionalidades antes do lançamento geral.  

---

### **11. Configurações de Email**  
- **Assinatura organizacional**:  
  - Criar uma assinatura de email padrão para todos os usuários (via link para o **Exchange Admin Center**).  
- **Encaminhamento global de email**:  
  - Configurar regras para redirecionar emails recebidos em domínios específicos.  

---

### **Observações Importantes:**  
1. **Permissões Necessárias**:  
   - A maioria das configurações exige a função **Administrador Global** ou **Administrador de Serviços**.  
2. **Impacto Global**:  
   - Alterações aqui afetam **toda a organização**, a menos que restritas a grupos específicos.  
3. **Integrações Externas**:  
   - Configurações avançadas (ex: políticas de MFA granular) são gerenciadas no **Azure Active Directory** ou **Centro de Segurança**.  

---

### **Ações Rápidas na Interface:**  
- **Pesquisar configurações** por palavra-chave (ex: "compartilhamento externo").  
- **Restaurar configurações padrão** em caso de erros.  
- **Exportar configurações** para auditoria ou backup.  

---

Essas opções permitem personalizar a experiência da organização, garantir conformidade com políticas internas e controlar o acesso a recursos críticos. Para ajustes específicos de serviços (ex: políticas do Teams), você será redirecionado aos respectivos centros administrativos (ex: **Teams Admin Center**, **Exchange Admin Center**).