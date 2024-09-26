# Hibernate @Fetch(FetchMode.JOIN)

The original idea is from  
https://medium.com/@antelll/solving-the-hibernate-n-1-problem-best-practices-and-strategies-fa437d327a98

See also
https://medium.com/jpa-java-persistence-api-guide/hibernate-optimization-with-batchsize-and-batch-size-configuration-579bf759fc05

This example shows @BatchSize At Collection Level

# @BatchSize At Class Level

Applying @BatchSize(size=50) to an entity class instructs Hibernate to load these entities in batches of 50 instances at
a time during lazy loading.

# @BatchSize At Collection Level

It loads the books of N authors at once. 


