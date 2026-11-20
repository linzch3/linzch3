# Hi, I'm linzch3

I work on **applied mathematics and numerical computing**, and contribute fixes to
**databases and data systems**, with a focus on correctness, reproducible bugs, and tests.

## Focus areas

- **Numerical methods for ODEs**: Runge–Kutta methods, stiff solvers, step-size control, stability analysis
- **Scientific Python and Julia**: SciPy, the SciML ecosystem
- **Data systems**: query engines, table formats, columnar data (Iceberg, Arrow, TiDB)

## Featured project

**[rkforge](https://github.com/linzch3/rkforge)**: Runge–Kutta methods built from their Butcher
tableaus. Explicit, embedded and implicit (stiff) integrators in Python, with a rooted-tree order-condition
checker, stability-region analysis and empirical convergence-order tests. Depends only on NumPy and SciPy.

## Open-source contributions

**Scientific computing**

| Project | Contribution | PR |
| --- | --- | --- |
| **Catalyst.jl** (SciML) · Julia | Added a "Common mistakes" documentation page for reaction-network modeling. | [#1584](https://github.com/SciML/Catalyst.jl/pull/1584) |
| **SciPy** · Python | Added references and a parameter mapping to the `scipy.stats.invgamma` docs. | [#26623](https://github.com/scipy/scipy/pull/26623) |
| **DataInterpolationsND.jl** (SciML) · Julia | Compact `show` output for N-dimensional interpolation objects. | [#109](https://github.com/SciML/DataInterpolationsND.jl/pull/109) |

**Databases and data systems**

| Project | Problem solved | PR |
| --- | --- | --- |
| **Apache PyIceberg** · Python | Fixed inconsistent filtered counts when a REST server omits the residual filter; added regression coverage for initial and paginated scan tasks. | [#4379](https://github.com/apache/iceberg-python/pull/4379) |
| **TiDB** · Go | Fixed incorrect query ordering for expressions involving `NULL`, including prepared statements with cached plans; added regression tests. | [#72707](https://github.com/pingcap/tidb/pull/72707) |
| **Armeria** · Java | Fixed sign extension when decoding values across buffers, preventing valid WebSocket frames from being rejected; added boundary tests. | [#7114](https://github.com/line/armeria/pull/7114) |

[More pull requests →](https://github.com/search?q=author%3Alinzch3+is%3Apr+is%3Apublic&type=pullrequests)

## Earlier projects and notes

- [Hidden-Markov-Model](https://github.com/linzch3/Hidden-Markov-Model): tutorials and notes on HMMs.
- [KNN MapReduce from scratch](https://github.com/linzch3/KNN-Mapreduce-From-Scratch): a KNN implementation using MapReduce.
- [Open Course Learning](https://github.com/linzch3/Open-Course-Learning): course notes and a long-running learning archive.

## How I work

Reproduce the failure, trace the cause, make a focused change, and back it with a test. For numerical code, that
test checks the mathematics too: convergence order, stability, conservation.

I use AI-assisted development, review the changes, and take responsibility for the work I submit.

Reach me here on GitHub: open an issue or mention **@linzch3**.

