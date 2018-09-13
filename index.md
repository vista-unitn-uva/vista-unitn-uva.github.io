## Contributors

<table id='contributor-table'>
  <tr>
    <td>
      <img class="headshots" src='images/ravi.jpg' alt='Ravi Shekhar'>
    </td>
    <td>
      <img class="headshots" src='images/tim.jpg' alt='Tim Baumg&auml;rtner'>
    </td>
    <td>
      <img class="headshots" src='images/aashish.jpg' alt='Aashish Venkatesh'>
    </td>
    <td>
      <img class="headshots" src='images/elia.jpg' alt='Elia Bruni'>
    </td>
    <td>
      <img class="headshots" src='images/raffa.jpg' alt='Raffaella Bernardi'>
    </td>
    <td>
      <img class="headshots" src='images/raquel.jpg' alt='Raquel Fern&aacute;ndez'>
    </td>
  </tr>
  <tr>
    <td>
      <div class='names'>Ravi Shekhar</div>
    </td>
    <td>
      <div class='names'>Tim Baumg&auml;rtner</div>
    </td>
    <td>
      <div class='names'>Aashish Venkatesh</div>
    </td>
    <td>
      <div class='names'>Elia Bruni</div>
    </td>
    <td>
      <div class='names'>Raffaella Bernardi</div>
    </td>
    <td>
      <div class='names'>Raquel Fern&aacute;ndez</div>
    </td>
  </tr>
</table>

## Papers

### Jointly Learning to See, Ask, and GuessWhat
We are interested in understanding how the ability to ground language in vision interacts with other abilities at play in dialogue, such as asking a series of questions to obtain the necessary information to perform a certain task. With this aim, we develop a Questioner agent in the context of the GuessWhat?! game. Our model exploits a neural network architecture to build a continuous representation of the dialogue state that integrates information from the visual and linguistic modalities and conditions future action. To play the GuessWhat?! game, the Questioner agent has to be able to do both, ask questions and guess a target object in the visual environment. In our architecture, these two capabilities are considered jointly as a supervised multi-task learning problem, to which cooperative learning can be further applied. We show that the introduction of our new architecture combined with these learning regimes yields an increase of 19.5% in task success accuracy with respect to a baseline model that treats submodules independently. With this increase, we reach an accuracy comparable to state-of-the-art models that use reinforcement learning, with the advantage that our architecture is entirely differentiable and thus easier to train. This suggests that combining our approach with reinforcement learning could lead to further improvements in the future. Finally, we present a range of analyses that examine the quality of the dialogues and shed light on the internal dynamics of the model.  
[arxiv](https://arxiv.org/abs/1809.03408)  

### Ask No More: Deciding when to guess in referential visual dialogue
#### COLING 2018
Our goal is to explore how the abilities brought in by a dialogue manager can be included in endto-end
visually grounded conversational agents. We make initial steps towards this general goal
by augmenting a task-oriented visual dialogue model with a decision-making component that
decides whether to ask a follow-up question to identify a target referent in an image, or to stop
the conversation to make a guess. Our analyses show that adding a decision making component
produces dialogues that are less repetitive and that include fewer unnecessary questions, thus
potentially leading to more efficient and less unnatural interactions.  
[arxiv](https://arxiv.org/abs/1805.06960) [code](https://github.com/timbmg/Ask-No-More) [cite](https://scholar.googleusercontent.com/scholar.bib?q=info:ALFJe6KKaIwJ:scholar.google.com/&output=citation&scisig=AAGBfm0AAAAAWx6dTtgn7xhHxES1SDP1x1zQp2KzyMv6&scisf=4&ct=citation&cd=-1&hl=en)
