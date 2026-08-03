# Hi, I'm Joshua 👋

IT student (BS Information Technology, Quezon City University, expected June 2028) specializing in privacy-preserving systems and applied cryptography — zero-knowledge proofs, homomorphic encryption, and tamper-evident data architectures, built on top of full-stack development experience.

I like building things that are hard on purpose: systems where the interesting part isn't "does it work" but "does it actually keep the guarantee it claims to."

**Currently exploring:** extending homomorphic encryption from statistics and credentials into federated machine learning.

---

## 🔐 Featured: Privacy-Preserving Systems

### [EncryptedHealthLedger](https://github.com/PoorProgrammer0A33/Encrypted-Health-Ledger)
Homomorphic encryption pipeline (CKKS via Microsoft SEAL) computing aggregate health statistics — the server never holds a decryption key, ever. Client generates its own keys and is the only party that can decrypt. Real-time stat broadcasting via SignalR, tamper-evident audit logging via Oracle 26ai Blockchain Tables.

`C#` `.NET 8` `Microsoft SEAL` `SignalR` `Oracle Database`

### [LihimSuri](https://github.com/PoorProgrammer0A33/LihimSuri-ZKP)
Zero-knowledge scholarship eligibility system — proves a student's income is below a threshold *without revealing the income itself*, to anyone. Circom + Groth16 circuit, Poseidon hashing, Oracle blockchain-table audit trail.

`Circom` `SnarkJS` `Groth16` `Node.js` `Oracle Database`

### [PrivacyMesh](https://github.com/PoorProgrammer0A33/privacymesh)
Federated learning platform where clients train locally and share only homomorphically-encrypted gradients — the aggregator sums and averages ciphertexts directly and is structurally unable to decrypt anything, verified by deliberately attempting decryption on the aggregator side and confirming it fails. 8-round training runs show consistent, monotonic loss convergence for every client tested. Deployed and validated across independently networked environments (native Windows + WSL2), with a live FastAPI dashboard streaming training progress in real time.

`Python` `PyTorch` `TenSEAL (CKKS)` `gRPC` `Docker` `FastAPI`

### MediProof — *in progress, pending academic defense*
ZKP-based medical credential verification system extending the same circuit architecture as LihimSuri into healthcare. Six-project .NET architecture (API, MAUI, Razor Pages admin). Repository private until capstone defense clears.

---

## 🧮 Also Building

### [SwarmLogistics](https://github.com/PoorProgrammer0A33/SwarmLogistics)
Delivery route optimization platform — custom Ant Colony Optimization engine solving the Vehicle Routing Problem with real road-network routing (OSRM), zone/location tracking, live analytics, and multi-vehicle auto-dispatch with priority-aware capacity bin-packing.

`Python` `FastAPI` `PostgreSQL` `Docker` `OSRM`

### [forensics-ml-cpp](https://github.com/PoorProgrammer0A33/forensics-ml-cpp)
Linear regression, logistic regression (gradient descent from scratch), and Mahalanobis-distance anomaly detection — implemented directly on raw linear algebra (Eigen), not library black-boxes.

`C++` `Eigen`

---

## 🛠️ Skills

**Applied Cryptography:** Zero-Knowledge Proofs (Circom, SnarkJS, Groth16), Homomorphic Encryption (CKKS, Microsoft SEAL, TenSEAL)

**Languages:** Python, C#, JavaScript, PHP, SQL, C++, Java

**Backend & ML:** FastAPI, ASP.NET Core, .NET MAUI, SignalR, Entity Framework Core, SQLAlchemy, PyTorch, gRPC

**Databases:** PostgreSQL, Oracle Database (26ai Blockchain Tables), Alembic

**Tools:** Git, Docker, Postman, JWT Auth, REST APIs

---

💼 [LinkedIn](www.linkedin.com/in/mendez-joshua-oxales)
