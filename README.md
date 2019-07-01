# paper-reading-RL
recent paper reading in Reinforcement Learning

1. Energent complexity via multi-agent competition
Reinforcement learning algorithms can train agents that solve problems in complex, interesting environments. Normally, the complexity of the trained agent is closely related to the complexity of the environment. This suggests that a highly capableagentrequiresacomplexenvironmentfortraining. Inthispaper,wepoint outthatacompetitivemulti-agentenvironmenttrainedwithself-playcanproduce behaviorsthatarefarmorecomplexthantheenvironmentitself. Wealsopointout thatsuchenvironmentscomewithanaturalcurriculum,becauseforanyskilllevel, an environment full of agents of this level will have the right level of difﬁculty. This work introduces several competitive multi-agent environments where agents compete in a 3D world with simulated physics. The trained agents learn a wide variety of complex and interesting skills, even though the environment themselves are relatively simple. The skills include behaviors such as running, blocking, ducking, tackling, fooling opponents, kicking, and defending using both arms and legs. A highlight of the learned behaviors can be found here: https://goo.gl/eR7fbX.


2. BenchmarkingDeepReinforcementLearningforContinuousControl
just RLLAB from OPENAI

3. Constrained Policy Optimization
For many applications of reinforcement learning it can be more convenient to specify both a reward function and constraints, rather than trying to design behavior through the reward function. For example, systems that physically interact with or around humans should satisfy safety constraints. Recent advances in policy search algorithms (Mnih et al., 2016; Schulman et al., 2015; Lillicrap et al., 2016; Levine et al., 2016) have enabled new capabilities in highdimensionalcontrol,butdonotconsidertheconstrained setting. We propose Constrained Policy Optimization (CPO),theﬁrstgeneral-purposepolicysearchalgorithm for constrained reinforcement learning withguaranteesfornear-constraintsatisfactionat eachiteration. Ourmethodallowsustotrainneuralnetworkpoliciesforhigh-dimensionalcontrol while making guarantees about policy behavior allthroughouttraining. Ourguaranteesarebased on a new theoretical result, which is of independent interest: we prove a bound relating the expectedreturnsoftwopoliciestoanaveragedivergence between them. We demonstrate the effectiveness of our approach on simulated robot locomotiontaskswheretheagentmustsatisfyconstraints motivated by safety.

its website:https://bair.berkeley.edu/blog/2017/07/06/cpo/
