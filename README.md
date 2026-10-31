# Java Lead Prep

A self-contained, browser-based interview preparation guide for Java backend developers preparing for senior developer, technical lead, or Custom Software Engineering Lead interviews.

The companion application is **`Java-Lead-Prep.html`**. Open it in a modern web browser to use the interactive study planner, topic library, and flashcard revision area. This README explains the purpose, content, workflow, features, progress behaviour, and practical usage of that HTML file.

> **Content note:** The topic inventory and feature descriptions below are taken from the supplied HTML application. The README documents what is present; it does not imply that every interview topic or code example is exhaustive or guaranteed to match every employer's interview process.

---

## 1. What this preparation guide contains

The application is organised as a **4-week roadmap** with:

- **20 learning modules**
- **365 individual topics**
- A combination of concepts, comparisons, coding exercises, design discussions, production scenarios, and behavioural/leadership questions
- Topic answers with concise explanations
- Java code examples and expected output where supplied in the HTML
- Follow-up interview questions and answers where supplied
- Search and topic filters
- Completion tracking, confidence ratings, revision flags, and personal notes
- A flashcard-style revision area

The roadmap is labelled for a **Custom Software Engineering Lead** preparation track. Its coverage is also relevant to Java backend and senior Java developer interviews.

## 2. Files and how to start

Keep these two files together in your project or download folder:

```text
Java-Lead-Prep/
├── Java-Lead-Prep.html
└── README.md
```

### Run it

1. Download or clone the folder containing both files.
2. Open `Java-Lead-Prep.html` in Chrome, Edge, Firefox, or another modern browser.
3. No build step, package installation, local server, database, or Java installation is required just to read and use the guide.
4. Use the **Plan**, **Study**, and **Revise** tabs at the top.
5. Set your plan start date on the Plan screen if you want the application to identify your current roadmap week.

The application is implemented as a standalone HTML document with embedded CSS, JavaScript, and preparation content. It loads Google Fonts when an internet connection is available; browser fallback fonts are defined if those fonts cannot be reached.

### Recommended environment

- A recent desktop browser gives the most comfortable experience for reading code and using the module navigation.
- The layout also adapts to tablet and mobile screen widths.
- Java is needed only if you want to independently compile and run the Java examples. The HTML guide itself does not execute Java code.

---

## 3. Application navigation

### Plan

The Plan screen is the roadmap dashboard. It provides:

- A four-week learning plan and each week's focus.
- The modules assigned to each week.
- Suggested daily study actions.
- A date field to set the plan start date.
- A current-week indicator when a start date is set.
- Overall topic completion and must-know completion.
- Counts for topics flagged for revision and topics rated Shaky.
- A progress bar.

Selecting a module from the roadmap takes you into the Study view for that module.

### Study

Study is the main learning area. It includes:

- A module navigation rail on larger screens and a module selector on smaller screens.
- A module description and module-level completion progress.
- An expandable topic list.
- Topic labels such as **Must-know**, **Good**, and revision/confidence states.
- Search across topic titles, answer text, key points, and follow-up question text.
- Filters for:
  - **All** — all topics in the current module or search result.
  - **Must-know** — topics marked as must-know in the source content.
  - **Not done** — topics not yet marked complete.
  - **Revise / Shaky** — topics flagged for revision or rated Shaky.
  - **With code** — topics that include a code example.
- Topic explanations, key points, code samples, expected output, and follow-up questions when available.
- A code-copy control for code examples.
- A **Done** control to mark a topic complete.
- A confidence rating:
  - **Shaky**
  - **OK**
  - **Confident**
- A **Flag for revision** control.
- A notes area for personal interview notes.

A topic can be expanded to study its content. Work through a module from top to bottom when following the roadmap, or use search to jump directly to a topic.

### Revise

Revise is a flashcard-style practice screen. It is designed to make you retrieve an answer from memory before reading the explanation.

The revision pools are:

| Pool | What it includes |
|---|---|
| Flagged + Shaky | Topics explicitly flagged for revision and topics rated Shaky |
| Must-know not yet Confident | Must-know topics that have not been rated Confident |
| Everything I've done | Topics marked Done |
| All topics | The complete topic library |

You can also filter the revision cards by module.

**Suggested flashcard routine:**

