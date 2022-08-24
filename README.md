# SystemReporter
One from a bit earlier in my dev journey, but probably the most successful! A Web App for reporting to senior leadership on air defence system outages and capability, adjusted for public viewing releasability. Due to the nature of the system it would eventually be deployed on it all had to be written within the HTML files, which made keeping track of variables a challenge in the 1000+ lines.

Whilst it is missing some of the cool radar-range calculation algorithms in this version, it still shows off some DOM manipulation and more advanced use of HTML5 Canvas. 

Personally, it really taught me the value of planning code architecture! The technical debt I left myself when writing the onclick functions using the 'sel' variable was brutal. If only I'd created each object with a 'sel' boolean property I could have made use of some foreach functions...
