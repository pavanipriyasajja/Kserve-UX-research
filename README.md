## GitHub Mining Research for KServe
### Overview:
This repository contains the complete documentation for an end-to-end GitHub mining research study focused on understanding the developer experience of deploying, operating, and maintaining machine learning inference workloads with KServe on Kubernetes.
The research analyzes community-reported GitHub issues to identify recurring developer challenges, workflow friction, usability gaps, and operational pain points throughout the ML inference lifecycle. In addition to long-term developer experience trends, the study investigates version-specific issues and Large Language Model (LLM) inference challenges to better understand how the KServe ecosystem has evolved over time.
The repository documents the complete research process, including the research methodology, data collection approach, issue categorization framework, analysis methodology, findings, and recommendations. It is intended to provide transparency into how the research was conducted and to serve as a reference for maintainers, contributors, researchers, and the broader KServe community.

The research is organized into three complementary studies:

<b>1. Long-Term Developer Experience Analysis</b>
- Examines recurring developer challenges across multiple KServe releases.
- Identifies common usability issues related to deployment, configuration, observability, debugging, upgrades, and day-2 operations.
- Highlights long-term trends affecting the overall developer experience.

<b>2. Version-Specific Analysis</b>
- Investigates issues reported for individual KServe releases.
- Identifies regressions, newly introduced problems, upgrade challenges, dependency changes, and version-specific usability concerns.
- Helps maintainers understand how developer experience evolves between releases.

<b>3. LLM Inference Developer Experience Analysis</b>
- Focuses specifically on challenges encountered while deploying and operating Large Language Model (LLM) inference workloads using KServe.
- Analyzes issues related to model serving frameworks, GPU infrastructure, distributed inference, scalability, configuration complexity, and operational workflows.
- Provides insights into improving the developer experience for modern AI and LLM inference use cases.

To better understand these real-world developer experiences, the KServe UX Research Team conducted a GitHub mining study by analyzing issues reported by the community. By identifying recurring patterns, workflow bottlenecks, documentation gaps, and common failure scenarios, this research <b>aims</b> to provide evidence-based insights that help improve the developer experience, product usability, documentation quality, and platform workflows across the KServe ecosystem.

### Purpose
The objective of this repository is to make UX research transparent, reproducible, and accessible to the KServe community. Research artifacts are organized to help maintainers, contributors, and community members better understand developer workflows, usability challenges, and opportunities for improving the overall developer experience.

### Research Objectives: 

This study aims to:

- Identify common developer pain points reported through GitHub issues.
- Understand where developers experience friction throughout the KServe lifecycle.
- Categorize challenges across deployment, observability, debugging, maintenance, and upgrades.
- Analyze recurring patterns across different KServe versions, Kubernetes environments, and deployment configurations.
- Generate research-backed recommendations that support future product and community improvements.
- Help maintainers prioritize improvements based on research evidence. 
- Support contributors by highlighting areas where documentation, tooling, and workflows can be improved. 
- Encourage community-driven, user-centered decision making for future KServe enhancements. 
- Provide a transparent and reproducible research process that the community can build upon.


### Research Methodology : 

The study follows an end-to-end GitHub Mining methodology including: 

- Research planning 
- Research questions 
- Repository selection 
- Data collection 
- Issue filtering 
- Issue categorization 
- Qualitative coding 
- Pattern identification
- Cross-version comparison 
- Research validation 
- Recommendation development 

### Who is this Research For? (Target Audience): 

KServe Maintainers, Contributors, Platform Engineers, ML Engineers , AI Infrastructure Engineers, UX Researchers, Cloud Native Researchers, CNCF Community Members 


### Research process: 

<b>Step : 1 Research Planning</b> - Define the research objectives, scope, timeline, and methodology for the GitHub mining study.

<b>Step: 2 Research Questions</b> - Establish the key research questions that guide the analysis of developer experience challenges.

<b>Step: 3 GitHub Issue Collection</b> - Collect relevant GitHub issues from the KServe repository that reflect real-world developer experiences.

<b>Step: 4 Issue Screening & Filtering</b> -  Review and filter issues based on the research scope, removing duplicates, irrelevant reports, and incomplete issues.

<b>Step: 5 Issue Analysis & Coding</b> - Analyze each issue and apply qualitative coding to identify developer workflows, pain points, and usability challenges.

<b>Step: 6 Issue Categorization</b> - Organize issues into categories such as deployment, observability, maintenance, documentation, and LLM inference.

<b>Step: 7 Pattern Identification</b> - Identify recurring themes, workflow bottlenecks, and common developer challenges across the dataset.

<b>Step : 8 Research Findings</b> -  Summarize the key insights, trends, and evidence discovered through the GitHub mining analysis.

<b>Step : 9 UX Recommendations</b> -  Provide actionable recommendations to improve KServe's developer experience, documentation, workflows, and platform usability.

### Research outcomes:

This research will deliver:

- A validated understanding of user needs and pain points across the KServe model serving lifecycle
- Identification of high-impact usability gaps that cause user friction and drop-off
- End-to-end journey maps highlighting critical friction points and opportunities
- Evidence-based insights to guide UX, documentation, and feature priorities
- Clear, actionable recommendations for the KServe project team
- Improved shared understanding of how real users interact with KServe in production
- Reusable research artifacts (findings, personas, journey maps) for ongoing decision-making 
- Developer workflow analysis
- Long-term developer experience trends
- Version-specific issue analysis
- LLM inference developer experience analysis
- UX findings and recommendations
- Documentation improvement opportunities
- Categorized GitHub issue dataset
- Research methodology documentation 

### Benefits of GitHub Mining

GitHub Mining provides a scalable and evidence-based approach to understanding developer experience by analyzing real-world issues reported by the community.This methodology enables researchers and maintainers to:

- Understand how developers use KServe in practice.
- Identify recurring usability challenges.
- Detects workflow bottlenecks across the ML inference lifecycle.
- Prioritize improvements based on community-reported evidence.
- Improve documentation, tooling, and platform usability.
- Inform future product and roadmap decisions with data-driven insights.

<b>Research Documentation:</b>  The repository contains detailed documentation covering. Research methodology, Dataset, Coding framework, Analysis process, Findings, Recommendations, Supporting resources. 

### Research team: 

Pavanipriya Sajja - UX researcher & Designer Independent (<a href="https://www.linkedin.com/in/pavanipriyasajja/" target="_blank"> Linkedin </a>) , Jooho Lee - Principal Software Engineer at Redhat & Kserve maintainer (<a href="https://www.linkedin.com/in/jooho/" target="_blank"> Linkedin </a>), (Filippe Spolti - Senior Software engineer & Kserve maintainer.(<a href="https://www.linkedin.com/in/spolti/" target="_blank"> Linkedin </a>)

### Acknowledgements 

This research is conducted by the KServe UX Research Team with the goal of improving the developer experience of machine learning inference on Kubernetes through evidence-based research and community collaboration.


<b>Community feedback is welcome.</b> If you identify additional usability challenges, have suggestions for improving the research, or would like to contribute, please open an issue or submit a pull request.

<b>Licence:</b> This repository follows the same license as the KServe project unless otherwise specified.

To get Involved and Learn more about the Kserve, Please visit the Kserve webiste: <a href="https://kserve.github.io/website/" target="_blank"> Kserve Website </a>




