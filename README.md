# PersonalProgression

## Mentoring

- [x] (Software Engineer) Discusses and compares professional development objectives with colleagues and peers.
- I take part of the mentoring program where I discuss my development objectives.
- [x] (Senior Software Engineer) Can conduct 1-to-1's and informal discussions with less experienced colleagues and peers, with a focus on learning opportunities.
- Earlier this year I mentored a junior member for two weeks. Paul and I help set him up, after which I helped him get on the right track towards completing several points of our sprint tasks. I made sure he was always supported and encouraged him to reach out for any advice, help or guidance for learning direction.

Furthermore I supported the Supernova team when they needed help to understand our code better and contribute to our repository to enable their Android-app based insurance.

## Engineering: Code and Design

- [x] (Software Engineer) Is able to consistently write testable, readable code and are starting to contribute to the technical design of the initiatives you are working on and proactively seek answers to technical problems
- I have taken part in multiple projects, writing code as well as tests, and always advocating for readability and reliability. I actively contribute to the technical designs and seek answers to technical problems, proven by my work on the Vortexuliser, which involved my own planning, technical design and reaching out to other teams for any information I needed / any issues I encountered.
- [x] (Senior Software Engineer) Is able to consistently write high quality code across large, complex initiatives and thinks about the whole problem to be solved and the objective to be achieved, not just the code
- One such initiative which I continue to work on is the Insurance Vortexuliser, where I maintain the solution to the highest degrees of quality and reliability, going out of my way to modify third party Trainline libraries to increase our reliability. This enabled the whole process from sending to receiving and then sending again (to Vortex) data events that we use for our statistics and reports.

## Engineering: Non-Functional

- [x] (Software Engineer) Actively considers key non-functional requirements when developing solutions
- [x] (Senior Software Engineer) Incorporates non-functional requirements in to the design of individual components and simpler sub-systems within the Platform

In my work for the Insurance Vortexuliser and Companjon Insurance API I have completed security compliance documents, built code and tooling for software monitoring and metrics (currently in New Relic and Kibana). We always take into account cost, performance and maintainability when implementing any new feature, focusing on loose coupling patterns and trying to keep the code simple and effective. A while ago we had architectural discussions on our chosen storage, and cost is the main reason we went with DynamoDB.

## Domain Expertise

- [x] (Software Engineer) Has a basic understanding of the team's products and services within the organisation.
- [x] (Senior Software Engineer) Has a good understanding of the team's products and services within the organisation.

During my work on the Insurance Vortexuliser, I communicated with multiple teams, acquiring knowledge well beyond what is in the scope for my team, to the point of going into other team repositories and adding features (BackgroundTaskProcessor - enabled DLQ), or fixing issues (Insurance Recommender - fixed faulty circuit breaker causing ERV insurance not to display). I have also become a friend of DietCode and can now release their project to Production.

## Driving engineering best practice

- [x] (Software Engineer) Keeps track of and is eager to make use of the latest engineering best practices being propagated through the tech organisation at Trainline. Suggests improvements to engineering practices to team lead and peers
- [x] (Senior Software Engineer) Pushes their team to adopt accepted engineering best practice and looks for ways to improve existing codebase by retro-fitting best practice approaches. Regularly identifies improvements to best practice and communicates these to their tech platform community. Regularly shares knowledge on best practice within their team.

One of the improvements I suggested and implemented after clear communication was enabling the DLQ in the BackgroundTaskProcessor. I identified that we will need this because of how important Vortex events are to our third-party. Later on, I shared that and other pieces of acquired knowledge throughout the company in a Brown Bag session. Another one was a refactor of our testing structure, as it used to be quite complicated. The latest improvement I identified and we agreed on was making was simplifying the event modification process for the Insurance Vortexuliser.

## Delivery

- [x] (Software Engineer) Is aware of the importance of a delivery focus. Assists on aspects of project delivery.
- [x] (Senior Software Engineer) Is able to manage delivery of their area of the product on a project by project basis.

One of the first projects that I delivered from start to finish was the Vortexuliser, where I setup the repos, developed the whole solution, setup the TeamCity and SpaceLift pipelines and created tools to allow for schema updates. Currently we are working on Inbound Booking Fees, where we split the work into multiple pieces, work and parallel and then join them together to form the complete product.

## Communicating and Influencing

- [x] (Software Engineer) Communicates effectively, clearly, concisely and in an audience-oriented way, in written and verbal form. Actively listens to others and ensures they are understood. Pays attention to nonverbal communication.
- [x] (Senior Software Engineer) Is able to explain concepts (business or technical depending on role) clearly and concisely, understands when detail is needed and when not. Takes and active part in group discussions.

After modifying the BackgroundTaskProcessor and adding additional functionality, I hosted a brown bag, where I went through my reasoning and a short guide on how to use the newly-added features.
One of the main feedbacks that I received from the last quarter was that, while my opinion during group discussions was found to be valuable, I expressed it too rarely. As such, I have focused on taking a more active part in group discussions, so I can contribute and assist my colleagues more with their tasks.

## Initiative

- [x] (Senior Software Engineer) Attempts to solve problems under their own initiative, and is comfortable with the risk of failure.

I am always on the lookout for issues that I can address. One example is the InsuranceRecommender circuit breaker issue, which was owned by a different team. While working on our bit for our project, I noticed that there might by an issue with ERV. After some further research, I was able to log it as a ticket and then later address it in due time, the owning team was very thankful as the change meant ERV was showing more often to customers.

## Hiring and Org Design

- [ ] (Senior Software Engineer) A competent interviewer. Able to follow a structured hiring process, and contribute to the hiring decision.

Currently in the process of applying and learning to interview.

## Architecture

- [x] (Senior Software Engineer) As a senior member of the technology team, you ensure that the technology that you maintain and deliver is aligned to Trainline agreed architectural vision and strategy, and is well described; and contribute to its evolution

One of the highest-quality projects I have delivered is the Insurance Vortexuliser, which includes a very detailed guide. Recently I made a refactor that greatly simplified the complexity of modifying existing schemas or adding new ones.

## Team Leadership 

- [x] (Senior Software Engineer) Capable of informally managing interns, contractors, suppliers and agencies. Doesn't look for glory, and doesn't complain about boring work. Assumes good decisions in others work. Broadly does what they say they're going to do.

This year, with the help of Paul, I helped manage and guide a junior placement in our team for his whole stay here. In his two weeks he managed to complete several of our tech debt tickets, which was amazing!
