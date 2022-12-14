---
title: FoodPrint

author: Jiexin

date: 2022-12-10
typora-root-url: ..
---

![foodprint](/assets/img/foodprint1.png)

# Team

Jack Hatcher - Architecture

Jialuo Mu - Management Information System / Finance

Jiexin Ding - Computer Science and Technology

### My role:

No official role was assigned to the 3 of us. In the stage of framing and scoping, I researched paper in the food area and summary the secondary research. Then, we all took part in the process of investigation and analyzed  requirements. In the solution and evaluation part, I designed the search page and shopping list page for our evaluation and conducted the usability test with my teammates.



# Design Question

#### How might we enhance college student’s food purchase planning experience to encourage them to choose low carbon options to reduce their contribution to greenhouse gases?



# Reason for focusing on this space

<img src="/assets/img/intro.JPG" alt="intro" style="zoom: 40%;" />

The choice of food can have a large influence on carbon emissions. The potential reduction of carbon emissions from people choosing low-carbon foods is significant enough to encourage everyone to make better decisions in a manner that cannot apply to other systemic forms of carbon emissions. 

<img src="/assets/img/intro_gap.JPG" style="zoom:33%;" />

Instead of just providing a carbon label, we aim to find a more efficient and practical approach to encourage more sustainable food purchasing decision-making among University of Washington (UW) students.

**Reflection: Food area is a very common area that we engage in very day. All members of our teams are interested in it. We found many evidence that support the relationship between the carbon emission and the food.  However, there are many different opinions about how the food is related to the carbon emission. In the future, we should compare different opinion in detail to have a better understanding.**



# Investigation

![intro_gap](/assets/img/insight.JPG)

## Secondary Research

* Food and grocery products do contribute a lot to carbon emissions. The food chain contributes to 26% of anthropogenic greenhouse gas (GHG) emissions (Poore & Nemecek, 2018).

* It is possible to reduce 70% to 80% of greenhouse gas emissions from the food system by switching to a low-carbon diet (Hedin et al., 2022).

* The existing solutions are based on carbon-label, either on packages of food products (Thøgersen & Nielsen, 2016) or in the shopping app (Fosgaard, 2021), but they are not very effective (Panzone et al., 2021). 

* There are 49,522 students enrolled in the Seattle campus in 2022 fall (Holtz, 2022).

* UW has a sustainability strategy including decarbonization and is going to double student, staff, and faculty sustainability impressions by 2024 (Eklund, 2020).

* There are many student organizations calling for environmental protection. It reflects students’ positive attitudes towards low carbon (*Sustainability Student Groups*, 2022).

  

## Field Study

![](/assets/img/field_study.JPG){:width="972" height="589" .w-50 .left}

* Students either knew exactly what they wanted and went directly to the shelves or wandered a lot.

* Students tended to buy more pre-made food rather than raw ingredients.

* A significant number of people actually seemed to check labels/packaging. At WholeFoods, people were more likely to check labels than at other grocery stores.

* Except at Whole Foods, people didn’t use cart / baskets / bags. They picked up what they wanted very quickly and held them in their hands.

  

## Survey

![](/assets/img/survey_consideration.png){:width="972" height="589" .w-50 .right}

* Students’ main consideration when buying food is flavor followed very closely by price. Of medium importance were time to prepare, diet, and nutrients.

* Carbon impact was the least important consideration ranked by students. With so many considerations weighing on students at any given time, it’s understandable that they aren’t actively thinking about their carbon footprint with every meal.

![](/assets/img/survey_media.png){:width="972" height="589" .w-50 .left}

* For our respondents, food education is inherently social. Students claim to learn about food from social media, online, and from friends and family. 
* It may be possible to leverage existing social networks to spread awareness about the importance of the carbon impact of food.

![](/assets/img/survey_list.png){:width="972" height="589" .w-50 .right}

* Most students do sometimes keep a grocery list when food shopping. When students write a grocery list, they do so either when they run out of items, or right before shopping.
* A phone app is the most common way to keep a grocery list, followed by memorizing the list.



