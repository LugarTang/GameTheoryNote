# Subgame Perfect Equilibrium

在**信息完善的**动态博弈中，增加了sequential rationality要求的均衡概念是“子博弈完善均衡”Subgame Perfect Equilibrium

**Definition**

该策略组合在所有的子博弈中都构成纳什均衡.

**Method**

For finite step game

backwards induction

backward induction cannot be applied to games of [imperfect](https://en.wikipedia.org/wiki/Imperfect_information "Imperfect information") or [incomplete information](https://en.wikipedia.org/wiki/Incomplete_information "Incomplete information") because this entails cutting through non-singleton [information sets](https://en.wikipedia.org/wiki/Information_set_(game_theory)).

- 从最后的决策节点开始，找出行动者的最优反应
- 给定这些最优反应，找出前一轮中行动者的最优反应
- 以此类推，直到最初

A subgame perfect equilibrium necessarily satisfies the [one-shot deviation principle](https://en.wikipedia.org/wiki/One-shot_deviation_principle "One-shot deviation principle").

定理：在任何**有限的延展型博弈中，一定存在子博弈完善均衡**

在每个决策节点上，博弈者声称他会选择的行动必须是“可信的”(credible)

- 有时外部手段可以用以解决这个问题；可称为“承诺机制”(commitment devices) - 破釜沉舟

## 验证子博弈完善

验证子博弈完善（1）：要考虑每一类信息集

• 子博弈完善要求在每一个（历史之后）信息集上（包括那些不在博弈路径上的），博弈者都没有动力偏离既定的策略组合

而纳什均衡只需要考虑在均衡路径上的信息集，博弈者有没有动力偏离

• 因为信息集（历史）非常多，需要根据所讨论的策略组合将信息集（历史）划分为几类，分类讨论
-分类时要保证：划分为同一类的信息集上，既定策略所指定的后续策略组合是相同的

• 一次性偏离(one-period deviation)：给定一个策略组合，博弈者i在**某一个信息集**上改变了自己（那一步）的行动，但是在随后的后续博弈中保持自己的原策略不变（注意是策略不变）

• 定理：在重复博弈中(包括有限重复和折扣系数小于1的无限重复) ，一个策略组合是子博弈完善均衡的充分必要条件是：给定其他人的策略，任意一个博弈者i都无法通过某个一次性偏离来提高自己的收益

• 所以，在验证一个策略组合是否为子博弈完善均衡时，只需考察对于任意的信息集，博弈者i是否有动力在该处一次性改变其行动，给定其他人的策略和他自己在后续步骤中的策略不变
