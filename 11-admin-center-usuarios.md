Na guia *Usuários* do *Microsoft 365 Admin Center*, podemos encontrar várias opções para gerenciar contas de usuários, licenças, funções e configurações relacionadas.
---

### *1. Usuários Ativos*  
- *Adicionar um usuário*: Criação de novas contas individuais.  
- *Adicionar vários usuários*: Importação em massa via arquivo CSV.  
- *Filtrar usuários*: Busca por nome, email, função, departamento, etc.  
- *Editar usuário*:  
  - *Informações de contato*: Nome, cargo, telefone, localização.  
  - *Funções*: Atribuir funções de administrador (ex: Global Admin, Teams Admin).  
  - *Licenças*: Adicionar/remover licenças (ex: Office 365, Enterprise Mobility + Security).  
  - *Senha*: Redefinir senha ou forçar alteração no próximo login.  
  - *Bloquear login*: Impedir acesso à conta temporariamente.  
- *Excluir usuário*: Remove a conta (move para "Usuários Excluídos").  
- *Reinicializar senha*: Opção rápida para redefinir a senha.  
- *Gerenciar produtos e licenças*: Visualização detalhada das licenças atribuídas.  
- *Atualizar dados de uso*: Define o "local de uso" para compliance regional.  

---

### *2. Usuários Excluídos*  
- *Restaurar usuário*: Recupera uma conta excluída nos últimos 30 dias.  
- *Excluir permanentemente*: Remove definitivamente a conta (não recuperável).  
- *Atribuir licenças durante a restauração*: Permite reativar a conta com licenças.  

---

### *3. Usuários Convidados (Guest Users)*  
- *Convidar um usuário convidado*: Adicionar colaboradores externos via email.  
- *Gerenciar permissões*: Definir acesso a recursos (ex: SharePoint, Teams).  
- *Filtrar por status de convite*: Pendente, Aceito ou Expirado.  

---

### *4. Configurações de Autenticação*  
- *Autenticação multifator (MFA)*:  
  - *Exigir MFA: Configurar por usuário (via link para o **Azure AD*).  
  - *Métodos de autenticação*: Gerenciar SMS, Authenticator App, etc.  

---

### *5. Ações em Massa*  
- *Seleção múltipla*: Aplicar ações a vários usuários simultaneamente (excluir, atribuir licenças).  
- *Exportar lista de usuários*: Gera um arquivo CSV com detalhes das contas.  

---

### *6. Status de Login*  
- *Ver atividade de login*: Acessar relatórios de login (sucessos/falhas).  
- *Status de login*: Ver se o usuário está ativo, bloqueado ou com sessão expirada.  

---

### *7. Configurações de Email*  
- *Aliases de email*: Adicionar endereços alternativos a uma conta.  
- *Caixa de correio compartilhada: Criar ou vincular a uma conta existente (via link para o **Exchange Admin Center*).  

---

### *8. OneDrive Retention*  
- *Retenção de arquivos*: Preservar dados do OneDrive após exclusão da conta (link para configurações de retenção).  

---

### *9. Recursos Relacionados (Links Diretos)*  
- *Grupos: Gerenciar grupos de segurança/distribuição (redireciona para a guia **Grupos*).  
- *Helpdesk*: Resetar senhas ou solucionar problemas de acesso.  

---

### *Observações Importantes:*  
- Algumas opções (ex: MFA detalhado, políticas de segurança) exigem acesso ao *Azure Active Directory* ou *Centro de Segurança do Microsoft 365*.  
- Permissões de administrador são necessárias para funções específicas (ex: Global Admin para atribuir funções).  
- Licenças específicas podem ser requeridas para recursos avançados (ex: Azure AD Premium para acesso condicional).  

Essas opções permitem gerenciar o ciclo de vida completo dos usuários, desde a criação até a exclusão, garantindo controle de acesso, segurança e conformidade.
