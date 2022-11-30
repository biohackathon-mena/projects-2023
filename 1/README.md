# Project 1

## Title:

Toward the treatment of Vaso-Occlusive Crisis: A Reinforcement
learning-based approach for non-opioid drug discovery

## Description:

The MENA region suffers from many genetic diseases because of
consanguineous marriage. Recent studies have shown that Sickle Cell
Disease (SCD) is affecting more than 300k children every year
worldwide, with an expected increase in prevalence in the upcoming
years. The hallmark of sickle cell disease is a recurrent and painful
vaso-occlusive crisis (VOC) and which is responsible for over 90% of
acute hospital admissions in SCD. Opioid pain medications, including
morphine and dilaudid, have long been leveraged as standard treatments
to mitigate this crisis. Despite their apparent efficiency advantages,
they have concerning side effects including the risk of addiction, the
slowing or cessation of breathing, and the deadly lowering of blood
pressure. Currently, in the MENA region, especially in Saudi Arabia,
the number of people who get addicted to morphine due to VOC has
increased. Thus, physicians are trying to find alternative drugs to
opioid medications but with fewer side effects. Recently, studies have
shown that Ketamine has proven to be amongst the most effective
treatments for VOC. Motivated by the need to discover alternative
drugs that can relieve VOC pain without causing addiction, we propose
a multi-objective deep reinforcement learning (RL) approach for novel
drug design discovery with desired properties. The usage of RL
approaches can be very beneficial since it does not require working on
labeled datasets that contain non-addictive drugs. In fact, gathering
and labeling such datasets can be time-consuming. Instead, by
leveraging an RL approach, we can conceive a specific reward function
geared toward guiding the model to explore a greedy policy through
trial and error. This policy will embody the non-addictive drug
properties. Nevertheless, having a large-scale action space for drug
discovery could lead to non-valid drug generation and model
divergence. Therefore, adding a pre-learned generative model for valid
drug generation in the RL loop can guarantee faster model
convergence. The generative model will be a deep learning (DL) model
trained on a general-purpose drug dataset. Regarding the model
architecture, we can adopt Graph Neural Networks, Transformers, or
diffusion models. In addition, inferring the reward value using a
hard-coded rule is not always feasible. However, the reward function
can be designed as a function of multiple selected properties. Indeed,
the property selection depends on the task. In our case, we have to
focus on particular pharmacokinetic and pharmacodynamic parameters. On
one hand, we know that rapid absorption, rapid entry into the central
nervous system, high bioavailability, short half-life, small volume of
distribution, and high free drug clearance are all characteristics
that predict the high potential of harmful use of opioid drugs. On the
other hand, a long half-life, low free drug clearance, and sufficient
drug exposure promote dependence and allow tolerance development. This
knowledge can direct us toward the optimal properties essential to
create non-opioid non-addictive drug alternatives. These properties
can be forecasted using a DL model. When training, the model will be
fed by a drug structure as input to predict relevant drug
properties. Our role will be to find the corresponding datasets for
our selected properties. As for the generative model, the predictive
model will be trained separately and then fine-tuned during the RL
optimization loop. The impact of this project will be promising since
it will accelerate the process of discovering new non-opioid drugs for
treating the VOC and propose possible combinations with their
resulting interactions. Eventually, we aim to build a general
framework, geared toward precision medicine, which suggests drugs with
desired properties for any kind of disease and for selective groups of
people.

## Theme:

machine learning and AI methods

## Team leader:

 * Name: Asma Alkhaldi
 * Contact: asma.akel98@gmail.com
 
## Submission number:

9
