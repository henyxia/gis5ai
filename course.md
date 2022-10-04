---
theme: gaia
paginate: true
backgroundColor: #fff
backgroundImage: url('./background.svg')
---

# **MLOPS**

Machine Learning and Operational

---

# Summary

- Architecture
- Machine Learning
- MLOps

---
<!--
footer: Architecture
-->

# Monolothic vs Web / API

#### And some communication protocol

- SOAP
- REST
- GRPC

---

<!--
push vs pull
-->

# Workers

---

# CDN

---

<!--
- Build
- Test
- Deploy
-->

# CI/CD

- Continuous Integration
- Continuous Deployment

---

<!--
- build: create artifact
- test: test types: unit / integration / functional / e2e
- deploy: git pull / ssh docker pull / nomad run
-->

# CI/CD

- Build
- Test
- Deploy

---

# Versioning

- Semantic
- CalVer

---

# Caching

- Redis
- Memcached
- MongoDB
- AWS DynamoDB
- Azure Cosmos DB

---

<!--
Client connection
Wait for server response?
HTTP Timeout
Example with database creation
-->

# Sync vs Async

---

# Queuing

- RabbitMQ
- MQTT
- Kafka

---

<!--
docker databases
-->

# Stateless / Stateful

---

<!--
Object: S3, AWS, hot vs cold
Block: VM, like disks
FS: mount point
-->

# Storage

- Object
- Block
- File System

---

# Observability

<!--
Rate Errors Duration
Utilization Saturation Errors
-->

- RED
- USE

Some software:

- Prom
- Grafana
- Alertmanager

---

<!--
footer: Machine Learning
-->

# Now the Machine Learning part!

- Supervised
- Unsupervised
- Encoding
- Data preparation

---

# Supervised algorithm

<!--
linear: y = w0*x0 + wn*xn +b (w and b parameters)
svm: support vector machine
        krbf(x1, x2) = exp -gamma*(|| x1 - x2 ||)
mlp: see page 108
-->

- Linear
- kNN
- Decision tree
- Random forest
- SVM kernel
- Multi Layer Perceptron (MLP)

---

# Unsupervised algorithm

<!--
PCA: see page 144 - transform correlated into uncorrelated data
NMF: see page 159 - reduce dimensions too
    pca: orthogonal features, maximal variance
    nmf: components and coeff non negatives
t-SNE: see page 167 - manifold learning (apprentissage de variete)
    explode then regroup values
    unusable on test data
-->

- PCA
- NMF
- t-SNE

---

### clustering

<!--
kMoy: create centers
Agglo: clustering
DBSCAN: see page 189 - clustering with empty space control (see two moons)
-->

- kMoy
- Agglo
- DBSCAN

----

<!--
One hot and data preparation
-->

# Preparation

- One-hot

---

<!--
footer: MLOps
-->

<!--
Tutorial aim: exposing an API
-->

# Now let's do everything together!

---

# An example

Physical shop, pay with your face.

---

<!--
Save model, compile it in the container
-->

# Real time vs asynchronous

---

<!--
Store model in container or load from S3
-->

# Local vs remote model

---

# Any question?
