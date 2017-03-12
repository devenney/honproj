# A Multi-Agent System Architecture for Carpooling Solutions

Submitted in partial fulfilment of the requirements of [@edinburgh-napier](https://github.com/edinburgh-napier) for the Degree of BEng (Hons) Software Engineering.

## Abstract

The global social, economic and environmental state lends itself to high adoption rates of participatory culture schemes such as carpooling. There has been significant government discussion around carpooling in the United Kingdom in recent years but no significant action taken to support or encourage uptake. Corporate solutions such as SAP and Comovee pose a high financial barrier to entry in some of the most troubling economic times. Meanwhile, the lack of research concerning modern carpooling system architecture creates a barrier to in-house development and deployment of such systems.

The aims of this project are: to investigate the factors for and against adoption of carpooling systems and schemes; to architect a system which takes into consideration these factors; and to investigate the benefits and drawbacks of agent technology in such a system. Evaluation and validation is conducted via a proof of concept implementation of the architecture which is based on the scenario of Edinburgh Napier University’s staff taxisharing when travelling between campuses.

The major discovery of the evaluation was a clear bottleneck in the Java Agent Development Framework (JADE) due to the directory facilitator offering significantly worse scaling than the rest of the framework in systems high on communication. This problem has previously been solved through search caching per container – a solution which is not applicable for a truly scalable carpooling system. The paper proceeds to provide a novel solution to this problem which builds upon the previous work.

In conclusion, agent technology is suitable to carpooling solutions due to the high distributability of the problem and the clear matching of the agent lifecycle to the lifecycle of the carpool negotiation process. Due to the unforeseen focus on the directory facilitator bottleneck, the paper concludes with a wealth of further work which would build upon the work presented in this paper.
