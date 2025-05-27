A guia **"ID Verificada"** no **Microsoft Entra ID** (Microsoft 365) está relacionada ao serviço de **credenciais verificáveis** (*verifiable credentials*), parte da solução de **identidade descentralizada** da Microsoft. Essa funcionalidade permite que organizações emitam e verifiquem credenciais digitais criptograficamente seguras, como diplomas, certificados profissionais ou comprovantes de emprego, sem depender de um banco de dados centralizado.  

A guia **"ID Verificada"** é específica para configuração e gerenciamento dessas credenciais. Abaixo, descrevo as opções e recursos disponíveis **exclusivamente** nesta seção:

---

### **Principais Opções da Guia "ID Verificada" do Entra ID**

#### **1. Emissão de Credenciais Verificáveis**  
   - **Criar credenciais personalizadas**:  
     - Defina o formato das credenciais (ex.: diploma universitário, certificado de treinamento).  
     - Adicione campos específicos (ex.: nome, data de emissão, organização emissora).  
   - **Integração com sistemas externos**:  
     - Conecte-se a APIs ou serviços para automatizar a emissão (ex.: integração com um sistema acadêmico para emitir diplomas digitais).  

#### **2. Configuração do Emissor**  
   - **Registro do Emissor**:  
     - Registre sua organização como uma **autoridade emissora** no ecossistema de ID Verificada.  
     - Configure o **Domínio Verificado** (ex.: `suaempresa.com`) para garantir autenticidade.  
   - **Chaves de Criptografia**:  
     - Gere ou importe chaves públicas/privadas para assinar credenciais digitalmente.  

#### **3. Verificação de Credenciais**  
   - **Políticas de Verificação**:  
     - Defina critérios para validar credenciais recebidas (ex.: verificar se o emissor é confiável, se a credencial não foi revogada).  
   - **Integração com Aplicativos**:  
     - Use APIs para adicionar verificação de credenciais em aplicativos ou serviços (ex.: portal de RH para validar certificados profissionais).  

#### **4. Revogação de Credenciais**  
   - **Lista de Revogação**:  
     - Revogue credenciais específicas em caso de expiração, erro ou fraude.  
     - Publique atualizações no **Registro Distribuído** (ex.: blockchain ou serviço decentralizado).  

#### **5. Modelos de Credenciais**  
   - **Galeria de Modelos Pré-Definidos**:  
     - Use modelos prontos para credenciais comuns (ex.: certificado de vacinação, identidade profissional).  
   - **Personalização Visual**:  
     - Adicione logos, cores e termos específicos da organização às credenciais.  

#### **6. Registros de Auditoria**  
   - **Logs de Emissão e Verificação**:  
     - Acompanhe todas as credenciais emitidas ou verificadas, com detalhes como data, emissor e destinatário.  
   - **Relatórios de Conformidade**:  
     - Exporte dados para auditorias regulatórias (ex.: GDPR, LGPD).  

#### **7. Integração com Microsoft Authenticator**  
   - **Armazenamento no Wallet Digital**:  
     - Os usuários podem armazenar credenciais verificáveis no app Microsoft Authenticator para acesso rápido e seguro.  
   - **Compartilhamento Controlado**:  
     - Permita que usuários compartilhem credenciais específicas com terceiros sem expor dados sensíveis.  

---

### **Recursos Exclusivos da Guia "ID Verificada"**  
- **Emissão descentralizada de credenciais**: Não disponível em outras seções do Entra ID.  
- **Registro de Emissor Verificado**: Configuração única para autorizar sua organização a emitir credenciais.  
- **Integração com Blockchains Públicas/Privadas**: Opção de usar redes como ION (Layer 2 da Bitcoin) ou Ethereum para registro imutável.  

---

### **Casos de Uso Comuns**  
1. **Diplomas Universitários Digitais**:  
   - Universidades emitem diplomas como credenciais verificáveis, evitando fraudes.  
2. **Comprovação de Emprego**:  
   - Funcionários compartilham credenciais verificáveis com bancos para contratar empréstimos.  
3. **Certificados de Treinamento**:  
   - Empresas emitem certificados que podem ser verificados por parceiros ou clientes.  

---

### **Pré-requisitos e Observações**  
- **Licenças**:  
  - Requer licenças específicas (ex.: **Microsoft Entra ID Premium P1/P2**) e acesso ao serviço **Verified ID**.  
- **Configuração Técnica**:  
  - Necessário configurar um **Serviço de Revogação** e integrar com APIs (ex.: Azure Key Vault para gerenciar chaves).  
- **Suporte a Padrões Abertos**:  
  - Baseado no padrão **W3C Verifiable Credentials** e **Decentralized Identifiers (DIDs)**.  

---

### **Como Acessar**  
1. Navegue até o **Portal do Microsoft Entra ID**.  
2. No menu lateral, selecione **"ID Verificada"** (ou **"Verified ID"**).  
3. Siga o assistente para configurar emissor, modelos e políticas.