1. Read the topic/question title.
2. Answer aloud in approximately 15–30 seconds without looking at the explanation.
3. Select **Show answer**.
4. Compare your response with the guide.
5. Rate yourself Shaky, OK, or Confident.
6. Move to the next card.

Shaky ratings automatically put a topic into the revision set. A Confident rating removes its revision flag in the flashcard flow.

---

## 4. Four-week study roadmap

| Week | Focus | Modules | Suggested approach |
|---|---|---|---|
| 1 | Core Java foundations | OOP & Java Fundamentals; Strings, Objects & Exceptions; Collections Framework; Java 8 Features; Must-Know Coding Programs | Spend 1–2 days per module. Keep coding practice running throughout the week: write two programs daily and revise flagged topics at the end of the week. |
| 2 | Concurrency, modern Java & design | Multithreading & Concurrency; Java 9–17 Features; JVM, Memory & Performance; SQL, Database & Transactions; Design Patterns, SOLID & Clean Code | Give threads 2–3 days and run the examples. Practise explaining answers in under 30 seconds and continue two coding programs daily. |
| 3 | Spring, security & APIs | Spring Core & Spring Boot; Spring Data JPA & Hibernate; Spring Security & JWT; REST APIs & Microservices; Testing, Build & Tools | Prioritise Spring and JPA. Practise the JWT flow end to end and connect topics to projects you have worked on. |
| 4 | Messaging, cloud & lead | Kafka & Messaging (JMS, RabbitMQ); Redis & Caching; Docker, Kubernetes & CI/CD; Production & Real-Time Scenarios; Leadership, Agile & System Design | Connect Kafka and Redis concepts to production scenarios. Replace placeholders in leadership answers with your own examples. Use the final two days for Shaky and flagged topics. |

### How to use the schedule

The weeks are a suggested sequence, not a restriction in the application. You can open any module at any time. The current-week indicator is based on the start date you enter and the four-week plan.

The Plan screen's guidance is to:

1. Follow the weeks in order and work through modules.
2. Read each answer and explain it aloud in 15–30 seconds without looking.
3. For programs, type the code yourself, run it, and compare the output.
4. Mark topics Done, rate confidence, and flag weak areas.
5. Use Revise every day for flagged and Shaky topics.

---

## 5. Complete module and topic index

The following index lists the modules and topic titles included in the supplied HTML file. It is useful for understanding the scope before starting and for locating subjects using the application's search field.

### OOP & Java Fundamentals

**Topics (16):**

- What is Java? JDK vs JRE vs JVM
- Class and object
- Four pillars of OOP
- Encapsulation
- Inheritance and the diamond problem
- Polymorphism: overloading vs overriding
- Abstraction
- Abstract class vs interface (Java 8+)
- Composition vs inheritance
- Association, aggregation, composition
- Access modifiers
- static keyword
- final vs finally vs finalize
- Constructors and chaining this() / super()
- Java is pass-by-value
- Marker interfaces
### Strings, Objects & Exceptions

**Topics (15):**

- String immutability and the string pool
- String vs StringBuilder vs StringBuffer
- == vs equals()
- equals() and hashCode() contract
- How to create an immutable class
- Comparable vs Comparator
- Exception hierarchy: checked vs unchecked
- Custom exceptions
- try-with-resources
- throw vs throws
- Exception handling best practices in services
- Generics, type erasure and PECS
- Wrapper classes, autoboxing and the Integer cache
- Shallow vs deep copy and clone()
- Serialization, serialVersionUID and transient
### Collections Framework

**Topics (17):**

- Collections hierarchy
- ArrayList vs LinkedList
- HashMap internal working
- HashMap vs Hashtable vs ConcurrentHashMap
- ConcurrentHashMap internals (Java 7 vs Java 8)
- Fail-fast vs fail-safe iterators
- HashSet internal working
- TreeMap and sorted collections
- LRU cache with LinkedHashMap
- Mutable keys in HashMap
- Iterator vs ListIterator vs Enumeration
- PriorityQueue
- Unmodifiable vs immutable collections
- ArrayDeque and BlockingQueue
- CopyOnWriteArrayList
- WeakHashMap and IdentityHashMap
- Choosing the right collection
### Multithreading & Concurrency

