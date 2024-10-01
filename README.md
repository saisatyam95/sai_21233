# ECS427 Multi-Agent Reinforcement Learning

Taught by **Prof. P B Sujit** at **Indian Institute of Science Education and Research Bhopal**, in _Fall 2024-25_.

## Student Details

- **Name:** Sattwik Kumar Sahu
- **Roll No.:** `21241`

# Installation

## Clone Repo

```bash
git clone https://github.com/sattwik-sahu/ecs427.git
cd ecs427
```

## Setup the virtual environment

### Create and Activate Virtual Environment

```bash
python3 -m venv .venv --prompt=ecs427   # Create the venv
source .venv/bin/activate               # Linux
source .venv/Scripts/activate.bat       # Windows
```

### Install Dependencies

```bash
python3 -m pip install -U pip           # Upgrade pip to latest version
python3 -m pip install poetry           # Install dependency manager
poetry install                          # Install all project dependencies
```

> If `poetry install` does not work, try
>
> ```bash
> python3 -m poetry install
> ```
>
> to run poetry as a module.

# Evaluation

## Assignments

- To evaluate assignments, please navigate to the [`assignments`](https://github.com/MOONLABIISERB/marl-ecs-course/tree/sattwik_21241/assignments) directory.
- Open the file named `ecs427__assignment-XX.ipynb` to evaluate the assignment code. For example, `XX = 01` for assignment #1.
- To evaluate the assignment report, open `ecs427__assignment-XX.pdf`. For example, `XX = 01` for assignment #1.

## Mid-Semester Exam

- After following the [installation](#installation) instructions, please open the [README](assignments/midsem/README.md) for the mid-semester exam.
- On opening the [notebook](assignments/midsem/ecs427__midsem.ipynb) specified in the above README, select the kernel in which you performed the installation instructions and click the `Run All` button in the notebook.
