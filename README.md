 <div align="center" style="border:none;">
    <a href="https://syedomair.github.io" target="_blank"><img alt="Guy working hard!" src="https://raw.github.com/syedomair/syedomair/master/images/githubOverview.png"></a>
    <br>
    <img align="center" src="https://visitor-badge.laobi.icu/badge?page_id=syedomair.syedomair" />
</div>
<h1 align="center" style="border: none;">Syed Omair</h1>
<h1 align="center" style="border: none;">Golang / Full Stack Developer</h1>
<hr>
<be>

<!--
👋 Hi, I'm Syed Omair, a passionate Full Stack Developer with over two decades of experience in building scalable and efficient applications. I specialize in backend development with Golang, crafting high-performance microservices, and leveraging modern cloud-native architectures.

🚀 What I Do:<br/>
✅ Golang Expertise – Implementing clean architectures with dependency injection.<br/>
✅ High-Performance Concurrency – Utilizing goroutines and channels for efficient parallel processing.<br/>
✅ Robust Backend Development – Building APIs with chi, structured logging with zap, and seamless database interactions with GORM & PostgreSQL.<br/>
✅ Cloud & DevOps – Writing optimized Dockerfiles, deploying applications to AWS, and maintaining CI/CD pipelines.<br/>
✅ Testing & Debugging – Writing unit & integration tests, optimizing performance with pprof, and ensuring code quality.<br/>
✅ Version Control & Collaboration – Following best practices with GitHub workflows, pull requests, and structured release management.<br/>

📌 I’m always excited to learn new tools and tackle challenging problems. Let’s connect and build something amazing!
-->

**Seasoned Full Stack Developer | 20+ Years of Experience**
Specializing in **high-performance backend systems** using **Golang** and **frontend systems** using **ReactJS + Redux** on **AWS cloud-native architectures.**


**🚀 Key Expertise:**
* **Golang Backend Development:** Proven track record in building scalable microservices with clean architectures, dependency injection, and high concurrency.
* **ReactJS + Redux Frontend Development:** Expertise in crafting responsive, modular, and maintainable frontend applications.
* **Concurrency & Performance Optimization:** Skilled in leveraging goroutines, channels, and pprof profiling to build high-performance systems.
* **Unit & Integration Testing:** Strong advocate for test-driven development (TDD), ensuring robust code quality through detailed unit and integration tests.
* **Cloud & DevOps:** Proficient in deploying and managing applications on, Kubernetes, AWS (ECR, ECS) using Docker, Docker Compose, and CI/CD pipelines.

**🛠️ Technical Skills:**
* **Languages:** Golang, JavaScript (ES6+) 
* **Databases:** PostgreSQL, MySQL
* **Frameworks/Libraries:** ReactJS, Redux
* **Cloud & DevOps:** AWS (ECR, ECS), Kubernetes, Docker, Docker Compose, CI/CD (GitHub Actions, BitBucket Pipelines)
* **Instrumentation:** pprof profiling, Prometheus, Zap, Grafana 
* **Testing:** Unit testing, Integration testing
* **Version Control:** Git, GitHub workflows, BitBucket

**Design Patterns & Architectural Expertise**
* **Concurrency Pattern:**
    * Utilized in [service/user_service/user/user_service](https://github.com/syedomair/backend-microservices/blob/main/service/user_service/user/user_serivce.go){:target="_blank" rel="noopener"} to execute multiple database queries and gRPC calls concurrently using Go's `errgroup`.
    * Enhances the performance of the `GetAllUserStatistics` method by leveraging parallel processing.
* **Dependency Injection Pattern:**
    * Utilized in [lib/container/container.go](https://github.com/syedomair/backend-microservices/blob/main/lib/container/container.go) {:target="_blank" rel="noopener"} to manage logging, database connections, and environment variables.
    * Promotes modularity and flexibility by injecting dependencies into a central container.
* **Singleton Pattern:**
    * Implemented in `lib/container/db.go` through synchronized lazy initialization (`sync.Mutex` + instance check) in `PostgresAdapter` and `MySQLAdapter`.
    * Ensures only one database connection instance is created per adapter while maintaining thread safety.
* **Adapter Pattern:**
    * Used in `lib/container/db.go` to create a unified database interface (`Db`) with concrete implementations (`PostgresAdapter` and `MySQLAdapter`).
    * Enables seamless switching between database providers without modifying client code.
* **Factory Pattern:**
    * Utilized in `lib/container/db.go` through the `NewDBConnectionAdapter` function.
    * Acts as a factory method to create instances of different database adapters based on the specified database type, encapsulating object creation logic.
* **External Configuration Pattern:**
    * Utilized in `lib/container/container.go` to manage and validate essential configuration through environment variables.
    * Ensures centralized and type-safe access to settings, promoting flexibility and ease of deployment.
* **Decorator Pattern:**
    * Utilized in `lib/response/response.go` to dynamically add behaviors to response handlers.
    * Allows setting headers or handling different response types without altering the underlying handler implementation.
* **Middleware Pattern:**
    * Utilized in `lib/router/router.go` to chain multiple handlers that add functionalities like logging, request ID management, and Prometheus metrics collection.
    * Enhances the HTTP request processing pipeline with modular and reusable components.
* **Object Pool Pattern:**
    * Implemented in `lib/container/connection.go` to manage a pool of reusable gRPC client connections.
    * Optimizes resource usage and improves performance by reducing the overhead of repeatedly creating and destroying connections.

**📚 Featured Post on dev.to:**
* [Improving Performance with Concurrency in Golang: A Case Study](https://dev.to/syed_omair/improving-performance-with-concurrency-in-golang-a-case-study-3dip)
* [The Singleton Pattern in Golang](https://dev.to/syed_omair/the-singleton-pattern-in-golang-29lp)
* [Using a Reverse Proxy to Expose Multiple Microservices Through a Single Port in Docker Compose](https://dev.to/syed_omair/using-a-reverse-proxy-to-expose-multiple-microservices-through-a-single-port-in-docker-compose-4h9e)
* [How to Deploy a Container from GitHub to AWS ECR and ECS through OIDC](https://dev.to/syed_omair/how-to-deploy-a-container-from-github-to-aws-ecr-through-oidc-2ma5)
* [Understanding Dependency Injection Through a Practical Golang Example](https://dev.to/syed_omair/understanding-dependency-injection-through-a-practical-golang-example-4b3k)
* [The Hidden Costs of Inefficient Code: A Case Study](https://dev.to/syed_omair/the-hidden-costs-of-inefficient-code-a-case-study-4ka9)


**🌟 What I Bring to the Table:**
* A deep understanding of **scalable system design** and **cloud-native architectures.**
* A passion for writing **clean, maintainable, and efficient code.**
* A commitment to **continuous learning** and sharing knowledge through technical articles and community engagement.

**🤝 Let's Connect!**
I'm always open to **collaborations, discussions, and new opportunities**. Let's build something amazing together!


* [LinkedIn Profile](https://www.linkedin.com/in/syed-omair/)
* [Resume](https://syedomair.github.io/)
* [email](mailto:omair@cogentproc.com)



<!--
**syedomair/syedomair** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