**Topics (21):**

- Thread vs Process
- Creating threads: Thread, Runnable, Callable
- Thread lifecycle and states
- synchronized: method vs block, object vs class lock
- volatile and the Java Memory Model
- wait/notify vs sleep vs join
- Producer-Consumer with BlockingQueue
- Deadlock: cause, detection, prevention
- Race condition, AtomicInteger and CAS
- ReentrantLock vs synchronized
- ReadWriteLock and StampedLock
- ExecutorService and thread pools
- ThreadPoolExecutor parameters, rejection and sizing
- Callable and Future
- CompletableFuture
- CountDownLatch, CyclicBarrier, Semaphore
- ThreadLocal and memory leaks in pools
- Print odd and even numbers with two threads
- ForkJoinPool and work stealing
- Livelock and starvation
- Virtual threads (Java 21)
### Java 8 Features

**Topics (2):**

- Java 8 features overview
- Lambda expressions
### Java 9–17 Features

**Topics (16):**

- Java 9–17 overview and why LTS matters
- Records
- Sealed classes
- Pattern matching for instanceof
- Switch expressions
- Text blocks
- var: local variable type inference
- Helpful NullPointerExceptions
- List.of, Set.of, Map.of: immutable factories
- Stream and Optional additions (9–16)
- String API additions
- Standard HttpClient (Java 11)
- JPMS modules and strong encapsulation
- GC improvements: G1 default, ZGC, Shenandoah
- Migrating Java 8 to 17 and Spring Boot 3
- After 17: switch patterns and virtual threads (Java 21)
### JVM, Memory & Performance

**Topics (15):**

- JVM architecture
- Heap vs stack
- Java 8 memory model: Metaspace vs PermGen
- Class loading and parent delegation
- Garbage collection basics
- GC algorithms and how to choose
- OutOfMemoryError types
- Memory leaks in Java
- StackOverflowError
- JIT compiler
- Key JVM tuning flags
- Diagnostic tools
- Strong, soft, weak and phantom references
- Performance tuning approach
- Reducing allocation and String deduplication
### Spring Core & Spring Boot

**Topics (19):**

- Spring vs Spring Boot
- IoC and Dependency Injection (why constructor injection)
- Bean scopes
- Bean lifecycle, @PostConstruct and @PreDestroy
- @Component, @Service, @Repository, @Controller vs @RestController
- Multiple implementations: @Qualifier and @Primary
- @SpringBootApplication and how auto-configuration works
- Starters and the embedded server
- Profiles, externalized config, @Value vs @ConfigurationProperties
- Global exception handling with @RestControllerAdvice
- Bean validation with @Valid
- Actuator, health checks and metrics
- Spring AOP, proxies and the self-invocation problem
- @Transactional: propagation, isolation, rollback and pitfalls
- Circular dependencies
- @Async and @Scheduled pitfalls
- Caching with @Cacheable
- Testing: @SpringBootTest, @WebMvcTest, @DataJpaTest, Mockito
- What happens when a Spring Boot app starts
### Spring Data JPA & Hibernate

**Topics (19):**

- JPA vs Hibernate vs Spring Data JPA
- Entity lifecycle states
- Persistence context, first-level cache and dirty checking
- Second-level cache
- Lazy vs eager loading and LazyInitializationException
- N+1 query problem and fixes
- Bidirectional @OneToMany / @ManyToOne, owning side and mappedBy
- Cascade types and orphanRemoval
- Derived query methods
- @Query: JPQL vs native, and @Modifying
- Pagination and sorting with Pageable
- Optimistic (@Version) vs pessimistic locking: concurrent debit
- save vs saveAndFlush, and flush modes
- getReferenceById vs findById
- Projections and DTOs
- Batch inserts and the IDENTITY caveat
- Open Session in View
- HikariCP connection pool tuning
- ID generation strategies
### Spring Security & JWT

**Topics (24):**

