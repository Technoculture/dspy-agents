## DSPy-Agents
One of the core challenges with current state of agents is that they can not be trained as agents. They are built out of frozen language models which then are barely if at all exposed to their target environment. DSPy with its automated prompt optimization and eventually automated fine tuning - could emerge as the ideal **optimization** oriented framework for higher order AI systems. Think DSPy-gym, DSPy-autoLLM and so on.

## Why DSPy-Agents?
Provide a highly opinionated stack for production grade dspy agents. We should be able to use this library at the abstraction level offered by CrewAI - and get code that runs reliably in an event driven architecture - deployable at scale on a kubernetes cluster.
- **Sqlite**: Database for Models and Compiled LLM Programs
- **DSPy**: Allow for agents to be compiled for their roles and model at hand
- **Dapr**: Deploy an orchestra of DSPy agents as a cluster of microservices

## Future Direction
- **SgLang**: Deploy optimized agents on GPUs

## References
- [CrewAI]()
- [AutoGen]()
