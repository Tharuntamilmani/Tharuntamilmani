# Hey, I'm Tharun

### Pre-Final Year Information Technology Student | AI/ML • Backend • Systems Engineering

I'm an IT student who likes building things I probably could have avoided building.

It started with:

> “I'll just train a model.”

Then came the API.

Then the database.

Then Docker.

Then testing.

Then some completely unnecessary architecture that somehow became necessary.

And now I'm here.

I’m interested in **AI, Machine Learning, Backend Engineering, MLOps, Computer Vision, AI Agents, and System Design**.

What I enjoy most is taking an idea from **“this would be cool”** to **“wait... this actually works.”**

I’m especially interested in what happens **after the model is trained** — how to turn it into something that can communicate with other systems, handle failures, store data, be tested, deployed, and hopefully not require me to manually restart it every morning.


## What I'm Building

### Universal Log Pre-Processing Framework — ULPF

Cybersecurity logs are supposed to help you understand what happened.

Unfortunately, they first have to agree on what language they're speaking.

ULPF is my attempt to solve that problem.

It's a modular cybersecurity event-processing framework designed to take **different security and network log formats** and turn them into **standardized, traceable events**.

The system covers:

* Log ingestion and format detection
* Parser engine and parser registry
* Event normalization
* Universal event schema validation
* Raw-event persistence
* Integrity and trace tracking
* REST APIs
* OpenSearch / SIEM integration
* Management Console and Parser Studio
* Synthetic test data
* Integration and contract testing

**Stack**

`Python` `FastAPI` `Pydantic` `PyYAML`
`MongoDB` `OpenSearch`
`React` `TypeScript` `Vite` `Tailwind CSS`
`Docker` `Docker Compose`
`Pytest` `HTTPX` `Vitest`

I'm also experimenting with **local AI through Ollama** for things like:

* Unknown-log analysis
* Parser suggestions
* Malformed-log explanations
* Event summarization
* Natural-language querying

But AI isn't allowed to randomly decide how the core pipeline behaves.

Because if the answer to a production bug is:

> “The model felt creative.”

we probably have bigger problems.


### THIRAN 2.7

At some point I thought:

> “It would be nice to have my own AI assistant.”

Apparently I didn't understand what I was getting myself into.

THIRAN 2.7 is a **local-first AI assistant and automation runtime for Windows**.

The idea is simple:

**Tell the computer what you want. Let the system figure out how to do it.**

Making that reliable is considerably less simple.

THIRAN currently explores:

* Task planning and execution
* Local LLMs through Ollama
* Mission Control / Command Center
* Windows automation
* Semantic UI element selection
* Plugin architecture
* Process-isolated execution
* Cooperative cancellation
* Voice-device integration
* Local telemetry
* Configuration migration
* Onboarding and demo workflows

**Stack**

`Python` `Ollama` `AI Agents`
`UI Automation` `Windows Automation`
`Plugin Architecture` `Task Planning`
`Local-First Systems`

The goal isn't to make a chatbot that says:

> “Done!”

while staring at the same screen it was staring at five seconds ago.

I want THIRAN to **plan, execute, verify, handle failures, and recover**.

Basically, I'm trying to make AI do useful computer work without giving it the ability to destroy civilization because I asked it to open Notepad.


### View-Invariant 3D Fall Detection

This one started with a relatively straightforward question:

> “Can we reliably detect a fall?”

Then came the obvious follow-up:

> “What if the camera moves?”

And suddenly we're discussing **3D pose lifting, skeleton representations, cross-view generalization, ST-GCNs, Transformers, and evaluation protocols**.

The project investigates **view-invariant human fall detection** using 3D and skeleton-based representations.

Current research directions include:

* 3D human-pose lifting
* View-invariant representations
* Cross-camera evaluation
* Skeleton-based learning
* ST-GCN
* Skeleton Transformers
* Cross-view generalization
* Research-grade validation protocols

**Stack**

`Computer Vision` `Deep Learning`
`3D Human Pose` `ST-GCN` `Transformers`

The basic idea:

```text
Camera
   ↓
Human Pose
   ↓
3D Representation
   ↓
Skeleton Model
   ↓
Fall / No Fall
```

The difficult part is convincing the model that a person falling from a completely different camera angle is still, in fact, the same person falling.

