# padroes_de_projeto_gof
PADRÕES DE PROJETO

1.	PADRÕES DE CRIAÇÃO
 
- ABSTRACT FACTORY – CRIA FAMÍLIAS DE OBJETOS COM ALTA FLEXIBILIDADE, ABSTRAÇÃO A MAIS. COMPOSTO POR VÁRIOS FACTORY METHODS. 

- BUILDER – SEPARAR A CONSTRUÇÃO DE UM OBJETO COMPLEXO CONSTRÓI O PRODUTO PASSO A PASSO. MESMO PROCESSO CRIA DIFERENTES REPRESENTAÇÕES.

- FACTORY – DEFINE UMA INTERFACE PARA CRIAR OBJETOS, DEIXANDO AS SUBCLASSES DECIDIREM QUE CLASSE INSTANCIAR. OBJETOS COM ALTA FLEXIBILIDADE

- PROTOTYPE – OBJETOS POR CÓPIA DE UMA INSTÂNCIA

- SINGLETON – UMA ÚNICA CLASSE DEVE TER SOMENTE UMA INSTÂNCIA, PONTO DE ACESSO GLOBAL, ACESSO A RECURSOS COMPARTILHADOS, PROTEGE A INSTÂNCIA. NÃO PERMITE O NEW FORA DA CLASSE. CONSTRUTOR DA CLASSE PRIVADO. SINGLETON |NULL >>>> VARIÁVEIS GLOBAIS. VIOLA PRINCIPIO DA RESPONSABILIDADE ÚNICA.  
“PROGRAME PARA INTEFACES E NÃO PARA IMPLEMENTAÇÕES.”
2.	PADRÕES DE ESTRUTURAS

- ADAPTER – PLUGA O CONTEÚDO AO SISTEMA

- BRIDGE – SEPARA IMPLEMENTAÇÕES DE ABSTRAÇÕES PARA QUE POSSA VARIAR E EVOLUIR SEPARADAMENTE. 

- COMPOSITE – TRATA TODOS OS OBJETOS DE FORMA JUSTA, DE MANEIRA UNIFORME. ARVORE.

- DECORATOR – INCREMENTA FUNCIONALIDADES DINAMICAMENTE A UM OBJETO. USA SUBCLASSES PARA ADCIONAR FUNCIONALIDADES. SEM MECHER NO QUE JÁ FOI CRIADO. ABERTO P/EXTENSÃO.

- FACEDE – OFERECE UMA INTERFACE PARA TORNAR O SISTEMA MAIS FACIL.

- FLYWHEIGTH – PEQUENOS RECURSOS PARA ECONOMIZAR ESPAÇO. USA COMPARTILHAMENTO. APERFEIÇOA, MAS TORNA MAIS COMPLEXO. 

- PROXY – FAZ UM OBJETO REPRESENTAR OUTRO OBJETO
 
“RELAÇÃO ENTRE OS OBJETOS PARA FORMAREM OUTROS MAIS COMPLEXOS”

3.	PADRÕES COMPORTAMENTAIS 

“COMUNICAÇÃO ENTRE OS OBJETOS.”

- CHAIN OF RESPONSABILITY - REPASSA REQUISIÇÕES PARA EVITAR DECISÕES

- COMAND – TRANFORMA REQUISIÇOES EM OBJETOS

- INTERPRETER – DEFINE UMA GRAMÁTICA E UM INTERPRETADOR 

- INTERATOR – PERCORRE UM CONJ. DE DADOS, INDEPENDENTE DA IMPLEMENTAÇÃO

- MEDIATOR – SIMPLIFICADOR DE RELACIONAMENTOS

- MEMENTO – EXTERNALIZA SEM QUEBRAR O ENCAPSULAMENTO

- OBSERVER – COMPARTTILHA RECURSOS DE MANEIRA INTELIGENTE 

- STATE – SIMPLIFICA A TROCA DE ESTADOS INTERNOS

- STRATEGY – SEPARA OS DADOS PARA ALCANÇAR A REUSABILIDADE

- TEMPLATE – DEFINE ALGORÍTIMOS EXTENSIVOS

- VISITOR – DEFINE UMA NOVA OPERAÇÃO PARA UMA CLASSE SEM ALTERÁ-LA. 


