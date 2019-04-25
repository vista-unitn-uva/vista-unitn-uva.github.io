## Welcome

This website provides an overview of our research on visually-grounded language in interactive settings. The work is jointly carried out by our two research groups: the Language and Vision group led by [Raffaella Bernardi](http://disi.unitn.it/~bernardi/) at the University of Trento and the Dialogue Modelling Group led by [Raquel Fernández](https://staff.fnwi.uva.nl/r.fernandezrovira/) at the University of Amsterdam. The two group leaders have equally contributed to all papers included here.

## Contributors

<table id='contributor-table'>
  <tr>
    <td>
      <img class="headshots" src='images/tim.jpg' alt='Tim Baumg&auml;rtner'>
    </td>
    <td>
      <img class="headshots" src='images/raffa.jpg' alt='Raffaella Bernardi'>
    </td>
    <td>
      <img class="headshots" src='images/elia.jpg' alt='Elia Bruni'>
    </td>
    <td>
      <img class="headshots" src='images/raquel.jpg' alt='Raquel Fern&aacute;ndez'>
    </td>
    <td>
      <img class="headshots" src='images/barbara.png' alt='Barbara Plank'>
    </td>
    <td>
      <img class="headshots" src='images/ravi.jpg' alt='Ravi Shekhar'>
    </td>
    <td>
      <img class="headshots" src='images/aashish2.jpg' alt='Aashish Venkatesh'>
    </td>
  </tr>
  <tr>
    <td>
      <div class='names'>Tim Baumg&auml;rtner</div>
    </td>
    <td>
      <div class='names'>[Raffaella Bernardi](http://disi.unitn.it/~bernardi/)</div>
    </td>
    <td>
      <div class='names'>Elia Bruni</div>
    </td>
    <td>
      <div class='names'>[Raquel Fern&aacute;ndez](https://staff.fnwi.uva.nl/r.fernandezrovira/)</div>
    </td>
    <td>
      <div class='names'>Barbara Plank</div>
    </td>
    <td>
      <div class='names'>Ravi Shekhar</div>
    </td>
    <td>
      <div class='names'>Aashish Venkatesh</div>
    </td>
  </tr>
</table>

## Papers

### Beyond task success: A closer look at jointly learning to see, ask, and GuessWhat
Ravi Shekhar, Aashish Venkatesh, Tim Baumg&auml;rtner, Elia Bruni, Barbara Plank, Raffaella Bernardi, and Raquel Fern&aacute;ndez
#### NAACL 2019
> We propose a grounded dialogue state encoder which addresses a foundational issue on how to integrate visual grounding with dialogue system components. As a test-bed, we focus on the GuessWhat?! game, a two-player game where the goal is to identify an object in a complex visual scene by asking a sequence of yes/no questions. Our visually-grounded encoder leverages synergies between guessing and asking questions, as it is trained jointly using multi-task learning. We further enrich our model via a cooperative learning regime. We show that the introduction of both the joint architecture and cooperative learning lead to accuracy improvements over the baseline system. We compare our approach to an alternative system which extends the baseline with reinforcement learning. Our in-depth analysis shows that the linguistic skills of the two models differ dramatically, despite approaching comparable performance levels. This points at the importance of analyzing the linguistic output of competing systems beyond numeric comparison solely based on task success.  

[PDF](https://arxiv.org/abs/1809.03408) | [Supplementary Material](https:vista-unitn-uva.github.io/jointly_supplementary.pdf) | Code coming soon  

### Ask No More: Deciding when to guess in referential visual dialogue
Ravi Shekhar, Tim Baumg&auml;rtner, Aashish Venkatesh, Elia Bruni, Raffaella Bernardi, and Raquel Fern&aacute;ndez
#### COLING 2018
> Our goal is to explore how the abilities brought in by a dialogue manager can be included in end-to-end visually grounded conversational agents. We make initial steps towards this general goal by augmenting a task-oriented visual dialogue model with a decision-making component that decides whether to ask a follow-up question to identify a target referent in an image, or to stop the conversation to make a guess. Our analyses show that adding a decision making component produces dialogues that are less repetitive and that include fewer unnecessary questions, thus potentially leading to more efficient and less unnatural interactions. 

[PDF](http://aclweb.org/anthology/C18-1104) | [Cite](https://aclanthology.info/papers/C18-1104/c18-1104.bib) | Code coming soon
