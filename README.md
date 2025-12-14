# SaveMyFinances

## Database Model

```text
           users
             |
        +----+----+
        |         |
    accounts   categories
        |
  +-----+-----+
  |           |
transactions  recurring_transactions
  |
debt_payments
  |
 debts
```

This diagram represents the core database entities of SaveMyFinances and their
direct relationships. A user owns multiple accounts and categories. Financial
activity is recorded through transactions, which can be generated manually or
from recurring transactions. Debts and their payments are tracked separately
to maintain clear financial history and consistency.
