# Hi, I'm Naji

Computer Science student at the University of Haifa (B.Sc., graduating February 2027), focused on **robotics, SLAM, and computer vision**, with a strong side interest in **multi-agent LLM systems**.

## What I build

**Claude plugins & MCP**
- [Research Desk](https://github.com/najikay/claude-research-skills) - published in the Claude plugin directory. Research skills for Claude (citation checking, literature notes, decision matrices, multi-answer review) with a standard-library MCP server that verifies references against OpenAlex and arXiv.
- [Study Desk](https://github.com/najikay/claude-study-desk) - published in the Claude plugin directory. Six study skills (flashcards with Anki export, quizzes, grading, explanations, revision plans, mock exams), every item tied to the material you give it; anything added from outside is labelled. Evals: 68/75 checks with the plugin vs 24/75 without.
- [Career Desk](https://github.com/najikay/claude-career-desk) - published in the Claude plugin directory. Seven skills that take you from a CV and a job posting to an honest application, built for entry-level candidates; it works only from your facts and lists every change it makes.
- [Sim Lab](https://github.com/najikay/claude-simlab) - under review for the Claude plugin directory. A robotics simulation lab for Claude: swarms, formations, coverage and EKF cooperative localisation over lossy radio, plus a synthetic visual-odometry world scored by ATE/RPE, run as reproducible experiments through a 12-tool MCP server.
- Research Desk checker - the hosted MCP server behind Research Desk's reference verification, under review as a standalone MCP server.

**3D vision & SLAM**
- [Monocular-SLAM-Pipeline](https://github.com/najikay/Monocular-SLAM-Pipeline) - visual odometry and sparse 3D reconstruction from scratch: ORB tracking, EPnP + Gauss-Newton pose refinement, keyframe triangulation, loop closure. ATE 0.34 m (~1.8% drift) on TUM RGB-D.
- [computer-vision-lab](https://github.com/najikay/computer-vision-lab) - four vision projects: metric reconstruction, Structure from Motion with COLMAP (PnP benchmarking, novel view synthesis), few-shot benchmarking of vision foundation models with a custom adapter, and differentiable 2D Gaussian Splatting with PCA initialization.

**Software engineering**
- [exam-management-system](https://github.com/najikay/hsts-v2) - full-stack exam-management platform (Java client-server): question bank, exam authoring, approval workflow, live exam delivery, grading, and reports. Led the three-person team - frozen wire contracts, per-PR review reports, CI. Built as our university semestral project.

**Multi-agent LLM systems**
- [research-paper-agents](https://github.com/najikay/research-paper-agents) - CrewAI agents that research a topic (biomimetic SLAM for drones) and emit a compiled IEEE LaTeX paper.
- [pursuit-cop-agent](https://github.com/najikay/pursuit-cop-agent) / [pursuit-thief-agent](https://github.com/najikay/pursuit-thief-agent) - autonomous game agents playing a distributed league over MCP against other teams, with commit-reveal integrity and audited, reproducible match reports. Our AI-orchestration final project.
- [graph-guided-debugger](https://github.com/najikay/graph-guided-debugger) - CrewAI agents that debug Python repos by navigating an AST knowledge graph, with a validation gate that blocks hallucinated fixes. 237 tests, ~96% coverage.
- [llm-debate-arena](https://github.com/najikay/llm-debate-arena) - a provider-agnostic three-agent debate framework with scoring, watchdogs, and cost tracking.

**Data science**
- [fraud-detection-ds](https://github.com/najikay/fraud-detection-ds) - reproduction and critical evaluation of a credit-card fraud detection model: found and fixed a data leak behind a "perfect" AUC, with a leak-free MLP baseline and feature-engineering ablation.

## Currently

- Finishing my B.Sc. (final semester, graduating February 2027) and heading toward a master's in robotics/SLAM.

email: najikayal4@gmail.com
