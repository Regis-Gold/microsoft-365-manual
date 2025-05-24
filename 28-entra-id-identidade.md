A guia **"Identidade"** (ou **"Identity"**) no **Microsoft Entra ID** (parte do Microsoft 365) concentra-se em recursos avançados de gerenciamento de identidades, segurança e governança. Essa seção é voltada para configurações e ferramentas específicas relacionadas à proteção, autenticação, autorização e ciclo de vida de identidades.

---

### **Principais Opções da Guia "Identidade" do Entra ID**

#### **1. Governança de Identidade**  
   - Ferramentas para gerenciar acesso a recursos e garantir conformidade:  
     - **Revisões de acesso**: Criar revisões periódicas de acesso a aplicativos, grupos ou funções.  
     - **Gerenciamento de direitos (Entitlement Management)**: Definir pacotes de acesso com políticas de atribuição automática de permissões.  
     - **Ciclo de vida de usuários convidados (B2B)**: Configurar políticas de expiração de acesso para usuários externos.  

#### **2. Proteção de Identidade**  
   - Recursos de segurança baseados em riscos:  
     - **Políticas de risco**: Configurar políticas para bloquear logins arriscados ou forçar a alteração de senha em caso de credenciais vazadas.  
     - **Usuários arriscados**: Lista de usuários com atividades suspeitas (ex.: viagens impossíveis, logins de IPs maliciosos).  
     - **Logins arriscados**: Detalhes de tentativas de login com indicadores de risco.  

#### **3. Autenticação**  
   - Configurações avançadas de métodos de autenticação:  
     - **Métodos de autenticação sem senha**: Habilitar/gerenciar FIDO2, Windows Hello ou Microsoft Authenticator.  
     - **Políticas de registro de autenticação multifator (MFA)**: Forçar usuários a registrar métodos MFA durante o login.  
     - **Proteção por senha**: Bloquear senhas comuns ou personalizadas (lista global e personalizada).  

#### **4. Acesso de Parceiros Externos (B2B e B2C)**  
   - Configurações específicas para colaboração externa:  
     - **Colaboração B2B**: Definir quais domínios são permitidos/bloqueados para convites.  
     - **Políticas de inscrição de usuário (B2C)**: Criar fluxos personalizados para autenticação de clientes (se integrado ao Azure AD B2C).  

#### **5. Identidade Híbrida**  
   - Integração com ambientes locais:  
     - **Azure AD Connect Health**: Monitorar sincronização de identidades entre AD local e Entra ID.  
     - **Configurações de write-back**: Habilitar write-back de senhas ou grupos para o Active Directory local.  

#### **6. Ciclo de Vida de Identidades**  
   - Automatização de processos de onboarding/offboarding:  
     - **Provisionamento em nuvem (Cloud Sync)**: Configurar sincronização de usuários de fontes HR (ex.: Workday, SAP).  
     - **Gerenciamento de contas obsoletas**: Definir políticas para desativar usuários inativos.  

#### **7. Monitoramento de Identidades**  
   - Relatórios e insights específicos:  
     - **Secure Score para Identidades**: Pontuação de segurança com recomendações para melhorar a postura de proteção.  
     - **Relatórios de atividade de autenticação**: Detalhes sobre métodos de autenticação usados (ex.: número de logins via MFA).  

#### **8. Funções e Administração**  
   - Gerenciamento de permissões privilegiadas:  
     - **Gerenciamento de Identidades Privilegiadas (PIM)**: Ativar atribuição just-in-time para funções administrativas.  
     - **Unidades administrativas**: Criar unidades para delegar gestão de usuários/grupos a administradores específicos.  

---

### **Recursos Exclusivos ou Centralizados na Guia "Identidade"**  
- **Identity Secure Score**: Disponível apenas aqui, oferece métricas personalizadas para melhorar a segurança.  
- **Entitlement Management**: Configuração centralizada de pacotes de acesso e políticas de governança.  
- **Políticas de Risco do Identity Protection**: Não estão disponíveis em outras guias como "Página Inicial".  
- **Azure AD Connect Health**: Monitoramento híbrido específico para integração com AD local.  

---

### **Observações Importantes**  
- **Licenças Necessárias**:  
  - Recursos como **Identity Protection**, **PIM** e **Entitlement Management** exigem licenças **Entra ID Premium P1/P2**.  
- **Interface Dinâmica**: A organização das opções pode variar conforme atualizações da Microsoft.  
- **Integração com Outros Serviços**: Algumas configurações (ex.: B2C) podem redirecionar para o portal do Azure.  

---

### **Exemplo de Uso**  
1. Para **reduzir riscos de credenciais vazadas**, navegue até **Proteção de Identidade > Políticas de Risco** e ative a política "Requer alteração de senha ao detectar credenciais vazadas".  
2. Para **automatizar o acesso de funcionários**, use **Governança de Identidade > Gerenciamento de Direitos** para criar um pacote de acesso ao SharePoint com aprovação gerencial.