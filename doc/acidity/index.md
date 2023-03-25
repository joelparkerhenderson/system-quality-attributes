# ACIDity

**The quality/ability/extent of being ACID.**

<span data-chatgpt-prompt="explain ACID, atomicity, consistency, isolation, durability (system quality attribute, non-functional requirement, cross-functional constraint )">

ACID is an acronym for Atomicity, Consistency, Isolation, and Durability. It is a set of properties that guarantees reliable processing of database transactions.

* Atomicity: the property of a transaction that ensures that either all changes made during the transaction are committed or none at all. If a transaction fails for any reason, all the changes made within it are rolled back, returning the system to its original state.

* Consistency: the fact that the system's data state will remain valid before and after a transaction. This means that the rules and constraints defined in the database must be followed consistently.

* Isolation: the property that ensures that a transaction runs independently of other transactions. This is important to prevent interference from other transactions and errors that could result from concurrent access to data.

* Durability: the property that guarantees that once a transaction has been committed, it is permanently saved even in the case of system failures or crashes. 

ACIDity is a system quality attribute, which is a property or characteristic of a system that describes its overall quality, especially with regard to databases and transactions.

ACIDity a non-functional requirement, as it describe how the system should behave overall.  For some high scalability systems, ACID is difficult to achieve practically or cost-effectively, and may be superseded by eventual consistency.

ACIDity is typically not an important cross-functional constraint, because in practice many organization teams agree on ACID. 

</span>

**Define ACID:** <span data-chatgpt-prompt="define ACID (computers and software)">ACID refers to a set of properties that guarantee that database transactions are processed reliably. These properties ensure that data remains accurate, reliable, and consistent, even when multiple users are simultaneously accessing and modifying data.</span>

## See Also

* [Wikipedia: ACID](https://wikipedia.org/wiki/ACID): ACID (atomicity, consistency, isolation, durability) is a set of properties of database transactions intended to guarantee data validity despite errors, power failures, and other mishaps.[1] In the context of databases, a sequence of database operations that satisfies the ACID properties (which can be perceived as a single logical operation on the data) is called a transaction. For example, a transfer of funds from one bank account to another, even involving multiple changes such as debiting one account and crediting another, is a single transaction. 
  
* [Dictionary: ACID](https://www.dictionary.com/browse/ACID)

