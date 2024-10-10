# resumo_lab_10
Resumo de aprendizagem Lab 10: Ferramentas de Implantação na Azure
## Bootcamp DIO Microsoft Azure Essentials AZ-900
Ferramentas de Implantação de Recursos: 
- Portal Azure
- Power Shell, CLI, Bash
- Azure Arc
- Azure Resource Manager (ARM)
- Azure Resource Manager (ARM) - Atividades: comando de gerenciamento, recebe a requisição, traduz como o portal vai entender, organiza as solicitações. Centraliza as requisições (template) em linguagem para a criação (JSON). A infraestrutura como código vem se tornando cada vez mais uma necessidade no dia-a-dia das organizações, para implantar recursos.
    - Fazer o gerenciamento de recursos do Portal, CLI, Power Shell, Bash.
    - Interpretação: como os recursos foram criados. Administração. Pode ajudar se trabalhar com modelos pré-definidos.
    - Guia para automação: CLI, Power Shell, Tasks (tarefas previsão), Exportar template. Comandos usados para criar recursos no Azure.

Portal Azure: acessar o portal com sua assinatura para criar recursos da sua solicitação. All service. Pesquisar e criar, configurar.

Could Shell: ferramenta para executar linhas de comando de código no Azure (funcionalidade). Cria uma barra na parte inferior da tela e começa a criar requisições. É obrigatório ter uma conta de armazenamento para ele poder carregar. Se não houver vai solicitar a criação de uma (storage account).

Power Shell: possui botões que permite você importar/exportar arquivos, pode abrir a tela em uma nova aba. Pode utilizar o az para o CLI ou help para saber mais sobre o PS. Faz upload e download.

Modelos de comando (CLI, PS, Bash - semelhantes). Usa a mesma estratégia para criar recursos, com mais de uma forma para executar.
Criar uma rede virtual (comando) apresenta parâmetros variáveis (nome, rede, prefixo, com uma subnet, na linguagem JSON) az network vnet list (comando), como aplicar variáveis.

Bicep - ferramenta que facilita a criação de comandos para iniciantes com automação. Link da comunidade http://azure.github.io/bicep/
  - Bicep Playgroud: uma forma de fazer comparativos. Modelo em ARM criar uma VM Windows 1º template 336 linhas, 2º template modelo Bash 257 linhas (verificar diferenças de implantação)

ARC - Ferramenta de gerenciamento multicloud. Está presente para toda assinatura, basta configurá-la, adicionar infraestruturas existentes, como:
  - Servidores
  - Clusters Kubernets
  - SQL Server
  - Validar na parte de plataforma, o Banco de dados
  - Serviços habilitados fora do Azure. Administra recursos do Azure ou não (AWS, outras)
  - Centraliza os recursos com suas funcionalidades.
