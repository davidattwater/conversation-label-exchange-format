# Conversation Label Exchange Format
A proposed format to label a conversation corpus for the purpose of training a conversational voice or text bot

The objective of this standard is to:
1. provide a specification that can be used to label a conversation corpus that includes features useful to train a chat or voice bot including features such as speech acts, dialog states, training utterances, and entities
2. provide a standard code framework that makes it easy to a. output a labeled conversation corpus that contains useful data for bot training and b. query a labeled corpus to extract specific data from a labeled corpus c. import features from a labeled corpus into a chat or voice bot
3. encourage collaboration and participation from the community including bot developers, data providers, data scientists, machine learning engineers, and end users
4. promote the adoption, sharing and re-use of standards-based language resources to benefit the whole chat or voice bot community 

# Guiding Principles
1. the standard shall be language and bot agnostic
2. The standard and related tools shall remain open source and in the public domain
3. The standard shall be flexible and extensible; meaning that every label is optional, and any new labels can be easily added
4. The standard shall be developer friendly: well documented, easy to use, with code frameworks in common programming languages
5. The standard shall have utility in mind: only labels that are directly useful to business analysts, data scientists, designers, and developers should be considered
6. the standard shall be applicable to written and spoken conversation

# Types of conversation labels (preliminary)
1. dialog acts based on a theory of conversation (such as DAMSL or DiaML)
2. semantic meaning of utterances that can be used to train NLU (such as AMR)
3. dialogue system labels that identify features in a conversation corpus that can be used as bot training data (i.e. intents, intent training utterances, dialog states, bot utterancs)

# Useful resources
- http://www.paulmckevitt.com/docs/readings/spoken_dialogue_technology.pdf This paper provides an overview of the various dialogue management approaches including State-based, Frame-based, and Agent-based and is useful to ensure labels will cover the needs of these different dialogue management models
  - https://pdfs.semanticscholar.org/2806/8bb6e387e2bebdcf7fa377f1a6354506cc81.pdf A paper written by David Traum that provides an overview of the information state update approach to dialogue management, one particular model of dialogue management
- https://amr.isi.edu/ Abstract Meaning Representation (AMR) is a simple way to represent the semantic meaning of sentences and is in part derived from previous projects including wordnet, verbnet, and framenet. AMR could be used to label the semantic meaning of utterances.
- https://www.cs.rochester.edu/research/cisd/resources/damsl/RevisedManual/ DAMSL is a conversation corpus annotation format that implements a dialogue act theory on how conversation works 
