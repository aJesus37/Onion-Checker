# Onion-Checker
### (Em Desenvolvimento)

##### Script para testar se hidden services no Tor estão em fucionamento, bem como catalogá-los de forma simples. (Funções adicionais sendo implementadas).

# Funcionalidades

[+] **_Implementadas Totalmente:_**

- [x] *Link Organization;*

- [x] *Check Tor Installation;*

- [x] *Check Link with timeout set by user;*

- [x] *Unir arquivos de texto em um só.*

[+] **_Implementadas Parcialmente:_**


# History 

*17/01/2017 -* Adicionada função para união de vários arquivos de texto em um único, ou imprime o resultado na tela. Adicionado suporte à função de organização que aceita qualquer quantidade de arquivos de entrada e manda para um de destino, ou imprime o conteúdo todo na tela. Mudada a forma com que o timeout é setado para o link-check, tendo valor default (ao pressionar enter sem nada) de 20 segundos.

*16/01/2017 -* Função de checagem de links totalmente implementada com timeout escolhido pelo próprio usuário. Teste feito com base em função if-else com regex, bem documentada no source code; Novas implementações nos comandos de limpeza para organização de links, abrangendo gama maior nos arquivos filtrados; Documentação das novas/editadas funções.

*14/01/2017 -* Função de organização de links totalmente implementada e simplificada pro usuário final. Função pra checagem da existência do Tor simplificada e adiciona retorno para exibição ao usuário. Código totalmente comentado à partir de agora.

*13/01/2017 -* Função implementada parcialmente: Filtragem de lista de links onion passada pelo programa. Criação de menu de ajuda e suporte à flags e argumentos de flags. Funções ainda sendo implementadas, link-org é a primeira a estar quase finalizada.

*05/01/2017 -* Começado o trabalho de elaboração do script e estudo de casos para decidir com base em que ferramentas ele trabalhará e a complexidade do mesmo. Decidido até o momento: Será feito em shell.
