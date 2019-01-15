**Liquibase Demo**

The project is to showcase the basic working of liquibase.

- mvn liquibase:help

    Help command, shows all commands which can be executed by liquibase plugin

- mvn liquibase:update

    To execute changesets (which havent run already)

- mvn liquibase:rollback -Dliquibase.rollbackCount=n

    To rollback n changesets
