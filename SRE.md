### Site Reliability Engineering 
It fills the gaps between developers, operations, and administration 
* Collaboration
* Integration

DevOps Key principles
* Collaboration between development and operation communication
* Feedback loops
* DevOps pipeline(Build, Test and Deploy)
  
**.Plan/Dev/Build**
   * Shift left model
      *  Shift Left Testing
      *  Shift Left Security

Principles of Site Reliability Engineering   
Mean time to Failure(MTTF)   
Mean time to Repair(MTTR}

SRE
* Minimize errors and failures
* Try to minimize the cost
* operations in right direction
  

Devops
* Accepts the failures
* Gradual changes  

**DevOps Research and Assessment(DORA) Matrics**
* Deployment Frequency--> Low Medium  High
* Lead time for Changes--> Low Medium  High
* Time to restore service -->Low Medium  High
* Change failure rate-->Low Medium  High

**Service Level Indicators(SLI)**
* Request Latency
* Error rate
* System throughput
* Availability
* Yield
* Durability

**Service Level objectives(SLO)**

**Service Level Agreement(SLA)**

**Measuring Service Risk**
* Performance
* Improvements
* Degradations

**SRE Service Life cycle**
 * Architecture & Design
 * Development
 * Limited availability
 * General availability
 * Deprecation

**SRE Impact Measuring**
 * Impact
 * Maturity matix
 * Re-evaluation

**Blameless Postmortem Culture Creation**

** Premortem---> 1. Imagine Failures 2. Work backwards

 **Key Activities**  
     * Analyze scenarios  
     * Determine likelihood  
     * Take preventative actions   
**key Best Practices**
  * Avoid Generalizations.
  * Capture practical and actionable points
  * Consider impact on existing plans
**Postmortem Culture**
* Document learnings
* Disseminate learnings
* Constructive feedback
* Improvement and resilience
* Iterative and collaborative process
* Benefits of Postmortem
   * Share across organization
   * Conduct cross team reviews
   * Hold tranining Excercises
   * Implement weekly reporting 

**Observability** -->Monitoring,Logging and Tracing 
* Pillars of Observability--> Metrics,Logs,Traces

**Event** -->Time stamped   
**Metrics**-->Measured over a time interval  
**Traces**-->Visualize the journey of request or transaction
Distributed Tracing 

**Production Readiness Review(PRR)**
* Service level factors
  * Service-Level Indicator--->Identtify SLI
  * Service-Level Objective--->Measure SLO
  * Service-Level agreement -->Create Service level agreements
* PRR Analysis
  * Service Investigation
  * Checklist Creation
    * General information
    * Development process
    * Architecture
    * Change management
    * Capacity planning
    * Observability
    * Incident response 
  * Identify Deficiencies
  * Refactoring
    * Code review
    * Code analysis
    * Code formatting
** Onboarding process**
 * Operations management
   *  Identify current processes
   *  Identify changes
   *  Training
   *  Feedback 
 * Change Management
   * Models
   * Processes
   * Plans
 * Access management
   * Framework
   * Authentication
   * Access control
 * Backup and recovery management
    * Principles -Data handling
    * Policies
    * Types (backup- full, incremental)

**Measuring Method **     
* Core web Vitals(customer Experience/UX)
* Red method (request Driven)
* Use method (Resource Driven)


**Incident Metrics**   
MTTD-->Mean time to Detect   
MTTA-->Mean time to acknowledge     
MTTR-->Mean Time to Recovery   
MTBF-->Mean time  between failures  

**Toil** --> Reduce or eliminate manaul  or low work tasks 

**SRE team responsible for**
* Availability
* Latency
* Performance
* Efficiency
* Change management
* Monitoring
* Emergency response
* Capacity planning 

**Error rate** =ratio of errors or successes/total number of requests 

**Error Budgets**

1.Define your problem space : SLOs and SLIs

2.Make your system as reliable as it must be but no more

3.Error budgets are your primary basis of communication 

4.SLOs are not set in stone forever

5.The team relationship has be strong to make this work

**The properties of good SLI metrics**

* Has predictable relationship with users happiness
* Show service is working as users expect it to
* Expressed as :Good events/Valid events
* Aggregated over a long time horizon

**Ways of measuring SLIs**
* Request logs
* Application Metrics
* Front-end infra metrics
* Synthetic clients
* Client-Side Instrumentation

**Request/Response SLIs**
* Availability -The proportion of minutes a virtual machine was booted and accessible
* Latency -The Proportion of work-queue tasks that are completed faster than a threshold
* Quality -The proportion of valid requests served without degrading quality

**Data processing SLIs**
* Freshness SLI-The proportion of valid data updated more recently than a threshold
* Correctness SLI-The proportion pf valid data producing correct output
* Coverage SLI-The Proportion of valid data processed successfully
* Throughput SLI -The proportion of time where the data processing rate is faster than a threshold

**Bucketing**
Bucketing simplifies analysis by reducing complexity, highlighting patterns, and allowing for targeted optimization based on meaningful categories.  
**Achieveable SLOs**
User expectations are strongly tied to past performance 




