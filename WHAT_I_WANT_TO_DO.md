I am am trying to create a complex decision tree with x amount of nodes.

Each node has a question and y number of answers.  
Each answer is in form of a button.
There can be 2 - 7 questions / buttons.
Each button will route to a new NODE.


The Node is displayed in somethng like a DIV.
I want to transition onClick event to be Right to left, with in the WEB PAGE.
It would be a similar effect as a mobile phone transition.

I do not need history.
I DO need to pass a parameter to the next node.

Ideally, each node would just be a changing values in a single NODE template.  This way I could just pass a parameter to the next node, have it look up its question and answers.

But I am ok for now having a separate node for each answer.


