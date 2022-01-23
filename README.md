# TestRail_Performance

Test plan of performance testing of TestRail for the folowing endpoints:

- create project;
- update project;
- get project;
- delete project;
- list of active projects.

This plan contains authorization manager, timer for delays between requests, configureted theread groups and response assertions.
To start performance testing, we need to open the file in Apache JMeter and start the scenario. The results of testing are saving to the local computer (as .csv file) and displayed as table and graph.

## Requerements

- Java 8 or above
- Apache JMeter 5.4.1
- Stable internet connection
