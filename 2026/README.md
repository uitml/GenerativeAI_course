# INF-3600 Generative AI — Spring 2026 Projects

Student projects from the INF-3600 Generative Artificial Intelligence course at UiT The Arctic University of Norway.

---

## ChordAI
| [GitHub](https://github.com/TheodorTredal/ChordAI) | [Demo video](https://www.youtube.com/watch?v=VxRHj6AtE0Q) |

A fully local, open-source system that turns a natural-language song description into a complete song draft: chord progressions, section-by-section lyrics, and an album cover. The central contribution is a custom chord-progression model trained from scratch on the Chordonomicon dataset, evaluated across three architectures (LSTM, minimal transformer, aligned-batching transformer) with a key finding that naive transformers condition on genre less strongly than LSTMs unless a corrected training recipe is applied.

---

## ARPX — Adaptive Research Paper Explainer

A RAG-based system that generates explanations of academic research papers adapted to the user's selected knowledge level, from beginner-friendly to advanced. It combines retrieval from both the uploaded paper and its cited references, semantic chunking, and multimodal output generation to make academic literature more accessible.

---

## Team Bodø — Satellite Image Inpainting with LoRA
| [GitHub](https://github.com/BeGj/inf3600-project) |

Investigates whether LoRA fine-tuning of Stable Diffusion 1.5 can improve inpainting performance on satellite imagery while avoiding the computational cost of full fine-tuning. The project trains on multiple satellite datasets (including Sentinel and OSM Nordic) and delivers a web application for applying the trained models to real imagery.

---

## Philosopher Debate Arena

An interactive multi-agent system that stages structured multi-round debates between two philosopher-inspired LLM personas, with configurable argumentation strategies, an automated judge panel, and neural text-to-speech audio output. It supports single-philosopher, team-philosopher, and free-topic modes, and explores to what extent prompt-conditioned LLM agents can produce coherent, distinguishable philosophical arguments.

---

## Extending Musical Works with Transformers (Veridis Quo)
| [GitHub — Composer](https://github.com/VegardChr/composer) | [GitHub — Transcriber](https://github.com/VegardChr/Transcriber) | [Demo video](https://youtu.be/hKmW4B_bf0Y) |

Demonstrates how transformer architectures can extend existing 4/4 solo MIDI pieces by learning next-token prediction over a compact 256-token musical vocabulary. The project consists of two components: a Transcriber that encodes/decodes MIDI files to token sequences, and a Composer, a GPT2-inspired transformer that continues a piece from a given prompt.

---

## MedSim RAG
|[GitHub](https://github.com/Arthur-PREVEL/MedSim-RAG)| [Demo video](https://youtu.be/sl_wyVNGyYw?si=X8N37PXTsvnKNsEK)

A clinical simulation system built around a strict "zero-hallucination" policy, grounding all medical knowledge in data retrieved from PubMed and NCBI rather than model weights. The system employs a tri-agent benchmark architecture that automatically evaluates multiple LLMs as virtual patients and doctors across a matrix of clinical cases, with a seven-graph visualization pipeline for results analysis.

---

## SwatchMagic
| [GitHub](https://github.com/HannaKristine00/SwatchMagic) | [Demo video](https://youtu.be/q_zKx4ksjhY) |

Fine-tunes a Stable Diffusion model with LoRA on ~1300 knitting images sourced from Ravelry, paired with captions capturing stitch type, yarn weight, and construction details, to generate knitting inspiration images from text prompts. The resulting Gradio web app lets designers visualize new stitch textures and color combinations before committing to a full knitting pattern.

---

## Offentlig Agent
| [GitLab](https://gitlab.com/fredeil/einnsyn-mcp) |

Builds a Python FastMCP server exposing nine tools over the Norwegian eInnsyn public-records API and studies how much of the agent's behavior can be controlled by swapping a structured skill layer in the prompt — without changing the model or tools. Three persona configurations (baseline, investigative journalist, commercial contractor) demonstrate that in-context skill conditioning, not the tool set, is the primary determinant of which records the agent surfaces and how it frames results.

---

## StrategAI
| [GitHub](https://github.com/maxtwotouch/StrategAI) | [Showcase video](https://youtu.be/b5gGroI2Log) | [Extended playthrough](https://youtu.be/nvO3DZogazM) |

A full-stack Civilization-style 4X strategy game where three AI civilizations (Mongolia, Egypt, India) are each controlled by GPT-5.4-mini via a novel intent-abstraction layer, while all visual assets are generated on demand by a LoRA-fine-tuned FLUX.2 Klein 4B Diffusion Transformer running on local GPU. The system integrates LLM-driven strategic reasoning, procedural pixel-art asset generation, and a TTS narration pipeline into a single self-hosted, open-source application.

---

## EscapeFromAI
| [GitHub](https://github.com/Pigiby/EscapeFromAI) | [Demo video](https://www.youtube.com/watch?v=K98yi5Wshs4) |

A four-room AI-powered escape room where players progress through challenges built around distinct generative AI paradigms: prompt injection against a hardened LLM guardian, gesture recognition via ControlNet image generation, voice negotiation with a mood-aware TTS agent, and a multi-agent social deduction game. All inference runs locally with no cloud APIs.

---

## PaRAGmedic
| [GitHub](https://github.com/0xdeki/paRAGmedic) | [Live demo](https://paragmedic.deki.io) | [Demo video](https://drive.google.com/file/d/1KWolPRsIonjsDKSTBPko2B9pAskWZ7an/view?usp=sharing) |

A generative AI training and simulation platform for paramedics that generates realistic medical cases from short prompts and then lets a student work the case interactively against an LLM role-playing the patient and bystanders. Clinical authority comes from locally ingested prehospital protocols and the RETTS triage system retrieved via agentic RAG, rather than the model's parametric knowledge, ensuring grounded and protocol-consistent behavior.

---

## Memento
| [GitHub](https://github.com/marcadella/memento) | [Demo video](https://filedn.com/lIFJC8ES6odhW7qS8AxmmHY/memento.mp4) |

Explores three independent designs for extending LLM agent memory beyond the context window: a RAG-based memory that the agent actively queries, a graph-based memory that incrementally builds a knowledge graph from conversation, and a pictorial emotional state that encodes the agent's internal mood as an image. The three designs are evaluated on LoCoMo benchmark conversations and compared using a shared architectural framework that distinguishes conscious from sub-conscious memory processes.
