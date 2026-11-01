# RecAgent

**Agent-as-a-Service for personalized recommendation.**

RecAgent balances immediate relevance with diversity, freshness, creator supply, and long-term user value.

面向推荐系统的 Agent：在相关性、多样性、新鲜度、生态健康与长期用户价值之间做动态权衡。

## Agent loop

| Stage | Responsibility |
|---|---|
| Data | User events, item graph, context, creator supply |
| Models | User/item encoders, generative recommender, ranking policy |
| Training | Preference optimization, long-term reward modeling |
| Inference | Candidate generation, constrained reranking, serving |
| Harness | Inventory, freshness, experimentation, policy tools |
| Eval | Relevance, diversity, retention, ecosystem health |

## Initial scope

- Build reproducible offline recommendation evaluation.
- Separate short-term engagement from long-term value.
- Support constrained candidate generation and explanation.

## Roadmap

- [ ] Evaluation dataset and metrics
- [ ] Retrieval and ranking baselines
- [ ] Generative recommendation prototype
- [ ] Multi-objective policy tuning
- [ ] Online experiment integration

## Engineering principles

- Never optimize a proxy metric without guardrails.
- Keep exploration, diversity, and freshness observable.
- Make recommendation decisions inspectable.

