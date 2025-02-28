![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# {Strategic Prompt Engineering for Enhanced LLM Performance}

1-liner description of your project
this project aims to pptimizing large language model outputs through systematically prompt design experimentation and analysis. It demonstrates that strategic prompt engineering offers a cost-effective approach to significantly enhance LLM outputs without model architecture changes. Our automated optimization system further shows that the prompt engineering process itself can be optimized through reinforcement learning techniques.

<!-- WHEN APPLICABLE, REMOVE THE COMMENT MARK AND COMPLETE
This is a response to the Assignment part of the COURSE.
-->

Authors: ScienQtist Bots B.C.
Group: ScienQtist B.C 
Members:  kbenoit2020@fau.edu , cherym2020@fau.edu
Academic Supervisor: Dr. Fernando Koch
Github Link: https://github.com/quantist25/prompt-eng
Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

  
# Research Question 

How can different prompting techniques significantly improve LLM performance without changing the underlying model? 

## Arguments

#### What is already known about this topic

•	Few-shot prompting can help models understand expected output formats
•	Label distribution in examples influences model responses
•	Temperature settings affect output predictability
•	Context window limitations constrain prompt complexity


#### What this research is exploring

<!-- Free-format; use the topics that are applicable to your exploration  -->

•	We employ three distinct prompting techniques (few-shot, meta-prompting, chain-of-thought)
•	We are building hybrid approaches that combine multiple techniques
•	We are exploring parameter optimization alongside prompt engineering
•	We are investigating automated prompt optimization systems with reinforcement learning


#### Implications for practice

<!-- Free-format; use the topics that are applicable to your exploration  -->

•	It will be easier to achieve reliable model outputs
•	It will optimize computational resource usage
•	We will better understand when to apply specific techniques
•	It will automate the prompt engineering process itself


# Research Method

We conducted comparative experiments with three primary prompting approaches and an automated optimization system:
1.	Few-Shot Prompting: Enhanced by expanding examples from 2 to 7, implementing consistent Question/Answer format, and optimizing temperature (0.3).
2.	Meta-Prompting: Implemented expert persona framing with reasoning guidance and result verification instructions.
3.	Chain-of-Thought: Optimized with explicit reasoning steps, clearer task description, and numbered problem-solving approach.
4.	Automated Prompt Optimization: Developed a self-improving system using reinforcement learning that generates, tests, and refines prompts based on performance metrics.

Parameters were systematically modified to identify optimal configurations for each technique.

# Results

Describe the results achieved through your research process.
Metric	Original System	Enhanced System	Improvement
Quality score accuracy	65%	92%	+27%
Domain terminology coverage	40%	85%	+45%
Evaluation dimensions	3	5	+67%
Error recovery rate	25%	95%	+70%
Prompt iteration efficiency	Manual	Automated	N/A

Overall
1.	Generates and tests multiple prompt variations simultaneously
2.	Provides more nuanced scoring across clarity, completeness, technical accuracy, specificity, and feasibility
3.	Automatically refines prompts based on performance metrics
4.	Maintains historical performance data for continuous improvement
5.	Implements readability analysis for optimal response structure
6.	Reduces prompt engineering time by approximately 60%
The enhanced system demonstrates that automating the prompt engineering process itself yields substantial improvements in both efficiency and output quality.

# Further research

Describe what we could do next and propose 
WHat we could do next is to automated prompt selection based on task type.

new ideas for further research.
2.	Domain-specific template development
3.	Prompt compression techniques to reduce token usage
4.	Multi-model comparative analysis
5.	Integration with fine-tuning for specialized applications
6.	Enhancing the automated optimization system with cross-domain learning

