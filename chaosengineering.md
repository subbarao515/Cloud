# Chaos engineering 
 * Chaos Engineering involves injecting faults into system
 * It helps to find risks address them before they more significant
    * Discover reliability risks before they cause outages.
    * Recreate past incidents and outages to verify resiliency mechanisms.
    * Validate runbooks and training teams to respond to incidents in a controlled environment.
    * Reduce risks in large-scale initiatives, such as cloud migrations.
    * Reduce revenue-impacting downtime.
 * Chaos Engineering is a preventative practice
 * <b>Fault injection</b> is a technique for causing an intentional failure in a computing component, such as a host, container, or service

## Chaos engineering steps 
 1. Create a Hypothesis.
     * How do you expect your systems to respond to a certain type of fault. 
 2. Define the experiment
    * What type of fault are you injecting and which systems do you want to test.
 3. Observer your system to understand its baseline behavior
    * Use an observability tool to measure key metrics about your system related to the test
 4. Perform the experiment
     * Inject faults to test the hypothesis
 5. Analyze the results
     * Observations gathered during the experiment to determine wheather systems passed or not. What fixed you may need to apply
 
 




