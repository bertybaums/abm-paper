ABM Paper Notes

# CPF

In 2014, The Monist will publish an issue devoted to Models and Simulations. Submissions are invited for this issue with a deadline of October 31, 2013. Prospective authors are encouraged to contact the Advisory Editor, Paul Humphreys, University of Virginia (pwh2a@virginia.edu) for further information and to ensure suitability of content. Papers must have a maximum length of 7,500 words and all submissions will be refereed by external referees. A brief description of the scope of the issue is as follows:

The introduction of computer simulation methods has radically changed certain scientific fields. Among the philosophical issues involved are: Why have some fields such as astrophysics embraced simulations while others such as economics resisted their introduction? What are the differences and similarities between laboratory experiments and computer simulations? Are very large scale simulations such as those used in climate models essentially different from smaller scale simulations? What is the status of data from simulations? How can simulation models be tested and validated and what is their relation to traditional theory and models? Contributions that answer  these and other, as yet unaddressed, issues in the area of models and simulations are invited. Papers dealing with general philosophical topics or with applications to specific sciences will be the focus of this issue; those addressing topics in biology and medicine are particularly welcomed.


# Short Abstract

We argue that agent-based models (ABMs) are better conceived of as multi- or intra-level models. Consequently, they are neither reductionistic nor emergent in the explanations they provide. We argue for this by first contrasting them with analytical models, which tend to focus on macro-level entities or properties. We then use an example of an ABM of group-selection from the biological sciences which is thought to be purely individualistic. However, we argue that the model is misconceived. The macro-level properties required to make the model work are not straightforwardly  given by the composition of the individuals in the group.


# Extended Abstract

Agent-based models (ABMs) are often contrasted with analytical models on grounds that they are ``bottom up" instead of ``top down". Whereas analytical models focus on relationships between groups, for example, ABMs focus on the individuals that make up the groups. The more traditional form of analytical modeling tends to ignore, idealize, or abstract away details about how the macro-level properties are produced. For example, when modeling certain relationships between predator and prey populations, the groups are assumed to be homogenous.  This allows us to develop rather elegant and tractable models. However, sometimes we want a better explanation of how macro-level properties come to be. Often this will require us to approach the make-up of groups more finely by considering, e.g., how individuals interact with one another and how differences between members lead to differences in macro-level properties. One of the many advantages that ABMs bring by focusing on individuals is that they can introduce heterogeneity and agent interactions with ease, while remaining relatively tractable.

