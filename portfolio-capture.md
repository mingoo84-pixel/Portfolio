# Joseph Mingoo Lee — Portfolio Capture

**Source:** https://www.joemlee.com/ (UXfolio site)
**Captured:** 11 June 2026
**Purpose:** Verbatim reference of the existing portfolio — copy, structure, screenshots, and mental model — to seed a new prototype design.

---

## 1. Global system & visual language

Observed patterns shared across the site:

- **Persistent author badge** (top-left of every case study): circular photo of Joe + "Joseph Lee" / "User Experience | Product designer".
- **Hero pattern:** full-bleed background image or illustration spanning the viewport, with a very large bold title overlaid, plus a one-line subtitle beneath it. Titles use a heavy sans-serif.
- **Entrance animation:** content fades/eases in on load (homepage text appears faint then resolves).
- **Body sections:** generous whitespace; large light-grey section headings; alternating image-left / text-right (and vice versa) layouts.
- **Section heading style:** large, light grey, sentence-case (e.g. "Brief: Create a new Stats panel").
- **Sub-labels:** small bold grey labels above bullet lists ("Project objectives", "Key Outcomes", "Role", etc.).
- **Stat callouts:** big number + small caption rows (e.g. "7 Interviews · 7 AB Tests · 3 Iterations").
- **Stepper / progress nav:** numbered circles (1, 2, 3) joined by a line, marking case-study chapters (Research → Insights → Final Designs).
- **Carousels:** prev / next controls for low-fi concept galleries and side-drawer screens.
- **Back-to-top** floating arrow button bottom-right.
- **Theme varies per project:** most are light (white bg, grey text); "Custom UI modules" is dark (black bg, white text); "Animation and Illustration" uses a night-scene hero + light lavender gallery background.

**Routing:** project tiles are JS buttons ("Open case study X"), not anchor links. URLs are `/p/<slug>`.

---

## 2. Homepage

**URL:** https://www.joemlee.com/
**Title:** Joseph Lee HCD Portfolio
**Meta description:** "I'm a UX designer. I'm passionate about creating usable digital products. I have worked with incredibly talented people across different companies."

**Hero copy (verbatim):**
> User Experience | Product Designer
> Riot Games UX Consultant & B2B Saas Product Designer.
> Joseph Mingoo Lee

**Navigation / links:**
- ABOUT → `/p/about`
- RESUMÉ → PDF (`Joseph_Lee_Resume__2025__iby.pdf`)
- LinkedIn → https://www.linkedin.com/in/lee23joseph/

**Project listing (in order, each a tile with title + one-line descriptor):**
1. **Esports Stats Panel** → `/p/Statspanel`
2. **Multiview** — "How to provide seamless control that is inituitive" → `/p/02f7403c`
3. **Frankieflow** — "A Visualisation of Configuration" → `/p/frankieflow`
4. **Custom UI modules** — "White label modules for Mobile sports streaming" → `/p/moduleUI`
5. **Animation and Illustration** — "Past 12 years of experience in Film and Tv." → `/p/animation`

---

## 3. About

**URL:** https://www.joemlee.com/p/about

**Copy (verbatim):**

> **About me**
>
> I'm a Product/Experience Designer that thrives on clear and simple designs.
>
> I got into UX because of its mix of Design and Psychology.
>
> In the past I have worked at Disney, Pixar and Bluesky studios as a 3D animator.
>
> When I'm not designing I like to go surf, play video games and hang out with family.
>
> My main career goal would be to be in a position where I can make a big impact on a product or service.

(Has a "⟵ Back" control.)

---

## 4. Case Study — Esports Stats Panel

**URL:** https://www.joemlee.com/p/Statspanel
**Hero:** full-bleed Valorant gameplay screenshot with the designed stats panel (left) and live chat (right) overlaid; big white title "Esports Stats panel". Theme: light body.
**Mental model / narrative arc:** Problem (a real discontinued Riot product) → ambiguous brief → research-led → insight → "lightbulb" reframe → final UI. Strongly research-driven; positions Joe as both designer and Valorant domain expert.

**Structure & copy (verbatim):**