Apparently computers need convincing.


## Things I Actually Enjoy Building

* AI systems that do more than generate text
* Machine learning pipelines
* Backend APIs
* AI agents and automation
* Computer vision systems
* Cybersecurity pipelines
* Data-processing systems
* MLOps workflows
* Modular architectures
* Databases and search systems
* Dockerized applications
* Things that sounded simple before I started building them


## My Toolbox

### Languages

`Python` `Java` `JavaScript` `TypeScript` `SQL`

### AI / ML

`Scikit-learn` `XGBoost` `Pandas` `NumPy`
`Computer Vision` `3D Pose Estimation`
`ST-GCN` `Transformers`

### Backend

`FastAPI` `Flask` `Node.js` `Express.js`
`REST APIs` `Pydantic`

### Databases & Search

`PostgreSQL` `MongoDB` `OpenSearch`

### AI / MLOps

`Ollama` `MLflow` `Docker` `Docker Compose`

### Frontend

`React` `TypeScript` `Vite`
`Tailwind CSS` `Streamlit`

### Testing & Engineering

`Git` `GitHub`
`Pytest` `HTTPX` `Vitest`
`Ruff` `Black` `Mypy`

---

## Other Things I've Built

| Project                          | What happened                                                                        | Stack                                               |
| -------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------- |
| **Student Placement Prediction** | Trained a model, then accidentally turned it into a complete application             | `XGBoost` `Flask` `PostgreSQL` `Streamlit` `MLflow` |
| **Natural Language → SQL**       | Tried to make databases understand humans                                            | `Python` `NLP` `SQL`                                |
| **SmartShop Lite**               | Built an inventory and billing system because spreadsheets eventually stop being fun | `Node.js` `Express.js` `JavaScript`                 |


## What I'm Really Interested In

The part of technology that interests me most is the gap between:

> **“The model works.”**

and

> **“The system works.”**

There's a surprisingly large amount of engineering hiding between those two sentences.

That's where I want to spend my time.

I'm particularly interested in:

`AI Agents` • `Generative AI` • `Machine Learning`
`Backend Engineering` • `Computer Vision`
`Cybersecurity` • `MLOps` • `System Design`


## How Most of My Projects Actually Go

```text
Have an idea
     ↓
"This should be easy."
     ↓
Build prototype
     ↓
Something breaks
     ↓
"Okay, that's weird."
     ↓
Fix it
     ↓
Something else breaks
     ↓
Add logging
     ↓
Add tests
     ↓
Break it again
     ↓
Dockerize everything
     ↓
Discover a completely unrelated problem
     ↓
Question architectural decisions
     ↓
Fix it
     ↓
"It works!"
     ↓
Don't touch anything
     ↓
Touch something
     ↓
It breaks again
```

This is generally where the learning happens.


## Engineering Philosophy

I don't think good engineering means never breaking things.

It means understanding **why they broke** and making the next version harder to break.

I like systems that are:

**Reliable enough to trust.
Simple enough to understand.
Modular enough to change.
Tested enough to survive my next idea.**

And I strongly believe:

> **If you don't understand why it works, you probably don't understand it yet.**

So my usual process is:

```text
Learn → Build → Break → Debug → Understand → Improve
```


## Where I'm Going

I don't have everything figured out yet.

I'm still learning, still experimenting, and still occasionally Googling errors that I definitely should have understood myself.

But I know the kind of engineer I want to become:

Someone who can take an idea, **design the system, build it, deploy it, break it, understand it, and make it better.**

Not just:

```text
model.fit()
```

but:

```text
idea
  ↓
architecture
  ↓
data
  ↓
intelligence
  ↓
backend
  ↓
storage
  ↓
testing
  ↓
deployment
  ↓
monitoring
  ↓
something people can actually use
```

That's the direction I'm building toward.


## Let's Connect

**LinkedIn:**
https://www.linkedin.com/in/tharuntamilmani/

**Email:**
[tharuntamilmani200601@gmail.com](mailto:tharuntamilmani200601@gmail.com)

If you're building something interesting around **AI, ML, backend systems, automation, computer vision, or just trying to make a piece of software behave**, feel free to connect.


### Learn. Build. Break. Improve. Repeat.
