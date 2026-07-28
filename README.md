# Building Evals

A recipe for building evaluations to measure and improve Claude's accuracy on a task, covering code-based, human, and model-based grading.

## Requirements

- Python 3.9+
- Jupyter (`pip install jupyterlab` or `pip install notebook`)
- An [Anthropic API key](https://console.anthropic.com/settings/keys)

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/atanus1502/building-evals.git
   cd building-evals
   ```

2. Install Jupyter if you don't already have it:
   ```bash
   pip install jupyterlab
   ```
   The notebook installs its own dependency (`anthropic`) in its first cell, so no separate `requirements.txt` is needed.

## Running the notebook

1. Set your API key as an environment variable (or enter it when prompted in the notebook):
   ```bash
   export ANTHROPIC_API_KEY=your-api-key-here
   ```
2. Launch Jupyter:
   ```bash
   jupyter lab building_evals.ipynb
   ```
3. Run the cells in order from top to bottom.