**Opening problem statement:**
> Poor adoption lead to Pro view being discontinued in 2022.
> NEWS: 'In February 2022, Riot announced that Pro view will be discontinued'
> Pro view was a paid service which provided extra features to the Esports watch experience. Fans would be able to access live in game stats as well as adding multiple views from their favourite game athletes.

**Brief: Create a new Stats panel**

*Project objectives*
- Understand which stats are useful to fans who watch esports.
- Design/strategise a new stats panel that will sit along side the new watch experience for both League of legends (LOL) and Valorant professional Esports.

*Key Outcomes*
- Conducted our own user testing and synthesized results into a PDF presentation.
- Collaborated on scope and framework for this feature with our client.
- Based off the insights we developed new ideas. These were presented higher up the organisation and there was very positive feedback on our designs.

*Role:* Consultant for Stategy and Design

*Key responsibilities*
- I was responsible for drafting the User test format: User questions, card sorting, survey creation and contextual inquiry format.
- Low fi wireframe and designs.
- Key Valorant stakeholder as an expert on game mechanics - Riot's first person shooter which is also a popular esport.
- Assist developers with any questions.

*Accomplishments*
- Responsible for wireframing all things Valorant in the Stats panel.
- Responsible for creating the Stats module for both LOL and Valorant.

*What was challenging?*
- The ambiguous brief. However we worked diligently alongside Riot's REN team to shape and form the scope of this feature.
- Some user testers were omitted due to no shows or were lying about their experience.

*What did I learn?*
- Defining clear research objectives is absolutely crucial. The setup needs to go beyond the surface level of what you're trying to acheive and understand the whole picture i.e. business goals of the client. This both satisfies the client and who they report to.

**Stepper:** 1 Research · 2 Insights · 3 Final Designs

### Research — Methodology
> Finding pc gamers was very difficult to recruit for, however we managed to find 7 League of legend (LOL) gamers who also watch professional LOL esports as fans.

*Our five step process to the testing:*
- General inquiry: Gaming and Esports habits.
- Contextual Inquiry: We presented the fans with early, mid and late game clips of LOL and asked what was relevant for their understanding of the match.
- Card sorting exercise: We asked the users to sort basic and advanced stats in to groups of most important to least for both early and late game.
- We AB tested some concepts between displaying just numbers only or also bold visual graphs over time.
- We finally asked them to fill a survey on key hypotheses and to rank them from 1-5. (disagree to agree)

(CTA: **View Research PDF** · image caption: "Card sorting exercise")

**Stat callouts:** 7 Interviews · 7 AB Tests · 3 Iterations

### Insights — Our findings
- The importance of a stats changes over time.
- Stats need to address both education and entertainment.
- Stats need to tell a narrative to enhance the viewing experience.
- Too many irrelevant stats are responsible for information overload.
- When to show a stat is as important as to which stats to show.
- Stats should be like a "nerdy" commentator on the broadcast team.
- Bold visualisations are easier to consume than just numbers.

### Ideate — Stats module and Match feed
> One major insight that we found was that fans of the game were too engrossed in the action on screen that there was little appetite to dig through a stats screen that might be 3 levels deep.
>
> Also the timing of when the stat would appear would be super crucial as not all stats are relevant at the start or late game (vice versa). So the timing of when needed to be in context to the action of the screen.
>
> This is when the lightbulb moment happened. The stats panel would be flattened into a stats module of four main categories and also a match feed that would provide extra insight to the action which had just occured. We found that there were lulls in the game where the broadcast and fan could take a break from the action. This provided the opportunity to provide the user with relevant stat information which was also not covered by the broadcast.

*This ticked all the boxes from the insights:* (repeats: importance changes over time; narrative; information overload; when vs which; "nerdy" commentator; bold visualisations).

*The 4 main stat categories which would be relevant at any stage of the match:*
- Accuracy (shot %)
- Damage per round
- Entry success %
- Overall team economy (most recent)

**Low fidelity wireframing**
> This early concept captured the essence of easily accessible information that would be really helpful for a fan to know:
- Stat rankings of accuracy (%), damage (average) and entry success (%).
- Who has the economic advantage each round.
- Who spent the most/least.
- Who clutched the last round and their accuracy% and damage.
- Also who killed who (sometimes it gets chaotic with multple kills going off at once)

