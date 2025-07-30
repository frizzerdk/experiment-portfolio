# My Experiment Portfolio

A collection of my experiments and learning projects across different domains of AI and control systems.

## What's Here

This repository organizes my experimental work using standalone repositories for each experiment, connected through git submodules for easy browsing.

🏆 **[Portfolio Showcase](portfolio.md)** - Featured experiments and skills demonstrated  
📓 **[Experiment Log](experiment-log.md)** - Current work and learning notes  
🔬 **[All Experiments](experiments/)** - Complete collection of experiments  
🛠️ **[Templates](templates/)** - Templates for quick experiment and utility setup

## Quick Start

### Browse Portfolio
```bash
# Clone everything
git clone --recursive https://github.com/username/experiment-portfolio.git

# Or browse individual experiments
git clone https://github.com/username/cnn-architecture-study.git
```

### Start New Experiment
```bash
# Create from GitHub template (web interface or CLI)
gh repo create my-new-experiment --template username/experiment-template

# Clone and customize
git clone https://github.com/username/my-new-experiment.git
cd my-new-experiment

# Customize experiment_info.yaml (single source of truth)
sed -i "s/EXPERIMENT_NAME_PLACEHOLDER/my-new-experiment/g" experiment_info.yaml
sed -i "s/EXPERIMENT_DESCRIPTION_PLACEHOLDER/Description of my experiment/g" experiment_info.yaml
sed -i "s/DOMAIN_PLACEHOLDER/machine-learning/g" experiment_info.yaml

# Sync markdown files from YAML
python scripts/sync_template.py

# Commit customizations
git add .
git commit -m "Customize template for new experiment"
git push origin main
```

## Philosophy

I learn by doing. This portfolio represents my hands-on exploration of:
- 🧠 Machine learning and deep learning
- 🎮 Reinforcement learning  
- 🤖 Control theory and robotics
- 💬 Language models and NLP

Each experiment is designed to be:
- **Self-contained** - Works independently with clear documentation
- **Educational** - Focuses on understanding, not just results
- **Practical** - Implements concepts from scratch when possible
- **Documented** - Captures both successes and failures 