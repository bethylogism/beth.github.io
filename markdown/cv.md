# BETH SWINGLER

Senior software engineer. Former neuroscientist & philosopher.

My team vibe is: aim high, experiment, and learn from each other.

---

## Languages

- TypeScript
- JavaScript (ES6+)
- A bit of Scala, Node, PHP, Haskell and Python
- Studied SICP in both Lisp and JavaScript versions.

---

## Testing

- Test-driven development (TDD)
- Unit: Jest
- Integration: React Testing library
- E2E: Cypress & Detox
- Visual regression: Chromatic

## State management

- Redux (Toolkit)
- React Context
- React Query
- SWR

## FE Frameworks

- React (Nov 2018 - present)
- React Native (Apr 2019 - present)

## Platform tools

- Firebase
- AWS (S3 buckets/Route 53 setup, IAM user management, some CI/CD CodeBuild)
- Jenkins (CI/CD)
- Tracking & monitoring (DataDog, Tideways, TrackJS, Sentry)

## Styling

- CSS: CSS3/SCSS/SASS and CSS in JS
- Styled-components
- Tailwind
- Flexbox/Grid
- Storybook

## General

- Git: GitFlow & Trunk-based
- Lerna package manager
- Yarn workspaces
- Webpack
- Matlab
- Vim

## DB toolkits

I have used but am by no means an expert with:

- PostgreSQL
- SQLAlchemy
- MongoDB

## Softer skills

- Public speaking (ReactJS Girls meetups, React Alicante 2025)
- Mentoring (Women Who Code)
- Writing readable docs
- Agile development practices
- Client skills
- Matomo & Google Analytics
- Stand-up comedy

# ENGINEERING EXPERIENCE

## Staff Software Engineer, Ledger (July 2024 - present)

Ledger is a global hardware security company headquartered in Paris.
Domain: Blockchain. Cryptocurrencies. Hardware wallets.

As a staff engineer I've worked across multiple teams within consumer services for buying, selling, and staking assets. Mainly I've created and maintained web applications embedded in Electron and React Native environments, which communicate with hardware wallets for securely signing blockchain transactions. I provide guidance, context, and mentoring to other engineers alongside taking on complex technical projects.

#### Some core achievements

