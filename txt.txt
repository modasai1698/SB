ConnectHub-Docker/
├── docker-compose.yml
├── .env.example
├── README.md
├── backend/
│   ├── Dockerfile
│   ├── pom.xml
│   └── src/
│       └── main/
│           ├── java/
│           │   └── com/
│           │       └── social/
│           │           ├── config/
│           │           │   └── DatabaseConfig.java
│           │           ├── model/
│           │           │   ├── User.java
│           │           │   └── Post.java
│           │           ├── dao/
│           │           │   ├── UserDAO.java
│           │           │   └── PostDAO.java
│           │           └── servlet/
│           │               ├── LoginServlet.java
│           │               ├── RegisterServlet.java
│           │               ├── FeedServlet.java
│           │               └── LogoutServlet.java
│           └── webapp/
│               ├── WEB-INF/
│               │   └── web.xml
│               ├── index.jsp
│               ├── register.jsp
│               └── feed.jsp
├── database/
│   ├── Dockerfile
│   ├── init.sql
│   └── my.cnf
└── nginx/
    ├── Dockerfile
    ├── nginx.conf
    └── default.conf
