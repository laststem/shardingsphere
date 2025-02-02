+++
pre = "<b>6.13. </b>"
title = "Shadow DB"
weight = 13
chapter = true
+++

## ShadowAlgorithm

### Fully-qualified class name

[`org.apache.shardingsphere.shadow.spi.ShadowAlgorithm`](https://github.com/apache/shardingsphere/blob/master/shardingsphere-features/shardingsphere-shadow/shardingsphere-shadow-api/src/main/java/org/apache/shardingsphere/shadow/spi/ShadowAlgorithm.java)

### Definition

Shadow algorithm's definition

### Implementation classes

| *Configuration Type* | *Description*                             | *Fully-qualified class name* |
| -------------------- | ----------------------------------------- | ---------------------------- |
| VALUE_MATCH | Match shadow algorithms based on field values     | [`org.apache.shardingsphere.shadow.algorithm.shadow.column.ColumnValueMatchShadowAlgorithm`](https://github.com/apache/shardingsphere/blob/master/shardingsphere-features/shardingsphere-shadow/shardingsphere-shadow-core/src/main/java/org/apache/shardingsphere/shadow/algorithm/shadow/column/ColumnValueMatchShadowAlgorithm.java) |
| REGEX_MATCH | Regular matching shadow algorithm based on field value  | [`org.apache.shardingsphere.shadow.algorithm.shadow.column.ColumnRegexMatchShadowAlgorithm`](https://github.com/apache/shardingsphere/blob/master/shardingsphere-features/shardingsphere-shadow/shardingsphere-shadow-core/src/main/java/org/apache/shardingsphere/shadow/algorithm/shadow/column/ColumnRegexMatchShadowAlgorithm.java) |
| SIMPLE_HINT    | Simple match shadow algorithm based on Hint | [`org.apache.shardingsphere.shadow.algorithm.shadow.hint.SimpleHintShadowAlgorithm`](https://github.com/apache/shardingsphere/blob/master/shardingsphere-features/shardingsphere-shadow/shardingsphere-shadow-core/src/main/java/org/apache/shardingsphere/shadow/algorithm/shadow/hint/SimpleHintShadowAlgorithm.java) |
