Na guia **Teams e grupos** do **Microsoft 365 Admin Center**, podemos gerenciar configurações específicas relacionadas ao Microsoft Teams e aos grupos do Microsoft 365 (como grupos de colaboração, equipes do Teams e listas de distribuição). Essa guia combina funcionalidades de colaboração e comunicação, focando em políticas, membros e integrações exclusivas.

---

### **1. Gerenciamento de Equipes do Teams**  
- **Criar uma nova equipe**:  
  - Vincular a um **grupo do Microsoft 365** existente ou criar um novo.  
  - Definir nome, descrição e privacidade (público, privado).  
  - Adicionar canais padrão ou personalizados durante a criação.  
- **Editar equipes existentes**:  
  - Alterar nome, descrição ou privacidade.  
  - Adicionar/remover **proprietários** e **membros**.  
  - Gerenciar **canais** (padrão ou privados).  
- **Arquivar/restaurar equipes**:  
  - Desativar equipes sem excluir dados (acessível apenas para leitura).  
  - Restaurar equipes arquivadas quando necessário.  
- **Excluir equipes**:  
  - Remover permanentemente a equipe e seu grupo associado (após 30 dias, a exclusão é irreversível).  

---

### **2. Configurações de Grupos do Microsoft 365**  
- **Criar grupos vinculados ao Teams**:  
  - Garantir que o grupo inclua recursos do Teams (canais, chat, reuniões).  
- **Gerenciar associação dinâmica**:  
  - Configurar regras baseadas em atributos do Azure AD (ex: departamento = "Vendas") para atualização automática de membros.  
- **Política de expiração de grupos**:  
  - Definir tempo para expiração automática de grupos não utilizados (ex: 180 dias).  
  - Renovar grupos manual ou automaticamente com base em atividade.  

---

### **3. Políticas do Teams**  
- **Políticas de mensagens**:  
  - Controlar quem pode enviar mensagens em canais públicos/privados.  
  - Restringir o uso de GIFs, memes ou menções (@channel).  
- **Políticas de reuniões**:  
  - Definir permissões para agendar reuniões, compartilhar tela ou gravar sessões.  
  - Habilitar/desabilitar **salas virtuais** (Together Mode).  
- **Políticas de chamadas**:  
  - Configurar acesso a chamadas VoIP e PSTN (se integrado a operadoras).  
  - Atribuir números de telefone a usuários ou **contas de recurso**.  
- **Políticas de aplicativos**:  
  - Permitir/bloquear aplicativos de terceiros no Teams (ex: Trello, Zoom).  
  - Gerenciar apps da Microsoft (ex: Planner, Forms).  

---

### **4. Acesso de Convidados**  
- **Habilitar/desabilitar convidados no Teams**:  
  - Permitir que usuários externos participem de equipes e canais.  
  - Definir restrições por domínio (ex: bloquear domínios concorrentes).  
- **Gerenciar convidados existentes**:  
  - Revogar acesso de convidados específicos a equipes ou canais.  

---

### **5. Integração com Outros Serviços**  
- **Canais compartilhados**:  
  - Permitir colaboração com usuários externos sem adicioná-los à equipe principal.  
  - Configurar limites de compartilhamento.  
- **Conectores e webhooks**:  
  - Adicionar integrações a serviços externos (ex: Twitter, GitHub) em canais específicos.  

---

### **6. Relatórios e Análise**  
- **Relatórios de atividade do Teams**:  
  - Visualizar métricas como mensagens enviadas, usuários ativos e tempo em reuniões.  
  - Exportar dados para análise de uso.  
- **Monitoramento de chamadas e reuniões**:  
  - Verificar qualidade de chamadas (latência, quedas) via **Dashboard de Chamadas**.  

---

### **7. Configurações de Compliance e Segurança**  
- **Retenção de dados**:  
  - Definir políticas para preservar/excluir mensagens e arquivos do Teams (link para o **Centro de Conformidade**).  
- **Busca e descoberta eletrônica (eDiscovery)**:  
  - Pesquisar mensagens, arquivos e chats do Teams para investigações legais.  
- **Information Barriers**:  
  - Restringir comunicação entre departamentos (ex: RH não pode conversar com Financeiro).  

---

### **8. Gerenciamento de Dispositivos do Teams**  
- **Políticas de dispositivos**:  
  - Controlar se usuários podem usar o Teams em dispositivos móveis, desktop ou web.  
  - Bloquear dispositivos não gerenciados (ex: pessoais) de acessar dados corporativos.  

---

### **9. Configurações de Voice (Voz)**  
- **Pacotes de chamadas**:  
  - Adquirir e atribuir números de telefone para usuários.  
  - Configurar **auto-atendimento** (IVR) e filas de chamadas.  
- **Roteamento de chamadas**:  
  - Definir regras para direcionar chamadas a departamentos específicos (ex: Suporte Técnico).  

---

### **10. Ações em Massa**  
- **Adicionar/remover múltiplos membros**:  
  - Atualizar associações de equipes ou grupos via arquivo CSV.  
- **Aplicar políticas a vários usuários**:  
  - Atribuir políticas de mensagens ou reuniões em lote.  

---

### **Observações Importantes:**  
1. **Integração com Outros Centros**:  
   - Configurações avançadas de voz, dispositivos e compliance exigem acesso ao **Teams Admin Center**, **Centro de Conformidade** ou **Azure AD**.  
2. **Licenciamento**:  
   - Recursos como PSTN, Information Barriers ou relatórios detalhados exigem licenças **Microsoft 365 E5** ou complementos (ex: **Audio Conferencing**).  
3. **Grupos vs. Equipes**:  
   - Excluir uma equipe do Teams **não** exclui o grupo do Microsoft 365 associado (e vice-versa), a menos que configurado explicitamente.  

---

### **Ações Rápidas na Interface:**  
- **Pesquisar equipes/grupos** por nome, proprietário ou status.  
- **Verificar conflitos de nomenclatura** em grupos e equipes.  
- **Ativar/desativar recursos organizacionais** (ex: Microsoft Teams para toda a organização).  

Essas opções permitem gerenciar colaboração, comunicação e segurança de forma centralizada, garantindo que equipes e grupos atendam às necessidades da organização. Para configurações avançadas, podemos redirecionar para o **Teams Admin Center** ou **Centro de Conformidade**.