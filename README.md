### Engr. Usman Hasan — Applied AI Engineer · AI agents, retrieval & computer vision

I build AI agents that use business data and tools to answer questions and carry out
workflows. I also build real-time computer vision systems, teach Generative AI, and have
published research on eye-controlled assistive communication.

Karachi, Pakistan · [LinkedIn](https://www.linkedin.com/in/usman-hassan) · BE Electrical
Engineering (Electronics), DHA Suffa University

---

#### Featured work

**[Verified Experience Memory](https://github.com/Usmanhassan7654/verified-experience-memory)**
*Problem:* agents that remember things across conversations get poisoned by fake messages and keep using outdated facts.
*What I did:* tested six memory designs on one 60-day business timeline with silent price changes, 11 poisoned messages and a database outage. My design checks facts before saving, blocks instructions from untrusted text, and re-checks memories before using them.
*Proof:* matched no-memory accuracy (100%) at 15% of the tool cost. Naive memory was poisoned in 55.6% of answers. 18 tests, runs offline.

**[Business Data Retrieval Lab](https://github.com/Usmanhassan7654/business-data-retrieval-lab)**
*Problem:* business assistants give wrong answers when company data is dumped into a vector
store as text chunks.
*What I did:* gave the same business facts to three setups (flat text chunks, labelled
records, and typed SQL tools behind an agent), then scored 64 questions against gold evidence.
*Proof:* runs in under a second with no API key. On held-out paraphrases, flat chunks had
enough context for 11/32 questions, records for 20/32, and the tool agent answered 29/32
correctly. All failures are listed in the repo.

**[PPE detection with timestamped video evidence](https://github.com/Usmanhassan7654/Usman-hassan)**
*Problem:* safety teams need to know *when* in a video something happened, not just a box on
one frame.
*What I did:* indexed video once with a 17-class PPE detector plus tracking, then answered
questions like "when is a helmet visible?" or "is anyone without a helmet?" with time
intervals and evidence frames.
*Proof:* the temporal logic is unit-tested, and there is a documented run on a CC BY-SA
construction clip with spot-checked evidence frames.

**[Generative AI course](https://github.com/Usmanhassan7654/Generative-ai-course)**
*Problem:* beginners need to see each AI technique fix a real limitation of the one before.
*What I did:* designed and taught a module-by-module course at Bano Qabil: LLM APIs, prompt
engineering, tool calling, embeddings, vector databases, RAG, advanced RAG and fine-tuning
datasets.
*Proof:* every module has slides plus runnable VS Code and Colab code.

#### Deployed work (client projects, code private)

- **AI sales & business assistant, [HB Innovations](https://hbinnovations.net/).** Answers
  service questions from company knowledge, qualifies leads, recommends services, drafts
  quotations and books meetings. I lead AI delivery at HB Innovations.
- **E-commerce shopping agent ([live test deployment](https://ai-shopping-assistant-y6yq.onrender.com/)).**
  Natural-language product search, budget-aware carts and recipe-to-cart shopping. Built for
  testing with U.S. stores.
- **Computer vision in the field.** We implemented camera surveillance and geofencing at a
  dairy farm. Our team has developed 5+ vision systems, including prototypes. Earlier, at
  Bleed AI, I worked on PPE detection, automated attendance, facial-expression analysis and
  parking detection.

#### Research

- **Pakistan Patent No. 144803** (granted 2026): *A Pupil Controlled System and Method of
  Operating Thereof.* Camera-based face and pupil movement controls an on-screen interface.
- **IEEE ICCIS 2021:** *Communication System for Non-Verbal Paralyzed Patients Using Computer
  Vision.* U. Hassan, H. A. Khan, H. Khan, M. Owais.
  [doi:10.1109/ICCIS54243.2021.9676383](https://doi.org/10.1109/ICCIS54243.2021.9676383).
  Eye movements move a cursor and blinks select multilingual messages.
- **Exploring now:** how the structure of business data, and an agent's verified past
  experience, change retrieval and decisions. The
  [retrieval lab](https://github.com/Usmanhassan7654/business-data-retrieval-lab) is the first
  experiment.

#### Teaching

Generative AI Instructor at **Bano Qabil**, and founder and educator at **Al-Tibyaan
Institute** (AI, robotics, machine learning, computer vision, electronics). I have taught
1,000+ students across both.

#### Work

Head of AI/ML Projects & Solutions, HB Innovations (2025–) · AI/ML Engineer, Ethisol
(2026–, contract) · Computer Vision Engineer, Bleed AI (2022, contract)

**Tools I use:** Python, LangChain, LangGraph, LLM APIs and tool calling, RAG and vector
search, FastAPI, Docker, OpenCV, YOLO, TensorFlow, MediaPipe
