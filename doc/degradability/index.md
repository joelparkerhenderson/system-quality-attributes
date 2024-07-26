# Degradability

**The quality/ability/extent of being degradable.**

<span data-chatgpt-prompt="degradability + template">

**Degradability** in systems refers to the ability of a system to maintain partial functionality and performance when some components fail or when under adverse conditions. It ensures that the system degrades gracefully, allowing it to continue operating, albeit with reduced performance or limited functionality.

### System Quality Attribute

As a **system quality attribute**, degradability focuses on the system's capacity to handle failures and adverse conditions without complete breakdown, maintaining essential services.

#### Key Aspects:
- **Graceful Degradation**: The system continues to operate with reduced functionality when components fail.
- **Fault Tolerance**: The system can tolerate faults and continue to provide services, possibly at a reduced level.
- **Performance Degradation**: The system's performance degrades gradually rather than abruptly failing.

### Non-Functional Requirement

As a **non-functional requirement** (NFR), degradability specifies the standards and criteria to ensure the system can handle failures and adverse conditions gracefully.

#### Key Aspects:
- **Redundancy**: The system includes redundant components that can take over in case of failures.
- **Failover Mechanisms**: The system has mechanisms in place to switch to backup components or systems during failures.
- **Monitoring and Alerts**: The system monitors its health and alerts operators about issues before they cause significant degradation.

### Cross-Functional Constraint

As a **cross-functional constraint**, degradability impacts various aspects of system design, development, and operation, requiring collaboration across different teams to ensure the system can degrade gracefully.

#### Key Aspects:
- **Design for Failure**: The system is designed with the expectation that components will fail and includes strategies for handling these failures.
- **Testing for Degradability**: The system undergoes rigorous testing to ensure it can degrade gracefully under different failure scenarios.
- **Operational Readiness**: The system is prepared for real-world conditions where failures and adverse situations are inevitable.

### Implementing Degradability

To implement degradability:
- **Incorporate Redundancy**: Design the system with redundant components and pathways to ensure continued operation during failures.
- **Implement Failover Mechanisms**: Develop robust failover mechanisms that can seamlessly switch to backup components or systems.
- **Use Graceful Degradation Techniques**: Ensure that the system can continue to provide essential services even if some features or performance levels are reduced.
- **Develop Robust Monitoring Systems**: Implement monitoring systems that continuously check the health of the system and provide early warnings of potential failures.
- **Perform Regular Degradability Testing**: Conduct regular testing to simulate different failure scenarios and assess the system's ability to degrade gracefully.
- **Maintain Comprehensive Documentation**: Provide detailed documentation on the system’s degradation strategies, including how to handle and recover from failures.
- **Design for Scalability**: Ensure that the system can scale down efficiently, maintaining essential functions even under constrained resources.
- **Ensure Clear Communication Channels**: Establish clear communication channels for alerting and informing stakeholders about system degradation and steps taken.
- **Implement Load Balancing**: Use load balancing to distribute workloads evenly and avoid overloading any single component.
- **Plan for Disaster Recovery**: Develop and regularly update disaster recovery plans to ensure quick recovery from major failures while maintaining essential services.

</span>

**Define degradable:** <span data-chatgpt-prompt="define degradable (computers and software)">Degradable refers to computer hardware or software that progressively loses functionality or performance over time. It may occur due to aging, obsolescence, wear and tear, or becoming outdated as newer and faster technology becomes available. Degradable components may cause computer systems to operate slower, glitch, or eventually fail altogether. Upgrading or replacing degradable parts is necessary to maintain system performance and prevent further degradation.</span>

## See Also

* [Wikipedia: TODO](TODO).

* [Dictionary: degrade](https://www.dictionary.com/browse/degrade): to reduce in amount, strength, intensity, etc. to lower in character or quality.

