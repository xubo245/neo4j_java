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
| Node[9]{username:"user9@neo4j.org"} |
| Node[10]{username:"user10@neo4j.org"} |
| Node[11]{username:"user11@neo4j.org"} |
| Node[12]{username:"user12@neo4j.org"} |
| Node[13]{username:"user13@neo4j.org"} |
| Node[14]{username:"user14@neo4j.org"} |
| Node[15]{username:"user15@neo4j.org"} |
| Node[16]{username:"user16@neo4j.org"} |
| Node[17]{username:"user17@neo4j.org"} |
| Node[18]{username:"user18@neo4j.org"} |
| Node[19]{username:"user19@neo4j.org"} |
| Node[20]{username:"user20@neo4j.org"} |
| Node[21]{username:"user21@neo4j.org"} |
| Node[22]{username:"user22@neo4j.org"} |
| Node[23]{username:"user23@neo4j.org"} |
| Node[24]{username:"user24@neo4j.org"} |
| Node[25]{username:"user25@neo4j.org"} |
| Node[26]{username:"user26@neo4j.org"} |
| Node[27]{username:"user27@neo4j.org"} |
| Node[28]{username:"user28@neo4j.org"} |
| Node[29]{username:"user29@neo4j.org"} |
| Node[30]{username:"user30@neo4j.org"} |
| Node[31]{username:"user31@neo4j.org"} |
| Node[32]{username:"user32@neo4j.org"} |
| Node[33]{username:"user33@neo4j.org"} |
| Node[34]{username:"user34@neo4j.org"} |
| Node[35]{username:"user35@neo4j.org"} |
| Node[36]{username:"user36@neo4j.org"} |
| Node[37]{username:"user37@neo4j.org"} |
| Node[38]{username:"user38@neo4j.org"} |
| Node[39]{username:"user39@neo4j.org"} |
| Node[40]{username:"user40@neo4j.org"} |
| Node[41]{username:"user41@neo4j.org"} |
| Node[42]{username:"user42@neo4j.org"} |
| Node[43]{username:"user43@neo4j.org"} |
| Node[44]{username:"user44@neo4j.org"} |
| Node[45]{username:"user45@neo4j.org"} |
| Node[46]{username:"user46@neo4j.org"} |
| Node[47]{username:"user47@neo4j.org"} |
| Node[48]{username:"user48@neo4j.org"} |
| Node[49]{username:"user49@neo4j.org"} |
| Node[50]{username:"user50@neo4j.org"} |
| Node[51]{username:"user51@neo4j.org"} |
| Node[52]{username:"user52@neo4j.org"} |
| Node[53]{username:"user53@neo4j.org"} |
| Node[54]{username:"user54@neo4j.org"} |
| Node[55]{username:"user55@neo4j.org"} |
| Node[56]{username:"user56@neo4j.org"} |
| Node[57]{username:"user57@neo4j.org"} |
| Node[58]{username:"user58@neo4j.org"} |
| Node[59]{username:"user59@neo4j.org"} |
| Node[60]{username:"user60@neo4j.org"} |
| Node[61]{username:"user61@neo4j.org"} |
| Node[62]{username:"user62@neo4j.org"} |
| Node[63]{username:"user63@neo4j.org"} |
| Node[64]{username:"user64@neo4j.org"} |
| Node[65]{username:"user65@neo4j.org"} |
| Node[66]{username:"user66@neo4j.org"} |
| Node[67]{username:"user67@neo4j.org"} |
| Node[68]{username:"user68@neo4j.org"} |
| Node[69]{username:"user69@neo4j.org"} |
| Node[70]{username:"user70@neo4j.org"} |
| Node[71]{username:"user71@neo4j.org"} |
| Node[72]{username:"user72@neo4j.org"} |
| Node[73]{username:"user73@neo4j.org"} |
| Node[74]{username:"user74@neo4j.org"} |
| Node[75]{username:"user75@neo4j.org"} |
| Node[76]{username:"user76@neo4j.org"} |
| Node[77]{username:"user77@neo4j.org"} |
| Node[78]{username:"user78@neo4j.org"} |
| Node[79]{username:"user79@neo4j.org"} |
| Node[80]{username:"user80@neo4j.org"} |
| Node[81]{username:"user81@neo4j.org"} |
| Node[82]{username:"user82@neo4j.org"} |
| Node[83]{username:"user83@neo4j.org"} |
| Node[84]{username:"user84@neo4j.org"} |
| Node[85]{username:"user85@neo4j.org"} |
| Node[86]{username:"user86@neo4j.org"} |
| Node[87]{username:"user87@neo4j.org"} |
| Node[88]{username:"user88@neo4j.org"} |
| Node[89]{username:"user89@neo4j.org"} |
| Node[90]{username:"user90@neo4j.org"} |
| Node[91]{username:"user91@neo4j.org"} |
| Node[92]{username:"user92@neo4j.org"} |
| Node[93]{username:"user93@neo4j.org"} |
| Node[94]{username:"user94@neo4j.org"} |
| Node[95]{username:"user95@neo4j.org"} |
| Node[96]{username:"user96@neo4j.org"} |
| Node[97]{username:"user97@neo4j.org"} |
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
