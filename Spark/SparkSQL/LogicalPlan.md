# Logical Query Plan (Logical Plan)

A Logical Query Plan is a tree of nodes of logical operators that in turn can have trees of [Catalyst Expressions](./Catalyst.md).

In other words, there are at least two trees at every level (operator).

LogicalPlan goes through execution stages (as a QueryExecution).

A logical operator is considered partially resolved when its child operators are resolved (aka children resolved).

A logical operator is (fully) resolved to a specific schema when all expressions and the children are resolved.

reference : https://jaceklaskowski.gitbooks.io/mastering-spark-sql/spark-sql-LogicalPlan.html

article for Logical Plan vs Physical Plan in Spark : https://dzone.com/articles/understanding-optimized-logical-plan-in-spark