- Authentication vs authorization
- Spring Security architecture and filter chain
- SecurityFilterChain configuration in Boot 3
- UserDetailsService and PasswordEncoder (BCrypt)
- JWT structure, stateless flow and OncePerRequestFilter
- Access vs refresh tokens and revocation
- JWT signing: HS256 vs RS256/ES256 and JWKS key rotation
- JWT validation checklist and common attacks
- Generating and validating a JWT in Java (jjwt and Spring)
- Where to store tokens in the browser
- JWT vs opaque tokens and token introspection
- Logout and revocation with stateless JWT
- Token propagation between microservices
- OAuth2 grant types: auth code + PKCE, client credentials, refresh
- OAuth2, OpenID Connect and resource server
- Method security with @PreAuthorize
- Roles vs authorities
- CSRF and when to disable it
- CORS configuration
- Session-based vs stateless authentication
- Secrets management
- OWASP risks for banking APIs (SQLi, XSS, IDOR)
- Rate limiting and brute-force protection
- mTLS between services
### REST APIs & Microservices

**Topics (23):**

- REST principles
- HTTP methods, safety & idempotency
- HTTP status codes
- PUT vs PATCH vs POST
- API versioning strategies
- Standard error response design
- Pagination, filtering & sorting
- Idempotency keys for payments
- OpenAPI / Swagger documentation
- Monolith vs microservices
- Microservice decomposition (DDD bounded contexts)
- API gateway
- Service discovery & load balancing
- Sync REST/Feign vs async messaging (Kafka)
- Kafka essentials
- Circuit breaker, retry, timeout & bulkhead
- Saga & outbox patterns
- Distributed tracing & correlation IDs
- Centralized configuration
- Database per service & eventual consistency
- Caching with Redis
- Docker & Kubernetes basics for Java devs
- 12-factor app
### SQL, Database & Transactions

**Topics (18):**

- ACID properties
- Isolation levels and read anomalies
- Indexes: B-tree, clustered vs non-clustered, composite
- Query optimization and EXPLAIN plan
- Join types
- Second / Nth highest salary
- WHERE vs GROUP BY vs HAVING
- Find and delete duplicate rows
- DELETE vs TRUNCATE vs DROP
- Normalization vs denormalization
- Database deadlocks and how to avoid them
- OFFSET vs keyset pagination
- Connection pooling
- JDBC PreparedStatement vs Statement
- Optimistic vs pessimistic locking at DB level
- Distributed transactions: 2PC vs Saga
- SQL vs NoSQL
- Stored procedures vs application logic
### Design Patterns, SOLID & Clean Code

**Topics (21):**

- SOLID principles (overview)
- Single Responsibility Principle
- Open/Closed Principle
- Liskov Substitution Principle
- Interface Segregation Principle
- Dependency Inversion Principle
- Singleton (and how it breaks)
- Factory pattern
- Builder pattern
- Strategy pattern
- Observer pattern
- Decorator pattern
- Adapter pattern
- Proxy pattern & Spring AOP
- Template Method pattern
- Chain of Responsibility
- Facade pattern
- Composition over inheritance
- Clean code: DRY, KISS, YAGNI
- Code review checklist (as a lead)
- Common anti-patterns
### Must-Know Coding Programs

**Topics (23):**

