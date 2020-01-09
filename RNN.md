

>RNN 

**Recurrent Neural Networks (RNN)**
Being human, when we watch a movie, we don’t think from scratch every time while understanding any event. We rely on the recent experiences happening in the movie and learn from them. But, a conventional neural network is unable to learn from the previous events because the information does not pass from one step to the next. On contrary, RNN learns information from immediate previous step.
For example, there is a scene in a movie where a person is in a basketball court. We will improvise the basketball activities in the future frames: an image of someone running and jumping probably be labeled as playing basketball, and an image of someone sitting and watching is probably a spectator watching the game.


Humans don’t start their thinking from scratch every second. As you read this essay, you understand each word based on your understanding of previous words. You don’t throw everything away and start thinking from scratch again. Your thoughts have persistence.

Traditional neural networks can’t do this, and it seems like a major shortcoming. For example, imagine you want to classify what kind of event is happening at every point in a movie. It’s unclear how a traditional neural network could use its reasoning about previous events in the film to inform later ones.

Recurrent neural networks address this issue. They are networks with loops in them, allowing information to persist.