> At the top we have the expanded stats module, then the match feed just under it which would be triggered by in game events. These match feed modules provide stat information in a timely consumable format.

*Distinguishing between stat module and match feed areas:*
- Green (Defending) vs Red (attacking) teams change per half.
- To not create confusion there must be order to when these modules appear.

### Final designs
> REN watch experience: The Stat panel will be sit on the left side of the player and can be toggled on/off.
> Final design and delivery of the Valorant stats panel. This will be a scrollable area however the most recent events will always update from the top.

**Final UI for Stats and Modules**
> Collapsed and expanded state for stats. Stats in the collapsed state would focus on the 3 top performers per stat category. In the expanded state it would be Team vs Team with the best formers in the middle.

**Stats feed modules** — triggered by in game events. E.g.
- Economy modules appear at the beginning of each round.
- Round MVP displays after a round has concluded.
- A kill feed module will appear every time an athlete performs a kill in game.

---

## 5. Case Study — Multiview

**URL:** https://www.joemlee.com/p/02f7403c
**Hero:** dual League of Legends streams side-by-side with pin/close controls; big white title "Multiview" + subtitle. Theme: light body.
**Subtitle:** "An exploration on how to give the Users full control while making the experience as intuitive as possible."
**Mental model / narrative arc:** Trend framing (why Multiview matters) → research questions → conclusions stated up front → research → insights → rapid low-fi → prototype → client steer → final anatomy → micro-interaction detail (audio switching) → reflective conclusion. Notable for stating conclusions early, then showing the work.

**Structure & copy (verbatim):**

**Multiview is the future in broadcasting**
> Multiview is fast becoming the newest feature in broadcasting for sports. It does two things:
1. Satisfies Gen Z's high demand for constant stimulation.
2. Perfect fit with the sports gambling cultural/tv media shift

> We were tasked to explore the best experience for Multiview which included:
- What is the best number of concurrent streams on a screen?
- Which audio gets prioritised?
- Is the Broadcast enough, why would viewers want extra POVs?

**Conclusion** (stated early)
- Majority of Users would want 2 streams at most, perhaps even 3 in some edge cases. 4 is just too much.
- Broadcast audio should be prioritised unless the User chooses to deprioritise it for a player POV audio.
- Yes broadcast's are enough. User's have expressed that they are very happy with broadcasted matches. The extra POVs are welcomed though and would be exciting to watch as a side piece.
- As a side note, we found that Users were not that interested in a players face cam POV. This could either be embedded within the player POV but not as a stream itself.

(Image caption: "Multiview in 'Back to the Future' (1985)")

**User Research**
> We conducted research over 1 week with eight participants to canvas attitudes towards 'League of Legends' professional broadcasts. We found:
- Attitudes towards the original broadcast of games was fairly positive. Users felt that the broadcast did a great job in helping understand who was winning and what was happening at any given instance in the match.
- When proposed with the idea of 'Multiview' it was varied as some just wanted the broadcast experience alone but others were excited about the prospect of following their favourite athlete/player for the entirety of a match.

**Insights.**
- Most users would be interested to watch the broadcast as their main video and audio source alongside a second stream with a favourite player POV.
- Multiview is highly desired.
- Keep it simple: Action on a screen is sometimes hard to follow as is, so having four streams playing at once is not beneficial and would lead to cognitive overload.

**Rapid Low fidelity exploration**
> We explored rapidly in Figma of how might we provide instantly feedback to the User by always having the stream viewable. We played around with side and bottom tray menus with the idea of the User selecting a form, i.e. I want 3 streams, so therefore let me select the form of 3 streams and then fill them. We also explored if we could allow the User to add a stream one by one and thus selecting the form in an additive process. However we felt that choosing the form was always the best idea so that each step was clear.
- This would help with the User never losing track of the match.
- Visually clear: watching a new empty stream be added and then filled with their selection would help the user understand the process of adding a stream.

(Captions: "(Some Low-Fi concepts below)", "We felt it was important to not lose the watch experience.", "Bottom tray exploration", "Mobile exploration" — with prev/next carousel.)

**Prototype**
> Exploration of pinning streams and adding streams.

