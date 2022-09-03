# changelog

This is a log of what I do ~~every day~~ most days. What tech I work with. And projects I build.

### 2022-09-02
* Doing something one should never do. Writing a date picker. Have a client that
  has a lot of special date issues in their db. The OTS solutions are all just a 
  bit lacking. Mostly just want experience of doing this. 
* Did a survey of website date controls. Southwest Airlines was the best most user 
  friendly. British Airways was dreadful. ALso checked American Airlines, Delta Airlines,
  Hilton and Marriot. Only Southwest Airliens took keyboard input. Accessability?
  American airlines looked like something from the early 2000s. Incredible.
* Built a flexible date parser. All of these work: "12-Sep 2021", "9/12/21", 
  "9/12/2021", "2021-09-12", "9-12-2021", "Sep 12 2021". What it doesn't do, 
  is dd/mo/yyyy format since no parser can tell if it's dd/mm or mm/dd (unless values 
  are out of range). Not great international support, but this customer is US-centric.

### 2022-08-15
* Troubleshot a long-standing but flakey bug in an Agenda.js job. Auth is hard. 
  
### 2022-08-02
* Built a responsive grid system using CSS grid with SASS for a design system. 

### 2022-07-28
* Wrote a complex custom validator for express-validator. 
* Built relational API using Mongoose. `.populate()` is improved, but still needed some manual tweaking for performance.
* Wrote the docs and tests for above. Highly detailed.

### 2022-05-20
* Wrote docs for design system typography styles

### 2022-05-19
* Wrote Node proxy route to third-party API. 
* 3 VueJS SFC compnents to display billing results for users
* Delicious Vue router endpoints

### 2022-05-18
* Troubleshoot a third-party API that was misbehaving and sending out flaky errors
* Build abstract Vue components. Start with generic Javascript classes to handle serializing to and 
  from the API, then display those components with unique UI controls in a Vue app. 
* Document design system typography design tokens

### 2020-11-27
* Setup a **very** basic Jenkins CI service.
* Setup a GitHub Actions service (to compare w/Jenkins)

### 2020-12-23
* Build a custom webpack loader
* Convert an front/back appliation into a monorepo, with Lerna

### 2020-12-21
* Write docs for an API
* User support to solve a bug

### 2020-12-20
* Build a custom Webpack plugin to convert JSON schema into SCSS variables.
* Use color variables in [Sketch](https://sketch.com) for a design kit.

### 2020-12-18
(last couple of weeks)
* Build a JSON configurable menu component in VueJS
* Restructure an app permission model
* Build a mini NodeJS app to interact with Athena Health's API for medical billing revenue cycle. 
* New color pallet for a design system

### 2020-11-13
* Add an upgrade migration to Postgres db
* Build routes in Express
* Build a data access controller uses Postgres transactions

### 2020-11-12
* Add vuepress to a project to server it's docs
* Build a vuepress plugin to extend markdown

### 2020-11-11
* Write content guidelines for a design system
* Postgres data schema (re)design for better performance

### 2020-11-09
* Refactor a NodeJS -> Postgres driver for better performance
  and plug a memory leak

### 2020-10-30
* Refactor and build new VueJS components
* Fix express-validator on an endpoint
* Debug a MongoDB issue casued by a version upgrade

### 2020-10-28
* Write spacing and accessibility docs for a design system
* Test a database->JSON->HL7 interface
* Manual reporting in MongoDB

### 2020-10-27
* Fix an AgendaJS job
* Rewrite a MongoDB aggregation pipeline
* Write typography guidelines for a design system
* Configure NGINX CSP headers
