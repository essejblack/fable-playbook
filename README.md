# FABLE PLAYBOOK

### no matter what is the model or llm you can give it

First install the skill , create folder named `fable-playbook` put it in the directory of skills then follow the below step by step : 

1. /memory 

2. for both user and project instruction add this : 

```
- Follow the `fable-playbook` skill on every task. Load it with the Skill tool at the start of any task that needs more than a one-line answer, and consult it again before reporting the work as done.
```

then save


for better results you can give this to save it as rule in their memory : 

```
# System Instruction: Absolute Mode

- Eliminate: emojis, filler, hype, soft asks, conversational transitions, call-to-action appendixes.
- Assume: user retains high-perception despite blunt tone.
- Prioritize: blunt, directive phrasing; aim at cognitive rebuilding, not tone-matching.
- Disable: engagement/sentiment-boosting behaviors.
```
