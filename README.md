# Foundation: An Economic Simulation Framework

This resource contains an implementation of Foundation, a framework for flexible, modular, and composable environments that **model socio-economic behaviors and dynamics in a society with both agents and governments**.

Foundation provides a [Gym](https://gym.openai.com/)-style API:

- `reset`: resets the environment's state and returns the observation.
- `step`: advances the environment by one timestep, and returns the tuple *(observation, reward, done, info)*.

This simulation can be used in conjunction with reinforcement learning to learn optimal economic policies, as detailed in the following papers:

**[The AI Economist: Improving Equality and Productivity with AI-Driven Tax Policies](https://arxiv.org/abs/2004.13332)**,
*Stephan Zheng, Alexander Trott, Sunil Srinivasa, Nikhil Naik, Melvin Gruesbeck, David C. Parkes, Richard Socher.*

**[The AI Economist: Optimal Economic Policy Design via Two-level Deep Reinforcement Learning](https://arxiv.org/abs/2108.02755)**
*Stephan Zheng, Alexander Trott, Sunil Srinivasa, David C. Parkes, Richard Socher.*

**[Building a Foundation for Data-Driven, Interpretable, and Robust Policy Design using the AI Economist](https://arxiv.org/abs/2108.02904)**
*Alexander Trott, Sunil Srinivasa, Douwe van der Wal, Sebastien Haneuse, Stephan Zheng.*

If you use this code in your research, please cite us using this BibTeX entry:

```
@misc{2004.13332,
 Author = {Stephan Zheng, Alexander Trott, Sunil Srinivasa, Nikhil Naik, Melvin Gruesbeck, David C. Parkes, Richard Socher},
 Title = {The AI Economist: Improving Equality and Productivity with AI-Driven Tax Policies},
 Year = {2020},
 Eprint = {arXiv:2004.13332},
}
```

For more information and context, check out:

- The AI Economist website](https://www.einstein.ai/the-ai-economist)
- Blog: The AI Economist: Improving Equality and Productivity with AI-Driven Tax Policies](https://blog.einstein.ai/the-ai-economist/)
- Blog: The AI Economist moonshot](https://blog.einstein.ai/the-ai-economist-moonshot/)
- Blog: The AI Economist web demo of the COVID-19 case study](https://blog.einstein.ai/ai-economist-covid-case-study-ethics/)
- Web demo: The AI Economist ethical review of AI policy design and COVID-19 case study

## Simulation Cards: Ethics Review and Intended Use

Please see our [Simulation Card](https://github.com/salesforce/ai-economist/blob/master/Simulation_Card_Foundation_Economic_Simulation_Framework.pdf) for a review of the intended use and ethical review of our framework.

Please see our [COVID-19 Simulation Card](https://github.com/salesforce/ai-economist/blob/master/COVID-19_Simulation-Card.pdf) for a review of the ethical aspects of the pandemic simulation (and as fitted for COVID-19).


### Multi-Agent Simulations

- economic_simulation_basic: Shows how to interact with and visualize the simulation.
- economic_simulation_advanced: Explains how Foundation is built up using composable and flexible building blocks.
- optimal_taxation_theory_and_simulation: Demonstrates how economic simulations can be used to study the problem of optimal taxation.
- covid19_and_economic_simulation: Introduces a simulation on the COVID-19 pandemic and economy that can be used to study different health and economic policies .

### Multi-Agent Training
- multi_agent_gpu_training_with_warp_drive
- Introduces our multi-agent reinforcement learning framework [WarpDrive](https://arxiv.org/abs/2108.13976), which we then use to train the COVID-19 and economic simulation.


## Changelog

For the complete release history, see [CHANGELOG.md](https://www.github.com/salesforce/ai-economist/blob/master/CHANGELOG.md).

## License

Foundation and the AI Economist are released under the [BSD-3 License](LICENSE.txt).

