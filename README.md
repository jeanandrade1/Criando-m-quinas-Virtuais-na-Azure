# Criando máquinas Virtuais na Azure

Acessar https://azure.microsoft.com/

Caso não tiver uma conta é necessário criar uma. Pode-se criar um teste de 30 dias com 200 USD de créditos.


Dica - Use um cartão virtual para validação e bloqueio, assim evita surpresas no cartão por algum erro.

Clique em "Criar um Recurso"
Escolha a software da máquina virtual desejado

Aba Básico

Escolha a assinatura de onde será debitados os créditos e o grupo de recursos ou crie um novo 
Adicione um nome para máquina virtual 
Escolha a região onde a máquina será implementada. Obs: Máquinas nos EUA são mais baratas, mas caso a aplicação necessite um tempo de resposta mais rápido ou por regulamentação necessite estar no Brasil, escolha a região do Brasil.
Escolha a Zona de disponibilidade. Obs: Quanto mais zonas, maior a disponibilidade da aplicação
Selecione o tipo de segurança. Obs: Para estudo pode ser o padrão
Selecione a imagem que será implementada na máquina e a arquitetura de VM
Selecione o tamanho da VM necessária para o tipo de aplicação
Selecione opcionalmente e caso suportado a opção de hibernar. Essa opção é útil para economizar custos enquanto uma aplicação não é utilizada
Insira o nome de usuário que será utilizado para acessar a VM
Gere um par de chaves públicas. Elas serão utilizadas para o acesso remoto, importane salvá-las ao final da criação.
Nas regras de porta de entrada pode se habilitar por exemplo o SSH para um acesso remoto caso desejado.

Aba Discos

Selecione criptogarfia do disco caso disponível na assinatura para a segurança
Selecione o tamanho e o tipo de disco de acordo com o necessário para a aplicação
Selecione excluir com VM caso desejado quando uma máquina é excluida automaticamente o disco relacionado também é excluído

Aba Rede
Selecione a rede virtual desejada com a Sub-rede e o IP Público
Selecione opconalmente para excluir o IP público e NIC para quando a máquina for excluída

Aba Marcas
Coloque o nome e um valor de classificação (informações apenas para controle de custos)

Aba Revisar e Criar
Crie a máquina virtual
Salve a chave privada para o acesso remoto

Pronto, agora é so aguardar a criação da máquina virtual


