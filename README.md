
REM — Recursive Evolving Memory 

A local-first architecture for lifelong personal artificial intelligence.
Models are temporary. Your personal intelligence should be continuous.
REM is a source-available project for building artificial intelligence that doesn't just remember a user—it learns, evolves, acts, and grows with them over time.
The goal is to make persistent personal AI available to ordinary people using hardware they already own.
A gaming PC and a phone should be enough.
REM is designed to run primarily on local models, store personal information locally, learn from user-authorized experiences, develop a dedicated Personal Expert, perform authorized actions through Personal Agentics, and preserve accumulated personalization when the underlying AI model is eventually replaced.
The AI model can change.
The user's accumulated personal intelligence remains.
Why REM?
Today's AI assistants are largely temporary.
You can spend years interacting with an AI system, but much of what it learns about you exists as:
chat history
prompts
retrieved documents
profile fields
vector embeddings
application-specific memory
Replace the model and much of the accumulated intelligence disappears.
REM approaches the problem differently.
Instead of asking:
How do we give an AI better memory?
REM asks:
How does an AI actually grow with one person over years—and how does that learned intelligence survive when the model itself becomes obsolete?
That requires more than memory.
It requires an entire lifecycle.
EXPERIENCE
     ↓
MEMORY
     ↓
UNDERSTANDING
     ↓
CONSOLIDATION
     ↓
LEARNING
     ↓
PERSONAL INTELLIGENCE
     ↓
REASONING
     ↓
ACTION
     ↓
OUTCOME
     ↓
NEW EXPERIENCE
     ↺
That is REM.
The Three Core Systems
REM is built around three major systems:
REM
│
├── Memory & Experience
│
├── MPC
│   Model Personalization Core
│
└── Personal Agentics
Each has a different responsibility.
REM Memory & Experience
REM determines:
What happened?
It receives experiences, identifies events, builds memories, connects related information, tracks confidence and contradictions, forgets insignificant information, and consolidates stable patterns.
MPC — Model Personalization Core
MPC determines:
What should the AI actually learn from those experiences?
MPC creates and maintains the user's Personal Expert.
It manages:
training
challenge generation
evaluation
gap detection
targeted retraining
versioning
behavioral extraction
model succession
Personal Agentics
Personal Agentics determines:
What should the AI do?
It gives the user's personal intelligence controlled access to tools, software, devices, services, and automations.
The results of those actions become new REM experiences.
Together they create a continuous loop:
REM
 ↓
MPC
 ↓
Personal Intelligence
 ↓
Personal Agentics
 ↓
Action
 ↓
Outcome
 ↓
REM
 ↺
Local First
REM is being designed primarily for local AI models.
The primary REM installation runs on a computer controlled by the user.
We call this machine the:
REM Mothership
┌─────────────────────────────────────┐
│            REM MOTHERSHIP           │
│                                     │
│ Local LLM / MoE                     │
│ Personal Expert                     │
│ Weighted RAG                        │
│ Memory Graph                        │
│ MPC                                 │
│ Training Engine                     │
│ Personal Agentics                   │
│ Agent Tools                         │
│ REM Vault                           │
│ Remote Access                       │
└─────────────────────────────────────┘
The Mothership is the center of the user's personal AI.
Personal memory does not need to live on somebody else's AI server.
Consumer Hardware First
REM should not require a datacenter.
The target platform is an ordinary modern gaming PC.
Different hardware can run different intelligence levels.
Gaming PC
    ↓
REM Hardware Detection
    ↓
Available CPU / GPU / RAM / VRAM
    ↓
Select Appropriate Model
    ↓
Select Quantization
    ↓
Configure REM
    ↓
