1. Escalabilidade (capacidade do sistema aumentar e diminuir a sua capacidade conseguindo manter suas métricas normais de operação):
    - deve manter a capacidade de operação independente da quantidade de pessoas/ações usando o sistema.
    - Um sistema de folha de pagamento precisa escalar pra atender uma demanda pontual. Fechamento de folha 1x no mês.
    - Se o sistema reponde em 100ms com 1 usuário ativo, com 10.000 ele deve responder nos mesmos 100ms; Assim você garante que ele está escalando de forma correta.
    - Deve ser capaz de adicionar hardware e diminuir hardware, garantindo a eficiência econômica mas ao mesmo tempo garantindo o funcionamento do sistema.
2. Disponibilidade:
    - Conceito raso: manter o sistema sempre disponível ao usuário.
    - Garantir que o sistema vai estar disponível em momentos de estresse.
    - Mas o que manter no sistema disponivel ? 
        - É necessário analisar o custo de manter X funcionalidade disponivel ou o sistema inteiro disponível;
    - Cenário que de manter disponivel um relatório extremamente custoso.
        - Analisar se todos os usuários da plataforma acessarem aquela funcionalidade o sistema ainda irá continuar disponível e qual o custo disso.
    - Como bancos utilizam isso:
        - Extrato dos ultimos 12 meses não está disponível a qualquer momento, é necessário solicitar esse relatorio, a funcionalidade está sempre disponível, mas não a qualquer momento. Essa é uma estratégia para evitar custos altos demais.
        - Trade-off: É melhor gastar X vezes mais em Infra e Banco para gerar um relatorio em tempo real ou simplesmente abrir um chamado e enviar esse relatório em até 24h no email do usuário ? 
3. Segurança:
    - Segurança de dados;
    - Segurança operacional;
    - Segurança de autenticação;
    - Segurança de autorização pessoas que vão ter acesso a X funcionalidade;
    - Segurança de rede;
    - Compartilhameto de informação;
    # Casos reais:
        - Um banco precisa se precaver com seus proprios gerentes e proprios executivos e diretores;
        