

# Near Warchest
Цього бота було створено задля динамічного моніторинга стейка делегатора, щоб розмір стейка видповідав ціні одного місця.  
Використовуємо [JSON-RPC](https://docs.near.org/docs/interaction/rpc) та [Near Shell](https://github.com/near/near-shell/).

## Features

Дінамічно моніторимо ціну одного місця

Пінгаємо нову епоху


## Використання


Встановіть або оновіть Go. Треба мати 1.13 або вище
https://medium.com/@khongwooilee/how-to-update-the-go-version-6065f5c8c3ec

Такод треба всановити [Near Shell](https://github.com/near/near-shell/).

Кредити від аккаунта делегатора мають бути тут `$HOME/.near-credential`.

    git clone https://github.com/yes-filippova/near-warchest.git

    cd near-warchest

    set -a
    environment-go.list
    set +a

    go warchest.go

    ./warchest -accountId <POOL_ID> -delegatorId <DELEGATOR_ID>


