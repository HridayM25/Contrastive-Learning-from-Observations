# ContrastiveImitationLearning
Experiments on Contrastive State Only Imitation Learning with Reducing Paradigm Gap.

## Report Reference
https://drive.google.com/file/d/1YFdDDuu859bEZ0gzJ30AH76Ok-Nn2odE/view?usp=drive_link

## Abstract 

Learning from Observations (LfO) deals with learning policies from expert demonstrations that encapsulate only the state information, relaxing the need to collect 
expensive, infeasible or often unattainable action information that is prevalent in
Learning from Demonstrations (LfD). A class of algorithms used to to learn the
imitator policy is Adversarial Imitation Learning (AIL), which primarily uses a
discriminator to provide the reward signal to guide the training. However, this calls
for a robust discriminator - whose training in representative AIL papers is done
using a simple binary objective, and thus may not learn good and smooth feature
representations. Motivated by previous methods which aim to learn a representation
space through contrastive learning, we propose Contrastive Adversarial Learning
from Observations (CALfO), which novelly uses the state transitions occupancy
to learn good representations. Identifying the change to an LfO paradigm, we also
attempt to bridge the gap between our work and prior methods in the LfD field by
minimizing their inverse dynamics disagreement. We utilize a reward based on
the learned representations and terms used for reducing this gap. We evaluate our
method on OpenAI’s Gym and Mujoco Environments and present the quantitative
results.

## Methodology 

![Screenshot 2024-10-30 175235](https://github.com/user-attachments/assets/0968b007-ff75-4422-8dbc-49f8b4ff4eed)