**Final Multiview Anatomy**
> After the prototype above, the Client felt confident moving forward however with one note, they wanted the menu for multiview to be a fullscreen modal experience. Because the watch experience would eventually have 2 side panels, one on either side of the stream for Chat and Stats panel- they felt that another side panel within the stream for multiview would be too much.
> The playback (mouse over) experience remained the same as the prototype.

(Caption: "Client opted for a fullscreen menu experience within the player.")

**Changing audio process** (micro-interaction walkthrough)
> The User wishes to change from Broadcast audio to the POV player Audio
- The User taps on screen for playback controls. Audio icon is active on Stream 1.
- The User then hovers over stream 2, and stream 2 is then highlighted by a white stroke around it. Audio Icon on stream 2 is inactive.
- Clicking over a highlighted stream now activates this audio, the audio icon which was faded is now bold in white.
- Audio now plays from Player POV from stream 2.

(prev/next carousel)

**Conclusion**
> What started out as just a mechanism of adding streams soon became an exercise of adding, removing, choosing audio priority and choosing video priority. There was so much to unpack than the initial brief but we felt confident as a team providing this final solution as best in class.

---

## 6. Case Study — Frankie Flow

**URL:** https://www.joemlee.com/p/frankieflow
**Hero:** the Frankie Flow workflow builder UI — a node canvas ("Workflow Name", Builder/Settings/Versions tabs, Test flow / Launch flow) showing coloured nodes (User Verification, Blocklist, Duplicate List, Risk Engine, KYC, Biometrics, Equifax, Experian, Cascade, Fail / Needs Attention). Big dark title "Frankie Flow". Theme: light body.
**Subtitle / one-liner:** "Frankie Flow: A workflow tool that visualises complex config code"
**Mental model / narrative arc:** Business problem (manual JSON config via Jira tickets) → self-service vision → explain the domain (what JSON config is, building blocks) → test the visual language → wireframe (canvas + side drawer) → UI design with an explicit visual key → candid personal reflection on solo workload / managing leadership → stats → next steps (handoff). The most senior / ownership-heavy story.

**Structure & copy (verbatim):**

**Intro**
> To keep up with Global market trends and demand, I lead the designs for Frankie Flow - A workflow tool that would visualise complex code into delightful and easy to use configuration.
> Frankieone specialises in verifying people (KYC) and businesses (KYB) for companies where accuracy is paramount. Think big banks, crypto and investment platforms needing to verify their customers.
> The premise was that our international competitors had a visual configuration available that their customers could use on the fly to adjust their rules for KYC and KYB. For feature parity purposes we were tasked to create our own workflow tool that leveraged our existing backend processes.
> My role was Lead Designer and at times the Product Owner to keep this project on track.

**Who is this for? — Self servicing as a scalable solution.**
> At Frankieone if our customers wanted to change their settings it would require a Jira ticket sent to our Tech-Ops team and they would manually alter JSON file to reflect the changes and deploy it. This by its very nature was tedious both for the customer and Tech-Ops team but also prone to human error. Further exaserbating the length of time to deploy the config changes.
> By visualising the JSON file into a workflow tool, it would mean the customer would have the ability to change their config settings and deploy their own settings without any internal help from the Frankieone team. This would benefit the workload of the Tech-Ops team but also provide an easy solution for our customers.

**What is JSON Config?**
> A list of Objects that would visualise Configuration into Workflow widgets.

*Configuration — Explained:*
> Configuration is a JSON file that contains product settings for a Client. In this JSON file there are products that may be switched on or off, customisable risk scores, product settings and conditions on how certain individuals/businesses are assessed before and after completing a series of checks which is a process called KYC (know your customer) or KYB (know your business).

*The Challenge:*
> The challenge was to understand the functions of the JSON file and visualise the checks, conditions and services used to perform KYC and KYB verifications. With extensive calls with the Tech-Ops team, a list of actions, conditions, checks and connector objects were assembled. These were the building blocks of configuration.
- **Actions** were terminator objects in the workflow. Whenever an action would be used, the workflow would come to conclusion. (these are used as the end result)
- **Conditions** are objects in the workflow that split the workflow into multiple lanes. Essentially it allowed branching of lanes to create specific criteria that need to be met for a verification flow.
- **Checks** are objects that represent internal product offerings that Frankieone provides that help KYC and KYB. E.g. Biometric checks, KYC checks, fraud checks. These are the core product offerings we provide at Frankieone to verify individuals and businesses.
- **Connectors** are the external data sources that Frankieone utilises to perform the checks.
- **Templates** are like saved config settings made by Frankieone that are a series of checks that are industry compliant for KYC and KYB.

