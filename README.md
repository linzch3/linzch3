# Hi, I'm linzch3

I contribute fixes to databases, data systems, and backend infrastructure, with a focus on correctness, reproducible bugs, and regression tests.

## Selected open-source contributions

| Project | Problem solved | Merged PR |
| --- | --- | --- |
| **Apache PyIceberg** · Python | Fixed inconsistent filtered counts when a REST server omits the residual filter; added regression coverage for initial and paginated scan tasks. | [#4379](https://github.com/apache/iceberg-python/pull/4379) |
| **TiDB** · Go | Fixed incorrect query ordering for expressions involving `NULL`, including prepared statements with cached plans; added regression tests. | [#72707](https://github.com/pingcap/tidb/pull/72707) |
| **Armeria** · Java | Fixed sign extension when decoding values across buffers, preventing valid WebSocket frames from being rejected; added boundary tests. | [#7114](https://github.com/line/armeria/pull/7114) |

[Explore my merged pull requests →](https://github.com/search?q=author%3Alinzch3+is%3Apr+is%3Amerged+is%3Apublic&type=pullrequests)

## Projects & learning

- [KNN MapReduce from scratch](https://github.com/linzch3/KNN-Mapreduce-From-Scratch) — a KNN implementation using MapReduce.
- [Open Course Learning](https://github.com/linzch3/Open-Course-Learning) — course notes and a long-running learning archive.

## How I work

Reproduce the failure, trace the cause, make a focused fix, and add a regression test.

I use AI-assisted development, review the changes, and take responsibility for the work I submit.
