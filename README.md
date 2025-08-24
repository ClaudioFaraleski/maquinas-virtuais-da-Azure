# Lab Azure: Criação de Máquinas Virtuais

## Entendendo o Desafio
Este laboratório tem como objetivo consolidar os conhecimentos em **máquinas virtuais (VMs)** da Azure. O desafio propõe aplicar os conceitos aprendidos em aula em um ambiente prático, documentando todo o processo de forma clara e estruturada.

Este é o momento de explorar os conceitos, experimentar na prática e construir um perfil de destaque na DIO.

## Objetivos de Aprendizagem
Ao concluir este desafio, você será capaz de:  
- Aplicar conceitos aprendidos em um ambiente prático.  
- Documentar processos técnicos de forma clara e organizada.  
- Utilizar o GitHub como ferramenta de compartilhamento de documentação técnica.

## 1. Criação de Conta no Azure
Antes de criar VMs, é necessário ter uma conta Azure:  
- Acesse [Microsoft Azure](https://azure.microsoft.com/) e clique em **Iniciar gratuitamente**.  
- Preencha os dados pessoais e informações de pagamento (verificação de identidade).  
- Após criar a conta, você terá acesso ao **Portal Azure** e um crédito inicial gratuito.  

> **Imagem de referência:**  
> ![Portal Azure](images/portal_azure.png)

## 2. Configurações Iniciais
- **Assinaturas (Subscription):** Define a cobrança e acesso aos recursos.  
- **Grupos de Recursos:** Organizam VMs e outros recursos relacionados.  
- **Região:** Escolha a região geográfica adequada.  
- **Preferências do Portal:** Personalize o dashboard e o tema (claro/escuro).  

> **Imagem de referência:**  
> ![Configurações Iniciais](images/configuracoes_iniciais.png)

## 3. Criando Máquinas Virtuais (VMs) no Azure
Para criar uma VM no Azure, siga os passos principais:  

1. **Acessar o Portal Azure:**  
   Entre no [Portal Azure](https://portal.azure.com/).  

2. **Criar um Novo Recurso:**  
   Clique em **Criar um recurso** → **Computação** → **Máquina Virtual**.  

> **Imagem de referência:**  
> ![Criar Recurso](images/criar_recurso.png)

3. **Configurações Básicas da VM:**  
   - Nome da VM  
   - Sistema operacional (Windows ou Linux)  
   - Região (mesma do grupo de recursos)  
   - Tipo de instância (CPU, memória e tamanho)  

> **Imagem de referência:**  
> ![Configurações Básicas VM](images/configuracoes_vm.png)

4. **Configurações de Discos e Rede:**  
   - Escolher disco de sistema (SSD ou HDD)  
   - Configurar rede virtual (VNet) e grupo de segurança  

> **Imagem de referência:**  
> ![Discos e Rede](images/discos_rede.png)

5. **Revisar e Criar:**  
   - Verifique todas as configurações e clique em **Criar**  
   - A implantação da VM será iniciada e, após alguns minutos, estará disponível  

> **Imagem de referência:**  
> ![Revisar e Criar VM](images/revisar_criar.png)

6. **Acessando a VM:**  
   - Para Linux: use SSH  
   - Para Windows: use RDP (Remote Desktop Protocol)  

> **Imagem de referência:**  
> ![Acessar VM](images/acessar_vm.png)

## 4. Filtros e Organização de Recursos
- Utilize **tags** para organizar VMs por finalidade, projeto ou ambiente.  
- Use **filtros do portal** para localizar rapidamente máquinas virtuais ou recursos específicos.  
- Agrupe VMs em **grupos de recursos** para melhor gerenciamento.  

> **Imagem de referência:**  
> ![Filtros e Tags](images/filtros_tags.png)

## 5. Aprendizado Obtido
Durante o laboratório, foi possível compreender:  
- Criação e configuração de contas Azure.  
- Organização de recursos com grupos e tags.  
- Processo detalhado para criar máquinas virtuais com diferentes sistemas operacionais e tamanhos.  
- A importância de configurar rede, disco e segurança na criação de VMs.  
- Navegação eficiente no portal Azure e utilização de filtros para gestão de recursos.

## Referências
- [Portal Microsoft Azure](https://portal.azure.com/)  
- [Documentação Oficial Azure - Máquinas Virtuais](https://docs.microsoft.com/azure/virtual-machines/)
