Dia 3 : Tipos de erros, validações e boas práticas em testes de API

Validações e Boas práticas para testes de APIs

Um exemplo de teste funional é quando voce testa a função do software.
Seguir as regras de negócio.

Tecnica de partição ou classe de equivalencia: quais são as possiveis entradas que voce dará para função de sua aplicação
        ex: Entradas: Credencial (Se for Administrador = registrar, Usuário = Não registrar, Invalida = Não registrar Expirada = Não registrar)

401 significa não autorizado.

Algumas das boas práticas:
    ► Entender o projeto;
    ► Documentação: Se ja está pronto, se os métodos estão sendo utilizados de forma correta;
    ► Validação: Tipos de Testes: 
                                Funcionais: requisitos;
                                Não funcionais: performance;
                                Estruturais: Arquitetura de API
    ► Segurança: Autenticação: POST /api/clients/ criar uma token de acesso.

TIPOS DE ERROS: Gravidade: Perigoso e sem solução.
                Prioridade: Quão rapido o bug é removido;
                Risco: Qualquer evento improvavel. Afeta o custi, a data...

    Causado por documentação: não feito corretamente, mudar os métodos.
    Causado por massa de dados: aceitabilidade. Um site suporta 1500 pessoa, e voce testa para 200.