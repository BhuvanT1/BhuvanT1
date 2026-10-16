# Themballi Bhuvan

B.Tech CSE (AI/ML) at Vellore Institute Of Technology. I build ML and LLM systems that are
measured before they are trusted: a model proposes, code checks, and the
evaluation says what the system cannot yet claim.

### Projects

**[Satark](https://github.com/BhuvanT1/satark-agent)**: a cyber-fraud
first-responder agent for India. It investigates a suspicious SMS or WhatsApp
message, scores scam risk behind deterministic safety floors that an LLM cannot
override, and drafts the complaint pack in Indian languages. On a 12-case
adversarial bench (leetspeak, homoglyphs, zero-width text, prompt injection in
English, Hindi and Telugu) it catches 12/12, even with the LLM reviewer forced
to say "legitimate". *Python, FastAPI, Docker.*

**[YojanaMitra](https://github.com/BhuvanT1/yojanamitra)**: tells a citizen
which government schemes they qualify for, from plain-language input in
English, Hindi, Telugu or code-mixed text. An LLM never decides eligibility: a
rule engine evaluates human-approved constraints over 2,066 schemes, every
extracted fact must quote the user's own words, and every verdict quotes the
source clause. *TypeScript, Next.js, scikit-learn.* Team project.

**[OnTime](https://github.com/BhuvanT1/ontime-delivery-risk)**: delivery-risk
and root-cause analytics on 99K e-commerce orders. A SQL warehouse with
leakage-safe history joins, a calibrated risk model (ECE 0.156 → 0.038 under a
base-rate shift), and a cost model that concludes the model should *not* be
deployed as an intervention trigger. *SQL, DuckDB, Python, LightGBM.*

**[Route Resilience](https://github.com/BhuvanT1/route-resilience)**:
satellite imagery → road mask → routable graph → criticality and failure
simulation. U-Net trained with synthetic occluders (test IoU 0.62, clDice
0.84), MST-based topology healing, and a resilience metric that is bounded by
construction. *PyTorch, NetworkX, FastAPI, React.* Capstone team lead.

**[DepthWizards](https://github.com/BhuvanT1/depthwizard)**: building heights
from one satellite image, measured from shadow geometry instead of guessed by a
depth model. Depth Anything V2 was tried first and scored R² = −0.74 against
shadow anchors, so it was demoted to ground-surface duty. Checked per building
against USGS LiDAR (RMSE 3.88 m on Fort Myers), with an offline Docker build
and a browser 3D viewer. *Python, PyTorch, FastAPI, Three.js.* Smart India
Hackathon 2026 team project.

### Tools

Python · TypeScript · SQL · PyTorch · scikit-learn · FastAPI · Next.js · React ·
DuckDB · Docker