- Built & deployed 2 cross-platform applications with 1.2M daily active users
- Converted passive data dashboard into interactive staking platform for stablecoins and cryptocurrencies. (to enable users to earn interest on their portfolios.)
- Rebuilt the staking flow to handle 3 options: redirections to third-party partner apps, integrations via third-party APIs (+ created a standard for this), and our own internal APIs and blockchain interactions. Increased optionality for the company via a single interface. Designed remote Firebase config that allows rapid release or rollback for any of these options for any currency.
- Standardised E2E testing with Playwright, behavioural tests with React Testing Library, and unit tests with Jest.
- Led initiative to use Mock Service Workers to "shift left" and use realistic API mocks in all of our tests.
- Rebuilt Buy/Sell application from scratch in Next.JS, Redux toolkit. Separated client state from server state.
- Built an internal transaction-crafting system (library? TODO) in a week after an unexpected partner API failure left our newly-created deposit system non-functional on the day of release. (sometimes you just gotta do it yourself, y'know?)
- Negotiated resourcing for tech initiatives to improve performance and UX of the app; with alerting and monitoring to prevent relapse.
- Close collaboration with SRE, data analytics, architecture to achieve & report on UX improvements.
- Interviewing & onboarding new software engineers and technical team leads.

## Senior Software Engineer (Jan 2023 - July 2024)

### YLD Ltd, London

YLD is consultancy specialised in Node.js and generative AI, which is based in London and Portugal. As a senior engineer, my role was to drop into any team to help on a range of projects.

I have worked on multiple projects within one large client at the centre of decentralised finance.

#### Technical contributions:

- Built a dashboard for visualising investments with a focus on growing engagement.
- I led the rebuild & handover of a Next.js app for buying and selling assets at Ledger (their second largest income stream) whilst I was the only front-end developer on the newly formed team. This allowed me to plan and implement a full spectrum of features and capabilities, from Kubernetes infrastructure to the organisation of the repo, configuring efficient cacheing for server state and persistent client state.
- Alongside this, I took ownership of integrating Coinbase into the Ledger platform, in collaboration with a new team. The absence of any documentation or established practices made this an excellent opportunity to create a structured partner integration process. We navigated many complexities and ensured a smooth collaboration between our teams and with stakeholders.

#### On the side:

- Leading workshops in collaboration with head of QA to agree on shared testing strategy across teams.
- Interviewing new engineers from junior to senior
- Contributing to the working group for generative AI initiatives
- Hosting regular Meetups for our ReactJS Girls community. Beyond public speaking and building rapport this also involved helping speakers who wanted to brainstorm ideas for how to present new topics and angles for their ideas.

## Frontend Engineer (Mar 2021 - Jan 2023)

### MySense AI, London

Building a medical product, my role is to develop features & display IoT data for clinicians, NHS staff, and family members on mobile and web.

Occasionally I dabble in Python and Node to help out on the backend, and aim to build some more full-stack features. However, my everyday life revolves around React, React Native TypeScript, Jest, React Testing Library, and Storybook.

#### Some key projects and contributions:

1.  Internationalised the React Native app and main React web dashboard:
    Planned and wrote a series of hooks to represent time-stamped data immutably across time zones, so that it remains in the time zone of the patient.
    Created shared hooks to translate all text copy across apps, including shared NPM modules, using i18n.
2.  Training FE team in Advanced TypeScript, TDD and BDD:
    I lead weekly TypeScript nerd out sessions;
    Presented “lunch and learn” for whole company on Business Driven Development (BDD), joined a “dictionary” project with the business directors and customer journey team, then introduced shared common vocabulary across the engineering teams.
    Created “you can TDD front-end components” video series for the team.
3.  Initiating close collaborations:
    Initiated fortnightly “journal club” to enhance shared conceptual space between data scientists, developers, and designers.

Workflow: Git flow

## Software Engineer (Jan 2020 - Feb 2021)

### MyBuilder.com, London

Contributor on a high-traffic web platform, I worked across 11 web apps and packages within the core monorepo and tributary microservices.
Mainly used React & TypeScript to build new software tools, and some “vanilla” JavaScript and PHP to fix up the older ones.
I created several mobile-first features for progressive web apps that work beautifully on both desktop and mobile.
On-call responsibilities for monitoring freshly released software; setting up new metrics & automated processes to notify the team about anomalies; investigating and resolving bugs.
Event stream processing: storing and reducing large amounts of historical data to ensure backwards compatibility of past quotes, invoices and legal documents.  
Learnt how to use test-driven development (TDD) to aid everyday problem-solving, not just to increase test coverage.
Overhauled our core marketplace app (where all the money is made) from React 15.4, bringing it up to 17.1 in one feil sweep. (Refactored out 6,000 lines of code in the process).
Gained comfort with the React Context API and deeper knowledge of Redux for managing state.

Workflow: Trunk-based

## Frontend Engineer (April 2019 - Jan 2020)

### Constellation AI, London

Mobile app development in React Native with Redux for state management.
Made small modifications to Python API endpoints.
Collaborated with data scientists on research into cognitive models to make the AI more engaging to the user.
My main project was to visualise the machine learning data. I consumed complex data from sentiment analysis, entity recognition and topic detection models, and created a iconographic system to reflect insights back to the user.
Initiated practices to enforce clean, consistent naming to optimise our AI data for API endpoints.
I also led a small, internal, full-stack project for monitoring the health status of each Docker pod. This was an end-to-end project where I devised the UI design, internal UX, and API endpoints for the final React desktop web app, set up a CI/CD pipeline in Jenkins and deployed using AWS.

NB: Operations ceased in UK and moved to Silicon Valley, USA

Workflow: Git flow

## Software Engineering Immersive (Nov 2018 - Mar 2019)

### General Assembly, London

Full-stack bootcamp. Daily stand-ups, time-pressured collaboration, self-organised sprints, and learning JavaScript, Node, React, Python and SQL with extreme speed.

In the 3 months, I completed 4 projects (1 JavaScript and 3 full-stack):

1.  JavaScript game

- Vanilla ES6 web-basded game for playing “Mastermind” with CSS3 animations.
- [Play](https://bethylogism.github.io/WDI-project-01/) | [See code](https://github.com/bethylogism/WDI-project-01)

2.  RESTful app

- React web app consuming data from two public APIs to create a map-based events app.
- [Visit](https://react-events-now.herokuapp.com/) | [See code](https://github.com/bethylogism/WDI-project-02)

3.  Full stack React web app with hierarchical DB

- React web app with a MongoDB database and Node/Express back-end.
- [See code](https://github.com/bethylogism/wdi-project-3)

4.  Full stack React web app with tabular DB

- React web app with SQL database and a Python/SQLAlchemy backend.
- [Visit](https://sunset-barlevard.herokuapp.com/) | [See code](https://github.com/bethylogism/wdi-project-04)

---

# ACADEMIC DEGREES 

## 2014 - 2015

### University College London (Institute of Cognitive Neuroscience)

#### Master of Research (MRes) - Cognitive Neuroscience

Research-focussed Master of Science programme, in collaboration with the Engineering faculty.

16,000 word dissertation on using near-infrared spectroscopy to measure dorsolateral prefrontal brain activity (during meta-cognition).

Additional modules included statistical analysis and experimental design

##### Publications: 

1. [Journal of Visual Exp. (2015](https://pubmed.ncbi.nlm.nih.gov/26651025/));
2. [Neuroimage (2017](https://pubmed.ncbi.nlm.nih.gov/28476662/));

On the side, performed stand-up comedy in monthly nerd-fest [Science Showoff](http://www.scienceshowoff.org/)

## 2008 - 2011

### University of Cambridge (Fitzwilliam College)

#### BA (Hons) – Philosophy (High 2.i)

Firsts achieved in 5/6 papers. 
Logic & Metaphysics paper (Can Qualia be Functional States?) accepted for Philosophy Conference at Brown University, U.S.A.

---

# PRIOR PROFESSIONAL EXPERIENCE

## Head of Digital (Nov 2015 - Nov 2018)

### Harley Academy, London

As the first and only employee of this start-up for the first 9 months, I was privileged to be a core part of its rapid transformation into a 40-employee business with multi-million-GBP annual turnover.

- Initially hired for R&D, I co-authored a Level 7 (master’s level) medical qualification alongside creating and optimising several iterations of the company’s Wordpress sites.
- Responsible for SEO, content, speed, and rankings, I increased web traffic from 100 to 15,000 monthly users in 2 years (25% compound growth per quarter in 2018.)
- Heavily involved in the CMS of several websites, installing and testing plugins, setting up pixels, and tweaking front-end HTML/CSS/PHP.
- Liaised twice weekly with the development team responsible for creating and maintaining the backend technical stack to collaborate on new features and improvements to security, encryption, data storage, UX, UI, and customer journey.
- Strategised quarterly content plans combining medical literature and target keywords.
- Managed a team of content contributors & external copywriters.

## Science Events Producer (2012 - 2014)

### Institute of Art and Ideas, London

Curated over 180 debates on contentious scientific topics.

- Owing to my success at securing nobel laureates and top-tier speakers such as Roger Penrose, George Ellis, Lawrence Krauss, and Martin Rees, I received very early promotion (within 3 months), led a team of 4, and trained new interns in the combined arts of persuasion, technical brief-writing and crowd management.
- Initiated the first series of science events at HowTheLightGetsIn philosophy festival, Hay-on-Wye (sold-out in their first year, 2013).
- This role demanded rapid research into very wide ranging topics from mathematical physics to epigenetic neurobiology so that I could conduct back-to-back technical and philosophical conversations with experts in these fields every day.

## Technology Analyst (Jun - Sep 2010)

### Accenture PLC, London

Formal training in technology-focussed business practices and client skills.

- 8-Week project: developing an internal HTML wiki containing guidelines, best practices and insights I gathered from (and for) Project Managers at a FTSE 100 pharmaceutical client.
- Received an award for high performance; offered a permanent position with Accenture.

# SAY "HELLO"

- [beth.swingler@gmail.com](mailto:beth.swingler@gmail.com)
- +44 7870 681 920
- [github.com/bethylogism](https://github.com/bethylogism)
