#Exploratory Factor Analysis on Personality Traits

This code and data set is to illustrate the visulisation of exploratory factor analysis to help with interpretation using the FactorAnalyzer Python module. See https://pypi.org/project/factor-analyzer/ for more information on this module and how to install. 

##Data-set
The data set for this example is based on responses the sample 50-item International Personality Item Pool (IPIP) personality questionnaire (see https://ipip.ori.org/New_IPIP-50-item-scale.htm). 

##EFA
Exploratory factor analysis (EFA) is a statistical technique that can be used to identify underlying, unobserved latent factors. Specifically, it looks at the relationships among observed variables (e.g. responses to statements on a questionnaire) to identify an underlying smaller set of structures or factors in the dataset. As it is exploratory in nature, it therefore is appropriate for use when there are no prior hypotheses for what the researcher expects to find. 


##Current application of EFA
The trait theory of personality argues that there are five core traits ("the Big Five"), which people vary on:

The five factors are:

1. Openness to experience
2. Conscientiousness 
3. Extroversion 
4. Agreeableness
5. Neuroticism 

While not strictly a correct application of EFA given an existing theory of personality, using the data set above, I have applied an EFA using the Oblimin approach with five factors corresponding to the five personality factors we expect to find. The output of the EFA is shown in a Panda's data frame along with the weights of each item to each of the five factors. Highlighted cells indicate the items showing the highest factor loadings for an item. 

For example, "Am the life of the party", "Feel comfortable around people", "Start conversations", "Talk to a lot of different people at parties", "Don't mind being the center of attention", "Don't talk a lot", "Keep in the background", "Have little to say", "Don't like to draw attention to myself" all have the strongest loading on Factor 1. The nature of items suggests that this factor is related to extroversion with some positively worded and others negatively. Therefore, we can infer that these items measure the trait of extroversion. The same idea can be applied to the other factors. 