Configure Training Strategy
A lower-memory gaming GPU may run a smaller quantized model.
A 16–24 GB GPU may run significantly larger models.
High-memory systems may run large Mixture-of-Experts architectures.
The REM architecture remains the same.
Better hardware should improve REM. Better hardware should not be required to participate.
The REM Mothership
The Mothership hosts the major REM services.
Conceptually:
REM MOTHERSHIP
│
├── Model Runtime
│
├── Personal Expert
│
├── Personal Router
│
├── REM Core
│   ├── Episodic Memory
│   ├── Semantic Memory
│   ├── Weighted RAG
│   ├── Memory Graph
│   ├── Salience
│   ├── Confidence
│   ├── Contradictions
│   └── Consolidation
│
├── MPC
│   ├── Training
│   ├── Evaluation
│   ├── Gap Detection
│   ├── Behavioral Extraction
│   ├── Versioning
│   └── Succession
│
├── Personal Agentics
│   ├── Planning
│   ├── Tools
│   ├── Skills
│   ├── Permissions
│   ├── Execution
│   └── Outcome Evaluation
│
├── REM Vault
│
├── Satellite Gateway
│
└── Remote Access
The Personal Expert
REM is ultimately intended to support a true neural Mixture-of-Experts architecture.
Most experts provide general intelligence.
One expert specializes in a single subject:
the user.
MoE MODEL
                       │
                     Router
                       │
       ┌───────────────┼───────────────┐
       ▼               ▼               ▼
    General          Domain         PERSONAL
    Experts          Experts         EXPERT
                                      │
                                      ▼
                                Learns the User
The Personal Expert can learn durable patterns involving:
preferences
relationships
projects
businesses
terminology
routines
equipment
goals
working methods
decision patterns
recurring behaviors
historical context
agentic preferences
The general model knows about the world.
The Personal Expert learns about you.
This Is a True MoE
REM's Personal Expert concept should not be confused with several independent AI models sending natural-language messages to one another.
In the intended architecture, experts exist inside the neural model.
The router decides which experts process a hidden-state representation.
Token Representation
        ↓
      Router
        ↓
   Expert Selection
    ↙    ↓     ↘
General Math Personal
    ↘    ↓     ↙
Combined Representation
        ↓
Next Transformer Layer
Personalization therefore becomes part of model computation rather than simply another prompt.
Memory Is Still Essential
Parametric learning does not replace explicit memory.
Some information should remain memory rather than become model weights.
For example:
Current appointment
Current balance
Recent conversation
Temporary project status
Exact phone number
Today's schedule
Other information may become stable enough to learn:
Long-term preferences
Recurring decision patterns
Stable relationships
Working methods
Communication preferences
Persistent goals
REM therefore combines:
explicit memory + parametric personalization.
Weighted Memory
Not every memory should have equal influence.
Traditional RAG primarily asks:
Which stored information is semantically similar to this query?
REM asks more.
A memory can be influenced by:
semantic relevance
recurrence
recency
salience
confidence
independent confirmation
graph connectivity
outcome usefulness
contradictions
temporal decay
user confirmation
source reliability
Conceptually:
Retrieval Influence

Semantic Similarity
        ×
Memory Strength
        ×
Context Relevance
        ×
Graph Proximity
        ×
Temporal Relevance
        ×
Confidence
The exact weighting system remains an active design and research problem.
Retrieval Is Not Truth
REM must avoid a dangerous feedback loop:
Incorrect Memory
      ↓
Retrieved Often
      ↓
Weight Increases
      ↓
Retrieved More Often
      ↓
Appears Important
      ↓
Becomes "Truth"
Retrieval frequency therefore cannot independently establish truth.
REM instead considers provenance, independent corroboration, contradictions, confidence, and outcomes.
Artificial Salience
Human memory does not treat every experience equally.
Neither should REM.
A routine event may quickly disappear.
A major event may remain significant even if it happened only once.
REM introduces Artificial Salience.
Routine Event
     ↓
Low Salience
     ↓
Decay


Important Event
     ↓
High Salience
     ↓
Long-Term Memory
     ↓
Potential Consolidation
Artificial salience is not intended to reproduce human emotion.
It is a computational mechanism for estimating:
How consequential is this experience to this user?
The Memory Graph
Memories are relational.
REM therefore maintains a graph connecting:
people
businesses
projects
devices
locations
objects
events
decisions
goals
preferences
rules
outcomes
concepts
For example:
Person
                 │
              works at
                 │
              Business
             /        \
        Project      Customer
           │
         Server
           │
        Software
Nodes and relationships can contain:
confidence
strength
salience
timestamps
evidence
provenance
contradictions
decay state
The graph evolves as the user's life changes.
Cross-Modal Corroboration
REM can identify when different observations support the same underlying event or pattern.
Example:
Search for Laptop
       ↓
Watch Reviews
       ↓
Compare Models
       ↓
Purchase Receipt
       ↓
Bluetooth Device Appears
       ↓
Repeated Usage
       ↓
