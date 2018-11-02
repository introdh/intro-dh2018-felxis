## Data Corpus

In this analysis, United States Supreme Court cases from different fields of expertise were mapped using network analysis to find underlying correlation between different areas of law. The data itself comes from a project conducted by Washington University in St. Louis, which worked to code every United States Supreme Court case to a specific legal issue, such as education, desegregation, etc.

For this networking assignment I decided to analyze two data sets from the Supreme Court data sets. The two topics I chose were Federal Taxation, typically under provisions of the Internal Revenue Code (120010) and State or Local Government Tax (80100) (for ease, there are instances where I refer to State and Local Tax as SALT). My reasoning for choosing these two topics is because both of these topics interested me, and I was interested in, if any, instances in which SALT laws were cited and used to enforce federal tax laws, or vice versa. My hope, was that correlations found through the network map would bring forth new information about how SALT laws will be written or changed in the future due to the massive recent changes in the federal tax code.

The following network maps were made regarding the analysis.

## Networks

### Plot Year

The data in this network tells us a few different things.

At first glimpse, the plot year network shows an almost even distribution of cases from 1950 to 2000. As long as the United States is around, there will always be tax disputes, especially as tax law is constantly changing, hence the need for dozens of Supreme Court cases to settle major disputes.

Many older Supreme Court cases tend to be on the outskirts of the network. This suggests that tax law was relatively linear in terms of its correlation during the 1950s. These older cases on the outskirts of the network also happen to be fairly linear with their edges. Take the top right of the network, for example. These are older cases that are linearly correlated, which tells us tax law in that decade was stubborn and fairly averse to adopting new tax standards.
![alt text](https://github.com/introdh/intro-dh2018-felxis/blob/master/images/plot%20year.JPG "Plot Year")

Conversely, cases that are more recent tend to be found in tighter clusters with more edges, meaning more cases are highly correlated.

### Plot Issue

The network shows to fairly large clusters of data points, which happen to separate the two issues being analyzed. I was very surprised by this network, I expected the issues to be more intertwined than what this network shows. There is only one SALT case that is close to the cluster of Federal Tax data points. Meanwhile, there are many Federal Tax cases that are close to, or within, the SALT cluster. This means that while some Federal Tax cases are used to decide SALT cases, there are rarely any instances where SALT cases are used in deciding Federal Tax cases. This explanation makes sense because federal law will always trump over state and local law, and the same can be said for their tax laws.

![alt text](https://github.com/introdh/intro-dh2018-felxis/blob/master/images/plot%20issue.JPG "Plot Issue")

### Plot Vote
I thought this network was one of the most interesting networks from this analysis. Cases with more votes tended to be found closer to the center of clusters, while cases with less votes were outside the concentrated areas of the two main clusters. The most important Supreme Court cases that make sweeping changes to tax laws are more likely the be cited in other Supreme Court cases. Realizing this, the Supreme Court acts justifiably by having more judges vote on these cases.

![alt text](https://github.com/introdh/intro-dh2018-felxis/blob/master/images/plot%20vote.JPG "Plot Vote")

### Plot Gatekeepers

I believe this network is the most important in this analysis.

Out of the dozens of court cases relating to all taxes, there are 10 cases that act as gatekeepers, meaning that there are at most 10 pivotal court cases that determine the relationships of all Federal Tax and SALT cases. There is also a healthy distribution of gatekeepers between both issues being studies, confirming an equal amount of edge relationships between SALT cases and Federal Tax cases.

![alt text](https://github.com/introdh/intro-dh2018-felxis/blob/master/images/plot%20gatekeeper.JPG "Plot Gatekeepers")

### Plot Clusters

The cluster network maps a number of communities within the dataset. The network found as many as 16 communities in the dataset. The network itself shows the largest community in the lower left cluster, which also happens to compromise of mostly SALT cases. This could be due to the fact that similar SALT related issues were brought up multiple times, with the only differentiator being the state in which the lawsuit was filed.

![alt text](https://github.com/introdh/intro-dh2018-felxis/blob/master/images/plot%20cluster.JPG "Plot Clusters")

(I tried for 15 minutes to hover my mouse over a data point for the screenshot, but unfortunately I could not get it to work.)

### Plot Centrality

The centrality network graphs the most important nodes in the entire network. Although it is covered by a case name in the screenshot, the centrality of this dataset happens to occur in the cluster in the lower left side of the network, again, which is mostly compromised of SALT cases. This network surprised me more than others. I would have assumed that Federal Tax cases impacted tax law on every level of jurisdiction, causing it to have the highest centrality of all the data points, however this network shows the opposite is true.

![alt text](https://github.com/introdh/intro-dh2018-felxis/blob/master/images/plot%20centrality.JPG "Plot Centrality")

### Plot Co-Citation Issue

I felt conducting this analysis using the co-citations function severly limited the scope of the network, and thus analysis. Out of the dozens of cases coded into these two topic areas, there was only a single federal taxation case that met the co-citation requirements, meaning it was cited in at least nine other cases. With only one federal taxation case correlated to many SALT cases, it is extremely difficult to generalize the relationship for any meaningful analysis.

![alt text](https://github.com/introdh/intro-dh2018-felxis/blob/master/images/cocitation%20plot%20issue.JPG "Co-Citation Plot Issue")
