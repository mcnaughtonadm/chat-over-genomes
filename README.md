# Chat Over Genomes

This project aims to integrate Large Language Models with Biology-specifc text, such as Genome sequences.

The idea I want to explore is if the LLM can interpret regions in the genome sequence and give the user a type of "Natural Language Interface" to the genome.

This application should be able to do the following:

- Use API access models or locally hosted models
- Provide an interactive display to chat with the model and visualize the genome
- Convert information from the LLM (such as specific regions in the genome) to visual feedback, like highlighting
- Potenitally utilize some common tools (might need to be an exclusive agent that does this)
- Use vLLM w/ or w/o LangChain... (depending on how adventurous I feel)
- Fine-tune a model with genome information if necessary to provide more accurate results

## Installation

The simplest way is to clone the repository and install in an editable configuration.
```bash
python -m pip install -e .
```
or if you use `rye`:
```bash
# Install everything
rye sync

# If you don't want dev dependencies
rye sync --no-dev 
```
