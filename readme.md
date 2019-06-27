# Voter Turnout is critical 

### The "did not vote" block has the power to swing elections.

Roughly 89% of active Democrats in Queens, NY did not vote in the June 2019 primary election which elected Tiffany Cabán as NY District Attorney for Queens. This means only 11% of all registered Democrats in Queens voted and less than 5% of all active Democrats in Queens selected the winner of the race. 

*editorial* The reason I created the diagram below is to instill hope in those who feel their *"vote doesn't count"*. Note that those who did not vote were the largest block by far. They had the power to swing the election in any direction they pleased. Please [register to vote in your state's primary election or caucus](https://www.usa.gov/register-to-vote), research the candidates, and then get out and vote on primary election (or caucus) day. 

Image: 

![sankey diagram](https://github.com/joedinoto/2019-06-26-NY-Queens-DA-Primary/blob/master/NY%20DA.png)

Data sources: 

https://www.elections.ny.gov/EnrollmentCounty.html
https://www.nytimes.com/interactive/2019/06/25/us/elections/results-queens-district-attorney-primary-election.html

Code for image. Made with http://sankeymatic.com/build/

```
' Type a list of Flows, like this:
'     SOURCE [AMOUNT] TARGET
' Examples:

All Active [766117] Democrats
All Active [128751] Republicans
All Active [27261] Independent 
All Active [257923] Other Parties
Democrats [33814] Winner Tiffany Cabán
Democrats [32724] 2nd Melinda Katz
Democrats [18851] Voted other Dems
Democrats [ 680728] DID NOT VOTE
Republicans [128751] COULD NOT VOTE
Independent [27261] COULD NOT VOTE
Other Parties [257923] COULD NOT VOTE

' After your Flows are entered, use the
' controls below to customize your
' diagram's appearance.

' For even finer control over presentation,
' see the Manual (linked above).
```
