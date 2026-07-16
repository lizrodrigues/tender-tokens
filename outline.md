# Tender Tokens
This sequence of assignments will ask you to engage with the poetry and poetics of Gertrude Stein and the parameters for text generation using a large language model.  
The goal of this work is to 
1) practice noticing, describing, and operationalizing literary style; 
2) better understand the levers under the hood of text generation; and 
3) reflect on what might constitute a human trace in experimentally generated language. 


## Part 1: Digging in to Stein
### Class 1:
**Read:** 
“Objects” section of Tender Buttons  

**Write:**
Select one object poem and model it in as many ways as you can think of: as parts of speech, as word frequencies, as a series of verbs describing transitions between ideas–any way of attempting to represent what you perceive to be the structure of the language that allows you to perceive a meaning  

#### Class 2: 
**Read:**
Stein’s essay “Portraits and Repetition”

**Write:**
Focus on one passage that describes Stein’s approach to Tender Buttons. Do you see something resembling this approach at work in the object poem you selected? How would using this governing idea affect your model?  

## Part 2: Digging into text generation
### Class 3 
**Read:** 
Tunstall et al., Natural Language Processing with Transformers, chapter 5, “Text Generation” 

**Prepare for discussion:**
Be able to define the following terms in this context: 
- greedy search decoding 
- beam search decoding 
- sampling 
- temperature 
- n-gram penalty

### Class 4
**Hands on:**
Using Google Collab or your own computer, work through the Jupyter notebook provided by Tunstall et al. for chapter 5

Experiment with prompts and decoding method, sampling parameters, temperature, and n-gram penalties to attempt to get as close as you think you can get to generating a Tender Buttons object poem.

**Write:**
Reflect on how close it seemed like you got to a Steinian output. What, if anything, seemed similar, and what parameters do you think were most responsible for that? What, if anything, seemed impossible to reproduce, and why do you think the existing parameters failed to account for it?


## Final deliverable
**Write:**
2-3 pages:

- Compare your selected object poem to the closest generated poem that you created by modeling your generated poem using at least one method you originally used to model the selected poem. 
- Make an argument about whether you believe Steinian aesthetics could be machine-generated. If so, what parameters are most crucial and how might they map to Stein’s own statements of poetics? If not, what features would you hypothesize accounts for the gap?
- Include: A screenshot of the parameters and output for your most successful attempt.