For these and other reasons, many scientific communities are optimistic about the use of ABMs as a new research tool.  But in the development of this optimism, some differences between ABMs and analytical models have been exaggerated, to the point where we think there has been a misconception about the kinds of explanations that ABMs provide. For example, it is a commonly held that ABMs provide a micro-level foundation for the investigation of macro-level properties (cellular automata, including Conway's Game of Life is a paradigm example).  The thought is that ABMs do not describe or appeal to group-level properties, but rather let them ``emerge" from agent-agent and agent-environment interactions; ABMs are thought to be purely individualistic. We will argue, as some critics have argued (Epstein 2011), that this conception of ABMs is often misconceived.

Our argument against the ``bottom up" conception of ABMs will come in two parts. First, we will look at an example of an ABM that one might expect to be free of macro-level property descriptions.  We will show, however, that this ABM still makes (implicit) use of macroscopic information in the algorithm that governs the state evolution of the model, so that without it, the simulations would no longer produce the macro-level properties the model is intended to explain. The case we will look at comes from the biosciences in which group-selection of E.coli is modeled using an ABM. Briefly, the idea is that as long as a certain number of E.coli have fimbriae (hair-like structures that grow on the surface, which can be turned on and off by each individual cell) a human gut will produce a certain amount of sialic acid, which E.coli can use as food. If too many E.coli have fimbriae at the same time, then they trigger an immune reaction, which kills off the entire group of E.coli. Since this excludes the possibility of evolutionary selection at the individual-level, biologists are interested in explaining how it could ever be the case that some groups of E.coli are able to regulate themselves in such a way that only a close to optimal number of E.coli have fimbriae at a time. We will show that the ABMs biologists use to model this phenomenon do not just appeal to micro-level properties, i.e., features of the agents (E.coli) and their environment (human guts), but also make use of macro-level properties, i.e., properties that hold of the group of E.coli that are not straightforwardly given by some composition of the individuals (not to mention that this information is fed back into the rules of how the agents interact with each other and the environment).

The second part attempts to give a more general argument that ABMs bring with them group-level information, or if they don't, then facilitate the means to do so in a way that makes it easy to oversee how they are not merely positing micro-level entities and properties. Consider the notion of an environment in an ABM. Placing agents in an environment is a specification of a relation (or relations) over the set of agents. Even if one thinks that the environment should be relegated to a subsidiary position in an explanation -- one could suggest that it is just a special kind of agent, and it's the agents and their interactions that do all the explanatory work -- nevertheless its role is to relate all the other agents in some particular way (and maybe even to itself). The introduction of an environment comes daringly close to also introducing macro-level properties. However, even if it doesn't count as introducing macro-level properties, we argue that many successful ABMs make use of group-level facts that are not intrinsic to either the agents or the environment.  And although such properties still depend on certain facts about agents and the environment, they are not wholly determined by them. In other words, the group-level facts do not supervene on the intrinsic facts about agents and the environment, since the group level facts could change without a change in the state of the agents or environment. 

We do not take our arguments to be a criticism of ABMs. Rather, we think that this leads to a more accurate conception of ABMs in which they are neither ``top-down" nor ``bottom-up". The conception we prefer is that ABMs are inherently multi-leveled.  We argue that this conception still reflects the reasons for why researchers are optimistic about ABMs, but provides a more accurate picture of how ABMs are used and the kinds of explanations they tend to provide.  For one, they are not mere analytic models because they include individuals as the constituents of groups. Moreover, they are not entirely reductionistic; they are partially reductionistic because they produce some macro-level properties in terms of the micro-level, but they need the aid of some other macro-level properties to get the job done. Nor are they completely emergent, for similar reasons.


# James' sketch

Primary conclusion: agent based models are better considered to be mixed-level, as opposed to bottom-up.

- Group selection is an interesting and widely discussed topic, worth using as an example in philosophy of biology
- It's the kind of thing where experiments are difficult, so modelling is important
- The main goal of a model of group selection would be to show how groups (or group-level properties) can plausibly play a role in the selection of individuals, and thus fit into our broader understanding of evolution
- Fimbriation is a particularly strong case for the pro-group-selection side
- The anti-group-selection side would like to "reduce" groups out of the fimbriation case. They could do so by providing an alternative model that does not appeal to groups in any way -- call this Goal A
- An analytic model of fimbriation will not meet Goal A, because the groups are baked in
- Agent Based Models are usually thought to be bottom-up, so an ABM might meet Goal A
- Here's an ABM of fimbriation
- However, it doesn't meet Goal A, because it uses groups in the following ways X,Y,Z (where these involve the environment, interaction rules, properties of agents, etc.)
- Maybe it's possible for an ABM of fimbriation to meet Goal A and avoid X,Y,Z
- However, when considering ABMs more generally, we should look for X,Y,Z
- (X,Y,Z are common or hard to avoid -- this would need support)
- Therefore, for a given ABM, until you can show that X,Y,Z have been avoided, you should assume that the ABM is mixed-level


# Reverse-engineered outline of 2013-10-18 draft

- Introduction
  - Computer models for reduction and emergence, GoL example
  ? get more explicit about bottom-up vs. top-down
  ? mention analytic models for contrast?
  - ABMs, agents as data structures, emergent behaviour
    + agents are explicit, robust, self-contained, stateful
  - conclusion that ABMs are mixed-level, introduce E.coli
  - ABMs invite macro-level properties
  - ABMs as a scaffold for bottom-up models
    - I disagree: scientists are not really after bottom-up models
- Evolution of optimal E.coli fimbriation levels
  - popularity and usefulness of ABMs
  - Target pheonomenon
    - fimbriae, virulence
    - relation to host, sialic acid, immune response, coordination
    - genetics (not important, but one paragraph is fine)
    - evolution of coordination, group selection
    - colonization, founder effect, survival and recolonization
    - modelling the details
  - An ABM of evolving fimbriation levels
    - figure with pseudo code
    - aggregating information is not problematic, see GoL
    - "spirit" of GoL: distinct levels, no causal mixing
    - variations on GoL in the same spirit
    - patterns can change without violating the "spirit"
    - you could also violate the spirit by mixing levels
    - the spirit is a "pure" constitution relation
    - the fimbriation ABM is mixed level: the host interacts with groups and individuals
    - the ABM is not really bottom-up, which is fine
    - perhaps the ABM is a step toward a bottom-up model
- Agent-Base Models as Mixed Level
  - Mixed-Level Models
    - constitution and levels, composition; a mixed-level model deliberately includes multiple levels
      ? explicit representation?
    - analytic predatory-prey models are not mixed-level: no individuals
    - GoL not mixed-level: gliders not explicitly represented
    - "for free" stronger than supervenience
    - levels of description in GoL
    - A mixed-level model is one where:
      i) the target phenomenon is conceived of in terms of two or more categories that reflect constitution relations, and either
      ii) the vocabulary of the model specifies things from at least two categories, or 
      iii) has the mechanisms in place to generate information about things in another category and then makes use of that information to create changes at the source.
    - GoL fails iii because information does not flow back down?
    - fimbriation ABM satisfies iii
  - The role of the environment
    - the fimbriation ABM has interactions between two levels mediated by the host
  - Interactions 
    - agents can belong to multiple levels
      ? or the environment
