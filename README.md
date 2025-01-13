# Configurando uma instância de Banco de Dados na Azure

*Seguindo o padrão de IaaS, temos uma visão geral de como realizar a criação de uma VM.

![image](images/Tela-1.png)

![image](images/Tela-2.png)

![image](images/Tela-3.png)
*Nas próximas telas temos muitos detalhes que podemos estar definindo para criação das maquinas virtuais.*

![image](images/Tela-4.png)
*Uma das opções que temos a seleção de imagem que nossa máquina vai utilizar, tendo selecionado umas das opções, já temos uma previsibilidade de valor mensal que vamos ter com nossa máquina. Como estamos montando uma maquina totalmente customizável toda a parte de manutenção delas sera por nossa responsabilidade.*

![image](images/Tela-5.png)
*Temos as opções de selecionar o tamanho do disco.*

![image](images/Tela-6.png)
*Configurações de rede.*

![image](images/Tela-7.png)
*Configurações de gerenciamento da maquina.*

![image](images/Tela-8.png)
*Monitoramento da VM.*

![image](images/Tela-9.png)
*Ao Finalizar todas as configurações necessárias já temos uma previa de quanto vai custar nossa máquina.*

## Agora vamos fazer a criação do banco de dados

![image](images/Tela-1-BD.png)
*Dentro do portal do Azure temos a opção de criar um banco de dados SQL.*

![image](images/Tela-2.png)

![image](images/Tela-3-BD.png)
*Os primeiros parâmetros que precisamos definir é a Assinatura e Grupo de recursos. Caso não existe um "Grupo de recursos" será necessário a criação. Como no proprio site da Azure diz. "Use grupos de recursos como pastas para organizar e gerenciar todos os seus recursos."*

![image](images/Tela-5-BD.png)
*Agora escolhemos um nome para nosso banco, caso não tenha nenhum servidor criado, vamos precisar fazer a criação de um.*

![image](images/Tela-4-BD.png)
*Definimos um nome, localização que ele vai estar e quais vão ser os métodos de autenticação.*

![image](images/Tela-6-BD.png)
*Na opção seguinte, podemos definir a redundância do armazenamento de backup.*

![image](images/Tela-7-BD.png)
*Com todas as opções configuradas, já temos uma previsão de quanto vai ser o custo do nosso bando de dados dentro da Azure.*