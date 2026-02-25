## **G. Data Quality — Failure Modes in Practice**

**Why:** Poor quality propagates silently, eroding decision reliability.

**What:** Errors include **duplicates, stale data, inconsistent units, or misaligned transformations**.

**How:** Monitor, validate, and clean data continuously. Example: Mismatched currencies in financial systems can distort forecasts.

---

From first principles, decisions are only as reliable as the signals informing them. Data is a representation of reality; if that representation is distorted, every downstream model, dashboard, or strategy inherits the distortion. The danger is not visible failure — it is silent drift.

Data quality failures propagate because systems assume inputs are valid. Once an error enters a pipeline, it is aggregated, transformed, and amplified. By the time it appears in an executive report, the original flaw is often invisible.

Common failure modes illustrate how subtle corruption occurs:

**Duplicates.** If a customer appears twice under slightly different identifiers, revenue may be double-counted and churn underestimated. Marketing spend may be misallocated because lifetime value appears inflated. Duplication distorts entity-level truth.

**Stale data.** Suppose inventory data updates weekly instead of in real time. A demand forecasting model trained on outdated stock levels may trigger unnecessary procurement or miss stockouts. The data is structurally correct but temporally wrong.

**Inconsistent units.** Mixing kilograms and pounds, or INR and USD without conversion, creates analytical illusion. A financial system aggregating revenue across currencies without normalization can dramatically misstate performance. The numbers look precise but represent incompatible realities.

**Misaligned transformations.** A common issue arises when different teams calculate the same metric differently. For example, “active user” may mean login in the past 7 days for one dashboard and 30 days for another. Decisions based on these conflicting definitions create organizational confusion.

The deeper principle: quality errors compound multiplicatively. A small upstream inconsistency, when passed through multiple transformations, becomes a structural bias.

Prevention requires continuous governance, not periodic cleanup. Effective systems implement:

* Validation checks at ingestion (range checks, format checks).
* Referential integrity constraints.
* Monitoring for anomaly detection (sudden spikes, drops).
* Reconciliation across systems.
* Clear metric definitions with version control.

Data cleaning is not a one-time project; it is an operational discipline. Quality must be measured like performance.

In strategic systems, the cost of poor data is not just technical debt — it is misallocated capital, flawed risk assessment, and lost trust.

Reliable decisions require reliable inputs. Without disciplined data quality practices, organizations optimize noise while believing they are optimizing reality.

