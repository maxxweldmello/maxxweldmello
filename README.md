<h1 align="center">Maxwel Joseph D'Mello</h1>

<p align="center">
<b>Java Backend Developer</b> · Mumbai, India · <b>● Open to work</b>
</p>

<p align="center">
<code>~2 yrs in production</code>&nbsp;
<code>20+ microservices</code>&nbsp;
<code>150+ REST APIs</code>&nbsp;
<code>Spring Boot</code>&nbsp;
<code>Kafka</code>&nbsp;
<code>AWS</code>&nbsp;
<code>Stripe</code>
</p>

<p align="center">
<a href="https://www.linkedin.com/in/maxwel-dmello-634405203"><b>LinkedIn</b></a> ·
<a href="https://maxfolio-io.vercel.app"><b>Portfolio</b></a> ·
<a href="mailto:maxxdmello777@gmail.com"><b>Email</b></a> ·
<a href="https://github.com/maxxweldmello"><b>GitHub</b></a>
</p>

<pre>
maxxweldmello@github:~/profile$ maxx
&nbsp;
         (   )  (                   maxxweldmello@github
          ) (   ))                  --------------------
         (   ) ((                   Role ........ Java Backend Developer
     _______________                Experience .. ~2 years
    |               |___            Location .... Mumbai, India
    |               |   \           Languages ... Java, SQL, JavaScript/TS
    |   { java }    |   |           Backend ..... Spring Boot, WebFlux, Security
    |               |___/           Microsvcs ... Spring Cloud, Eureka, Resilience4j
    |               |               Data ........ PostgreSQL, MySQL, Redis, Kafka
     \_____________/                Cloud ....... AWS (ECS, S3, Cognito, MSK)
  (_______________________)         DevOps ...... Docker, GitHub Actions, Maven
                                    Payments .... Stripe Connect, Terminal
 __  __      _     __  __ __  __    Testing ..... JUnit, Mockito, Postman
|  \/  |    / \    \ \/ / \ \/ /    Status ...... ● Open to work
| |\/| |   / _ \    \  /   \  /
| |  | |  / ___ \   /  \   /  \
|_|  |_| /_/   \_\ /_/\_\ /_/\_\
&nbsp;
maxxweldmello@github:~/profile$ cat work.txt
&nbsp;
&gt; 20+ Spring Boot microservices on ECS      &gt; Kafka push, SMS and email service
&gt; Stripe payments, webhooks via Kafka       &gt; 13+ production modules, Web Admin
&gt; Cognito + Spring Security RBAC            &gt; 17 fee types behind one JSONB API
&gt; 150+ REST APIs, built end to end          &gt; Async audit logging with Spring AOP
&nbsp;
maxxweldmello@github:~/profile$ █
</pre>
&nbsp;

### 📜 Experience

```diff
$ git log --stat

@@ commit a1f9c3e (HEAD -> main) · Mar 2025 – Present @@
  Java Backend Developer · Kayanak Technologies LLP (Kayana)

  Ordering, payments and fundraising across 20+ Spring Boot
  microservices, deployed via Docker + GitHub Actions to AWS ECS

+ Stripe Connect onboarding, payments & payouts on non-blocking WebClient
+ Stripe webhooks processed into Kafka, matched to orders across services
+ Primary backend developer for 13+ production modules (Kayana Web Admin)
+ Cognito + Spring Security RBAC with instant session revocation
+ Fund transfers across 3 services; webhook race fixed with isolated txns
+ 17 payment fee types unified behind one PostgreSQL JSONB-backed API
+ Kafka notification service: push, SMS, email, scheduled campaigns
+ Kayana Aid: solo full-stack, 150+ REST APIs + Next.js frontend

  payments/   | Stripe Connect, Terminal    ++++++++++++
  messaging/  | Kafka, WebSockets           +++++++++
  security/   | Cognito, RBAC               +++++++
  data/       | PostgreSQL, Redis           ++++++
  4 areas changed

@@ commit 7b2d4e8 · Dec 2024 – Feb 2025 @@
  Application Developer Intern · Go Digital Technology Consulting LLP
  Hands-on project training

+ Real-time collaborative Kanban board (WebSockets, JWT, MySQL),
+ delivered as a feature in a major client project

  backend/    | Spring Boot 3               ++++++
  frontend/   | Angular 16                  ++++
  2 areas changed
```

<table>
<tr>
<td valign="top" width="330">
☕ <b>How I work</b>
&nbsp;

```java
@Component
public class HowIWork {

  String[] workflow = {
    "Understand the problem",
    "Design the API and data",
    "Build it in clean Java",
    "Test with JUnit, Mockito",
    "Ship through CI/CD",
    "Check downstream impact"
  };

  String[] principles = {
    "Own it end to end",
    "Secure by default",
    "Non-blocking where needed"
  };
}
```

</td>
<td valign="top" width="515">
✅ <b>Can they do the job?</b>
&nbsp;

```diff
$ mvn test
  [INFO] Running com.maxx.CanTheyDoTheJob
  [INFO]
+ [INFO] ✓ ownsFeaturesEndToEnd ........ PASSED
+ [INFO] ✓ testsWithJUnitAndMockito .... PASSED
+ [INFO] ✓ shipsThroughCiCd ............ PASSED
+ [INFO] ✓ securesWithRoleBasedAccess .. PASSED
+ [INFO] ✓ buildsEventDrivenServices ... PASSED
+ [INFO] ✓ integratesStripePayments .... PASSED
+ [INFO] ✓ designsSpringCloudServices .. PASSED
+ [INFO] ✓ checksDownstreamImpact ...... PASSED
+ [INFO] ✓ isOpenToWork ................ PASSED
  [INFO]
  [INFO] Tests run: 9, Failures: 0, Errors: 0
  [INFO] Total time: ~2 years
+ [INFO] BUILD SUCCESS
```

</td>
</tr>
</table>
&nbsp;

### ⚙️ Tech Stack

```yaml
# src/main/resources/application.yml
stack:
  languages:     [Java, SQL, JavaScript/TypeScript]
  backend:       [Spring Boot, Spring WebFlux, Spring Security, Spring Data JPA,
                  Hibernate, Spring AOP, REST APIs]
  microservices: [Spring Cloud, OpenFeign, Eureka, Config Server, API Gateway,
                  Resilience4j, Event-Driven Architecture]
  data:          [PostgreSQL, MySQL, Redis, Apache Kafka (AWS MSK), WebSockets]
  cloud:         [AWS ECS, ECR, S3, Cognito, MSK]
  devops:        [Docker, GitHub Actions CI/CD, Maven, Git]
  payments:      [Stripe Connect, Checkout, Subscriptions, Terminal, Payouts,
                  Webhooks, Branch.io]
  testing:       [JUnit, Mockito, Postman]
  ways-of-work:  [Jira, Agile/Scrum]
```

<table>
<tr>
<td valign="top" width="279">
🎓 <b>Education</b>
&nbsp;

```sql
mysql> SELECT * FROM
    -> education\G
*** 1. row ***
 degree: B.E. Information
         Technology
college: Don Bosco
         Institute of
         Technology
   city: Mumbai
  years: 2020 - 2024
   cgpa: 7.25 / 10
1 row in set (0.00 sec)
```

</td>
<td valign="top" width="288">
📬 <b>Contact</b>
&nbsp;

```js
// $ curl localhost/contact
{
  "github": "maxxweldmello",
  "openToWork": true,
  "email":
   "maxxdmello777@gmail.com"
}
```

<a href="https://www.linkedin.com/in/maxwel-dmello-634405203">LinkedIn</a> · <a href="https://maxfolio-io.vercel.app">Portfolio</a> · <a href="mailto:maxxdmello777@gmail.com">Email</a>

</td>
<td valign="top" width="279">
🚨 <b>Open to work</b>
&nbsp;

```diff
- Exception in thread
-   "main"
-  OpenToWorkException:
-  Backend / full-stack
-  roles in Mumbai
   at Career.next()
   at Mumbai.main()
```

</td>
</tr>
</table>
&nbsp;

<p align="center">
<code>Process finished with exit code 0</code> · thanks for stopping by
</p>
