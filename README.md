# Tech Startup Maturity Levels
A SaaS software company is formed to mainly build solutions that a target market has demand for. For a tech company to be 
generally successful at what they do, they need to build their software solution in a way that: 

* It continuously delivers value to the end users with best user experience possible.
* It has high quality and it's well-engineered.
* It's scalable, maintainable, and future friendly as much as possible.
* It continuously minimizes time and financial costs during software delivery to increase profitability.
* It continuously drives innovation to be relevant in the ever-changing tech scene.

In reality, tech companies are in the constant battle of time, resources, and deliverables. The product management
team along with tech leadership decides what needs to be done to achieve aforementioned goals. Companies at different
levels of maturity need to be equipped with right technologies and processes to be considered high performing. 

Here is the checklist for every level of maturity of any tech company. The higher level a tech company is on this scale,
the more it's considered a high performing tech organization.

## Level 1
* Use a software development methodology that works for your team.
* Structured goal setting is in place: Using a systematic way of setting goals that drives what is built by developers.
 This brings alignment to all functions of an organization and helps everyone have focus and ensure individual 
 contributors are working on the right thing. Let's face it, building and shipping software is very expensive! therefore,
 building the wrong products or features can really hurt a tech company. [OKRs](https://www.goodreads.com/book/show/39286958-measure-what-matters) 
 are a very handy tool for structured goal setting.
* Extreme ownership in the engineering team: once developers are code complete, they are not done! They are trained to 
have this mindset that they are done once what they are working on is in production creating value for end-users.
* Continuous negotiation with the product team: There is a constant line 
of communication open between engineers and product managers to bring down the feature scope/complexity while not 
drastically minimize the value delivered to the user. The result of this practice is to save time and development costs
while still delivering great customer experience.  
* Using an issue & project tracking software system: Platforms such as Jira enable you to implement the software 
development methodology you are using and ensure any engineering work is being tracked through the entire development
lifecycle.    
* Using version control systems, proper branching and code merging model that works for your team resulting in fast code
integration.
* Using an effective communication mechanism such as Slack.
* Developers can reproduce bugs and test everything in their development environments.
## Level 2
* Everything mentioned in level 1 is practiced.
* A prioritization model is in place: the engineering team is always working on what matters the most. [RICE](https://www.intercom.com/blog/rice-simple-prioritization-for-product-managers/) 
is a very effective prioritization model. Also, product team always ensures engineers do not run out of high priority
work.
* Engineers understand the big picture: technical individual contributors can sometimes get into too much implementation
detail of what they are working on. This results in them losing touch with the big picture and the overall intended value
being delivered. To help with this, we always want to ensure engineers follow the "working backwards" method. i.e. always
asking ourselves "imagine we are done and this feature is live! How would the user use the output of this work and is it 
creating the value the user is looking for?"
* Processes are defined in a way that people are not blocked on each other as much as feasible. Leaders are very 
attentive to the the word "blocked", strive to resolve the situation immediately and place processes in place to minimize
the amount of blockage occurring from the same root cause.
* Genuine care for developer happiness: ensure developers are heard, they are appreciated, their concerns are addressed,
and there is a clear career growth plan laid out for them by retrospective and 1-on-1 meetings. 
* Engineers get architectural design buy-in before implementation: engineers talk to as many colleagues as they can about
how they are going to address a problem before actual implementation. This is to ensure the solution is the most optimal 
and follows the best engineering practices.
* Having a systematic way of communicating internally and external regarding what is going to be built long term and 
short term.
* Application environments are isolated: Modern software systems can consist of many different services. Any instance of
any service running in an environment should be completely isolated from services running on a different environment
(having a test, staging, and a production environment is very common).
* Log application output and and expose them to the team: engineers need to have access to application logs for
debugging purposes. Ideally, logs for all the environments are available through a logging aggregator. 
## Level 3
* Everything mentioned in level 2 is practiced.
* Unify design systems: When building new features, engineers at don't have to think about how the general UI elements 
look like as they use a repository commonly called style guide. 
* Educate engineers to be product-oriented: Engineers building out features are trained to have a passion for the product
as a whole. This helps them make better decisions during development and make the right comprises.
* Build out technology radar: Clearly communicate what tools, frameworks, and languages will be used in the org. 
[Tech Radar](https://www.thoughtworks.com/radar) can be a handy tool regarding this matter. This allows a cohesive 
development strategy and more code reusability resulting in faster product delivery. 
* Develop with SEO in mind: effective tech organizations do not let SEO be afterthought. They are always up-to-date with
 the latest SEO trends and ensure engineers follow them during feature development.  
* Develop with mobile-first mind set: where applicable, all the experiences delivered to the user are mobile-friendly.
* Know your users: start gathering data on how users are using your software while respecting their privacy.
* Feature toggle strategy is in place: there is a way to incrementally and continuously release new features to 
  customers. 
* Zero downtime deployments: when production deployments take place, there is no downtime for current users.
## Level 4
* Everything mentioned in level 3 is practiced.
* Maximize code reusability: for all the back-end, front-end, and infrastructure code there is a strategy in 
place to maximize code reusability across projects.  
* Systematic documentation in place: there is a consistent way of documenting any transferable knowledge across the tech
 organization. The company culture entices engineers to keep the documentation updated as things change.
* Constantly asking and addressing this question: are we automating anything that can be automated?
* Have a systematic way to handle escalations when the software is not working as expected in the production environment
and close the loop with support and non-tech stake holders when issues are scheduled to be addressed. 
* Document production issues caused by human error as post-mortems. This is a mechanism to continuously improve the tech
organization.
* There is a systematic way of training and onboarding in place for new hires. There is also protocol in place to 
knowledge transfer and revoke access rights when people decide to leave the company. Services and tools are registered
using a company identity (e.g. email) and not a specific person's identity. 
* There is a structure in place for engineers to grow in their career.
* Unit tests, integration tests, and end-to-end tests are in place as much as possible to ensure quality and 
maintainability.
* Common data exposure mechanism: if microservices are being used in the tech infrastructure, there is a strategy in 
place to expose all the data endpoints using the same consistent mechanism as much as possible (e.g. consistently use 
GraphQL or RESTful APIs).
* CI/CD: there is a clear operational strategy for continuous integration and continuous delivery of the software.
## Level 5
* Everything mentioned in level 4 is practiced.
* Train everyone to be a leader! As the organization grows, it's crucial to build leadership skills in as many people as
possible. This sense of ownership helps the company to succeed in the long run.
* Monitoring performance and find what's slowing down the system on both the front-end(e.g. using Lighthouse) and the 
back-end(e.g. using APMs). Monitoring service health to be proactive instead of reactive when problems arise 
(i.e. strategy in place to find issues before users find them). There should also be load testing involved as part of 
the monitoring system. 
* Having a systematic way to monitor security and develop with security in mind.
* Engineers and leaders consider the financial cost of any third party service vs ROI and scalability when choosing a 
technology to use. 
* If the organization is involved in building software systems that include different levels of users, there needs to be
 a system in place to let users know, who did what action at what time (i.e. have user activity tracking system in place)
* A/B testing strategy in place: there is a way for the product team to deliver different experiences to different users
where applicable. This is to learn more about what users want, what works for the product, and continuously build the right features.  

Feel free to submit PRs if you think there are items missing in this checklist. If you need help implementing any of the
 levels in your organization, you can reach out to me through my website at [www.mehdi.tech](https://www.mehdi.tech)

