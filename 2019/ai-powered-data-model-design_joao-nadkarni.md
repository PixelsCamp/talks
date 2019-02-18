AI-powered Data Model Design
=========================

* Speaker   : [João Nadkarni](https://pixels.camp/joaonadkarni)
* Length    : 45/50 minutes + QA
* Language  : English

Description
-----------

Machine Learning applied t Software is the next frontier of Artificial Intelligence, but it poses many challenges. 

Recently we’ve seen many advances using AI with natural language interpretation and generation. You may think Natural Language Processing (NLP) would be harder than code, as compilers can parse through the code to create an executable file while we don’t have an accurate deterministic natural language parser. However, NLP can be easier for AI. For instance, in NLP your vocabulary is limited to the number of words a language has, but the code identifiers of programs (functions, variables) are not bound to a dictionary (example: get, user, getUser, getUser2, get_user, findUser, ...) and can result in a much bigger and sparser vocabulary which will difficult the learning process of a machine learning model. 

How can we leverage millions of code patterns to train Machine Learning models that can understand and automatically design robust application Data Models?

In this talk, you will learn how at OutSystems AI we leverage machine learning techniques to assist the development of data models. You will see how we approach our sparse and noisy dataset to build a predictive model capable of accurately giving a set of suggestions that can accelerate and guide you through the development of your data model.  

You will also learn:
* The challenges we faced in the data preprocessing stage and how we addressed them, including:
    * The high vocabulary size of the attribute and entity name identifiers;
    * The presence of names that can’t be correctly normalized using simple heuristics;
    * The abundance of very rare names that negatively impact the performance of the model.
* The results and implementation details of both our initial frequency-based baseline and our neural-network based implementations.
* How we leveraged Graph Neural Networks to feed structured information into a Deep Learning model.
* Some future next steps planned.


Speaker Bio
-----------

**João Nadkarni**

![Speaker Image](https://avatars2.githubusercontent.com/u/38245862?v=4)


I graduated from Instituto Superior Técnico (IST) in 2017, obtaining a Master’s Degree in Electrical and Computer Engineering. During my dissertation I investigated the use of machine learning and evolutionary computing techniques in financial trading, proposing a new approach to the problem based on a neuroevolution algorithm. 

Currently, I'm an AI Engineer working in OutSystems.AI research team, with a focus on exploring how to use AI and machine-learning techniques (neural program synthesis and natural language processing are two examples) to improve software development.


Links
-----

* Company: https://www.outsystems.com/
* Github: https://github.com/joaonadkarni

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
