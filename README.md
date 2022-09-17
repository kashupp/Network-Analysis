# Network-Analysis
Network-Analysis
PageRank and HITS algorithms calculates important measures about structure of a network. They are applicable in network biology (e-g protein protein interaction analysis) as well as web structure analysis.
PageRank was presented by Sergey Brin and Larry Page at the Seventh International World Wide Web Conference (WWW7) in April, 1998. Google search engine was built on the basis of this algorithm.

PageRank interprets a hyperlink from page A to page B as a vote, by page A, for page B.
Instead of only counting votes, it also analyzes the page that casted the vote.
Vote casted by a page that are themselves important weigh heavily.
The casted vote helps to make other pages more important.
 
<img width="250" alt="image" src="https://user-images.githubusercontent.com/56387631/190867007-d3c2bfd8-b1d2-4611-813f-a5016825b6b3.png"> 

A HITS Algorithm is a link-based object ranking algorithm proposed by Jon M. Kleinberg 1998 at Cornell University.
The central issue HITS addresses is the distillation of broad search topics, through the discovery of “authoritative” information sources on queried topics.

Authority: 
An authority is a measure of in-links of a page. The idea is that a page may have authoritative content on some topic and thus many people trust it and link to it.

Hub:
A hub is a page with many out-links. The page serves as an organizer of information on a particular topic and points to many good authority pages on the topic.
It is a part of Ask search engine.

<img width="450" alt="image" src="https://user-images.githubusercontent.com/56387631/190867017-612da295-5b23-4a5d-8c88-e6a09d09ae85.png">

 


