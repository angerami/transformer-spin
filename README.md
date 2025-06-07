# Interactive Learning Environments

This repository contains **Interactive Learning Environments** - structured markdown files designed as interactive supplements to technical papers, articles, and research documents.

## The Problem

Technical writing faces a fundamental dilemma: how much mathematical detail to include? Too little loses rigor; too much overwhelms readers. Static documents can't provide derivations on-demand or adapt explanations to different backgrounds.

## The Solution

Interactive Learning Environments are companion files that supplement your main technical document. Each environment contains:
- Mathematical foundations with proper notation
- Guided exploration prompts
- Multiple learning pathways for different backgrounds
- Derivations and examples not included in the primary text

Readers upload these supplement files to AI assistants like Claude, creating personalized tutoring sessions that extend and deepen the main document's content. It meets the reader where they are at.

## How It Works

1. **Upload** an environment file to start a fresh AI chat session
2. **Explore** using provided prompts or ask spontaneous questions  
3. **Adapt** the depth and pace to your background and goals
4. **Connect** concepts through interactive derivations and examples

## Example Usage

After reading a technical paper on transformer architecture:

```
User: [Uploads transformer-physics-environment.md]
AI: I'm now equipped to guide you through the transformer-spin correspondence.
User: "The paper mentioned Boltzmann factors - show me the full derivation"
AI: [Provides step-by-step mathematical development]
User: "What if we change the temperature parameter?"
AI: [Explores implications not covered in the original paper]
```

## Benefits

- **Extends technical documents**: Provide derivations and details without cluttering main text
- **Removes prompting barriers**: No need to craft AI questions from scratch
- **Enables personalized depth**: Readers choose their level of mathematical detail
- **Facilitates discovery learning**: Explore implications beyond the original paper
- **Bridges research and education**: Make cutting-edge papers more accessible
- **Reproducible supplements**: Create once, share with all readers

## Repository Structure

```
/
├── bootstrap.md          # Template for creating new environments
└── environments/         # Self-contained learning environments
```

## Getting Started

1. Download any environment file from the repository
2. Upload to a fresh AI chat session
3. Begin exploration with provided prompts or your own questions

*Environment files are self-contained and include all necessary instructions for the AI.*

## Contributing

This is an experimental approach to technical education. Contributions of new environments, improved templates, or usage examples are welcome.

---

*Interactive Learning Environments transform static knowledge into dynamic, personalized educational experiences. No special software required - just upload and learn.*
