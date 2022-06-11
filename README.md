# Neo4j ช่วยแก้ปัญหาความสัมพันธ์อันซับซ้อน
ฐานข้อมูลแบบ Graph Database (GDBMS) ที่พัฒนาด้วย JAVA และใช้ภาษา CQL (Cypher Query Language Neo4j) ในการ Query ข้อมูล ช่วยให้การค้นหาข้อมูลจากความสัมพันธ์อ่านง่ายขึ้น

![alt neo4j simple](https://raw.githubusercontent.com/jimmy18dev/neo4j-find-mutual-friends/master/screenshot/neo4j-simple.png)

## รัน Neo4j เพื่อทดลองใช้งานไปพร้อมกัน
*จำเป็นต้องติดตั้ง **Git** และ **Docker Engine**

### Cloning a Repository.
```
git clone https://github.com/jimmy18dev/neo4j-find-mutual-friends.git
```

### Change the current directory to Project
```
cd neo4j-find-mutual-friends
```

### Build and Start with docker-compose
```
docker-compose up -d --build && docker-compose ps
```

#### Web Application
```
http://127.0.0.1:7474/browser/
```

![alt neo4j dataset](https://raw.githubusercontent.com/jimmy18dev/neo4j-find-mutual-friends/master/screenshot/neo4j-dataset.png)

อ่านบทความฉบับเต็ม: [https://link.medium.com/acGdKvuRBqb](https://link.medium.com/acGdKvuRBqb) 