**Reflection: we only observed during 4-6 pm in the field study, so our results can only represent users' behaviors in that time. We got some insights from our field notes, but we didn't focus on them when we designed our survey. It caused that some of our questions is not helpful for the brainstorm.  Besides, we should recruit more undergraduate students on main campus to take our survey.**



# Requirements

![](/assets/img/requirements.png)



# Ideation

![](/assets/img/ideation.png){:width="459" height="300" .w-50 .left}

We came up with three scenarios including on campus and at home. We also consider users that have and don't have the habit of using shopping list. We decided that our product would be an phone app which is the most common ways from which students learned cooking and ordered food. The app should have the features of ordering food and making a shopping list.



**Reflection: we all sketched in this step. It was very helpful because we considered different aspects of our problem and my teammates' sketch expanded my thinking.**



# Prototype and Evaluation

## Prototype

We decided to create a digital medium fidelity prototype to test since we planned the final project to be a phone application that most college students are familiar with. The prototype was an interactive user interface by Figma and it allowed users to experience the flow of interaction quite like a real app. The prototype included a home page, a search page, an item page, a map page, and a shopping list page. The first four pages were used to test the process of picking up foods when students were in a hurry. The last page was aimed to test the shopping list function. There were pictures of foods, labels of carbon-level, nutrients and calorie information and distance estimation on pages. Participants can click the hot-spots to interact with our prototype.

![](/assets/img/prototype.JPG)



**Reflection: our solution is very straight-forward. However, due to lack of communication, the interface styles made by different team members were not uniform in the end. The work flow of the app is also a little bit confusing.  The good things is that the prototype we made using Figma is very easy to use and close to an actual app.**



## Evaluation

Our main purpose was to evaluate student’s understanding and prioritization of carbon data when integrated with a regular food ordering system. If our app could actively encourage students to collectively make lower carbon impact food purchasing decisions then we could have a significant impact on the carbon footprint of the University of Washington and influence the surrounding market to be more environmentally considerate. 

![](/assets/img/evaluation.png){:width="972" height="589" .w-50 .right}

Key research questions include:

* Do the participants notice the carbon labels in the search results?
* Do the participants understand the meaning of the carbon labels?
* Will the participants select the suggested low-carbon option at a higher price, or will they scroll down to the bottom of the search results to select an option that is cheaper with a worse carbon score?

Key usability findings include:

* Users care more about price, distance, and calories than carbon emission data.
* Users have trouble understanding the carbon emission labels like the red icon or ‘D’.
* Users prefer to interact with recommended foods rather than search for them.
* Users care more about the general shopping function which should be the foundation of the app.
* Users think that the flow of purchasing needs to be better.

Recommendation summary:

* Focus on the shopping function of this app.
* Simplify the checkout flow.
* Improve clarity of labels, e.g. carbon emissions, calories, and price.



**Reflection: our app has two major functions but most of our tasks focused on the first one and only two tasks was about the second one. This made some of our participants really confused. Besides, we should printed out our instructions for users, so it was more easy to read and follow. Fortunately, most of our users could understand our purposes in s short time. It would also be ideal to be able to test the app for an extended period of time with a small number of participating shops and students before launching it for everyone to use.**



# Overall Reflections

* In this class, I experienced the whole process from understanding a question to figure our a solution. Some investigation methods such as field study and affinity diagram offer me new tools to understand the problem.
* The solution that come at the first place are not always a good one. I need to analyze the problem in various way before I start to think about solutions.
* I need to combine both convergent thinking and divergent thinking in this process. I needs to adjusts my thoughts depends on which stage I'm in. Opening to different opinions is helpful to get more insights and focus on some results is helpful to dig out the requirements.
* The ability to re-frame a problem is an important ability. It is based on the deep understands of a problem. It is necessary to get the real solution not the most obvious one.
* It is almost impossible to come up with a good solution at the first glance, so the iteration is very important. Imperfection is norm and we should be comfortable with it.
* Everyone thinks and works in a different way. I need to understand other people's ways to collaborate with them more effectively.