> With the building blocks of config set, it was time to visualise it as a flow.

**Testing the visualisation of objects in a workflow setting**
> To test that the objects were robust enough, we decided to visualise a current config setup of one of our more complex customers. By using the building blocks we assigned shapes and flows to represent what the config was actually doing.

(Caption: "A rough test of visualising config though Actions, Conditions, Checks and Connectors.")

**The Canvas and the Side drawer — Wireframing**
> There were 2 core design components for this design. First was the canvas and the visualisation of the objects. Second was the setup of each object which was conceptualised as a side drawer that would sit above the canvas.

**Designs**
> The inspiration for the Canvas came from Miro and Figjam. It was a space where objects would be visually represented but also manipulated by our customers to place around the canvas in which ever order they wished. These objects would be connected to each other which would provide the eventual workflow.
> The side drawer was directly associated with the objects on the canvas. It provided the framework of adding objects to the canvas but also setting up the rules for each object also.

(Caption: "A very early wireframe of the Object widgets on a workflow canvas")

**Filling in the details**
> Each object that would be deployed on the canvas had to have its own settings criteria so that each configuration variation was available. This proved challenging to visually represent each process to be no less than the actual JSON config file.
> After many iterations and attempts we had finally come to a polished design

(Caption: "Configuration visualised")

**UI Design**
> The UI went through many iterations but the end result I'm very happy with.

*The visual guide:*
- The visual approach leveraged the current styling of the Frankieone products which was bold colouring of objects.
- Distinct colours and shapes represented different catergories of objects that would make objects easily identifiable.
- Blue rectangles represented the Checks.
- Orange Diamonds represented Conditions.
- Actions were represented by pill shapes that were either red, yellow or green (fail, manual attention, pass)
- White rhombus' represented Connectors.
- The Canvas was conceptualised inside a workflow builder which would open a dashboard for the config files to be saved and edited. (this was scoped for MVP 2).
- White circle icons with blue plus signs in the middle were buttons to bring up the side drawer to invite the user to add an object to that workflow branch.
- Users would be able to pick up branches and attach them to other objects on the canvas. (in the future this would need error messaging of what is possible but this was scoped for MVP version 2).
- The Side drawer design allowed the user to add objects to the canvas but also alter the settings within each object. Here are examples of some side drawer screens. (prev/next carousel)

**What have I learnt from this?**
> From the beginning, limited resources were allocated to this project. It was just myself and a Product Manager. Most of the initial work was solely on me to do so I often was left alone to complete the weekly tasks that were directly presented back to company leadership. I took on many hats for this project and at times I was the product owner explaining the complexities of backend processes and how this would be visually represented.
> My biggest hurdle in this project was managing expectations from the company leadership every week. It was very sink or swim situation where I had to learn to adapt to the pressures.
> By speaking the language of CEO's, I was able to manage the expectations and provide status updates each week of the progress that was made.
> Time management and workload was at an all time high as I was across multiple squads and fulfilling their needs as the sole designer. It was very pressure intensive!
> In the end, I am thankful for this experience as I learned a lot on the project. It tested my capabilities and pushed me to go beyond anything I had experienced before.

**Stat callouts:** 5 Iterations · 60 Screens · 10 Weeks of work · 3 Prototypes

**So what's next? — The Project is out of Design and now entering Front End development**
> Hand off to Front end development has been finished. I have provided all the detailed designs specs alongside with our BA's to create tickets for building.

---

## 7. Case Study — Custom UI modules

