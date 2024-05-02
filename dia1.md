DIA 1 - CONCEITOS HTTP, API REST, JSON, USER STORIES E ISSUES.

User Stories ou História de usuários é a descrição resumida das features.
    ► Cada história deve ser independente.
    ► Deve ser testável (automatizado ou manual).
    ☼ História do usuário mensurável: quanto de esforço deve ser aplicado para sua conclusão.

EXAMPLE MAPPING:
    ☼ Técnica para identificar.
    ☼ 3 amigos: Cliente, Desenvolvedor e Testador.
    ☼ Apenas 30 minitos de reunião.

AMARELO: HISTÓRIA → Descrição do que será implementada.
                    ☼ Como/sendo;
                    ☼ Eu quero/ gostaria;
                    ☼ Para/porque
AZUL: REGRAS → As regras que serão implementadas.
VERDE: EXEMPLOS → Como essa regra deve ser testada:
                    ☼ Contexto;
                    ☼ Ação;
                    ☼ Resultados;
VERMELHO: QUESTIONAMENTOS.

Exemplo de uma User Stories:
HISTÓRIA: Como um usuário autenticado, quero criar um anúncio pago para vender meu produto rapidamente.
    REGRAS: Deve prencher os dados obrigatórios do produto.
            EXEMPLO: Prencheu todos os dados obrigatórios, submeteu ao form → OK
                     Esqueceu de informar o título do produto, submeteu ao form → ERRO

    REGRAS: Anuncio com destaque deve ficar pendente até confirmação do pagamento.
            EXEMPLO: Prencheu todos os campos, selecionou o anuncio destacado. Submeteu ao form → pendente
                    QUESTIONAMENTOS: Como o usuário faz para pagar o anúncio?
                    Será uma nova feature (Como usuário, quero pagar meu anuncio para ativá-lo).

Definition of Ready (DoR) -“Definição de preparado"- é uma técnica de qualidade e gestão de risco que apoia a entrada de uma história para o delivery. Deixar claro o que a gente precisa para o desenvolvimento, exemplo o que ter de ferramentas. Quem faz a definição do DoR é o time. É uma descrição para a User Stories. 
    Na nossa challenge, o DoR será:
        ☼Banco de dados e infraestrutura para desenvolvimento disponibilizados;
        ☼Ambiente de testes disponibilizado.

 Basicamente, o DoR é para iniciar o trabalho. O DoD é quando o trabalho já está finalizado e aceitando os critérios de aceitação.                
 Critério de Aceitação está embutido no DoR e do DoD. Ver se está definido no DoR, e se está atendido no Dod.


 CONCEITOS:
 ☼ HTTP: "HyperTextTransferProtocol",  é um protocolo usado para obter recursos,  como por exemplo documentos e além disso servem  também para intermediar a comunicação com APIs. 
 ☼ API REST: é um estilo de arquitetura que define padrões que facilitam a comunicação entre sistemas via Web,permite que o cliente e o servidor sejam implementados independentemente,sem an  necessidade que um tenha conhecimento da implementação do outro. Usa o protocolo HTTP e é baseado em contrato.
 ☼ JSON: É o formato em que a resposta da requisição será escrita.