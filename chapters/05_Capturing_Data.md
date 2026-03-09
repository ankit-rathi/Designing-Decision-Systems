## Chapter 5 — Capturing Data

### Chapter Crux

Data quality begins at the moment reality is observed.

Before organizations can analyze data or build intelligence systems, they must first **capture reliable observations of real-world events**. This process—often called instrumentation—is the foundation of every data system.

Reality generates a continuous stream of activities: users clicking on products, machines producing output, customers making purchases, and systems interacting with one another. Data capture converts these activities into **recorded events** that can be stored, analyzed, and used for decision-making.

The accuracy, completeness, and consistency of these observations determine the usefulness of everything that follows. If data is captured poorly, even the most sophisticated analytics or machine learning systems will produce misleading results.

In other words, **data quality does not begin in analytics—it begins at the moment data is generated and recorded**.

---

### Problem

Many organizations focus heavily on analytics and machine learning while overlooking the importance of data capture.

Common issues include:

* missing event tracking in applications
* inconsistent logging across systems
* incomplete instrumentation of business processes
* poorly defined data fields
* fragmented data sources

When data is captured inconsistently, organizations face problems such as:

* incomplete datasets
* unreliable metrics
* inaccurate models
* difficult system integration

For example, if a digital product fails to track key user actions—such as searches, clicks, or purchases—analysts cannot reconstruct user behavior accurately.

The fundamental challenge is that **reality must first be observed before it can be analyzed**. If observation is incomplete or inconsistent, the resulting data will distort the underlying reality.

---

### Key Diagram

**From Real-World Events to Data Records**

```id="q8sp6b"
Real-World Activity
   ↓
Instrumentation
   ↓
Event Capture
   ↓
Data Records
   ↓
Data Storage
```

Explanation:

* **Real-world activity:** actions occurring in business systems or environments
* **Instrumentation:** mechanisms that observe these actions
* **Event capture:** recording events as structured logs or transactions
* **Data records:** stored representations of those events

This process converts **continuous reality into discrete data**.

---

### Core Mechanism

Capturing data typically involves four key components.

**1. Instrumentation**

Instrumentation refers to the mechanisms used to observe and record events.

Examples include:

* application tracking code
* logging systems
* sensors and monitoring devices
* transaction records in operational systems

Instrumentation determines **what events are visible to the data system**.

---

**2. Event Tracking**

Many modern data systems use **event tracking** to capture interactions.

Events typically record:

* what happened
* who performed the action
* when it occurred
* where it happened
* additional context

For example, a product click event might capture:

* user ID
* product ID
* timestamp
* device type

These events form the raw behavioral data used for analytics and modeling.

---

**3. Data Generation Sources**

Data originates from multiple sources across an organization, including:

* operational transaction systems (orders, payments)
* digital applications (user interactions)
* sensors and IoT devices
* system logs and infrastructure monitoring

Each source captures different aspects of organizational activity.

---

**4. Structured vs Unstructured Data**

Captured data can take different forms:

* **Structured data:** organized into predefined fields (transactions, database records)
* **Unstructured data:** text, images, audio, or logs without rigid structure

Both types can provide valuable signals, but structured data is typically easier to analyze.

---

### Example

Consider a streaming platform that wants to understand viewer behavior.

To capture relevant data, the platform instruments its application to track events such as:

* video play
* pause
* rewind
* completion
* search queries

Each time a user interacts with the platform, an event is recorded containing:

* user ID
* content ID
* timestamp
* device type
* viewing duration

These events are stored in logs and later processed into datasets for analytics and recommendation algorithms.

Without this instrumentation, the platform would have little visibility into how users interact with its content.

---

### Insight

Organizations often think of data as something that appears automatically within systems.

In reality, **data must be deliberately captured through well-designed instrumentation**.

The quality of a data system depends heavily on:

* what events are tracked
* how consistently they are recorded
* how completely they represent real-world behavior

If important events are not captured, no amount of analysis can recover them later.

In other words:

> Data systems cannot analyze what they fail to observe.

Capturing accurate observations of reality is therefore the first critical step in building reliable data and intelligence systems.
