Lista das principais **guias e funcionalidades do Microsoft 365 Admin Center** que exigem permissões de **Administrador Global** para acesso completo ou para configurações críticas. As ações mais sensíveis geralmente requerem privilégios de Global Admin.

---

### **Guias e Seções Exclusivas ou Críticas para Global Admins**

#### **1. Configurações da Organização (Org Settings)**
- **Domínios**: Adicionar/verificar domínios personalizados.
- **Perfil da Organização**: Editar nome, endereço, configurações de idioma.
- **Liberação Direcionada**: Configurar atualizações de versão (Standard/Targeted).
- **Relacionamentos com Parceiros**: Gerenciar parceiros de suporte ou CSPs.
- **Configurações do SharePoint/OneDrive**: Políticas globais de armazenamento e compartilhamento.

---

#### **2. Gerenciamento de Licenças e Cobrança (Billing)**
- **Subscriptions (Assinaturas)**: Adquirir/remover licenças, alterar planos.
- **Métodos de Pagamento**: Adicionar/remover cartões de crédito ou faturas.
- **Histórico de Pagamentos**: Acessar faturas detalhadas.
- **Transferência de Propriedade da Conta**: Em casos de migração de tenant.

---

#### **3. Azure Active Directory (Azure AD)**
- **Funções e Administradores**: Atribuir/remover funções administrativas (ex: Global Admin, Exchange Admin).
- **Configurações de Identidade**: Políticas de senha, autenticação multifator (MFA).
- **Acesso Condicional**: Criar políticas de segurança para acesso a recursos.
- **Governança de Identidade**: Configurar revisões de acesso e ciclos de vida.

---

#### **4. Segurança e Conformidade (Security & Compliance)**
- **Centro de Conformidade Microsoft Purview**:
  - **eDiscovery**: Pesquisas legais e retenção de dados.
  - **Prevenção de Perda de Dados (DLP)**: Criar políticas avançadas.
  - **Rótulos de Sensibilidade**: Configurar classificação de dados.
  - **Retenção e Exclusão**: Políticas de retenção em toda a organização.

---

#### **5. Exchange Admin Center (Centro de Administração do Exchange)**
- **Conectores de Fluxo de Email**: Configurar regras de roteamento personalizadas.
- **Permissões de Administração**: Delegar acesso a funções específicas do Exchange.

---

#### **6. Configurações Globais de Segurança**
- **Microsoft Defender para Office 365**: Configurar proteção contra ameaças.
- **Gerenciamento de Dispositivos (Endpoint Manager/Intune)**: Políticas de conformidade e acesso condicional.

---

#### **7. Gerenciamento de Usuários Avançado**
- **Restaurar Usuários Excluídos**: Recuperar usuários além do período padrão (30 dias).
- **Gerenciar Delegados**: Configurar acesso delegado a caixas de correio.

---

#### **8. Integrações e Aplicativos**
- **Aplicativos Empresariais (Azure AD)**: Configurar SSO (Single Sign-On) e provisionamento.
- **Consentimento de Aplicativos**: Gerenciar permissões de aplicativos de terceiros.

---

#### **9. Relatórios Sensíveis**
- **Relatórios de Auditoria**: Acessar logs detalhados de atividades administrativas.
- **Relatórios de Segurança**: Dados sobre ameaças detectadas.

---

#### **10. Gerenciamento de Suporte**
- **Solicitações de Serviço**: Abrir e gerenciar tickets diretamente com a Microsoft.
- **Status do Serviço**: Verificar incidentes críticos reportados pela Microsoft.

---

### **Observações Importantes:**
1. **Acesso Total**: O Administrador Global tem acesso irrestrito a **todas as guias** do Admin Center, mas as seções listadas acima envolvem ações que só podem ser executadas por esse perfil.
2. **Delegação de Funções**: Muitas tarefas podem ser delegadas a administradores especializados (ex: Administrador de Segurança, Administrador de Cobrança), mas o Administrador Global é o único que pode criar ou modificar outros administradores.
3. **Centros de Administração Específicos**: Algumas áreas (ex: Azure AD, Compliance Center) podem exigir navegação para interfaces separadas, mas o acesso é vinculado às permissões do Administrador Global.