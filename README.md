# product-roadmap
Taking a software product from an idea to deployment.

Need to add: 
- Time estimates
- Better $ estimates
- Marketing Strategy? Or is that covered?

Basic Requirements for any project from idea to deployment:

1. User Research - identify stakeholders and all users

#### 2. User stories (https://www.mountaingoatsoftware.com/agile/user-stories)

These are short descriptions of a product's functionality in customer terms.  A useful structure is: "As a [type of user], [function to perform] so that [business value]".

3. Design and Hard Technical Requirements 

4. Iterate through design → High-fidelity mockups [Coding starts]  

5. Build first basic version of application (the heavy programming lifting)
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
  
6. Continuously deploy until launch. 
  Harden infrastructure and deployment based on potential traffic 
  Plan ahead for traffic spikes
  https://en.wikipedia.org/wiki/Continuous_integration
  
7. Soft launch

8. Fix bugs

9. Hard launch

# At this point, project is live and responsibilities shift somewhat:
1. Site Reliability Engineering  - budget $2k
   Monitor for outages (Pingdom, Pager Duty)
2. Gather analytics - budget $4k
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
 3. A/B testing (Optimizely)


**Two developers, get design firm I work with hard for a couple of weeks to get high fidelity mockups.  Take a couple of weeks.** This is very important.   
