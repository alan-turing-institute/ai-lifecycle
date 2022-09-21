# Definition of Categories
###### tags: `organisation`

## List of Categories and Case Studies

- [Recognition: Autonomous vehicles](https://hackmd.io/@ailifecycle/HkWrDySZq/edit)
- [Event Detection: Smart City Infrastructure]()
- [Forecasting: Predicting the effects of interventions on health outcomes](https://hackmd.io/@ailifecycle/By-JSNAe5/edit)
- [Personalisation: Price Discrimination](https://hackmd.io/@ailifecycle/B1dtw4Ae9/edit)
- [Interaction Support: Generative Design]()
- [Goal Driven Optimisation: Agriculture]()
- [Reasoning with Knowledge Structures: LawTech]()

# Definition of Category Section

:::success
**Typical Structure for Definition**
- Intuitive (non-technical) definition/explanation
- Illustrative example
- Typical application and structure in DS/AI
- Common techniques
:::

<!-- Mention that these categories are not mutually exclusive. -->

### Recognition 
Recognition involves sorting different objects or persons into particular categories (for example, sorting an individual into a specific group). In the context of artificial intelligence, it deals with the identification and classification of (generally) unstructured data into specific categories. 

Recognition has a wide range of applications which depend on the type of data being classified (text, images, videos, audio, etc.). The output of the task is usually a label or tag which categorises the previously unstructured data. For example, in image recognition the label might be "This is a tree", in audio recognition, "This is the sound of a barking dog", and in handwritting recognition "This is a letter C". The most common type of AI technique used for recognition are convolutional neural networks (e.g. facial recognition).

A model or system can be defined as recognition if it takes (generally) unstructured data as input (D) and generates an output variable (O) that is a label which classifies D into a particular category.

<!-- Facial recognition -->
<!-- image recognition -->
<!-- Autonomous cars -->
<!-- Handwritting (detect strcuture in the writing: ex, social sec number, table etc) -->
<!-- sound and audio rec: music, speech, languages, animal noises, car noises?, -->
<!-- gesture recognition (video game industry, retail, surgeons, sign language) -->
<!-- emotion recognition -->
<!-- medical imaging (spot anomalies) -->
<!-- help identify counterfeit products (fabric, drugs, digital copyright infringement) -->
<!-- insurance -->

### Event Detection 

<!-- Start with basic (non-AI) definition. -->
In its simplest form, event detection involves connecting data points to detect an event. 

Event detection allows for anomaly detection, ie finding an anomalous data point or pattern in a given data set. It is often used in areas such as fraud detection, health diagnoses, or intrusion / security detection. Data can be pre-labelled (ie supervised), semi-labelled (semi-supervised), or unlabelled (unsupervised), depending on the level of direction the algorithm is to have in detecting an event.

<!--For case study: 

There are three types of anomalies commonly seen. A point anomaly (aka global outlier) occurs where certain data has different attributes from the set in a single instance. A contextual anomaly (aka contextual outlier) occurs where certain data is anomalous in a given context—and without that context, the data might not seem anomalous, eg weather temperature spikes relative to historical data. And a collective anomaly (aka collective outlier) refers to a subset of anomalous data.-->

### Forecasting
Forecasting involves the prediction or estimation of a future event or phenomenon. This could include the prediction of future trends in house prices, or an estimation of the rise in global temperatures over the next 10 years as a result of climate change. 

In the context of artificial intelligence, there are many techniques that could fall within the category of 'forecasting' because of the manner in which they are deployed and used. For example, a  decision tree model could be used within a system for triaging patients during admission to hospital, based on the severity of their presenting symptoms, to predict the risk of their symptoms worsening. The use of this model within the hospital is for forecasting health outcomes and supporting the allocation of limited resources.

In more general terms, a model or system can be described as forecasting if it takes some historical input data (D) and generates an ouput variable (O) that represents an estimate or  probabilistic value about a future trend or event.

### Personalisation 
In a general sense, personalisation is the targeting or adapting of some behaviour or outcome to a specific individual. In the context of AI, personalisation occurs when an algorithm learns about an individual's profile in order to taylor the services or products offered to that person. 

A range of AI techniques can be employed in personalisation, but the most common are modelled-based algorithms which create a model of the specified individual. Other techniques include collaborative methods or content-based filtering. The output usually involves some form of ranking.

Recommendation systems are a well-known application of personalisation. For instance, an algorithm can provide recommendations on what content to watch or listen to based on a consumer's previous browsing or purchase patterns.



<!-- Finance
Medicine
Advertising -->
### Interaction Support 

Interaction support--sometimes referred to as interaction analytics--uses AI to power interactions between humans and machines. This can take place across a range of media such as voice or visual content.

Algorithms convert data from multiple sources such as social media posts, texts, emails, etc into a structured form that can be sorted, searched, and analysed. Interaction support software is often used to measure the effectiveness of machine-assisted customer support channels, as well as to extract analytics data.


### Goal-driven Optimisation [work in progress]
As it names suggests, goal-driven optimisation involves finding the optimal solution to a problem. An AI system is given a goal, and the solution is found through an iterative process of trial and error where the program learns what the best course of action is. This allows the AI to arrive at solutions which are not obvious and completely innovative. 

One of the most common artificial intelligence techniques in goal-driven optimisiation is reinforcement learning. A system is given a goal plus a simple set of rules, and then it is allowed to learn through trial and error. It uses feedback from its environment to learn which strategies work and which do not, all the while advancing towards its set goal. 

Classical examples involves game-playing AI, such as Alpha Go and Alpha Zero. The AI system is given very basic rules and a goal to achieve (in this case win at Go), and then learns how to play through iteration (playing the game multiple times), thus finding completely innovative moves and strategies. Its application is not confined to game-playing AI though, as it can help solve complex problems in supply chains or logistics, as well as make huge strides in previously unsolved problems such as protein folding.


### Reasoning with Knowledge Structures 

Reasoning with knowledge structures involves inferring new outcomes that are possible even if they are not present in existing data, through modelling and simulation. 

One example is where an algorithm is used to link constitutions and conventions, laws, case law and legal theory. This is often done in order to generate document templates (court applications, lease agreements, etc.). More complex algorithms can go even beyond this and allow for anticipating legal outcomes. 

For instance, the statistical processing of word groups in case law reveals the relevance that certain concepts might play in deciding a case. Here, an algorithm can build links between the different lexical groups composing judicial decisions. Predictive justice software uses either generative (ie Bayesian) or discriminative reasoning, which estimate the range of possible values for a given variable—such as the outcome of a trial—based on antecedents. 

Ethical questions concern the extent to which a human should be responsible for carrying out legal analysis.
