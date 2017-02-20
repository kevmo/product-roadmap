# product-roadmap
Taking a software product from an idea to deployment.

Product Roadmap for Upsolve

Need to add: 
Time estimates
Better $ estimates
Marketing Strategy? Or is that covered?

Basic Requirements for any project from idea to deployment:
User Research - identify stakeholders and all users
User stories (https://www.mountaingoatsoftware.com/agile/user-stories)
Design and Hard Technical Requirements 
Iterate through design → High-fidelity mockups [Coding starts]  
Build first basic version of application (the heavy programming lifting)
General design principles: https://12factor.net/
Front-end - open source software
HTML, CSS, and JavaScript
Either Wordpress/Drupal or JS framework like React, Ember, or Angular
Backend - RESTful API
Either use Python (Django or Flask) or Node (Express) [NOT rails]
Postgres Database
Set up continuous integration for rapid iteration and future bug fixing - open source
Jenkins (CI pipelines) + Ansible (deployment scripts)
If electing Heroku, you will bypass this step.
[have staging and production environments]
Use git flow - Build new features using git flow practice + semantically versioned releases. (http://nvie.com/posts/a-successful-git-branching-model/)
Infrastructure (i.e. how do you actually get this on the internet)
Amazon Web Services or Heroku or Aptible
Costs may vary, but I would allocate $12,000 to be safe.  (could come in way less)
Heroku is more expensive, but simpler.
Issue tracking software
JIRA - $100/year
Continuously deploy until launch. 
Harden infrastructure and deployment based on potential traffic 
Plan ahead for traffic spikes
https://en.wikipedia.org/wiki/Continuous_integration
Soft launch
Fix bugs
Hard launch

At this point, project is live and responsibilities shift somewhat:
Site Reliability Engineering  - budget $2k
Monitor for outages (Pingdom, Pager Duty)
Gather analytics - budget $4k
Google analytics
New Relic This should be part of Site Reliability Engineering
Custom backend tracking (can have a hidden admin page with statistics) See above.
Segment.io?
Salesforce?
Crazyegg
Intercom for support ( if needed )
Mixpanel
Kissmetrics
Heap Analytics
A/B testing (Optimizely)


Employee Costs - salaries.  Can divide 
CTO - $120k budget.  May be able to get a do-gooder for less, but you’re playing with fire there.
Developer - 120k budget. May be able to get a do-gooder for less, but you’re playing with fire there.
UX/UI Designer  - design firm or freelancer for around $15-30k.  May play dev role and QA role.
QA Engineer or specialist - $40K TO $80K.  Possible to forgo this if non-technical employees willing to be thorough and CTO trains and harders processes. [I can get by without if I do this - go to training for a day]

A lot of bugs from one developer.  

**Two developers, get design firm I work with hard for a couple of weeks to get high fidelity mockups.  Take a couple of weeks.** This is very important.   

Have CTO/Developer, build 1 to 3 months.  Will cut a lot of corners.  

A combination of CTO and dev for a couple months.  



