Na guia **Dispositivos** do **Microsoft 365 Admin Center**, podemos gerenciar dispositivos (como PCs, smartphones e tablets) conectados à organização, com foco em políticas de segurança, conformidade e configurações básicas.

---

### **1. Inventário de Dispositivos**  
- **Listar dispositivos**:  
  - Visualizar todos os dispositivos registrados ou ingressados no Azure AD.  
  - Filtrar por tipo (Windows, iOS, Android, macOS), status (conformidade, atividade) ou usuário associado.  
- **Detalhes do dispositivo**:  
  - Ver informações como:  
    - Sistema operacional e versão.  
    - Último login.  
    - Status de conformidade com políticas.  
    - Proprietário (corporativo ou pessoal, se marcado como **BYOD**).  

---

### **2. Políticas de Conformidade**  
- **Políticas básicas de conformidade**:  
  - Definir requisitos mínimos de segurança para dispositivos, como:  
    - Exigir senha ou PIN.  
    - Bloquear dispositivos com jailbreak/root.  
    - Forçar criptografia (ex: BitLocker para Windows).  
- **Ações para não conformidade**:  
  - Configurar alertas ou bloquear acesso a recursos corporativos até a correção.  

---

### **3. Ações Remotas**  
- **Wipe (Limpeza)**:  
  - **Limpeza Corporativa**: Remove apenas dados da organização (mantém dados pessoais).  
  - **Limpeza Completa**: Restaura o dispositivo para configurações de fábrica (apenas para dispositivos corporativos).  
- **Bloquear dispositivo**: Impede temporariamente o acesso aos dados da organização.  
- **Reiniciar dispositivo**: Disponível para dispositivos Windows 10/11 gerenciados.  

---

### **4. Configurações de Inscrição (Enrollment)**  
- **Windows Autopilot**:  
  - Gerenciar perfis de **Autopilot** para provisionamento automatizado de dispositivos Windows.  
  - Atribuir dispositivos a grupos ou usuários específicos.  
- **Restrições de inscrição**:  
  - Limitar tipos de dispositivos permitidos (ex: bloquear Android pessoal).  
  - Definir número máximo de dispositivos por usuário.  

---

### **5. Categorias de Dispositivos**  
- **Marcar dispositivos como Corporativos ou Pessoais (BYOD)**:  
  - Aplicar políticas diferentes com base na propriedade.  
- **Atribuir tags personalizadas**:  
  - Organizar dispositivos por departamento, localização ou função (ex: "Vendas", "TI").  

---

### **6. BitLocker Recovery Keys**  
- **Visualizar chaves de recuperação do BitLocker**:  
  - Acessar chaves armazenadas no Azure AD para desbloquear dispositivos Windows criptografados.  
  - Exportar chaves em caso de emergência.  

---

### **7. Relatórios e Monitoramento**  
- **Relatório de Conformidade**:  
  - Ver quantos dispositivos atendem ou violam políticas de segurança.  
- **Atividade de Dispositivos**:  
  - Monitorar logins, sincronizações de dados e ações remotas executadas.  

---

### **8. Configurações de Segurança**  
- **Bloquear dispositivos perdidos ou roubados**:  
  - Marcar dispositivos como comprometidos para bloquear acesso imediato.  
- **Integração com o Microsoft Defender**:  
  - Visualizar alertas de segurança vinculados a dispositivos (ex: malware detectado).  

---

### **9. Limpeza de Dispositivos Inativos**  
- **Remover dispositivos antigos**:  
  - Excluir dispositivos não utilizados há mais de X dias (ex: 90 dias).  
  - Evitar acumulação de registros obsoletos no Azure AD.  

---

### **10. Configurações do Azure AD Join**  
- **Personalizar mensagens de login**:  
  - Adicionar textos ou logos corporativos na tela de login de dispositivos Windows.  
- **Gerenciar híbrido**:  
  - Configurar integração com Active Directory local (requer **Azure AD Connect**).  

---

### **Observações Importantes:**  
1. **Integração com o Endpoint Manager (Intune)**:  
   - Configurações avançadas (ex: políticas de aplicativos, perfis de email) são gerenciadas no **Microsoft Intune**, acessível via link nesta guia.  
2. **Licenciamento**:  
   - Requer licenças **Microsoft 365 Business Premium**, **Enterprise Mobility + Security (EMS)** ou **Intune**.  
3. **Dispositivos Pessoais (BYOD)**:  
   - Políticas aplicáveis podem variar dependendo da marcação como corporativo ou pessoal.  

---

### **Ações Rápidas na Interface:**  
- **Pesquisar dispositivos** por nome, usuário ou ID.  
- **Exportar lista** em CSV/PDF.  
- **Agrupar dispositivos** por status, tipo ou categoria.  

Essas opções permitem garantir segurança, conformidade e controle sobre dispositivos que acessam recursos da organização, mesmo sem configurar o Intune detalhadamente. Para recursos avançados, podemos redirecionar ao **Endpoint Manager**.