Positive Comments
These are not necessarily seven unrelated memories.
Together they may provide strong evidence that:
the purchase occurred
which device was purchased
the user actually uses it
the user appears satisfied with it
Independent evidence can therefore strengthen memory confidence.
REM Satellites
The Mothership cannot directly experience everything happening around the user.
REM uses Satellites.
The primary Satellite will typically be the user's phone.
Potential satellites and information sources may include, where technically available and explicitly permitted:
phones
computers
AI glasses
wearables
microphones
cameras
vehicles
smart-home devices
ONVIF video feeds
Bluetooth devices
browser activity
email
messages
calendars
contacts
files
photos
videos
purchases
receipts
connected services
Access is always subject to user permission, platform restrictions, security boundaries, and applicable privacy and recording laws.
Local Sensory Processing
REM is not intended to continuously stream a person's raw life to another server.
Where practical, raw information is interpreted locally.
Camera
Audio
Messages
Photos
Device Events
     │
     ▼
Small Local Models
     │
     ▼
Perception
     │
     ▼
Event Extraction
     │
     ▼
Salience / Confidence
     │
     ▼
Structured REM Event
     │
     ▼
Mothership
The Satellite observes.
The Mothership learns.
Short-Term Episodic Memory
Most sensory information should disappear.
RAW EXPERIENCE
      ↓
Temporary Local Buffer
      ↓
Local Interpretation
      ↓
Potentially Significant?
     ↙              ↘
   NO                YES
   ↓                  ↓
Expire             REM Event
REM is not intended to create a permanent indiscriminate recording of someone's existence.
Forgetting is part of the architecture.
Memory Consolidation
Over time, REM identifies connected experiences that may represent stable patterns.
Individual Memories
        ↓
Connected Evidence
        ↓
Pattern Detection
        ↓
Contradiction Analysis
        ↓
Stability
        ↓
Generalization
        ↓
Consolidated Knowledge
Consolidated knowledge can remain explicit or become eligible for Personal Expert training.
MPC — Model Personalization Core
The Model Personalization Core connects REM memory to neural learning.
REM asks:
What happened?
MPC asks:
What should the model learn from what happened?
REM
 ↓
Stable Knowledge
 ↓
MPC
 ↓
Training Examples
 ↓
Personal Expert
MPC controls the entire lifecycle of the Personal Expert.
Personal Expert Birth
A Personal Expert should never simply be trained and released.
Training is only the beginning.
Historical Evidence
       +
      REM
       ↓
Training Dataset
       ↓
Personal Expert Candidate
       ↓
Challenge
       ↓
Evaluate
       ↓
Identify Gaps
       ↓
Targeted Training
       ↓
Retrain
       ↓
Retest
       ↺
Only a validated Personal Expert becomes active.
Three Birth Tests
MPC should test at least three forms of personalization.
1. Recall
Did the Personal Expert actually learn established information?
2. Generalization
Can it apply what it learned to situations it has never encountered?
3. Behavioral Consistency
Does its reasoning reflect established user patterns without REM simply retrieving the answer?
During testing, REM can intentionally withhold relevant memories.
This tests whether information has actually become parametrically learned.
Personal Expert Evolution
Personal intelligence continues developing.
Personal Expert v17
        +
New Consolidated Experience
        ↓
Candidate v18
        ↓
Train
        ↓
Challenge
        ↓
Validate
      ↙      ↘
   PASS      FAIL
    ↓          ↓
 Deploy      Reject
Previous versions can be retained for rollback.
Personalization therefore becomes a controlled evolutionary process rather than uncontrolled continual training.
The .rem Format
REM is designed around a portable representation of personal intelligence.
Conceptually:
USER.rem

├── events
├── episodic memories
├── semantic knowledge
├── memory graph
├── relationships
├── consolidated patterns
├── preferences
├── behavioral patterns
├── decision patterns
├── salience
├── confidence
├── contradictions
├── provenance
├── training examples
├── counterexamples
├── behavioral probes
├── evaluation datasets
└── training specifications
The .rem format must remain model-independent.
It should not matter whether the user eventually moves between fundamentally different AI architectures.
Behavioral Extraction
A problem appears after a Personal Expert has spent years learning.
Some knowledge may exist inside its neural weights without remaining explicitly represented in REM.
Those weights usually cannot simply be copied into a completely different model architecture.
REM therefore proposes Behavioral Extraction.
OLD PERSONAL EXPERT
        ↓
MPC INTERROGATOR
        ↓
Adaptive Questions
        ↓
Preferences
Scenarios
Counterfactuals
Associations
Decisions
Edge Cases
Contradictions
        ↓
Behavioral Dataset
        ↓