- Rough Work
- References


# James' questions 2013-10-19

- What is a constitution relation? Is it like Wimsatt's aggregation? A mere sum?
- Do scientist really aim for reduction? I don't think that it's a goal of biologists, per se.


# Revised outline: James 2013-10-19

- Introduction
  - traditional top-down analytic models (in biology)
    - predator-prey
  - newer bottom-up models such as GoL
  - bottom-up models particularly useful for reduction and emergence
  - bottom-up models accomplish an ontological reduction
    - however they quickly run into epistemic limits
  - distinction between modelling and simulation
    - neither requires a computer in principle, but do in practise
  - "evolution" of CAs into ABMs
    - agents have more internal structure, state
    - there's usually an environment
    - rules can be more complex
  - popularity of ABMs
    - ant foraging example, reducing complex social behaviour to simple local interactions
  - one might think that creating an ABM accomplishes the same ontological reduction as the CA
    - take a strong group selection case
    - propose an ABM that models it
    - if the ABM succeeds then you might think you've made your ontological reduction
  - conclusion that ABMs are mixed-level, introduce E.coli
  - ABMs invite macro-level properties
    - particularly the environment and its interactions with agents
  - ABMs as a scaffold for bottom-up models
    - I disagree: scientists are not really after bottom-up models
- Evolution of optimal E.coli fimbriation levels
  - Target phenomenon
    - fimbriae, virulence
    - relation to host, sialic acid, immune response, coordination
    - genetics (not important, but one paragraph is fine)
    - evolution of coordination, group selection
    - colonization, founder effect, survival and recolonization
    - modelling the details
  - An ABM of evolving fimbriation levels
    - figure with pseudo code
    - aggregating information is not problematic, see GoL
      - feeding back aggregated information?
    - "spirit" of GoL: distinct levels, no causal mixing
    - variations on GoL in the same spirit
    - patterns can change without violating the "spirit"
    - you could also violate the spirit by mixing levels
    - the spirit is a "pure" constitution relation
    - the fimbriation ABM is mixed level:
      - the host is not modelled on the same level as the bacteria
      - the host interacts with groups and individuals
    - the ABM is not really bottom-up, which is fine
    - perhaps the ABM is a step toward a bottom-up model
- Agent-Base Models as Mixed Level
  - Mixed-Level Models
    - constitution and levels, composition; a mixed-level model deliberately includes multiple levels
      ? explicit representation?
    - analytic predatory-prey models are not mixed-level: no individuals
    - GoL not mixed-level: gliders not explicitly represented
    - "for free" stronger than supervenience
    - levels of description in GoL
    - A mixed-level model is one where:
      i) the target phenomenon is conceived of in terms of two or more categories that reflect constitution relations, and either
      ii) the vocabulary of the model specifies things from at least two categories, or 
      iii) has the mechanisms in place to generate information about things in another category and then makes use of that information to create changes at the source.
    - GoL fails iii because information does not flow back down?
    - fimbriation ABM satisfies iii
  - The role of the environment
    - the fimbriation ABM has interactions between two levels mediated by the host
  - Interactions 
    - agents can belong to multiple levels
      ? or the environment
- Rough Work
- References


