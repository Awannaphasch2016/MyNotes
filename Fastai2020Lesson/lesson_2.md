# Content to add to Roam Research is denote by [[content]]
# Status
* First read
    * Comment: currently read up to Gathering Data.
    
# References
1. Google Colab
    * https://colab.research.google.com/github/fastai/fastbook/blob/master/02_production.ipynb#scrollTo=c5tj5aHmwaF6
2. Deisng Grate DAta product
    * https://www.oreilly.com/radar/drivetrain-approach-data-products/

# Terminology
* out-of-domain data 
    * data is doesn't appear during the developement iteration. 
* [[A Drivetrain Approach]]
    * "goal is not to generate more data (in the form of prediction), but to produce actionalbe outcomes.)"
    * first mentioned in "Design Greate Data Products"^[2]
    * There are many accurate models that are of no use to anyone, and many inaccurate models that are highly useful. 
     To ensure that your modeling work is useful in practice, you need to consider how your work will be used.
    * Concept is as followed 
        * start with considering your objective
        * think aboutw what actions you can take to meet that objective
        * what data you have that can help
        *  build a model that you can use to optimize that objective

# Lesson
* Goal: look at the end-to-end process of creating a deep leanring application.
    * builing bear classifier
    * talk about constraints of deep learning
    * explroe how to create dataset.

* how to start and finish a new deep learning project.
    * before select a project
        * factos to consider 
            * what data is available
                * the goal is to find some data -> iterate -> and go from there.
    * working on a project
        * focus on iteration, do not spend months fine-tuning your model, or polish the perfect GUI, or labeling the perfect dataset.
            * do not spend time so much on eveyr step in each iteration. focusing on complete the iteration and repeat iteration.
        * eg. 
            * goal is to create app to run on mobile pholne
                * thesefore, each iteration. you should have new version of the app that can run on mobile phone
                    * each step should be maturing at the same rate.
                    * by completing the project end to end, you will see where the trickiest bit are, and the hard part will be 
                     * what you need to sovle in the future
* Deep learning state of the art 2020 
    * Computer Vision 
        * object recognition is better than human
        * bad at reconizing image structure/angle/relative distance/parts/style
    * Text 
        * on part with human on 
            * document classification based on categories
        * good (and sometimes better than human) at generating context-appropriate text
            * eg social media posts.
        * not good at generating correct responses
        * application   
            * tranlation
    * text + image 
        * application
            * output caption written of image
    * Tablular data 
        * deep learning in 2020 is making progress in working with tabular data
        * application
            * eg enhance performance on columns data containing NLP, and high-cardinality categorical columns