- Reverse a string (multiple ways)
- Palindrome check
- Character frequency
- First non-repeated character
- Anagram check
- Find duplicates in an array
- Second highest number
- Fibonacci series
- Prime number check
- Swap two numbers without a temp variable
- Missing number in 1..n
- Two sum with HashMap
- Sort a Map by value
- Employee stream problems
- Word count in a sentence
- Remove duplicates preserving order
- Balanced parentheses
- Binary search
- String compression (aabccc → a2b1c3)
- Maximum subarray sum (Kadane's algorithm)
- Thread-safe Singleton
- Count vowels and consonants
- Reverse words in a sentence
### Production & Real-Time Scenarios

**Topics (20):**

- High CPU in production
- OutOfMemoryError in production
- Memory leak
- Slow API / latency spike
- Deadlock in production
- DB connection pool exhaustion
- Duplicate payment / double debit
- Race condition in balance update
- Thread pool saturation & rejected requests
- Downstream timeouts & cascading failures
- Data inconsistency between microservices
- Long GC pauses
- Kafka consumer lag
- Intermittent errors only in production
- Processing millions of records (large file / batch)
- Stale cache data
- Production incident handling & RCA
- Deployment strategy & rollback
- Logging & monitoring strategy
- End-to-end performance tuning approach
### Leadership, Agile & System Design

**Topics (19):**

- Tell me about yourself
- Role & responsibilities of a tech lead
- Running technical design reviews
- Handling technical disagreement in the team
- Mentoring junior developers
- Setting code quality & development standards
- Estimation & sprint planning
- Agile/Scrum ceremonies & my role
- Requirement analysis with business/BA
- Handling a missed deadline or scope change
- Prioritizing technical debt
- Handling a production issue under pressure (STAR)
- A challenging bug you solved (STAR)
- System design approach (step by step)
- Design a fund transfer / payment service
- Designing for scalability & high availability
- Why this role / why are you leaving?
- Strengths & weaknesses
- Questions to ask the interviewer
### Kafka & Messaging (JMS, RabbitMQ)

**Topics (22):**

- Why messaging and async processing in banking
- Kafka architecture: brokers, topics, partitions, replication, KRaft
- Producer internals: partitioning, acks, idempotence, batching
- Consumer groups, partition assignment and rebalancing
- Offset commit and delivery semantics
- Message ordering guarantees
- Idempotent consumers and de-duplication
- Exactly-once with Kafka transactions and read_committed
- Spring Kafka producer and KafkaTemplate
- @KafkaListener: manual ack, concurrency and error handling
- Retries and dead letter topics
- Poison messages
- Schema evolution with Avro and Schema Registry
- Retention vs log compaction
- Consumer lag: causes and fixes
- Scaling consumers and choosing partition count
- Kafka vs RabbitMQ vs JMS
- JMS concepts: queue vs topic, sessions and acknowledgement modes
- Spring JMS: JmsTemplate and @JmsListener (ActiveMQ / IBM MQ)
- JMS transactions, redelivery and DLQ
- RabbitMQ exchanges and routing keys
- Transactional outbox with Kafka
### Redis & Caching

**Topics (18):**

- What is Redis and why is it fast?
- Redis data structures and banking use cases
- Common Redis use cases in enterprise systems
- Caching strategies: cache-aside, read-through, write-through, write-behind
- TTL and eviction policies
- Spring Boot Redis cache with RedisCacheManager
- RedisTemplate vs StringRedisTemplate and serializers
- Keeping the cache consistent with the database
- Cache penetration, breakdown (stampede) and avalanche
- Distributed lock with Redis (SET NX PX, Redisson, Redlock)
- Rate limiting with Redis
- Distributed session store with Spring Session
- Redis persistence: RDB vs AOF
- Replication, Sentinel and Redis Cluster
- Redis Pub/Sub vs Redis Streams vs Kafka
- Hot keys and big keys
- Local cache (Caffeine) vs Redis and two-level caching
- What not to cache in banking
### Docker, Kubernetes & CI/CD

**Topics (22):**

- Container vs virtual machine
- Docker image, container, layers & build cache
- Dockerfile for a Spring Boot app
- Docker commands for troubleshooting
- docker-compose for local development
- JVM in containers: memory limits and OOMKilled
- Kubernetes architecture
- Pod, ReplicaSet and Deployment
- Service types and Ingress
- Deployment and Service YAML for a Spring Boot service
- ConfigMap & Secret and Spring configuration
- Liveness vs readiness vs startup probes
- Resource requests, limits and QoS classes
- Horizontal Pod Autoscaler
- Rolling update, rollback, blue-green and canary
- Graceful shutdown in Kubernetes
- StatefulSet vs Deployment
- Helm basics
- Troubleshooting CrashLoopBackOff, ImagePullBackOff, OOMKilled and Pending
- CI/CD pipeline for a Java service
- Observability: metrics, logs and traces
- Git branching strategy, merge vs rebase, cherry-pick
### Testing, Build & Tools

**Topics (15):**

- Test pyramid and what a lead expects
- JUnit 5 essentials
- Mockito: mock, spy, stubbing, verify and ArgumentCaptor
- Unit testing a service layer: fund transfer
- Controller tests with @WebMvcTest and MockMvc
- Integration tests with Testcontainers
- Testing Kafka consumers and async code
- Contract testing (Spring Cloud Contract / Pact)
- Code coverage with JaCoCo
- TDD in practice
- Maven lifecycle, scopes and dependency conflicts
- Maven vs Gradle
- Logging with SLF4J, Logback and MDC
- SonarQube quality gates and static analysis
- Performance and load testing basics

---

## 6. What an individual topic may contain

The exact fields vary by topic. Depending on the content authored for that topic, the Study view can show:

- **Answer:** A direct interview-style explanation.
- **Key points:** Additional rules, caveats, design considerations, or practical reminders.
- **Code:** A Java or configuration example.
- **Expected output:** Output associated with selected runnable Java examples.
- **Follow-up questions:** Likely interviewer follow-ups with short answers.
- **Topic type:** A category such as Concept, Compare, Program, Scenario, Design, or Behavioral.
- **Priority tag:** For example, Must-know or Good.

Not every topic has every field. If a code sample or follow-up section is not shown for a topic, that content was not supplied for that topic in the HTML.

## 7. Search and filtering tips

Use the search box in the top navigation to find terms such as:

- `HashMap`
- `deadlock`
- `@Transactional`
- `CompletableFuture`
- `JWT`
- `Kafka`
- `Redis`
- `N+1`
- `OutOfMemoryError`

Search checks topic titles, the main answer, key points, and follow-up question text. When you type a search term, the application switches to the Study view and shows matching topics. Clear the search field to return to the selected module.

Use the Study filters after searching to narrow the displayed topics further.

## 8. Progress, confidence, notes, and data storage

The application tracks your preparation in the browser.

### What is tracked

- Topics marked Done.
- Topics flagged for revision.
- Confidence ratings for topics.
- Personal notes entered against topics.
- Your selected roadmap start date.
- Selected view, module, filters, and revision pool.

### Browser storage

The HTML stores preparation data in browser `localStorage` using these keys:

- `jlp-state-v1` — completion, revision flags, confidence ratings, notes, start date, and state timestamp.
- `jlp-ui-v1` — interface preferences such as selected view/module/filter and revision pool.

This means progress is normally retained when you close and reopen the same HTML file in the same browser profile.

**Important limitations:**

- Browser storage is local to the browser profile and origin/file context. It is not automatically shared between computers, browsers, or browser profiles.
- Clearing browser site data or local storage can remove saved progress.
- Use the same browser and the same HTML file location/context when you want to continue with the same local progress.
- The HTML includes an optional `window.claude` database integration. If that host integration is available, the app attempts to sync user progress remotely; otherwise, it falls back to local browser storage. A normal browser opened directly on the HTML file should be treated as local-storage mode.
- The small status label in the top bar indicates local/saving/synced status where applicable.

### Back up your progress

Because local browser data can be cleared, keep your own notes separately if the preparation progress is important. The current HTML interface does not provide a dedicated export/import or reset-progress control.

---

## 9. Code examples and Java versions

The content includes Java examples and expected outputs where authored. The HTML marks selected examples with runtime labels such as `java8` or `java17`; the guide itself displays the code and expected output rather than compiling or executing it in the browser.

For independent practice:

1. Copy the example using its Copy control, or select and copy the code manually.
2. Create a Java class in your IDE or local project.
3. Compile and run it using a compatible JDK.
4. Compare the result with the expected output shown in the guide.
5. Modify the example to test edge cases and explain the behaviour in your own words.

Some topics also contain Spring, SQL, YAML, shell, or other configuration snippets. Treat those as learning examples and adapt them to the versions and conventions used in your own project.

---

## 10. Recommended preparation method for a senior/lead interview

A useful way to get value from the guide is to practise at three levels:

### Level 1 — Explain the concept

Be able to define the concept clearly and explain why it matters. Avoid memorising the paragraph word for word.

### Level 2 — Demonstrate with an example

Use the included code, a small scenario, or a real project example. Explain the important lines and expected behaviour.

### Level 3 — Discuss trade-offs and production impact

For senior and lead interviews, go beyond definitions. Explain when you would choose one approach over another, what can fail under load or concurrency, how you would monitor it, and how you would recover safely.

For leadership and behavioural topics, replace generic examples or any `[placeholders]` with truthful examples from your own experience. Structure situation-based answers using the STAR approach where appropriate.

### Daily routine (suggested)

- Study one focused topic group or a manageable portion of a module.
- Explain important answers aloud without reading.
- Write and run two coding exercises when possible.
- Mark progress immediately after studying.
- Spend 10–20 minutes in Revise on flagged/Shaky topics.
- At the end of each week, revisit Must-know topics and topics you could not explain confidently.

---

## 11. Responsive layout, appearance, and accessibility

The HTML includes:

- Light and dark colour palettes.
- Automatic dark-mode support based on the operating system/browser preference, plus explicit theme styles in the document.
- Responsive layouts for desktop, tablet, and mobile.
- A sticky top navigation on larger screens.
- A module rail on larger screens and a selector on smaller screens.
- Visible keyboard focus styling.
- Reduced-motion support for users who prefer less animation.
- Safe-area spacing for devices with display cut-outs.

---

## 12. Technical overview

The application is a single-page, client-side HTML document:

| Area | Implementation |
|---|---|
| Markup | HTML5 |
| Styling | Embedded CSS with custom properties/design tokens |
| Behaviour | Vanilla JavaScript |
| Content | JavaScript data objects embedded in the HTML (`PREP.modules`) |
| Progress persistence | Browser `localStorage`; optional host-provided `window.claude` database integration |
| Typography | Google Fonts: Bricolage Grotesque, IBM Plex Sans, IBM Plex Mono, with system fallbacks |
| External runtime dependencies | No JavaScript framework or package manager required |

### Customising the content

The preparation content is defined in the HTML's JavaScript data section through `PREP.modules`. Each module contains an ID, module number, title, description, and topic array. Topic entries use fields such as:

- `id`
- `title`
- `tag`
- `type`
- `answer`
- `points`
- `code`
- `run`
- `output`
- `followups`

Only fields relevant to a topic need to be present. If you edit topic IDs, keep them unique because the application uses topic IDs to associate completion, notes, confidence, and revision state.

The four-week roadmap is defined separately in the `WEEKS` array. If you add or rename modules, update the roadmap module IDs as needed.

**Tip:** Make a backup of the HTML before editing its embedded JavaScript. A missing comma, quote, bracket, or template-literal delimiter can prevent the application from loading.

---

## 13. Troubleshooting

| Issue | What to try |
|---|---|
| The page is blank or content does not load | Re-download the HTML and open it in a current browser. If you edited the file, check the JavaScript for syntax errors. |
| Progress is not retained | Use the same browser profile and file context; check that browser storage is not disabled or being cleared automatically. |
| Progress differs on another computer | Local browser storage does not automatically transfer. The optional remote sync works only when the expected host integration is provided. |
| Google Fonts do not appear | Check internet access. The page has fallback fonts, so the guide remains usable offline. |
| Code Copy does not work | Clipboard access may be restricted by browser security or file context. Select the code block and copy it with the keyboard instead. |
| The current week is not displayed | Set a Plan start date. |
| Revise says there are no flagged cards | Flag topics or rate topics Shaky, or switch to another revision pool such as Must-know or All topics. |

---

## 14. Scope and limitations

- This is an interview preparation and self-tracking guide, not a complete Java reference manual.
- The guide does not connect to a Java compiler and does not run Java code inside the browser.
- The quality and completeness of each answer depend on the content included for that topic.
- It does not guarantee interview questions, job offers, or coverage of a particular company's interview process.
- The four-week plan is a suggested study sequence; adjust the pace based on your experience and target role.
- Remote progress sync depends on a host-provided integration and is not a general cloud-sync service for ordinary local HTML use.

---

## 15. Final checklist before an interview

- [ ] Complete the Must-know topics in all relevant modules.
- [ ] Explain core Java, collections, concurrency, JVM, Spring, JPA, security, REST, SQL, Kafka, and Redis without reading.
- [ ] Write common coding programs from memory and discuss time/space complexity.
- [ ] Practise production scenarios with investigation steps, mitigation, root cause, and prevention.
- [ ] Prepare truthful project examples for design decisions, migrations, performance improvements, incidents, and delivery.
- [ ] Prepare leadership stories about mentoring, technical disagreements, estimation, code quality, and stakeholder communication.
- [ ] Use Revise until Shaky topics become confident.
- [ ] Prepare thoughtful questions for the interviewer.

---

**Happy learning — understand the concept, practise the example, and explain the trade-offs like an engineer who has built and supported production systems.**
