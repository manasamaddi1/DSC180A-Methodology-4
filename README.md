
# DSC 180A — Methodology Assignment 4

**Name:** Lakshmi Manasa Maddi
**UCSD Email:** lmaddi@ucsd.edu 
**Section:** D37
**Mentor:** Renu Raman & Jack Brzenzinski 

---

## Quarter 2 Project Brainstorming

**1. What is the most interesting topic covered in your domain this quarter?**

One topic I found particularly interesting this quarter was learning how AI agents can help organize and connect information across different datasets. In my previous data science projects, I mostly worked with individual datasets, so I hadn't given much thought to the challenges of working with multiple data sources. While analyzing our two cardiovascular datasets, I noticed that even though they included similar clinical information, such as cholesterol levels and blood pressure, the features weren't always recorded or defined in the same way. We also came across some values that weren't clearly explained in the documentation, which made comparing the datasets more challenging than I expected. This experience got me interested in semantic data lakes and how they could help us better understand the relationships between different sources of information. I was especially interested in the possibility of using AI agents to identify these connections and reduce some of the manual work involved in understanding and comparing datasets.


**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

For Quarter 2, I'd be interested in looking at how well AI agents can work with information from multiple cardiovascular datasets. Since we spent most of Quarter 1 understanding the datasets and documenting their features, I think it would be interesting to see how much of that work an agent could do accurately on its own. One idea would be to have the agent compare factors like cholesterol, blood pressure, and chest pain across both datasets, especially since some of these features are recorded differently. I'd also want to compare its findings with the results from our own Python and SQL analyses to check whether it's interpreting the data correctly. We could look at things like whether the agent matches the right columns, understands the different categories, and generates accurate queries. I'm particularly interested in seeing where the agent struggles and whether providing more detailed metadata helps improve its results. I think this would be a good way to continue our work from Quarter 1 while keeping the project focused enough to complete within the quarter.


**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

If I could change one thing about our Quarter 1 approach, I would probably spend more time evaluating the datasets before moving into the technical implementation. When we first started, we were mainly thinking about how to build an AI agent that could extract metadata and understand database structures. But once we started doing EDA, we realized that understanding the data itself was a bigger challenge than we initially expected. For example, one of our datasets had cholesterol values recorded as zero, even though those weren't realistic clinical measurements. We also came across categorical values that weren't fully explained in the documentation. These are details that an AI agent could easily misunderstand if we don't give it enough context. Looking back, I think it would have helped to create a more detailed data dictionary and identify these issues earlier. I would also test the agent on a few columns that we already understand well before moving on to the full dataset. This would give us a better sense of how accurately it's interpreting the data and help us catch any issues early on.


**4. What other techniques would you be interested in using in your project?**

One technique I'd like to explore further is retrieval-augmented generation (RAG), along with tools like LangChain and LangGraph. Since we're working with medical datasets, I think it's important that our agents can refer to actual documentation instead of making assumptions about what certain columns or values mean. Using RAG could allow the agents to look through data dictionaries and metadata when they need more information. I'm also interested in trying schema-matching methods to see how accurately we can identify similar features across datasets, even when they have different names or formats. Another approach I'd like to try is having the agents write SQL queries to calculate statistics directly from the data. We could then compare those results with our own analysis to check whether the agents are getting the correct information. I think testing these different methods would help us understand which approaches work best and where we might still need to make improvements.

