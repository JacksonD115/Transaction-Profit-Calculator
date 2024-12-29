# Transaction-Profit-Calculator
Simple app for calculating transaction profit. All transactions are saved and additional statistics are calculated on them.

Before coding any of the files we create a new data model (file -> new -> file -> Data Model(under Core Data)). We name this data model profitModel.
Under this data model we want to create 2 entities, the TaxRate entity and the Transaction entity. Under the TaxRate entity we add an attribute named taxRate which is of type double. Under the Transaction entity we add attributes buyPrice(Double), profit(Double), sellPrice(Double), transactionName(String), transactionTime(Date). From here we are now ready to start the application.
