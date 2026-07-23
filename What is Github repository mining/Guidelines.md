## Guidelines to follow while working on the Github mining user research:

To ensure consistency, objectivity, and research quality, the following guidelines should be followed throughout the GitHub mining study:

<b>Define a clear research scope.</b>

- Identify the repositories, issue types, and time period to be analyzed before starting the research.
- Align the scope with the research objectives (e.g., deployment, observability, maintenance, or developer experience).

<b>Use consistent inclusion and exclusion criteria.</b>
- Analyze only issues that are relevant to the research questions.
- Exclude duplicate issues, spam, dependency updates, and non-usability discussions unless they directly impact the developer experience.

<b>Review the complete issue discussion.</b>
- Read the issue description, comments, maintainer responses, linked pull requests, and resolution before coding the issue.
- Avoid drawing conclusions from the issue title alone.

<b>Focus on the developer's perspective.</b>
- Capture the challenges developers experience while using the project.
- Document workflow pain points, usability issues, documentation gaps, configuration challenges, error messages, and feature requests.

<b>Record contextual information.</b>
When available, document relevant metadata such as: Project version, Kubernetes version, Cloud provider or infrastructure, User role, Environment, Related tools and dependencies

<b>Use a standardized coding framework.</b>

- Categorize issues consistently using predefined themes (e.g., Deployment, Observability, Maintenance, Documentation, Installation, Configuration, or LLM Inference).
- Apply the same coding criteria across all issues.

<b>Document evidence instead of assumptions.</b>

- Base findings only on information explicitly stated in the GitHub issue and discussion.
- Do not infer user intent or technical details that are not supported by the evidence.

<b>Identify recurring patterns.</b>
- Look for common pain points across multiple issues instead of emphasizing isolated incidents.
- Prioritize themes that repeatedly affect developers.

<b>Capture both problems and resolutions.</b>
- Note how maintainers responded, whether the issue was resolved, and if documentation or product improvements were introduced.
- This helps identify opportunities to improve both the product and the contributor experience.

<b>Maintain traceability.</b>
- Record the GitHub issue number or URL for every coded finding.
- This enables future validation and makes the research reproducible.

<b>Remain objective throughout the analysis.</b>
- Analyze issues without bias toward specific solutions or contributors.
- Focus on understanding developer needs and usability challenges rather than evaluating individual performance.

<b>Protect privacy and respect community norms.</b>
- Report findings in aggregate whenever possible.
- Avoid highlighting individual contributors unless their comments are essential to understanding the usability issue.

Following these guidelines helps ensure that GitHub mining produces reliable, reproducible, and actionable insights that can inform UX improvements, documentation enhancements, and better developer experiences for open-source communities like KServe.

## Restrictions of GitHub Mining User Research:

While GitHub mining provides valuable insights into developer experiences, it also has several limitations that should be considered when interpreting the findings.

<b>Limited to Publicly Reported Issues</b>
- The research only captures problems that developers choose to report on GitHub.
- Challenges discussed privately, in Slack, mailing lists, or internal company channels are not included.

<b>Incomplete User Context</b>
- GitHub issues often lack important contextual information such as the developer's experience level, workflow, organization size, or project requirements.
- This can make it difficult to fully understand the root cause of an issue.

<b>Variation in Issue Quality</b>
- Some issues contain detailed reproduction steps and discussions, while others have minimal information.
- Incomplete reports may limit the accuracy of the analysis.

<b>Potential Reporting Bias</b>
- Developers are more likely to report bugs, failures, and frustrations than successful experiences.
- As a result, GitHub issues may overrepresent negative experiences and underrepresent positive usability aspects.

<b>Repository-Specific Findings</b>
- The results reflect the selected GitHub repository and the issues analyzed during the defined research period.
- Findings may not generalize to all users or other open-source projects.

<b>Cannot Observe User Behavior Directly</b>

- Unlike usability testing, GitHub mining does not allow researchers to observe how developers interact with the product or understand their thought process while completing tasks.

<b>Limited Opportunities for Follow-up</b>
- Researchers cannot ask clarification questions or explore unexpected findings as they would during interviews or usability studies.

<b>Issue Discussions May Change Over Time</b>
- GitHub issues are continuously updated with new comments, fixes, and resolutions.
- Research findings represent the state of the repository during the selected analysis period.

<b>Dependence on Available Documentation</b>
- Some usability problems may originate from missing or outdated documentation rather than the product itself.
- Additional investigation may be required to distinguish documentation issues from product usability issues.

<b>Requires Consistent Coding</b>
- GitHub mining involves qualitative interpretation of issue content.
- To reduce researcher bias, issues should be categorized using a standardized coding framework and consistent inclusion criteria.


