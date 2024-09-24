---
layout: page
title: "Lesson 1"
description: "Comparing coding to law"
---

## Intro to Python

### Why learn python?
Python is an easy to learn programming language that's highly intuitive. 

### What has this got to with law? *[aka you already know how to code]*
Python, as a computing language follows logic a lot like what we use when solving a legal problem.

Take the example of negligence:

{% highlight python %}
# importing packages
import torts_law_knowledge

# defining a class
class Context:
    def __init__(self, social_utility, prob_harm, burden, seriousness, new_intervening_acts = []):
        self.social_utility = social_utility
        self.prob_harm = prob_harm
        self.burden = burden
        self.seriousness = seriousness
        self.new_intervening_acts = new_intervening_acts


# defining functions
def duty_of_care(context):


def breach(context):
    ...

    # conditionals and basic math
    if (context.prob_harm + context.seriousness > context.social_utility + context.burden):
        return TRUE

def causation(context):
    ...

    if context.new_intervening_acts:
        # recursion
        if (run_negligence(context.new_intervening_act)):
            return(None)
    
    ...


def run_negligence(context):
    if duty_of_care(context):
        if breach(context):
            if causation(context):

                # using other packages
                if not torts_law_knowledge.defences(context):
                    return("Negligence is present")

def exam(problem_list):
    # lists
    outcome = []
    for context in problem_list:
        # using methods
        outcome.append(run_negligence(context))
    
    # printing
    print(outcome)

# running code
__main__:
    # using objects
    NIA_1 = Context(social_utility = 5, prob_harm = 8, burden = 7, seriousness = 7)

    question1 = Context(social_utility = 6, prob_harm = 2, burden = 8, seriousness = 2, new_intervening_acts = [NIA_1])

    question_2 = Context(social_utility = 2, prob_harm = 8, burden = 3, seriousness = 7, new_intervening_acts = [question1])

    problem_list = [question_1,question_2]
    exam(problem_list)


{% endhighlight %}

Here you can see that in our (simplified) process of stepping through negligence we use a lot of fundamental coding ideas:
* We break our work into parts (functions)
* We define go through the problem and identify the relevant facts (building the context object) 
* We dismiss the cause of action if there is insufficient evidence (conditionals)

AND MORE!

Through this mini-python series we will take a look at some of these python capabilities and build a function that we can bring into law.