USER.rem
The interrogation does not need to be a fixed questionnaire.
It can recursively explore conceptual areas exposed by previous answers.
Potentially hundreds of thousands or millions of targeted probes could be generated for a mature Personal Expert.
The objective is to reconstruct as much learned personalization as practical without requiring compatible neural weights.
Model Succession
Eventually every model becomes obsolete.
REM assumes this will happen.
The solution is not merely:
Give the new model the old memories.
The objective is:
Teach the new model what the previous model learned from living alongside the user.
OLD PERSONAL EXPERT
        │
        ├──── REM History
        │
        ├──── Behavioral Extraction
        │
        └──── User Corrections
                    │
                    ▼
                USER.rem
                    │
                    ▼
          NEW PERSONAL EXPERT
                    │
                 TRAIN
                    │
                    ▼
           COMPARE OLD vs NEW
                    │
           ┌────────┴────────┐
           ▼                 ▼
        MATCHES             GAPS
                              │
                      Probe Old Model
                              │
                      Targeted Dataset
                              │
                           Retrain
                              │
                              ▼
                            RETEST
                              ↺
The predecessor remains available until the successor demonstrates acceptable continuity.
The REM Continuity Principle
A successor Personal Expert is not considered successfully migrated merely because it has consumed the predecessor's data. It must demonstrate preservation of the predecessor's learned personalization through comparative evaluation, targeted gap extraction, retraining, and re-evaluation.
The predecessor is not automatically considered absolute truth.
Succession can be grounded against:
Predecessor Personal Expert
            +
REM Provenance
            +
Historical Evidence
            +
Explicit User Corrections
This allows mistakes to be corrected rather than permanently inherited.
Personal Agentics
Knowing the user is only part of personal intelligence.
REM is also designed to act.
Personal Agentics gives the AI controlled access to tools and external systems.
Potential capabilities may include:
email
calendars
files
browsers
coding
local applications
messaging
servers
databases
APIs
business software
smart-home systems
IoT devices
automations
The Personal Expert helps determine context and reasoning.
The Agentic layer performs authorized actions.
Observation and Action Are Different Permissions
REM should never assume that permission to observe something means permission to modify it.
For example:
EMAIL

Read       ✓
Remember   ✓
Draft      ✓
Send       Ask
Delete     ✗
Permissions can be independently assigned to different tools and data sources.
Agentic Risk
Actions can be classified according to consequence.
Conceptually:
LEVEL 0
Observation

LEVEL 1
Low-impact reversible action

LEVEL 2
Moderate-impact external action

LEVEL 3
Financial / contractual / consequential action

LEVEL 4
Critical or difficult-to-reverse action
Higher-risk actions can require stronger authorization.
Learning From Actions
Agentic AI creates an entirely new category of experience.
REM can record:
Goal
 ↓
Context
 ↓
Reasoning / Plan
 ↓
Tool Selection
 ↓
Action
 ↓
Result
 ↓
User Response
 ↓
Outcome
This allows the AI to learn not merely from what the user says, but from what happens after the AI acts.
Personal Agentic Skills
Repeated successful workflows may eventually become reusable Personal Skills.
Repeated Goal
     ↓
Successful Agentic Trajectories
     ↓
Pattern Recognition
     ↓
Skill Candidate
     ↓
Validation
     ↓
Personal Skill
For example, REM may eventually learn how one particular user prefers a recurring business process handled.
Personal Skills should remain inspectable, editable, permission-controlled, and removable.
Historical Bootstrapping
A new REM installation should not necessarily begin with zero knowledge.
Users may choose to import their existing digital history.
Potential importers could eventually support:
Previous AI Conversations
Google Data
Email
Calendar
Messages
Browser History
Photos
Videos
Documents
Purchases
Receipts
Other Personal Archives
Historical data becomes evidence.
It does not automatically become truth.
Every imported source should retain provenance and appropriate confidence.
Remote Access
REM is local-first, but personal AI needs to be available when the user leaves home.
The Mothership can establish an outbound encrypted connection to remote-access infrastructure.
PHONE
  │
Internet
  │
Encrypted REM Connection
  │
Tunnel / Rendezvous / Relay
  │
User's Network
  │
REM MOTHERSHIP
The goal is to avoid requiring ordinary users to configure:
static IP addresses
dynamic DNS
NAT
CGNAT workarounds
firewall rules
router port forwarding
The connection originates from the Mothership.
Remote infrastructure should facilitate connectivity rather than become the owner or primary storage location of REM personal data.
Pairing a Phone
The intended experience should eventually be simple:
Install REM
    ↓
