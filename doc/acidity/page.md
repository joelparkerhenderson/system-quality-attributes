# ACIDity

**The quality/ability/extent of being ACID.**

<span data-chatgpt-prompt="explain ACID, atomicity, consistency, isolation, durability (system quality attribute, non-functional requirement, cross-functional constraint)">

ACIDity is a system quality attribute that is an acronym for Atomicity, Consistency, Isolation, and Durability. Atomicity is the property of a transaction that ensures that either all changes made during the transaction are committed or none are. Consistency is the fact that the system's data state will remain valid before and after a transaction. Isolation is the property that ensures that a transaction runs independently of other transactions. Durability is the property that guarantees that once a transaction has been committed, it is permanently saved even in the case of system failure.

ACIDity is a non-functional requirement that describes how the system should manage data, especially with considerations for transaction processing, error rollbacks, and complex testing for parallel use.  For some high scalability systems, ACID is difficult to achieve practically or cost-effectively, and may be superseded by eventual consistency.

ACIDity is typically not an contentious cross-functional constraint, because in practice many organizations are strongly in favor of  ACID and already use it regularly.

</span>

**Define ACID:** <span data-chatgpt-prompt="define ACID (computers and software)">ACID refers to a set of properties that guarantee that database transactions are processed reliably. These properties ensure that data remains accurate, reliable, and consistent, even when multiple users are simultaneously accessing and modifying data.</span>

## See Also

* [Wikipedia: ACID](https://wikipedia.org/wiki/ACID): ACID (atomicity, consistency, isolation, durability) is a set of properties of database transactions intended to guarantee data validity despite errors, power failures, and other mishaps.[1] In the context of databases, a sequence of database operations that satisfies the ACID properties (which can be perceived as a single logical operation on the data) is called a transaction. For example, a transfer of funds from one bank account to another, even involving multiple changes such as debiting one account and crediting another, is a single transaction. 
  
* [Dictionary: ACID](https://www.dictionary.com/browse/ACID)

