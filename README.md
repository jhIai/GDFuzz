# GDFuzz

A black-box approach to detect logic bugs, performance bugs, crash bugs on GDBMS.

# There are some problems we find.

| DBMS  | Type  |                         Description                          | Status | Fix                                                          |
| :---: | ----- | :----------------------------------------------------------: | :----: | ------------------------------------------------------------ |
| Neo4j | other | [round function description misleading](https://github.com/neo4j/neo4j/issues/12972) | fixed  | [ae345d0](https://github.com/neo4j/docs-cypher/commit/ae345d0aa141b69477e01abe92e5d982eb18ffda) |