Launch Mothership
    ↓
Install REM Phone App
    ↓
Scan QR Code
    ↓
Devices Exchange Identity
    ↓
Encrypted Pairing
    ↓
Connected
The complexity remains underneath the interface.
Offline Operation
REM should continue functioning locally when Internet connectivity is unavailable.
Where dependencies permit:
Memory             ✓
Memory Graph       ✓
Weighted RAG       ✓
Local AI           ✓
Personal Expert    ✓
Local Agentics     ✓
MPC                ✓
Training           ✓
Local Devices      ✓
Remote access and Internet-dependent integrations naturally become unavailable until connectivity returns.
Installation Philosophy
Running REM should eventually feel like installing software—not administering an AI datacenter.
The target installation flow:
Download REM
     ↓
Install
     ↓
Detect Hardware
     ↓
Select Appropriate Local Model
     ↓
Install Dependencies
     ↓
Create Encrypted REM Vault
     ↓
Configure Mothership
     ↓
Configure Secure Remote Access
     ↓
Pair Phone
     ↓
Choose Permissions
     ↓
Optional Historical Import
     ↓
Build Initial Memory Graph
     ↓
Birth Personal Expert
     ↓
Validate
     ↓
REM
Security
REM may contain some of the most personal information a user possesses.
Security must therefore be architectural.
The project will need to address:
encrypted local storage
encrypted .rem exports
transport encryption
device identity
satellite authentication
permission isolation
agent sandboxing
audit logs
credential isolation
model trust
plugin/tool trust
provenance
backups
device revocation
secure deletion
recovery mechanisms
Personal Agentics should never automatically mean unrestricted operating-system access.
Privacy
REM is designed around user-controlled observation.
A user chooses which information sources REM can access.
Permission to access one source does not imply permission to access another.
Permission to observe does not imply permission to act.
Systems involving recordings, communications, cameras, or information about other people must respect applicable platform restrictions, privacy requirements, and consent laws.
The Complete REM Architecture
┌─────────────────────────────────────────────┐
│               SENSORY NETWORK               │
│                                             │
│ Phone / Computer / Glasses / Audio / Video  │
│ Services / Devices / Digital Activity       │
└──────────────────────┬──────────────────────┘
                       ↓
┌─────────────────────────────────────────────┐
│                PERCEPTION                   │
│                                             │
│ Local Models / Event Extraction / Filtering │
└──────────────────────┬──────────────────────┘
                       ↓
┌─────────────────────────────────────────────┐
│                  REM CORE                   │
│                                             │
│ Episodic Memory / Weighted RAG / Graph      │
│ Salience / Confidence / Decay / Provenance  │
└──────────────────────┬──────────────────────┘
                       ↓
┌─────────────────────────────────────────────┐
│               CONSOLIDATION                 │
│                                             │
│ Experience → Stable Patterns                │
└──────────────────────┬──────────────────────┘
                       ↓
┌─────────────────────────────────────────────┐
│                    MPC                      │
│          MODEL PERSONALIZATION CORE         │
│                                             │
│ Birth / Train / Challenge / Validate        │
│ Evolve / Extract / Transfer / Succession    │
└──────────────────────┬──────────────────────┘
                       ↓
┌─────────────────────────────────────────────┐
│            PERSONAL INTELLIGENCE            │
│                                             │
│      Local Model + Personal Expert          │
└──────────────────────┬──────────────────────┘
                       ↓
┌─────────────────────────────────────────────┐
│             PERSONAL AGENTICS               │
│                                             │
│ Plan / Tools / Skills / Execute / Observe   │
└──────────────────────┬──────────────────────┘
                       ↓
                    ACTION
                       ↓
                    OUTCOME
                       │
                       └──────────────► REM
REM Lifecycle
The complete lifecycle can be summarized as:
SENSE
 ↓
INTERPRET
 ↓
EXPERIENCE
 ↓
REMEMBER
 ↓
CONNECT
 ↓
WEIGH
 ↓
FORGET
 ↓
CONSOLIDATE
 ↓
LEARN
 ↓
CHALLENGE
 ↓
VALIDATE
 ↓
REASON
 ↓
ACT
 ↓
OBSERVE
 ↓
EVOLVE
 ↺
When the underlying model becomes obsolete:
EXTRACT
 ↓
