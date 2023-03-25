# Atomicity

**The quality/ability/extent of being atomic transactionally.**

<span data-chatgpt-prompt="explain atomicity (system quality attribute, non-functional requirement, cross-functional constraint )">

Atomicity is a system quality attribute that refers to the property of a system where a sequence of operations is treated as a single, indivisible transaction. In other words, the atomicity of a system is the guarantee that a series of related operations will either succeed or fail as a single unit, without any partial completion.

Atomicity is also considered a non-functional requirement because it does not deal with the specific functionalities of the system, but rather with its overall behavior and performance. It is a critical non-functional requirement for systems that handle complex transactions, such as finance and banking.

Atomicity is a typically not an important cross-functional constraint, because most organizational teams want atomicity, and rely on it. However, some high-scalability systems may need to involve cross-functional contraints when the scale issues must change from atomicity to other approaches such as eventual consistency, or out-of-order event stream processing, or probability-weighted transactions.

To achieve atomicity, a system should have mechanisms that ensure that transactions are executed reliably, securely, and consistently. These mechanisms should support rollback and recovery, isolation, and consistency of the data, and ensure that the system is fault-tolerant and available.

</span>

**Define atomic:** <span data-chatgpt-prompt="define atomic (computers and software)">An atomic transaction is a data transaction in which a series of data operations are treated as a single, indivisible operation. In other words, either all of the operations are executed and the transaction is committed, or none of the operations are executed and the transaction is rolled back. This guarantees that data are always in a consistent state, even if an error occurs during the transaction. Atomicity is one of the four key properties of an ACID data transaction.</span>

## See Also

* [Wikipedia: Atomicity (database systems)](https://wikipedia.org/wiki/Atomicity_(database_systems)): a transaction must be "all or nothing"; see [ACID](https://wikipedia.org/wiki/ACID).

* [Dictionary: TODO](TODO)
