A rede de academias Model Fitness está desenvolvendo uma estratégia de interação com o cliente baseados em dados analíticos.

Um dos problemas mais comuns que academias e outros serviços enfrentam é a rotatividade de clientes. Como você sabe se um cliente não está mais com você? Você pode calcular a rotatividade baseado nas pessoas que se livram das suas contas ou não renovam seus contratos. No entanto, às vezes não é óbvio que um cliente saiu: eles podem sair de fininho.

Indicadores de rotatividade varia de área para área. Se um usuário compra de uma loja online raramente mas regularmente, você não pode dizer que é um fujão. Mas se por duas semanas eles não abriam o canal que é atualizado diariamente, essa é uma razão para se preocupar: seu seguidor pode ter ficado aborrecido e deixado você.

Para uma academia, faz sentido dizer que os clientes saíram se eles não aparecem há um mês. É claro, é possível que eles estejam em Cancun e virão tornar a frequentar quando retornarem, mas esse não é um caso comum. Normalmente, se um cliente ingressa, vem algumas vezes, depois desaparece, ele provavelmente não voltará.

O conjunto de dados gym_churn_us.csv inclui os seguintes campos:

- 'Churn'  a rotatividade do mês em questão

- Campos de dados atuais:

    - Dados do mês anterior
    - 'gender'
    - 'Near_Location' — se o cliente morar ou trabalhar na vizinhança onde a academia está localizada
    - 'Partner' — se o usuário for um funcionário de uma companhia parceira (a academia tem empresas parceiras cujos funcionários conseguem descontos; nesses casos, a academia armazena informações sobre clientes de são funcionários)
    - Promo_friends — se o cliente originalmente se inscreveu através de uma oferta "traga um amigo" eles normalmente usam o código de promoção do amigo quando pagam pela primeira filiação)
    - 'Phone' — se o usuário fornece o seu número de telefone
    - 'age' (idade)
    - 'Lifetime' — o tempo (em meses) desde a primeira vez que o cliente veio à academia
- Dados do log de frequência e compras e dados sobre status de filiação atual
    - 'Contract_period' — 1 mês, 3 meses, 6 meses, ou um ano
    - 'Month_to_end_contract' — os meses remanescentes até que o contrato expira
    - 'Group_visits' — se o cliente participa de sessões em grupo
    - 'Avg_class_frequency_total' — frequência média de idas por semana por toda a vida do cliente
    - 'Avg_class_frequency_current_month' — frequência média de visitas por semana durante o mês corrente
    - 'Avg_additional_charges_total' — a quantidade total de dinheiro gasto em outros serviços da academia: café, artigos esportivos, cosméticos, massagem, etc.