TRANSFER
 ↓
REBIRTH
 ↓
COMPARE
 ↓
TEACH
 ↓
VALIDATE
 ↓
CONTINUE
Proposed Project Structure
REM/
│
├── rem-core/
│   Memory lifecycle
│
├── rem-graph/
│   Memory and relationship graph
│
├── rem-rag/
│   Weighted retrieval
│
├── rem-salience/
│   Significance and retention
│
├── rem-consolidator/
│   Memory consolidation
│
├── rem-mpc/
│   Model Personalization Core
│
├── rem-trainer/
│   Personal Expert training
│
├── rem-evaluator/
│   Birth and evolution testing
│
├── rem-distill/
│   Behavioral extraction
│
├── rem-continuity/
│   Model succession
│
├── rem-agent/
│   Personal Agentics runtime
│
├── rem-tools/
│   Agent tools and permissions
│
├── rem-skills/
│   Personal agentic skills
│
├── rem-satellite/
│   Phone/device sensory layer
│
├── rem-import/
│   Historical importers
│
├── rem-vault/
│   Local encrypted storage
│
├── rem-connect/
│   Secure remote access
│
├── rem-format/
│   .rem specification
│
└── rem-model-adapters/
    Model-specific integrations
Development Roadmap
REM is a large project and should be developed incrementally.
Phase 1 — REM Core
Build the fundamental local memory system:
Conversation / Files
        ↓
REM Events
        ↓
Weighted Memory
        ↓
Memory Graph
        ↓
Retrieval
Phase 2 — Consolidation
Implement:
salience
confidence
contradiction detection
temporal decay
cross-memory reinforcement
pattern detection
consolidation
Phase 3 — MPC
Build the first personalization lifecycle:
REM
 ↓
Training Dataset
 ↓
Local Fine-Tune / Adapter
 ↓
Challenge
 ↓
Gap Detection
 ↓
Targeted Retraining
 ↓
Validation
A true custom MoE is not required to prove the MPC concept.
Phase 4 — Personal Agentics
Introduce:
tool framework
permissions
action execution
outcome recording
Personal Skills
agentic learning loops
Phase 5 — REM Satellite
Develop the phone application and local sensory processing.
Phase 6 — Historical Import
Develop standardized importers for existing personal data.
Phase 7 — .rem
Formalize the portable REM format and export/import system.
Phase 8 — Continuity
Implement behavioral extraction and predecessor/successor comparative training.
Phase 9 — True Personal MoE
Integrate the Personal Expert directly into compatible Mixture-of-Experts architectures.
Current Status
REM is currently in the architecture and early-development stage.
Many components described in this document are proposed systems and research directions rather than completed features.
The architecture will evolve as implementations are built, tested, measured, and challenged.
We would rather document what REM is trying to become than pretend unfinished systems already exist.
Contributing
REM is intended to become a community-developed project.
Contributions may eventually span:
machine learning
local LLM inference
Mixture-of-Experts architectures
continual learning
LoRA/adapters
knowledge graphs
RAG
databases
mobile development
multimodal AI
networking
cryptography
privacy
agentic systems
UX
evaluation
model distillation
The project should remain modular.
A contributor should be able to improve one component without understanding the entire REM architecture.
License
REM is source-available and free for personal/noncommercial use.
The project is intended to use the:
PolyForm Noncommercial License 1.0.0
Personal and other qualifying noncommercial use is permitted according to the terms of that license.
Commercial use requires a separate commercial license.
This includes commercial incorpora
tion, redistribution, products, services, hardware, hosted implementations, or other commercial exploitation where the noncommercial license does not grant the necessary rights.
Commercial licensing terms may include attribution requirements such as:
Built on REM — Recursive Evolving Mind
The exact legal rights and obligations are governed by the applicable license files and agreements, not this README summary.
See LICENSE for the complete license terms.
Project Philosophy
REM begins with a simple premise:
Personal AI should belong to the person.
The computer can be replaced.
The phone can be replaced.
The operating system can be replaced.
The local model can be replaced.
The underlying neural architecture can be replaced.
But decades of accumulated understanding should not disappear every time technology changes.
REM is an attempt to separate personal intelligence from the temporary model carrying it.
The model provides intelligence.
REM provides continuity.
The Personal Expert provides individuality.
MPC provides evolution.
Personal Agentics provides action.
Together, they create something fundamentally different from a chatbot with memory.
They create an AI capable of growing alongside one person over time.