**URL:** https://www.joemlee.com/p/moduleUI
**Hero:** **dark theme** (black/dark-grey background, white text). Top strip of blurred sports imagery; a phone mockup (right) showing a sports-content app (All Clubs / For You · News · Video · Players tabs, placeholder cards). Big white title "Custom UI modules".
**Subtitle:** "White label modules for Mobile sports streaming"
**Mental model / narrative arc:** Systems / design-ops story — building scalable white-label components. Overview → challenges → goal → the white-label base vs rebranded examples → final UI craft notes → learnings. Less research narrative, more systems thinking and visual craft.

**Structure & copy (verbatim):**

**Overview**
> I was responsible as the Lead designer to take ownership in creating white-label modules that would then be scalable across multiple sports brands and cater for all use cases. This was then picked up by the rest of the design department for rebranding wireframes and also the front-end team to create generic module components that would sync to the backend data streams.

*Some of the challenges of creating a white-label module were:*
- To cater for all types of edge cases such as score, state, player or team and font selection.
- Cater for different rebranding stylisations.
- Design each module to be visually compelling without sacrificing any of the scalable rebranding options.

**Goal**
> The goal was to have a scalable UI module system robust enough to be rebranded seamlessly across an indefinite amount of sports brands willing to integrate into our sports content platform for media and streaming. This involved careful planning so that each module type was robust enough to cater for all types of edge cases and branding styles.

**White label modules / White Label module**
> On the left are the base white-label modules. Each module has its own bespoke content and anatomy setup to perform its function while not being restricted by stylisation

*Examples*
> On the right side are some examples of rebranding sport type, font, colour and stylisation.

**Final UI Design**
> Once the usability issues were resolved, I moved on to design the final screens in Figma. My goal was to create a visual identity that's aligned with the brand's values and message. Also, I've checked the competition and took a deep dive into my catalog of references for inspiration.
- Some of the modules appear to be a frosted glass style to allow the background colour to bleed through, creating a sense of depth.
- Modules followed Material 3 guidelines.
- iOS and Android compatible.
- Users in testing preferred the top pill navigation as it allowed for many sub-navigation options.

(Caption: "(Please feel free to scroll through the designs to the right and below)", "Mobile examples are scrollable")

**Learnings**
- In this instance, function is more important than form, as each module needs to clearly demonstrate its purpose across all brands.
- Potential iterations will need more bespoke modules for each sports brand. Inevitably, repeating the same module will be all too formulaic.

---

## 8. Case Study — Animation and Illustration

**URL:** https://www.joemlee.com/p/animation
**Hero:** illustrated night-desert scene (mariachi character playing guitar by a campfire under a full moon). Big white title "Animation and Illustration".
**Subtitle:** "Past work from 11 years experience in Film and Tv."
**Format:** This is a **showcase / gallery page**, not a written case study. Minimal copy.
**Content:**
- Embedded **Vimeo showreel** (Animal Logic branding visible — LEGO-style 3D animation).
- Section heading: **"Illustration and Design"**
- Below: a **grid gallery of illustration images** on a light lavender (#E8E8F5-ish) background, arranged in a two-column layout.

**Mental model:** Establishes Joe's craft/visual-arts pedigree (Disney, Pixar, Animal Logic, Bluesky) as the foundation beneath the UX work — a credibility and personality piece rather than a process narrative.

---

## 9. Implications for a new prototype

Distilled takeaways to carry into a redesign:

- **Voice:** first-person, candid, plain-spoken; admits constraints and pressures; pairs business framing with user insight. Keep that authenticity.
- **Narrative spine that recurs:** Problem/business context → brief & role → research → insights → ideation ("lightbulb") → low-fi → final UI → reflection/learnings → stats. A reusable case-study template.
- **Signature components to consider keeping/upgrading:** full-bleed hero with bold title + one-liner; persistent author badge; numbered chapter stepper; stat-callout row; alternating image/text sections; prev/next concept carousels.
- **Range to showcase:** consumer/esports product (Riot), complex B2B SaaS tooling (Frankie Flow), design systems (white-label modules), and craft/animation. Breadth across consumer ↔ enterprise ↔ visual craft is a key selling point.
- **Inconsistencies worth fixing in a redesign:** mixed light/dark themes across cases; a few typos ("inituitive", "Stategy", "acheive", "exaserbating", "catergories"); "12 years" on homepage vs "11 years" on the Animation page; the Animation gallery is thin on context.
