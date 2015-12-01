# neo4j_java
neo4j、java、Cypher


search by cypher 
examples:
1.select all nodes and return nodes:
start n=node() return n;
2.select all relationships and return relationships :
start n=node() match (n)-[r]->() return r;

instance:
search from target/neo4j-store database(create by examples/EmbeddedNeo4jWithIndexing.java)

result:
hello neo4j log
+---------------------------------------+
| n |
+---------------------------------------+
| Node[0]{username:"user0@neo4j.org"} |


| Node[1]{username:"user1@neo4j.org"} |

| Node[2]{username:"user2@neo4j.org"} |

| Node[3]{username:"user3@neo4j.org"} |

| Node[4]{username:"user4@neo4j.org"} |

| Node[5]{username:"user5@neo4j.org"} |

| Node[6]{username:"user6@neo4j.org"} |

| Node[7]{username:"user7@neo4j.org"} |

| Node[8]{username:"user8@neo4j.org"} |

......


| Node[98]{username:"user98@neo4j.org"} |

| Node[99]{username:"user99@neo4j.org"} |
+---------------------------------------+
100 rows

+---+
| r |
+---+
+---+
0 row

like：community/embedded-examples/src/main/java/org/neo4j/examples/ java files in https://github.com/neo4j/neo4j/
