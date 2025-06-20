---
layout: post
title: Publications

# TO ADD A NEW PUBLICATION:
# Add a new entry to the beginning of the list below
# New entry must have authors, title, venue, url and abstract key/values

papers:

---

{% include publications-template.html items=page.papers %}

<ul> 
<li>
<div style="text-align: justify">
<a href="https://link.springer.com/article/10.1007/s10664-025-10664-8">Process smells in practice: an evaluative case study</a>
<br><i> Uğur Can Altun, Ismail Sergen Göçmen, Emre Sülün, Erdem Tuna, Eray Tüzün</i>
<br> Empirical Software Engineering Journal
<br><button data-toggle="collapse" data-target="#demo59">See Abstract</button><br>

            <div id="demo59" class="collapse">
            Context:
Software development comprises many processes, including Code Review (CR) and Bug Tracking (BT). Although no perfect practices exist, recognizing bad practices helps avoid detrimental habits in CR and BT.

Objective:
This study investigates CR and BT process smells in industrial settings using Smellyzer, a detection tool based on established smell taxonomies. We aimed to explore the challenges, insights, and outcomes of applying a smell detection tool in real-world software projects. 
                    
Methods:
We conducted an evaluative case study involving a large-scale proprietary company, analyzing CR and BT smells in a large software project using Smellyzer. We collected data through pre-surveys, focus groups, questionnaires, follow-up study and tool-based analyses, and then analyzed these data using triangulation and grounded theory methods.

Results:
Practitioners confirmed the presence of CR and BT smells in their workflows and provided detailed feedback on root causes and their impacts on development efficiency. They also rated the tool’s usefulness at identifying CR smells as 5 out of 5 and BT smells as 4.6 out of 5. Its practicality, measured by the System Usability Scale, scored 77.5 for CR and 80.0 for BT smell detection.
              
Conclusion:
This study highlights the presence of CR and BT smells in industrial settings and their potential to affect workflow efficiency and software quality. While our tool, Smellyzer, proved effective in identifying these smells, the findings emphasize the importance of integrating theoretical frameworks with practical solutions. Future work should explore these smells across diverse project contexts and investigate their influence on development practices over time.
</div>
</div>
</li>  
<br> 

       
<li>
<div style="text-align: justify">
<a href="https://arxiv.org/abs/2412.18531">Automated Code Review In Practice</a>
<br><i> Umut Cihan, Vahid Haratian, Arda İçöz, Mert Kaan Gül, Ömercan Devran, Emircan Furkan Bayendur, Baykal Mehmet Uçar, Eray Tüzün</i>
<br> ICSE 2025 47th International Conference on Software Engineering
<br><button data-toggle="collapse" data-target="#demo58">See Abstract</button><br>

            <div id="demo58" class="collapse">
            Context:
Code review is a widespread practice among practitioners to improve software quality and transfer knowledge. It is often perceived as time-consuming due to the need for manual effort and potential delays in the development process. Several AI-assisted code review tools (Qodo, GitHub Copilot, Coderabbit, etc.) provide automated code reviews using large language models (LLMs). The overall effects of such tools in the industry setting are yet to be examined.

Objective:
This study examines the impact of LLM-based automated code review tools in an industry setting. 
                    
Methods:
The study was conducted within an industrial software development environment that adopted an AI-assisted code review tool (based on open-source Qodo PR Agent). 238 practitioners across ten projects had access to the tool. We focused our analysis on three projects, encompassing 4,335 pull
requests, of which 1,568 underwent automated reviews. Our data collection comprised three primary sources: (1) a quantitative
analysis of pull request data, including comment labels indicating whether developers acted on the automated comments, (2) surveys sent to developers regarding their experience with the reviews on individual pull requests, and (3) a broader survey of 22 practitioners capturing their general opinions on automated
code reviews.

Results:
73.8% of automated code review comments were labeled as resolved. However, the overall average pull request closure duration increased from five hours 52 minutes to eight hours 20 minutes, with varying trends observed across different projects. According to survey responses, most practitioners observed a minor improvement in code quality as a result of automated code reviews. 
              
Conclusion:
The LLM-based automated code review tool proved useful in software development, enhancing bug detection, increasing awareness of code quality, and promoting best practices. However, it also led to longer pull request closure times and introduced drawbacks such as faulty reviews, unnecessary corrections, and irrelevant comments. Based on these findings, we discussed how practitioners can more effectively utilize automated code review technologies.
</div>
</div>
</li>  
<br> 


<li>
<div style="text-align: justify">
<a>Uncovering the Challenges: A Study of Corner Cases in Bug-Inducing Commits</a>
<br><i> Atakan Şerifoğlu, Eray Tüzün</i>
<br>IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER)
<br><button data-toggle="collapse" data-target="#demo57">See Abstract</button><br>

            <div id="demo57" class="collapse">
            Context:
In software development, accurately identifying bug-inducing commits (BICs) is crucial for maintaining code integrity and ensuring the reliability of software systems. The complexities involved in pinpointing the exact commits responsible for bugs necessitate a thorough investigation of the underlying issues and limitations of existing tools and algorithms.

Objective:
This study investigates and identifies corner cases in BIC identification, clarifying definitions and examining issues with existing algorithms and tools. By analyzing these cases, we aim to reveal challenges faced by current methods and propose insights for future improvements. 
                    
Methods:
We evaluated the SZZ algorithm and two large language models, GPT-4o and Llama 3.1, using a curated repository of corner case bugs with detailed reports. This setup allowed us to assess the strengths and weaknesses of both traditional algorithms and LLMs. 

Results:
The SZZ algorithm achieved a recall of 0.8 and a precision of 0.36, resulting in an F1 score of 0.5 for corner cases and a recall of 1 and a precision of 0.5 for non-corner cases with an F1 score of 0.67. In comparison, the LLMs showed varied performance: for corner cases, Llama had an MRR of 0.7, while GPT scored 0.5. For non-corner cases, both models performed better, with an MRR of 0.875. 
              
Conclusion:
Corner cases in BIC identification expose limitations in current methods, emphasizing the need for improved approaches to accurately handle these challenges.
</div>
</div>
</li>  
<br> 

         
<li>
<div style="text-align: justify">
<a href="https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Evaluating+ReLink+for+Traceability+Link+Recovery+in+Practice&btnG=" >Evaluating ReLink for Traceability Link Recovery in Practice</a>
<br><i> Ayberk Yaşa, Cemhan Kaan Özaltan, Görkem Ayten, Fatih Kaplama, Ömercan Devran, Baykal Mehmet Uçar, Eray Tüzün</i>
<br>IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER)
<br><button data-toggle="collapse" data-target="#demo56">See Abstract</button><br>

            <div id="demo56" class="collapse">
            Context:
Traceability is important in the software development life cycle for managing the connections among various software artifacts, particularly pull requests (PRs) and issues. Developers often neglect to link these manually, reducing traceability. Existing algorithms to recover these links have limited application in closed-source projects.

Objective:
In this study, we share the experience of using ReLink, a predictive PR-issue linking tool with visualization capabilities, in a closed-source project environment. 
                    
Methods:
ReLink stands out due to its availability as a fully functional web application and its semi-automated nature, which enhances usability. ReLink determines missing links between PRs and issues based on a confidence score normalized between 0 and 100, calculated using text similarity and heuristic rules.

Results:
The tool’s effectiveness was evaluated in both an open-source project and an industry-based case study. In the open-source project, ReLink achieved a top-5 accuracy of 0.80 and a precision of 0.77. In the industrial case study, ReLink’s effectiveness was validated by practitioners selecting the correct link from five issue suggestions, resulting in a top-5 accuracy of 0.86 and a mean reciprocal rank (MRR) of 0.84. 
              
Conclusion:
Through this experience, we offer insights into both the benefits and challenges of implementing traceability link recovery in the industry and provide recommendations for practitioners seeking to bridge traceability gaps efficiently. 
</div>
</div>
</li>  
<br> 

     
<li>
<div style="text-align: justify">
<a>Enhanced Code Reviews Using Pull Request Based Change Impact Analysis</a>
<br><i>İsmail Sergen Göçmen, Ahmed Salih Cezayir, Eray Tüzün</i>
<br>Empirical Software Engineering
<br><button data-toggle="collapse" data-target="#demo55">See Abstract</button><br>

            <div id="demo55" class="collapse">
            Context:
Code reviewing is an essential yet challenging activity due to the potential repercussions associated with changes to the codebase. While version control highlights differences between versions, it may not adequately alert developers to potential side effects of changes. Change impact analysis alongside code differences can guide reviewers in making informed decisions.

Objective:
We aim to enhance the code review process by providing helpful insights to reviewers by analyzing change impact.
                    
Methods:
We propose a novel change impact analysis approach with the granularity of pull requests by combining call graph-based dependency analysis and history mining techniques. By utilizing these, we calculate several file metrics and an overall risk score for each pull request. To validate the approach, we conducted two focus group sessions, including a feature feedback survey, a tool demo, a post-demo survey, and focus group discussions. Additionally, we performed experiments on three open-source projects to evaluate the computational feasibility.

Results:
From the focus groups, our approach received an average of 3.66 out of 5.0 for enhancing the code review experience across five aspects. The current risk score formula averaged 3.2 out of 5.0 for accurately representing change impact, with 71% agreement on the selected metrics. Experiments confirmed computational viability, with analysis times ranging from 7.4 to 22.43 seconds.
              
Conclusion:
Our study underscores the potential benefits of integrating change impact analysis into the code review process. By leveraging this approach, developers can conduct more thorough reviews, enhancing their ability to detect and mitigate potential issues arising from code changes.
</div>
</div>
</li>  
<br> 



<li>
<div style="text-align: justify">
<a href="https://doi.org/10.1002/smr.2750">A Serious Game Approach to Introduce the CodeReview Practice</a>
<br><i>Baris Ardic, Eray Tuzun</i>
<br>Journal of Software: Evolution and Process
<br><button data-toggle="collapse" data-target="#demo53">See Abstract</button><br>

            <div id="demo53" class="collapse">
            Context:
Code review is a widely utilized practice that focuses on improving code via manual inspections. However, this practice is not addressed adequately in a typical software engineering curriculum.

Objective:
We aim to help address the code review practice knowledge gap between the software engineering curricula and the industry with a serious game approach. We determine our learning objectives around the introduction of the code review process.
                    
Methods:
To realize these objectives, we design, build, and test the serious game. We then conduct three case studies with a total of 280 students. We evaluated the results by comparing the student's knowledge and confidence about code review before and after case studies, as well as evaluating how they performed in code review quizzes and game levels themselves. 

Results:
Our analysis indicates that students had a positive experience during gameplay, and an in-depth examination suggests that playing the game also enhanced their knowledge. We conclude that the game had a positive impact on introducing the code review process. 
              
Conclusion:
This study represents a step taken toward moving code review education from industry starting positions to higher education. The game and its auxiliary materials are available online.
</div>
</div>
</li>  
<br> 


            
<li>
<div style="text-align: justify">
<a href="https://doi.org/10.1109/ASE56229.2023.00015">Bus Factor Explorer</a>
<br><i>Egor Klimov, Muhammad Umair Ahmed, Nikolai Sviridov, Pouria Derakhshanfar, Eray Tuzun, Vladimir Kovalenko</i>
<br>38th IEEE/ACM International Conference on Automated Software Engineering (ASE)
<br><button data-toggle="collapse" data-target="#demo49">See Abstract</button><br>

            <div id="demo49" class="collapse">
            Context:
Bus factor (BF) is a metric that tracks knowledge distribution in a project. It is the minimal number of engineers that have to leave for a project to stall.

Objective:
Despite the fact that there are several algorithms for calculating the bus factor, only a few tools allow easy calculation of bus factor and convenient analysis of results for projects hosted on Git-based providers.
                    
Methods:
We introduce Bus Factor Explorer, a web application that provides an interface and an API to compute, export, and explore the Bus Factor metric via treemap visualization, simulation mode, and chart editor. It supports repositories hosted on GitHub and enables functionality to search repositories in the interface and process many repositories at the same time.

Results:
Our tool allows users to identify the files and subsystems at risk of stalling in the event of developer turnover by analyzing the VCS history.
              
Conclusion:
The application and its source code are publicly available on GitHub at https://github.com/JetBrains-Research/bus-factor-explorer. The demonstration video can be found on YouTube: https://youtu.be/uIoV79N14z8
</div>
</div>
</li>  
<br> 

            
<li>
<div style="text-align: justify">
<a href="https://link.springer.com/article/10.1007/s10664-023-10425-5">Taxonomy of inline code comment smells</a>
<br><i>Elgun Jabrayilzade, Ayda Yurtoglu, Eray Tuzun</i>
<br>Empirical Software Engineering An International Journal
<br><button data-toggle="collapse" data-target="#demo48">See Abstract</button><br>

            <div id="demo48" class="collapse">
            Context:
Code comments play a vital role in source code comprehension and software maintainability. It is common for developers to write comments to explain a code snippet, and commenting code is generally considered a good practice in software engineering. However, low-quality comments can have a detrimental effect on software quality or be ineffective for code understanding.
                        
Objective:
This study aims to create a taxonomy of inline code comment smells and determine how frequently each smell type occurs in software projects.
                        
Methods:
We conducted a multivocal literature review to define the initial taxonomy of inline comment smells. Afterward, we manually labeled 2447 inline comments from eight open-source projects where half of them were Java, and another half were Python projects. We created a taxonomy of 11 inline code comment smell types and found out that the smells exist in both Java and Python projects with varying degrees. 

Results:
Moreover, we conducted an online survey with 41 software practitioners to learn their opinions on these smells and their impact on code comprehension and software maintainability. The survey respondents generally agreed with the taxonomy; however, they reported that some smell types might have a positive effect on code comprehension in certain scenarios. We also opened pull requests and issues fixing the comment smells in the sampled projects, where we got a 27% acceptance rate.
              
Conclusion:
We share our manually labeled dataset online and provide implications for software engineering practitioners, researchers, and educators.

</div>
</div>
</li>  
<br> 


<li>
<div style="text-align: justify">
<a href="https://doi.org/10.1016/j.jss.2024.112101">Do code reviews lead to fewer code smells?</a>
<br><i>Erdem Tuna, Carolyn Seaman, Eray Tuzun</i>
<br>Journal of Systems and Software
<br><button data-toggle="collapse" data-target="#demo47">See Abstract</button><br>

            <div id="demo47" class="collapse">
            Context:
The code review process is conducted by software teams with various motivations. Among other goals, code reviews act as a gatekeeper for software quality.
                        
Objective:
In this study, we explore whether code reviews have an impact on one specific aspect of software quality, software maintainability. We further extend our investigation by analyzing whether code review process quality (as evidenced by the presence of code review process smells) influences software maintainability (as evidenced by the presence of code smells).
                        
Methods:
We investigate whether smells in the code review process are related to smells in the code that was reviewed by using correlation analysis. We augment our quantitative analysis with a focus group study to learn practitioners’ opinions.
              
Results:
Our investigations revealed that the level of code smells neither increases nor decreases in 8 out of 10 code reviews, regardless of the quality of the code review. Contrary to our own intuition and that of the practitioners in our focus groups, we found that code review process smells have little to no correlation with the level of code smells. We identified multiple potential reasons behind the counter-intuitive results based on our focus group data. Furthermore, practitioners still believe that code reviews are helpful in improving software maintainability.
              
Conclusion:
Our results imply that the community should update our goals for code review practices and reevaluate those practices to align them with more relevant and modern realities.

</div>
</div>
</li>  
<br> 

           
<li>
<div style="text-align: justify">
<a href="https://www.computer.org/csdl/proceedings-article/icsme/2024/956800a163/22NQCy7c8eI">Towards Unmasking LGTM Smells in Code Reviews: A Comparative Study of Comment-Free and Commented Reviews</a>
<br><i>Mahmut Furkan Gön, Burak Yetistiren, Eray Tuzun</i>
<br>40th International Conference on Software Maintenance and Evolution
<br><button data-toggle="collapse" data-target="#demo46">See Abstract</button><br>

            <div id="demo46" class="collapse">
            Context:
Code review is a crucial component of the software development life cycle and is adopted as a best practice in the industry. However, like any process, counterproductive practices and pitfalls exist within code review, such as the occurrence of the "Looks Good to Me" (LGTM) smell. LGTM smell occurs when superficial review is conducted. LGTM review smells potentially result in the accidental inclusion of low-quality changesets in the codebase, leading to severe bugs, possibly many reopens of the associated issues, and subsequent time wasted by additional changes to the changeset. 
                        
Objective:
In this study, we aim to explore LGTM smells and examine their potential impacts on the related repository.
                        
Methods:
Given the inherent challenge of automatically detecting LGTM smells in code reviews, this study introduces an alternative approach by categorizing code reviews into two distinct types: comment-free and commented reviews. The primary hypothesis is that comment-free reviews are more prone to LGTM smells due to their lack of detailed examination and discourse. To test this hypothesis, we conduct an empirical analysis on a subset of PRs comprising code reviews from five large-scale software projects. We further investigate the impact of comment-free and commented reviews on key development metrics, specifically focusing on the number of reopens and late commits in pull requests (PRs).
              
Results:
According to the results, 64.7% of the PRs in these projects exhibited comment-free reviews. Our manual analysis reveals that comment-free reviews exhibit the LGTM smell 3.5 times more frequently than the commented reviews. We also observed a statistically significant difference, indicating that comment-free review PRs tend to include more late commits (i.e., commits made after the reviewer’s approval) than the commented PRs. However, no statistically significant difference was observed in the reopening ratio of associated issues between comment-free reviews and commented reviews. 
              
Conclusion:
Our approach provides a novel method for detecting and exploring the impacts of LGTM smell, emphasizing the significance of comprehensive code reviews and setting the stage for future research aimed at automatically identifying LGTM smell occurrences.

</div>
</div>
</li>  
<br> 

            
<li>
<div style="text-align: justify">
<a href="https://dl.acm.org/doi/abs/10.1145/3617555.3617870">Do Developers Fix Continuous Integration Smells?</a>
<br><i>Ayberk Yaşa, Ege Ergül, Hakan Erdogmus, Eray Tuzun</i>
<br>PROMISE 2023: Proceedings of the 19th International Conference on Predictive Models and Data Analytics in Software Engineering
<br><button data-toggle="collapse" data-target="#demo45">See Abstract</button><br>

            <div id="demo45" class="collapse">
            Context:
Continuous Integration (CI) is a common software engineering practice in which the code changes are frequently merged into a software project repository after automated builds and tests have been successfully run. CI enables developers to quickly detect bugs, enhance the quality of the code, and shorten review times. However, developers may encounter some obstacles in following the CI principles. They may be unaware of them, they may follow the principles partially or they may even act against them. These behaviors result in CI smells. CI smells may in turn lessen the benefits of CI. Addressing CI smells rapidly allows software projects to fully reap the benefits of CI and increase its effectiveness.
                        
Objective:
The main objective of this study is to investigate how frequently developers address CI smells.
                        
Methods:
To achieve this objective, we first selected seven smells, then implemented scripts for detecting these smells automatically, and then ran the scripts in eight open-source software projects using GitHub Actions. To assess the resolution extent of CI smells by practitioners, we calculated the occurrences and time-to-resolution (TTR) of each smell.  
              
Results:
Our results suggest that Skipped Job smell has been fixed slightly more than other CI smells. The most frequently observed smell was Long Build, which was detected in an average of 19.03% of all CI builds. Fake Success smell does not get resolved in projects where it exists. 
              
Conclusion:
Our study reveals that practitioners do not fix CI smells in practice. Further studies are needed to explore the underlying reasons behind this, in order to recommend more effective strategies for addressing these smells.
</div>
</div>
</li>  
<br> 

         
<li>
<div style="text-align: justify">
<a href="https://dl.acm.org/doi/abs/10.1145/3643673">An Empirical Analysis of Issue Templates Usage in Large-Scale
Projects on GitHub</a>
<br><i>Emre Sülün, Metehan Saçakçı, Eray Tuzun</i>
<br>ACM Transactions on Software Engineering and Methodology
<br><button data-toggle="collapse" data-target="#demo44">See Abstract</button><br>

            <div id="demo44" class="collapse">
            Context:
GitHub Issues is a widely used issue tracking tool in open-source software projects. Originally designed with broad flexibility, its lack of standardization led to incomplete issue reports, impeding software development and maintenance efficiency. To counteract this, GitHub introduced issue templates in 2016, which rapidly became popular.
                        
Objective:
Our study assesses the current use and evolution of these templates in large-scale open-source projects and their impact on issue tracking metrics, including resolution time, number of reopens, and number of issue comments.
                        
Methods:
Employing a comprehensive analysis of 350 templates from 100 projects, we also evaluated over 1.9 million issues for template conformity and impact. Additionally, we solicited insights from open-source software maintainers through a survey.  
              
Results:
Our findings highlight issue templates’ extensive usage in 99 of the 100 surveyed projects, with a growing preference for YAML-based templates, a more structured template variant. Projects with a template exhibited markedly reduced resolution time (381.02 days to 103.18 days) and reduced issue comment count (4.95 to 4.32) compared to those without. The use of YAML-based templates further significantly decreased resolution time, the number of reopenings, and the discussion extent.
              
Conclusion:
Thus, our research underscores issue templates’ positive impact on large-scale open-source projects, offering recommendations for improved effectiveness.
</div>
</div>
</li>  
<br> 

        
<li>
<div style="text-align: justify">
<a href="https://dl.acm.org/doi/abs/10.1145/3611643.3613877">BFSig: Leveraging File Significance in Bus Factor Estimation</a>
<br><i>Vahid Haratian, Mikhail Evtikhiev, Pouria Derakhshanfar, Eray Tuzun, Vladimir Kovalenko</i>
<br>ESEC/FSE 2023: Proceedings of the 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering
<br><button data-toggle="collapse" data-target="#demo43">See Abstract</button><br>

            <div id="demo43" class="collapse">
            Context:
Software projects experience the departure of developers due to various reasons. As developers are one of the main sources of knowledge in software projects, their absence will inevitably result in a certain degree of knowledge depletion. Bus Factor (BF) is a metric to evaluate how this knowledge loss can affect the project’s continuity. Conventionally, BF is calculated as the smallest set of developers, removing over half the project knowledge upon departure.
                        
Objective:
Current state-of-the-art approaches measure developers’ knowledge by the number of authored files, utilizing version control system (VCS) information. However, numerous studies have shown that files in software projects have different significance. In this study, we explore how weighting files according to their significance affects the performance of two prevailing BF estimators.
                        
Methods:
We derive significance scores by computing five well-known graph metrics from the project’s dependency graph: PageRank, In- /Out-/All-Degree, and Betweenness Centralities. Furthermore, we introduce BFSig, a prototype of our approach. Finally, we present a new dataset comprising reported BF scores collected by surveying software practitioners from five prominent Github repositories. 
              
Results:
Our results indicate that BFSig outperforms the baselines by up to an 18% reduction in terms of Normalized Mean Absolute Error (NMAE). Moreover, BFSig yields 18% fewer False Negatives in identifying potential risks associated with low BF. Besides, our respondent confirmed BFSig versatility by showing its ability to assess the BF of the project’s subfolders.
              
Conclusion:
In conclusion, we believe to estimate BF from authorship, software components of higher importance should be assigned heavier weight. Currently, BFSig exclusively explores the topological characteristics of these components. Nevertheless, considering attributes such as code complexity and bug proneness could potentially enhance the performance of BFSig.
</div>
</div>
</li>  
<br> 

            
<li>
<div style="text-align: justify">
<a href="https://dl.acm.org/doi/abs/10.1145/3593434.3593504">Analyzing Bug Life Cycles to Derive Practical Insights</a>
<br><i>Çağrı Eren, Kerem Şahin, Eray Tuzun</i>
<br>27th International Conference on Evaluation and Assessment in Software Engineering (EASE 2023)
<br><button data-toggle="collapse" data-target="#demo42">See Abstract</button><br>

            <div id="demo42" class="collapse">
            Context:
Bug tracking systems define bug life cycles that outline their bug tracking process.
                        
Objective:
In this study, we assess bug life cycles to identify bottlenecks in the bug tracking processes, and examine the effectiveness of bug tracking system usage practices linked to bug states and state transitions.
                        
Methods:
To achieve this, we examined the bug life cycles of three open-source software projects which use Bugzilla as their bug tracking system. In total, we have analyzed 106.196 bugs gathered from these projects. We started by looking at the temporal and quantitative aspects of these projects’ bug life cycles. After that, we collected data about how bug life cycles differ over time. Finally, we inspected the frequency of reopened and state-looping bugs in these projects.
              
Results:
After our analysis, we have deduced that the presented temporal and quantitative analysis of bug life cycles is useful for finding bottlenecks and undesired behaviors in the bug tracking processes. We also inferred that examining the changes in bug life cycles over time can provide insights into how bug tracking practices changed throughout the project’s lifetime, and it can be used as a parameter to assess whether the bug tracking system usage has improved. Lastly, we deducted that analyzing undesired state trails’ frequency provides insights into the performance of bug tracking processes.
              
Conclusion:
 Based on the insights gained from analyzing bug life cycles with the presented methods, we believe that decision makers can improve their workflow by introducing or removing new states to the bug life cycle and adding new rules and restrictions to their bug tracking process.
</div>
</div>
</li>  
<br>           
                       
            
<li>
<div style="text-align: justify">
<a href="https://www.computer.org/csdl/proceedings-article/icssp/2023/119600a092/1OyNcT0ikQ8">Towards Better Code Reviews: Using Mutation Testing to Improve Reviewer Attention</a>
<br><i>Ziya Mukhtarov, Mannan Abdul, Mokhlaroyim Raupova, Javid Baghirov, Osama Tanveer, Haluk Altunel, Eray Tüzün</i>
<br> The International Conference on Software and System Processes (ICSSP 2023)
<br><button data-toggle="collapse" data-target="#demo41">See Abstract</button><br>

            <div id="demo41" class="collapse">
            Context:

Code reviews, while effective, can be crippled by process smells if not performed correctly. A typical process smell that harms the efficacy of code reviews is the ‘Looks Good To Me’ (LGTM) smell, wherein a reviewer approves a code review task without reviewing the code attentively. Low-quality code reviews can be harmful, as they can cause bugs to slip into a product codebase leading to potentially severe consequences.

Objective:
In this paper, we propose an innovative solution to potentially minimize the occurrence of the LGTM smell commonly found in code reviews.
                        
Methods:
We built a tool that is a proof-of-concept implementation of our solution, which incorporates the concept of mutation testing into code reviews. It provides a platform where pull request authors can apply mutations to the pull request code in GitHub.
              
Results:
Reviewer attention and review efficacy are measured based on their mutation score. We validated our proposed solution with eight developers and received promising results.
              
Conclusion:
To the best of our knowledge, our proof of concept implementation is the first-ever code review tool that uses the concept of mutation testing.

</div>
</div>
</li>  
<br>            
                     
            
            
<li>
<div style="text-align: justify">
<a href="https://dl.acm.org/doi/abs/10.1145/3558489.3559072">Assessing the quality of GitHub copilot’s code generation</a>
<br><i>Burak Yetistiren, Isik Ozsoy, Eray Tuzun</i>
<br> 18th International Conference on Predictive Models and Data Analytics in Software Engineering
<br><button data-toggle="collapse" data-target="#demo40">See Abstract</button><br>

            <div id="demo40" class="collapse">
            Context:

The introduction of GitHub’s new code generation tool, GitHub Copilot, seems to be the first well-established instance of an AI pair-programmer. GitHub Copilot has access to a large number of open-source projects, enabling it to utilize more extensive code in various programming languages than other code generation tools. Although the initial and informal assessments are promising, a systematic evaluation is needed to explore the limits and benefits of GitHub Copilot.

Objective:
The main objective of this study is to assess the quality of generated code provided by GitHub Copilot. We also aim to evaluate the impact of the quality and variety of input parameters fed to GitHub Copilot.

Methods:
To achieve this aim, we created an experimental setup for evaluating the generated code in terms of validity, correctness, and efficiency.
              
Results:
The results suggest that GitHub Copilot was able to generate valid code with a 91.5% success rate. In terms of code correctness, out of 164 problems, 47 (28.7%) were correctly, while 84 (51.2%) were partially correctly, and 33 (20.1%) were incorrectly generated.
              
Conclusion:
Our empirical analysis shows that GitHub Copilot is a promising tool based on the results we obtained, however further and more comprehensive assessment is needed in the future.

</div>
</div>
</li>  
<br>  
  
  
  
  <li>
<div style="text-align: justify">
<a href="https://doi.org/10.1016/j.infsof.2022.106956">Cleaning ground truth data in software task assignment</a>
<br><i>K. Ayberk Tecimer, Eray Tüzün, Cansu Moran, Hakan Erdogmus</i>
<br> Information and Software Technology Journal 2022
<br><button data-toggle="collapse" data-target="#demo39">See Abstract</button><br>

            <div id="demo39" class="collapse">
            Context:

In the context of collaborative software development, there are many application areas of task assignment such as assigning a developer to fix a bug, or assigning a code reviewer to a pull request. Most task assignment techniques in the literature build and evaluate their models based on datasets collected from real projects. The techniques invariably presume that these datasets reliably represent the “ground truth”. In a project dataset used to build an automated task assignment system, the recommended assignee for the task is usually assumed to be the best assignee for that task. However, in practice, the task assignee may not be the best possible task assignee, or even a sufficiently qualified one.

Objective:
We aim to clean up the ground truth by removing the samples that are potentially problematic or suspect with the assumption that removing such samples would reduce any systematic labeling bias in the dataset and lead to performance improvements.

Methods:
We devised a debiasing method to detect potentially problematic samples in task assignment datasets. We then evaluated the method’s impact on the performance of seven task assignment techniques by comparing the Mean Reciprocal Rank (MRR) scores before and after debiasing. We used two different task assignment applications for this purpose: Code Reviewer Recommendation (CRR) and Bug Assignment (BA).

Results:
In the CRR application, we achieved an average MRR improvement of 18.17% for the three learning-based techniques tested on two datasets. No significant improvements were observed for the two optimization-based techniques tested on the same datasets. In the BA application, we achieved a similar average MRR improvement of 18.40% for the two learning-based techniques tested on four different datasets.

Conclusion:
Debiasing the ground truth data by removing suspect samples can help improve the performance of learning-based techniques in software task assignment applications.

</div>
</div>
</li>
<br>
  
  
<li>
<div style="text-align: justify">
<a href="https://www.sciencedirect.com/science/article/pii/S0950584922001094">Taxonomy of bug tracking process smells: Perceptions of practitioners and an empirical analysis</a>
<br><i>Khushbakht Ali Qamar, Emre Sülün, Eray Tüzün</i>
<br> Information and Software Technology Journal 2022
<br><button data-toggle="collapse" data-target="#demo38">See Abstract</button><br>

            <div id="demo38" class="collapse">
            Context:

While there is no consensus on a formally specified bug tracking process, some certain rules and best practices for an optimal bug tracking process are accepted by many companies and open-source software (OSS) projects. Despite slight variations between different platforms, the primary aim of all these rules and practices is to perform a more efficient bug tracking process. Practitioners’ non-compliance with the best practices not only impedes the benefits of the bug tracking process but also negatively affects the other phases of software development life cycle.

Objective:
The goal of this study is to gain a better knowledge of the bad practices that occur during the bug tracking process (bug tracking process smells) and to perform quantitative analysis to show that these process smells exist in bug tracking systems. Moreover, we want to know the perception of software practitioners related to these process smells and also observe the impact of process smells on the bug tracking process.

Methods:
Based on the results of a multivocal literature review, we analyzed 60 sources in academic and gray literature and propose a taxonomy of 12 bad practices in the bug tracking process. To quantitatively analyze these process smells, we inspected bug reports collected from eight projects which use Jira, Bugzilla, and GitHub Issues. To get an idea about the perception of practitioners about the taxonomy of bug tracking process smells, we conducted a targeted survey with 30 software practitioners. Moreover, we statistically analyzed the impact of bug tracking process smells on the resolution time and reopening count of bugs.

Results:
We observed from our empirical results that a considerable amount of bug tracking process smells exist in all projects and some of the process smell categories have statistically significant impacts on quality and speed. Survey results shows that the majority of software practitioners agree with the proposed taxonomy of BT process smells.

Conclusion:
The statistical analysis reveals that bug tracking process smells have an impact on OSS projects. The proposed taxonomy may serve as a foundation for best practices and tool support for detecting and avoiding bug tracking process smells.

</div>
</div>
</li>
<br>
<li>
<div style="text-align: justify">
<a href="https://arxiv.org/abs/2204.07669">Investigating the Impact of Forgetting in Software Development</a>
<br><i>Utku Ünal, Eray Tüzün, Tamer Gezici, Ausaf Ahmed Farooqui</i>
<br>19th International Conference on Mining Software Repositories (MSR 2022)
<br><button data-toggle="collapse" data-target="#demo37">See Abstract</button><br>

            <div id="demo37" class="collapse">
            Context: Forgetting is defined as a gradual process of losing information. Even though there are many studies demonstrating the effect of forgetting in software development, to the best of our knowledge, no study explores the impact of forgetting in software development using a controlled experiment approach.

Objective: We would like to provide insights on the impact of forgetting in software development projects. We want to examine whether the recency & frequency of interaction impact forgetting in software development.
Methods: We will conduct an experiment that examines the impact of forgetting in software development. Participants will first do an initial task. According to their initial task performance, they will be assigned to either the experiment or the control group. The experiment group will then do two additional tasks to enhance their exposure to the code. Both groups will then do a final task to see if additional exposure to the code benefits the experiment group's performance in the final task. Finally, we will conduct a survey and a recall task with the same participants to collect data about their perceptions of forgetting and quantify their memory performance, respectively.

</div>
</div>
</li>
<br>
<li>
<div style="text-align: justify">
<a href="https://link.springer.com/article/10.1007/s10664-022-10129-2">Analyzing developer contributions using artifact traceability graphs</a>
<br><i>H. Alperen Cetin, Eray Tuzun</i>
<br>Empirical Software Engineering
<br><button data-toggle="collapse" data-target="#demo36">See Abstract</button><br>

            <div id="demo36" class="collapse">
            Context: In a software project, properly analyzing the contributions of developers could

provide valuable insights for decision-makers. The contributions of a developer could be
in many different forms such as committing and reviewing code, opening and resolving
issues. Previous approaches mainly consider the commit-based contributions which provide
an incomplete picture of developer contributions.
Objective: Different from the traditional commit-based approaches for analyzing developer
contributions, we aim to provide a more holistic approach to reflect the rich set of software
development activities using artifact traceability graphs.
Method: For analyzing the developer contributions, we propose a novel categorization of
developers (Jacks, Mavens and Connectors) in a software project. We introduce a set of algorithms on artifact traceability graphs to identify key developers, recommend replacements
for leaving developers and evaluate knowledge distribution among developers.
Results: We evaluate our proposed algorithms on six open-source projects and demonstrate
that the identified key developers match the top commenters up to 98%, recommended
replacements are correct up to 91% and identified knowledge distribution labels are
compatible 94% on average with the baseline approaches.
Conclusions: The proposed algorithms using artifact traceability graphs for analyzing developer contributions could be used by software project decision-makers in several scenarios.
(1) Identifying different types of key developers. (2) Finding a replacement developer in
large teams. (3) Evaluating the overall knowledge distribution amongst developers to take
early precautions.

</div>
</div>
</li>
<br>
<li>
<div style="text-align: justify">
<a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/smr.2446">Characterizing duplicate bugs: Perceptions of practitioners and an empirical analysis</a>
<br><i>Berfin Kucuk,Idil Hanhan,Eray Tuzun</i>
<br>Journal of Software: Evolution and Process
<br><button data-toggle="collapse" data-target="#demo35">See Abstract</button><br>

            <div id="demo35" class="collapse">
            Bug handling is an essential part of the software development process. Ideally, in a bug-tracking system, bugs are reported, fixed, verified, and closed. In some cases, bugs have to be reopened mostly due to an incorrect fix. However, instead of reopening the existing bug report, users may submit a new report for a previously reported bug, which results in duplicate bug reports. Users might report duplicate bugs if they miss the previous bug report or if the previous bug is unresolved (i.e., in progress) and therefore cannot be reopened. These duplicate bug reports may cost extra maintenance efforts in triaging and bug fixing. There have been several studies on characterizing reopened bugs and duplicate bug reports; however, to the best of our knowledge, there has been no prior work on understanding the dynamics of their interaction, which is missed reopen bugs. Our study is based on analyzing the difference between duplicate and nonduplicate bugs and further categorizing the duplicate bugs. In this regard, we categorize duplicate bugs according to the original bug's resolution status at the duplicate's creation time as Master-Unresolved bugs and Master-Resolved (Missed Reopen) bugs to distinguish their properties. We compare these two types of bugs in terms of their relationship to their master bug, bug surface time, bug fix time, bug's severity, and the number of users involved. We perform case studies using the Eclipse and Mozilla projects' bug repositories that include more than 165,500 and 394,000 bug reports, respectively. Additionally, we investigate the perceived importance, impact, and causes of duplicate bugs, as well as the difference between nonduplicate and duplicate bugs and its categories for practitioners in the software industry by conducting a survey.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://arxiv.org/abs/2202.01523">Bus Factor In Practice</a>
            <br><i>Elgun Jabrayilzade, Mikhail Evtikhiev, Eray Tüzün, Vladimir Kovalenko</i>
            <br> 44th International Conference on Software Engineering (ICSE 2022)
            <br><button data-toggle="collapse" data-target="#demo34">See Abstract</button><br>

            <div id="demo34" class="collapse">
            Bus factor is a metric that identifies how resilient is the project to the sudden engineer turnover. It states the minimal number of engineers that have to be hit by a bus for a project to be stalled. Even though the metric is often discussed in the community, few studies consider its general relevance. Moreover, the existing tools for bus factor estimation focus solely on the data from version control systems, even though there exists other channels for knowledge generation and distribution. With a survey of 269 engineers, we find that the bus factor is perceived as an important problem in collective development, and determine the highest impact channels of knowledge generation and distribution in software development teams. We also propose a multimodal bus factor estimation algorithm that uses data on code reviews and meetings together with the VCS data. We test the algorithm on 13 projects developed at JetBrains and compared its results to the results of the state-of-the-art tool by Avelino et al. against the ground truth collected in a survey of the engineers working on these projects. Our algorithm is slightly better in terms of both predicting the bus factor as well as key developers compared to the results of Avelino et al. Finally, we use the interviews and the surveys to derive a set of best practices to address the bus factor issue and proposals for the possible bus factor assessment tool.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/9610717">Towards a Taxonomy of Inline Code Comment Smells</a>
            <br><i>Elgun Jabrayilzade, Olcaytu Gürkan, Eray Tüzün</i>
            <br>IEEE 21st International Working Conference on Source Code Analysis and Manipulation (SCAM 2021)
            <br><button data-toggle="collapse" data-target="#demo33">See Abstract</button><br>

            <div id="demo33" class="collapse">
            Code comments play a vital role in source code comprehension and software maintainability. It is common for developers to write comments for explaining a code snippet. However, low-quality comments can have a detrimental effect on software quality or be ineffective for code understanding. This study aims to create a taxonomy of inline code comment smells and determine how commonly each smell type occurs in software projects. We conducted a multivocal literature review for defining the initial taxonomy of inline comment smells. Afterward, we manually labeled 899 inline comments from three open-source Java projects. We created a taxonomy of 11 inline code comment smell types and found out that the smells exist in practice with varying degrees.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/publication/357871610_Bug_Tracking_Process_Smells_In_Practice">Bug Tracking Process Smells In Practice</a>
            <br><i>Erdem Tuna, Vladimir Kovalenko, Eray Tüzün</i>
            <br> 44th International Conference on Software Engineering (ICSE 2022)
            <br><button data-toggle="collapse" data-target="#demo32">See Abstract</button><br>

            <div id="demo32" class="collapse">
            Software teams use bug tracking (BT) tools to report and manage bugs. Each record in a bug tracking system (BTS) is a reporting entity consisting of several information fields. The contents of the reports are similar across different tracking tools, though not the same. The variation in the workflow of teams prevents defining an ideal process of running BTS. Nevertheless, there are best practices reported both in white and gray literature. Developer teams may not adopt the best practices in their BT process. This study investigates the non-compliance of developers with best practices, so-called smells, in the BT process. We mine bug reports of four projects in the BTS of JetBrains, a software company, to observe the prevalence of BT smells in an industrial setting. Also, we survey developers to see (1) if they recognize the smells,(2) their perception of the severity of the smells, and (3) the potential benefits of a BT process smell detection tool. We found that (1) smells occur, and their detection requires a solid understanding of the BT practices of the projects,(2) smell severity perception varies across smell types, and (3) developers considered that a smell detection tool would be useful for six of the smell categories.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/publication/357745711_Teaching_Design_Patterns_Using_Interactive_Methods">Teaching Design Patterns Using Interactive Methods</a>
            <br><i>Ata Yurtsever, Eray Tüzün</i>
            <br> CSEE&T / HICSS 2022 ▪ Conference on Software Engineering Education and Training: Special Track of Hawaii International Conference on System Sciences
            <br><button data-toggle="collapse" data-target="#demo31">See Abstract</button><br>

            <div id="demo31" class="collapse">
            Even though design patterns are one of the most important building blocks in the current software engineering ecosystem, computer science and software engineering graduates face trouble applying these patterns. To address this, we propose a tutorial and an online lab assessment method to solidify the idea of design patterns for students. The tutorial part integrates a live coding session. The online lab assessment consists of a three-stage process (designing a solution using a class diagram, peer review, and implementation) where students are expected to come up with a fully working solution using design patterns. The proposed approach is applied twice over two semesters to a total sum of 196 students. We discuss the effects of these interactive educational methods on learning by comparing pre-surveys, post-surveys and analyzing final grades. The analysis of the surveys shows that live coding is highly beneficial in enhancing the understanding of design patterns.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/profile/Elgun-Jabrayilzade/publication/357684242_An_Interactive_Approach_to_Teaching_Git_Version_Control_System/links/61da7f3ed4500608169b56aa/An-Interactive-Approach-to-Teaching-Git-Version-Control-System.pdf">An Interactive Approach to Teaching Git Version Control System</a>
            <br><i>Elgun Jabrayilzade, Fatih Sevban Uyanık, Emre Sülün, Eray Tüzün</i>
            <br> CSEE&T / HICSS 2022 ▪ Conference on Software Engineering Education and Training: Special Track of Hawaii International Conference on System Sciences
            <br><button data-toggle="collapse" data-target="#demo30">See Abstract</button><br>

            <div id="demo30" class="collapse">
            Although the Git version control system is widely used in software engineering, it has been observed that most Computer Science and Software Engineering students do not have the necessary knowledge and practices to use Git. To address this issue, we have prepared a Git and GitHub training program consisting of four sessions as a part of the Object-Oriented Software Engineering course where junior students utilized these tools for their term projects. The program was conducted in three academic terms for a total of 258 students. To evaluate the effectiveness of the training sessions, we have conducted two surveys, before (224 respondents) and after (200 respondents) the program. According to the survey results, the number of students considering themselves insufficient to use the tools for their projects decreased from 67% to 9% after the training program. Additionally, the majority of the students found the lectures and laboratory assignments beneficial
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.sciencedirect.com/science/article/abs/pii/S0950584921001877">Towards a taxonomy of code review smells</a>
            <br><i>Emre Doğan, ErayTüzün</i>
            <br>Information and Software Technology
            <br><button data-toggle="collapse" data-target="#demo29">See Abstract</button><br>

            <div id="demo29" class="collapse">
            Code review is a crucial step of the software development life cycle in order to detect possible problems in source code before merging the changeset to the codebase. Although there is no consensus on a formally defined life cycle of the code review process, many companies and open source software (OSS) communities converge on common rules and best practices. In spite of minor differences in different platforms, the primary purpose of all these rules and practices leads to a faster and more effective code review process. Non-conformance of developers to this process does not only reduce the advantages of the code review but can also introduce waste in later stages of the software development.

Objectives:
The aim of this study is to provide an empirical understanding of the bad practices followed in the code review process, that are code review (CR) smells.

Methods:
We first conduct a multivocal literature review in order to gather code review bad practices discussed in white and gray literature. Then, we conduct a targeted survey with 32 experienced software practitioners and perform follow-up interviews in order to get their expert opinion. Based on this process, a taxonomy of code review smells is introduced. To quantitatively demonstrate the existence of these smells, we analyze 226,292 code reviews collected from eight OSS projects.

Results:
We observe that a considerable number of code review smells exist in all projects with varying degrees of ratios. The empirical results illustrate that 72.2% of the code reviews among eight projects are affected by at least one code review smell.

Conclusion:
The empirical analysis shows that the OSS projects are substantially affected by the code review smells. The provided taxonomy could provide a foundation for best practices and tool support to detect and avoid code review smells in practice.

</div>
</div>
</li>
<br>
<li>
<div style="text-align: justify">
<a href="https://ieeexplore.ieee.org/document/9604852">Augmenting Code Review Experience Through Visualization</a>
<br><i>Faruk Balcı, Dilruba Sultan Haliloğlu, Onur Şahin, Cankat Tilki, Mehmet Ata Yurtsever, Eray Tüzün</i>
<br>Working Conference on Software Visualization (VISSOFT 2021)
<br><button data-toggle="collapse" data-target="#demo28">See Abstract</button><br>

            <div id="demo28" class="collapse">
            Code review is a systematic inspection of the code-base. It ensures that the software satisfies the required functionalities and standards; thus, it is an essential stage in the modern development process and is used frequently in the industry. For a successful review, the reviewer should be able to identify defects; therefore, the process is highly dependent on the awareness of the reviewer. Currently, code review is done by comparing the line-by-line differences on the codebase. However, this does not give structural information, such as design pattern changes or dependency changes between services.To address this problem, we propose an augmented next-generation code review experience using visual and holistic approaches to streamline the reviewing process. The proposed code review experience shows the structural representation of the change by visualizing it into a UML-like relationship diagram. Along with this diagram, the risk percentage for each commit is highlighted to emphasize the differences that possibly can be most affected by the change. An artifact map is also produced that includes issue-commit relation for bug tracking, to make reviewers aware of the frequent issues that are brought up. This map also highlights the change frequency of the files, for focusing the reviewers on the possibly vulnerable parts of the software for better quality reviews. The proposed visualizations have been implemented in a plugin-based proof-of-concept tool integrated within GitHub, supporting the visual reviewing of changes in codebases developed with Java language.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://research.tue.nl/en/publications/a-fine-grained-data-set-and-analysis-of-tangling-in-bug-fixing-co">A Fine-grained Data Set and Analysis of Tangling in Bug Fixing Commits</a>
            <br><i>Steffen Herbold, Alexander Trautsch, Benjamin Ledel, Alireza Aghamohammadi, Taher Ahmed Ghaleb, Kuljit Kaur Chahal, Tim Bossenmaier, Bhaveet Nagaria, Philip Makedonski, Matin Nili Ahmadabadi, Kristóf Szabados, Helge Spieker, Matej Madeja, Nathaniel Hoy, Valentina Lenarduzzi, Shangwen Wang, Gema Rodriguez Perez, Ricardo Colomo-Palacios, Roberto Verdecchia, Paramvir Singh,Yihao Qin, Debasish Chakroborti, Willard Davis, Vijay Walunj, Hongjun Wu, Diego Marcilio, Omar Alam, Abdullah Aldaeej, Idan Amit, Burak Turhan, Simon Eismann, Anna-Katharina Wickert, Ivano Malavolta, Matúš Sulír, Fatemeh Fard, Austin Z Henley, Stratos Kourtzanidis, Eray Tüzün, Christoph Treude, Simin Maleki Shamasbi, Ivan Pashchenko, Marvin Wyrich, James C. Davis, Alexander Serebrenik, Ella Albrecht, Ethem Utku Aktas, Daniel Strüber, Johannes Erbel</i>
            <br>Empirical Software Engineering
            <br><button data-toggle="collapse" data-target="#demo27">See Abstract</button><br>

            <div id="demo27" class="collapse">
            Context: Tangled commits are changes to software that address multiple concerns at once. For researchers interested in bugs, tangled commits mean that they actually study not only bugs, but also other concerns irrelevant for the study of bugs.

Objective: We want to improve our understanding of the prevalence of tangling and the types of changes that are tangled within bug fixing commits.

Methods: We use a crowd sourcing approach for manual labeling to validate which changes contribute to bug fixes for each line in bug fixing commits. Each line is labeled by four participants. If at least three participants agree on the same label, we have consensus.

Results: We estimate that between 17% and 32% of all changes in bug fixing commits modify the source code to fix the underlying problem. However, when we only consider changes to the production code files this ratio increases to 66% to 87%. We find that about 11% of lines are hard to label leading to active disagreements between participants. Due to confirmed tangling and the uncertainty in our data, we estimate that 3% to 47% of data is noisy without manual untangling, depending on the use case.

Conclusion: Tangled commits have a high prevalence in bug fixes and can lead to a large amount of noise in the data. Prior research indicates that this noise may alter results. As researchers, we should be skeptics and assume that unvalidated data is likely very noisy, until proven otherwise.

</div>
</div>
</li>
<br>
<li>
<div style="text-align: justify">
<a href="https://ieeexplore.ieee.org/abstract/document/9496156/authors">What Makes Agile Software Development Agile</a>
<br><i>M. Kuhrmann,P Tell,R Hebig,J Ann-Christin Klunder,J Munch,O Linssen,D Pfahl,M Felderer,C Prause,S Macdonell,J Nakatumba-Nabende,D Raffo,S Beecham,E. Tuzun,G Lopez,N Paez,D Fontdevila,S Licorish,S Kupper,G Ruhe,E Knauss,O Ozcan-Top,P Clarke,F Hugh Mc Caffery,M Genero,A Vizcaino,M Piattini,M Kalinowski,T Conte,R Prikladnicki,S Krusche,A Coskuncay,E Scott,F Calefato,S Pimonova,R Pfeiffer,U Pagh Schultz,R Heldal,M Fazal-Baqaie,C Anslow,M Nayebi,K Schneider,S Sauer,D Winkler,S Biffl,C Bastarrica,I Richardson
</i>
<br>IEEE Transactions on Software Engineering
<br><button data-toggle="collapse" data-target="#demo26">See Abstract</button><br>

            <div id="demo26" class="collapse">
            Together with many success stories, promises such as the increase in production speed and the improvement in stakeholders' collaboration have contributed to making agile a transformation in the software industry in which many companies want to take part. However, driven either by a natural and expected evolution or by contextual factors that challenge the adoption of agile methods as prescribed by their creator(s), software processes in practice mutate into hybrids over time. Are these still agile In this article, we investigate the question: what makes a software development method agile We present an empirical study grounded in a large-scale international survey that aims to identify software development methods and practices that improve or tame agility. Based on 556 data points, we analyze the perceived degree of agility in the implementation of standard project disciplines and its relation to used development methods and practices. Our findings suggest that only a small number of participants operate their projects in a purely traditional or agile manner (under 15%). That said, most project disciplines and most practices show a clear trend towards increasing degrees of agility. Compared to the methods used to develop software, the selection of practices has a stronger effect on the degree of agility of a given discipline. Finally, there are no methods or practices that explicitly guarantee or prevent agility. We conclude that agility cannot be defined solely at the process level. Additional factors need to be taken into account when trying to implement or improve agility in a software company. Finally, we discuss the field of software process-related research in the light of our findings and present a roadmap for future research.
        </div>
    </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/abstract/document/9491146">Ground Truth Deficiencies in Software Engineering: When Codifying the Past Can be Counterproductive</a>
            <br><i>E. Tüzün, H. Erdogmus, M. T. Baldassarre, M. Felderer, R. Feldt and B. Turhan</i>
            <br>IEEE Software
            <br><button data-toggle="collapse" data-target="#demo25">See Abstract</button><br>

            <div id="demo25" class="collapse">
            Many software engineering tools build and evaluate their models based on historical data to support development and process decisions. These models help us answer numerous interesting questions, but have their own caveats. In a real-life setting, the objective function of human decision-makers for a given task might be influenced by a whole host of factors that stem from their cognitive biases, subverting the ideal objective function required for an optimally functioning system. Relying on this data as ground truth may give rise to systems that end up automating software engineering decisions by mimicking past sub-optimal behaviour. We illustrate this phenomenon and suggest mitigation strategies to raise awareness.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/publication/352106199_Detection_and_Elimination_of_Systematic_Labeling_Bias_in_Code_Reviewer_Recommendation_Systems">Detection and Elimination of Systematic Labeling Bias in Code Reviewer Recommendation Systems</a>
            <br><i>Kazım Ayberk Tecimer, Eray Tüzün, Eray Tüzün, Hamdi Dibeklioğlu, Hakan Erdogmus</i>
            <br>The International Conference on Evaluation and Assessment in Software Engineering (EASE 2021)
            <br><button data-toggle="collapse" data-target="#demo24">See Abstract</button><br>

            <div id="demo24" class="collapse">
            Reviewer selection in modern code review is crucial for effective code reviews. Several techniques exist for recommending reviewers appropriate for a given pull request (PR). Most code reviewer recommendation techniques in the literature build and evaluate their models based on datasets collected from real projects using open-source or industrial practices. The techniques invariably presume that these datasets reliably represent the "ground truth. " In the context of a classification problem, ground truth refers to the objectively correct labels of a class used to build models from a dataset or evaluate a model's performance. In a project dataset used to build a code reviewer recommendation system, the recommended code reviewer picked for a PR is usually assumed to be the best code reviewer for that PR. However, in practice, the recommended code reviewer may not be the best possible code reviewer, or even a qualified one. Recent code reviewer recommendation studies suggest that the datasets used tend to suffer from systematic labeling bias, making the ground truth unreliable. Therefore, models and recommendation systems built on such datasets may perform poorly in real practice. In this study, we introduce a novel approach to automatically detect and eliminate systematic labeling bias in code reviewer recommendation systems. The bias that we remove results from selecting reviewers that do not ensure a permanently successful fix for a bug-related PR. To demonstrate the effectiveness of our approach, we evaluated it on two open-source project datasets-HIVE and QT Creator-and with five code reviewer recommendation techniques-Profile-Based, RSTrace, Naive Bayes, k-NN, and Decision Tree. Our debiasing approach appears promising since it improved the Mean Reciprocal Rank (MRR) of the evaluated techniques up to 26% in the datasets used.
            </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/9582562">Towards a Taxonomy of Bug Tracking Process Smells: A Quantitative Analysis</a>
            <br><i>Khushbakht Ali Qamar, Emre Sülün, Eray Tüzün</i>
            <br>EuroMicro 2021
            <br><button data-toggle="collapse" data-target="#demo23">See Abstract</button><br>

            <div id="demo23" class="collapse">
            Code review is the process of inspecting code changes by a developer who is not involved in the development of the changeset. One of the initial and important steps of code review process is selecting code reviewer(s) for a given code change. To maximize the benefits of the code review process, the appropriate selection of the reviewer is essential. Code reviewer recommendation has been an active research area over the last few years, and many recommendation models have been proposed in the literature.
            <br>
            Bug tracking is the process of monitoring and
            reporting malfunctions or issues found in software. While there is
            no consensus on a formally specified bug tracking process, some
            certain rules and best practices for an optimal bug tracking
            process are accepted by many companies and open-source software
            (OSS) projects. Despite slight variations between different
            platforms, the primary aim of all these rules and practices is to
            perform a more efficient bug tracking process. Practitioners' noncompliance
            with the best practices not only impedes the benefits
            of the bug tracking process but also negatively affects the other
            phases of the life cycle of software development.
            In this study, based on the results of a multivocal literature
            review, we analyzed 60 sources in academic and gray literature
            and propose a taxonomy of 12 bad practices in the bug tracking
            process, that is bug tracking process smells. To quantitatively
            analyze these process smells, we inspect bug reports collected
            from six projects. Among these projects, four of them are Jirabased
            (MongoDB Core Server, Evergreen, Confluence Server &
            Data Center, Jira Server & Data Center) and the other two
            are Bugzilla-based (GCC and Wireshark). We observed that a
            considerable amount of bug tracking process smells exist in all
            projects with varying ratios.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.sciencedirect.com/science/article/abs/pii/S0167642321000459">A Review of Code Reviewer Recommendation Studies: Challenges and Future Directions</a>
            <br><i>H. Alperen Cetin, Emre Doğan, Eray Tüzün</i>
            <br>Science of Computer Programming Journal 2021
            <br><button data-toggle="collapse" data-target="#demo22">See Abstract</button><br>

            <div id="demo22" class="collapse">
            Code review is the process of inspecting code changes by a developer who is not involved in the development of the changeset. One of the initial and important steps of code review process is selecting code reviewer(s) for a given code change. To maximize the benefits of the code review process, the appropriate selection of the reviewer is essential. Code reviewer recommendation has been an active research area over the last few years, and many recommendation models have been proposed in the literature.
            <br>
            In this study, we conduct a systematic literature review by inspecting 29 primary studies published from 2009 to 2020. Based on the outcomes of our review: (1) most preferred approaches are heuristic approaches closely followed by machine learning approaches, (2) the majority of the studies use open source projects to evaluate their models, (3) the majority of the studies prefer incremental training set validation techniques, (4) most studies suffer from reproducibility problems, (5) model generalizability and dataset integrity are the most common validity threats for the models and (6) refining models and conducting additional experiments are the most common future work discussions in the studies.
        </div>
        </div>
    </li>
    <br>
     <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/9426000">Characterizing Duplicate Bugs: An Empirical Analysis</a>
            <br><i>Berfin Küçük, Eray Tüzün</i>
            <br>The Third International Workshop On Intelligent Bug Fixing, 2021
            <br><button data-toggle="collapse" data-target="#demo1">See Abstract</button><br>

            <div id="demo1" class="collapse">
            Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively.

        </div>
        </div>
    </li>
        <br>

   <li>
        <div style="text-align: justify">
            <a href="https://www.sciencedirect.com/science/article/pii/S0950584920300021">RSTrace+: Reviewer Suggestion using Software Artifact Traceability Graphs</a>
            <br><i>Emre Sülün, Eray Tüzün, Uğur Doğrusöz</i>
            <br>Information and Software Technology, 2020
            <br><button data-toggle="collapse" data-target="#demo2">See Abstract</button><br>

            <div id="demo2" class="collapse">
            <br>Context:<br>
            Various types of artifacts (requirements, source code, test cases, documents, etc.) are produced throughout the lifecycle of a software. These artifacts are connected with each other via traceability links that are stored in modern application lifecycle management repositories. Throughout the lifecycle of a software, various types of changes can arise in any one of these artifacts. It is important to review such changes to minimize their potential negative impacts. To make sure the review is conducted properly, the reviewer(s) should be chosen appropriately.

            <br>Objective:<br>
            We previously introduced a novel approach, named RSTrace, to automatically recommend reviewers that are best suited based on their familiarity with a given artifact. In this study, we introduce an advanced version of RSTrace, named RSTrace+ that accounts for recency information of traceability links including practical tool support for GitHub.

            <br>Methods:<br>
            In this study, we conducted a series of experiments on finding the appropriate code reviewer(s) using RSTrace+ and provided a comparison with the other code reviewer recommendation approaches.

            <br>Results:<br>
            We had initially tested RSTrace+ on an open source project (Qt 3D Studio) and achieved a top-3 accuracy of 0.89 with an MRR (mean reciprocal ranking) of 0.81. In a further empirical evaluation of 40 open source projects, we compared RSTrace+ with Naive-Bayes, RevFinder and Profile based approach, and observed higher accuracies on the average.

            <br>Conclusion:<br>
            We confirmed that the proposed reviewer recommendation approach yields promising top-k and MRR scores on the average compared to the existing reviewer recommendation approaches. Unlike other code reviewer recommendation approaches, RSTrace+ is not limited to recommending reviewers for source code artifacts and can potentially be used for recommending reviewers for other types of artifacts. Our approach can also visualize the affected artifacts and help the developer to make assessments of the potential impacts of change to the reviewed artifact.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://dl.acm.org/doi/10.1145/3368089.3417932">CRSG: A Serious Game for Teaching Code Review</a>
            <br><i>Kaan Ünlü, Barış Ardıç, Eray Tüzün</i>
            <br>ESEC/FSE 2020 Tool Demonstrations Track, 2020
            <br><button data-toggle="collapse" data-target="#demo3">See Abstract</button><br>

            <div id="demo3" class="collapse">
            The application of code review in a development environment is essential, but this skill is not taught very often in an educational context despite its wide usage. To streamline the teaching process of code review, we propose a browser based "Code Review Serious Game" (CRSG) with high accessibility, progressive level difficulty and an evolvable foundation for prospective improvements or changes. The application is built as a serious game to reinforce the learning experience of its users by immersing them in its story and theme, helping them learn while having fun. The effectiveness of the game components are measured with a case study of 132 students of 2 software engineering courses. The promising result of this case study suggests CRSG can indeed be used effectively to teach code review. The demo video for the game can be accessed at https://youtu.be/FLnr3p4bhOg, and CRSG itself at: https://github.com/barisardic/crsg.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/publication/343712903_Identifying_Key_Developers_using_Artifact_Traceability_Graphs"> Identifying Key Developers using Artifact Traceability Graphs</a>
            <br><i>H.Alperen Çetin, Eray Tüzün</i>
            <br>16th International Conference on Predictive Modeling in Software Engineering (PROMISE 2020)
            <br><button data-toggle="collapse" data-target="#demo4">See Abstract</button><br>

            <div id="demo4" class="collapse">
            Developers are the most important resource to build and maintain software projects. Due to various reasons, some developers take more responsibility, and this type of developers are more valuable and indispensable for the project. Without them, the success of the project would be at risk. We use the term key developers for these essential and valuable developers, and identifying them is a crucial task for managerial decisions such as risk assessment for potential developer resignations. We study key developers under three categories: jacks, mavens and connectors. A typical jack (of all trades) has a broad knowledge of the project, they are familiar with different parts of the source code, whereas mavens represent the developers who are the sole experts in specific parts of the projects. Connectors are the developers who involve different groups of developers or teams. They are like bridges between teams.

            To identify key developers in a software project, we propose to use traceable links among software artifacts such as the links between change sets and files. First, we build an artifact traceability graph, then we define various metrics to find key developers. We conduct experiments on three open source projects: Hadoop, Hive and Pig. To validate our approach, we use developer comments in issue tracking systems and demonstrate that the identified key developers by our approach match the top commenters up to 92%.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/9206173">Creation of a Serious Game For Teaching Code Review: An Experience Report</a>
            <br><i>Barış Ardıç, İrem Yurdakul, Eray Tüzün</i>
            <br>32nd IEEE International Conference on Software Engineering Education & Training (CSEE&T 2020)
            <br><button data-toggle="collapse" data-target="#demo5">See Abstract</button><br>

            <div id="demo5" class="collapse">
            Code review, a manual inspection of source code by developers other than the author, is a frequently used practice for improving code quality in the software development life-cycle. Employing a tool-based review of code changes has become the norm for a wide variety of open source and industrial systems. Despite its widespread usage and importance, software development practices such as code review are often not addressed in typical Software Engineering education. To address this knowledge gap, we propose to use a serious game approach for teaching code review practices. In this study, we define our learning objectives and design a code review serious game along with its companion quizzes. Then we conduct a small preliminary experiment in order to procure feedback. Using the results of the experiment and participant interviews, we improve our game prototype for integration into a software engineering course while optimizing the initial experiment for student's benefit. We document the process, lessons learned and the future directions of the game. The results we gather indicate that the game is ready to be used in a software engineering course setting.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://dl.acm.org/doi/abs/10.1145/3360497">Understanding the knowledge gaps of software engineers: An empirical analysis based on SWEBOK </a>
            <br><i>Vahid Garouisi,  Görkem Giray, Eray Tüzün</i>
            <br>ACM Transactions on Computing Education, 2019
            <br><button data-toggle="collapse" data-target="#demo6">See Abstract</button><br>

            <div id="demo6" class="collapse">
            <br>Context:<br>
            Knowledge level and productivity of the software engineering (SE) workforce are the subject of regular discussions among practitioners, educators, and researchers. There have been many efforts to measure and improve the knowledge gap between SE education and industrial needs.

            <br>Objective:<br>
            Although the existing efforts for aligning SE education and industrial needs have provided valuable insights, there is a need for analyzing the SE topics in a more “fine-grained” manner; i.e., knowing that SE university graduates should know more about requirements engineering is important, but it is more valuable to know the exact topics of requirements engineering that are most important in the industry.

            <br>Method:<br>
            We achieve the above objective by assessing the knowledge gaps of software engineers by designing and executing an opinion survey on levels of knowledge learned in universities versus skills needed in industry. We designed the survey by using the SE knowledge areas (KAs) from the latest version of the Software Engineering Body of Knowledge (SWEBOK v3), which classifies the SE knowledge into 12 KAs, which are themselves broken down into 67 subareas (sub-KAs) in total. Our analysis is based on (opinion) data gathered from 129 practitioners, who are mostly based in Turkey.

            <br>Results:<br>
            Based on our findings, we recommend that educators should include more materials on software maintenance, software configuration management, and testing in their SE curriculum. Based on the literature as well as the current trends in industry, we provide actionable suggestions to improve SE curriculum to decrease the knowledge gap.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/8870190">Investigating the Validity of Ground Truth in Code Reviewer Recommendation Studies </a> (Best Emerging Results and Vision Paper Award)
            <br><i>Emre Doğan,  Eray Tüzün,  K. Ayberk Tecimer  and  H. Altay Güvenir</i>
            <br>13th ACM/IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM 2019)
            <br><button data-toggle="collapse" data-target="#demo7">See Abstract</button><br>

            <div id="demo7" class="collapse">
            Background: Selecting the ideal code reviewer in modern code review is a crucial first step to perform effective code reviews. There are several algorithms proposed in the literature for recommending the ideal code reviewer for a given pull request. The success of these code reviewer recommendation algorithms is measured by comparing the recommended reviewers with the ground truth that is the assigned reviewers selected in real life. However, in practice, the assigned reviewer may not be the ideal reviewer for a given pull request.Aims: In this study, we investigate the validity of ground truth data in code reviewer recommendation studies.Method: By conducting an informal literature review, we compared the reviewer selection heuristics in real life and the algorithms used in recommendation models. We further support our claims by using empirical data from code reviewer recommendation studies.Results: By literature review, and accompanying empirical data, we show that ground truth data used in code reviewer recommendation studies is potentially problematic. This reduces the validity of the code reviewer datasets and the reviewer recommendation studies. Conclusion: We demonstrated the cases where the ground truth in code reviewer recommendation studies are invalid and discussed the potential solutions to address this issue.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://dl.acm.org/doi/10.1145/3345629.3345637">Reviewer Recommendation Using Software Artifact Traceability Graphs </a>
            <br><i>Emre Sülün, Eray Tüzün, Uğur Doğrusöz</i>
            <br>15th International Conference on Predictive Models and Data Analytics in Software Engineering - PROMISE '19, 2019
            <br><button data-toggle="collapse" data-target="#demo8">See Abstract</button><br>

            <div id="demo8" class="collapse">
            Various types of artifacts (requirements, source code, test cases, documents, etc.) are produced throughout the lifecycle of a software. These artifacts are often related with each other via traceability links that are stored in modern application lifecycle management repositories. Throughout the lifecycle of a software, various types of changes can arise in any one of these artifacts. It is important to review such changes to minimize their potential negative impacts. To maximize benefits of the review process, the reviewer(s) should be chosen appropriately.

            In this study, we reformulate the reviewer suggestion problem using software artifact traceability graphs. We introduce a novel approach, named RSTrace, to automatically recommend reviewers that are best suited based on their familiarity with a given artifact. The proposed approach, in theory, could be applied to all types of artifacts. For the purpose of this study, we focused on the source code artifact and conducted an experiment on finding the appropriate code reviewer(s). We initially tested RSTrace on an open source project and achieved top-3 recall of 0.85 with an MRR (mean reciprocal ranking) of 0.73. In a further empirical evaluation of 37 open source projects, we confirmed that the proposed reviewer recommendation approach yields promising top-k and MRR scores on the average compared to the existing reviewer recommendation approaches.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://dl.acm.org/citation.cfm?id=3342487">
                Identifying the Most Valuable Developers Using Artifact Traceability Graphs</a>
            <br><i>H. Alperen Cetin</i>
            <br>In Proceedings of The 27th ACM Joint European Software Engineering Conference and Symposium on the
            Foundations of Software Engineering (ESEC/FSE 2019)
            <br><button data-toggle="collapse" data-target="#demo9">See Abstract</button><br>

            <div id="demo9" class="collapse">
            Finding the most valuable and indispensable developers is a crucial task in software development. We categorize these valuable developers into two categories: connector and maven. A typical connector represents a developer who connects different groups of developers in a large-scale project. Mavens represent the developers who are the sole experts in specific modules of the project.

To identify the connectors and mavens, we propose an approach using graph centrality metrics and connections of traceability graphs. We conducted a preliminary study on this approach by using two open source projects: QT 3D Studio and Android. Initial results show that the approach leads to identify the essential developers.

</div>
</div>
</li>
<br>
<li>
<div style="text-align: justify">
<a href="https://dl.acm.org/doi/10.1145/3338906.3342507">
Suggesting Reviewers of Software Artifacts Using Traceability Graphs</a>
<br><i>Emre Sülün</i>
<br>In Proceedings of The 27th ACM Joint European Software Engineering Conference and Symposium on the
Foundations of Software Engineering (ESEC/FSE 2019)
<br><button data-toggle="collapse" data-target="#demo10">See Abstract</button><br>

            <div id="demo10" class="collapse">
            During the lifecycle of a software project, software artifacts constantly change. A change should be peer-reviewed to ensure the software quality. To maximize the benefit of review, the reviewer(s) should be chosen appropriately. However, choosing the right reviewer(s) might not be trivial especially in large projects. Researchers developed different methods to recommend reviewers. In this study, we introduce a novel approach for reviewer recommendation problem. Our approach utilizes the traceability graph of a software project and assigns a know-about score to each developer, then recommends the developers who have the maximum know-about score for an artifact. We tested our approach on an open source project and achieved top-3 recall of 0.85 with an MRR (mean reciprocal ranking) of 0.73.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.sciencedirect.com/science/article/pii/S0164121219301347?dgcid=author">Aligning software
                engineering education with industrial needs: a meta-analysis </a>
            <br><i>Vahid Garousi, Görkem Giray, Eray Tüzün, Cagatay Catal, Michael Felderer</i>
            <br>Journal of Systems and Software,2019
            <br><button data-toggle="collapse" data-target="#demo11">See Abstract</button><br>

            <div id="demo11" class="collapse">
             <br>Context <br>
            According to various reports, many software engineering (SE) graduates often face difficulties when beginning their careers, which is mainly due to misalignment of the skills learned in university education with what is needed in the software industry.

             <br>Objective <br>
            Our objective is to perform a meta-analysis to aggregate the results of the studies published in this area to provide a consolidated view on how to align SE education with industry needs, to identify the most important skills and also existing knowledge gaps.

             <br>Method <br>
            To synthesize the body of knowledge, we performed a systematic literature review (SLR), in which we systematically selected a pool of 35 studies and then conducted a meta-analysis using data extracted from those studies.

             <br>Results <br>
            Via a meta-analysis and using data from 13 countries and over 4,000 data points, highlights of the SLR include: (1) software requirements, design, and testing are the most important skills; and (2) the greatest knowledge gaps are in configuration management, SE models and methods, SE process, design (and architecture), as well as in testing.

             <br>Conclusion <br>
            This paper provides implications for both educators and hiring managers by listing the most important SE skills and the knowledge gaps in the industry.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a
                href="https://www.researchgate.net/publication/330222041_Catching_up_with_Method_and_Process_Practice_An_Industry-Informed_Baseline_for_Researchers">Catching
                up with Method and Process Practice: A new Baseline for Researchers </a>
            <br><i>HELENA Consurtium</i>
            <br>International Conference on Software Engineering in Practice, 2019
            <br><button data-toggle="collapse" data-target="#demo13">See Abstract</button><br>

            <div id="demo13" class="collapse">
            Software development methods are usually not applied by the book. Companies are under pressure to continuously deploy software products that meet market needs and stakeholders’ requests. To implement efficient and effective development processes, companies utilize multiple frameworks, methods and practices, and combine these into hybrid methods. A common combination contains a rich management framework to organize and steer projects complemented with a number of smaller practices providing the development teams with tools to complete their tasks. In this paper, based on 732 data points collected through an international survey, we study the software development process use in practice. Our results show that 76.8% of the companies implement hybrid methods. Company size as well as the strategy in devising and evolving hybrid methods affect the suitability of the chosen process to reach company or project goals. Our findings show that companies that combine planned improvement programs with process evolution can increase their process’ suitability by up to 5%.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.sciencedirect.com/science/article/pii/S0164121218302565">Adopting Integrated
                Application Lifecycle Management within a Large-Scale Software Company: An Action Research Approach </a>
            <br><i>Eray Tuzun, Bedir Tekinerdogan, Yagup Macit, Kursat Ince</i>
            <br>Journal of Systems and Software, 2018
            <br><button data-toggle="collapse" data-target="#demo14">See Abstract</button><br>

            <div id="demo14" class="collapse">
            <br>Context<br>
            Application Lifecycle Management (ALM) is a paradigm for integrating and managing the various activities related to the governance, development and maintenance of software products. In the last decade, several ALM tools have been proposed to support this process, and an increasing number of companies have started to adopt ALM.

            <br>Objective<br>
            We aim to investigate the impact of adopting ALM in a real industrial context to understand and justify both the benefits and obstacles of applying integrated ALM.

            <br>Method<br>
            As a research methodology, we apply action research that we have carried out within HAVELSAN, a large-scale IT company. The research was carried out over a period of seven years starting in 2010 when the ALM initiative has been started in the company to increase productivity and decrease maintenance costs.

            <br>Results<br>
            The paper presents the results of the action research that includes the application of ALM practices. The transitions among the different steps are discussed in detail, together with the identified obstacles, benefits and lessons learned.

            <br>Conclusions<br>
            Our seven-year study shows that the adoption of ALM processes is not trivial and its success is related to many factors. An important conclusion is that a piecemeal solution as provided by ALM 1.0 is not feasible for the complex process and tool integration problems of large enterprises. Hence the transition to ALM 2.0 was found necessary to cope with the organizational and business needs. Although ALM 2.0 appeared to be a more mature ALM approach, there are still obstacles that need attention from both researchers and practitioners.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://doi.org/10.1049/iet-sen.2018.5144">An Auction-Based Serious Game for Bug Tracking</a>
            <br><i>Cagdas Usfekes, Eray Tuzun, Murat Yılmaz, Yagup Macit, Paul Clarke</i>
            <br>IET Software, 2019
            <br><button data-toggle="collapse" data-target="#demo15">See Abstract</button><br>

            <div id="demo15" class="collapse">
            Today, one of the challenges in software engineering is utilising application lifecycle management (ALM) tools effectively in software development. In particular, it is hard for software developers to engage with the work items that are appointed to themselves in these ALM tools. In this study, the authors have focused on bug tracking in ALM where one of the most important metrics is mean time to resolution that is the average time to fix a reported bug. To improve this metric, they developed a serious game application based on an auction-based reward mechanism. The ultimate aim of this approach is to create an incentive structure for software practitioners to find and resolved bugs that are auctioned where participants are encouraged to solve and test more bugs in less time and improve quality of software development in a competitive environment. They conduct hypothesis tests by performing a Monte Carlo simulation. The preliminary results of this research support the idea that using a gamification approach for an issue tracking system enhances the productivity and decreases mean time to resolution.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://arxiv.org/abs/1812.01954">Closing the gap between software engineering education and
                industrial needs </a>
            <br><i>Vahid Garousi, Görkem Giray, Eray Tüzün, Cagatay Catal, Michael Felderer</i>
            <br>IEEE Software
            <br><button data-toggle="collapse" data-target="#demo16">See Abstract</button><br>

            <div id="demo16" class="collapse">
            Many recent software engineering graduates often face difficulties when beginning their professional careers, due to misalignment of the skills learned in their university education with what is needed in industry. In this article, we report a literature review of the studies that have been done to make improvements on this issue.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://link.springer.com/chapter/10.1007/978-3-319-97925-0_16">Adopting Augmented Reality for the
                Purpose of Software Development Process Training and Improvement: An Exploration </a>
            <br><i>İpek Ohri, İrem Öge, Bora Orkun, Murat Yılmaz, Eray Tüzün, Paul Clarke, RV O’Connor</i>
            <br>European Conference on Software Process Improvement, 195-206
            <br><button data-toggle="collapse" data-target="#demo17">See Abstract</button><br>

            <div id="demo17" class="collapse">
            Augmented reality (AR) is a technological field of study that bridges the physical and digital world together with a view to improving user experience. AR holds great potential to change the delivery of software services or software process improvement by utilizing a specific set of components. The purpose of this exploratory study is to propose an integration framework to support AR for improving the onboarding process, notably in introducing new hires to the development process while performing their daily tasks. In addition, it also aims to enhance the software development workflow process using AR. Similar to a GPS device that can guide you from point A to point B, our goal is to create software artifacts like navigation components where software teams may benefit from digitally enhanced working conditions provided using AR. After conducting a review in the literature, we confirmed that there is lack of studies about the combination of augmented reality with software engineering disciplines for onboarding. In this paper, we formalized our approach based on the benefits of AR. Ultimately; we propose an AR-based preliminary model for improving the software development process.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/publication/320596390_IoT_System_Development_Methods">IoT System
                Development Methods </a>
            <br><i>Görkem Giray, Bedir Tekinerdogan, Eray Tüzün</i>
            <br>Internet of Things: Challenges, Advances and Applications, CRC Press, 2018 (Book Chapter)
            <br><button data-toggle="collapse" data-target="#demo18">See Abstract</button><br>

            <div id="demo18" class="collapse">
            This chapter presents an overview of system development methods (SDMs) dedicated for Internet of Things (IoT) systems. It summarizes IoT SDMs along with their process flows represented using Business Process Model and Notation. The chapter presents the characterization of these methods using the evaluation criteria. The objective of an IoT SDM is to guide a project team in developing and combining these components in order to be able to fulfill user requirements. SDM is preferred over the "software development method" concept since an IoT system encompasses many software, hardware, and communication components. An important aspect in IoT is that changes in the properties of a thing and its corresponding virtual entity need to be synchronized. The IoT Methodology is a generic, lightweight method built on iterative prototyping and Lean start-up approaches. Ignite provides guidance for developing IoT services and software components for IoT devices from a business and project management perspective; however, it does not provide a low-level, technical guidance.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a
                href="https://www.researchgate.net/publication/322272564_Adopting_the_Essence_Framework_to_Derive_a_Practice_Library_for_the_Development_of_IoT_Systems">Adopting
                the Essence Framework to Derive a Practice Library for the Development of IoT Systems </a>
            <br><i>Görkem Giray, Bedir Tekinerdogan, Eray Tüzün</i>
            <br>Connected Environments for the Internet of Things, Challenges and Solutions, Springer International
            Publishing, 2018 (Book Chapter)
            <br><button data-toggle="collapse" data-target="#demo19">See Abstract</button><br>

            <div id="demo19" class="collapse">
            The Internet of Things (IoT) is a global network of smart devices which enables these objects to collect and exchange data. Research in the IoT is still progressing, and it is now being applied in various domains. One of the key observations is that the development of IoT systems is not trivial and needs to be carefully managed to meet the required functional and quality concerns. Due to the heterogeneous aspects including software, hardware, and communication, developing the IoT systems implies various challenges that need to be explicitly considered in the development process and successfully resolved. Unfortunately, less focus has been provided so far on the development methods for the IoT systems. To address the particular IoT development concerns, we analyze and discuss the existing approaches that target the development of IoT systems. For this purpose, we use the Essence Framework, which has been recently developed as a framework for modeling various kinds of software development practices and methods. We propose an initial practice library, which can be used to develop and/or tailor project-specific IoT system development methods.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a
                href="https://www.researchgate.net/publication/322697487_Modeling_Software_Product_Line_Engineering_with_Essence_Framework">Modeling
                Software Product Line Engineering with Essence Framework </a>
            <br><i>Eray Tüzün, Görkem Giray, Bedir Tekinerdogan, Yagup Macit</i>
            <br>International Journal of Informatics Technologies, 2018
            <br><button data-toggle="collapse" data-target="#demo20">See Abstract</button><br>

            <div id="demo20" class="collapse">
            Although several software product line engineering (SPLE) methods have been described in the literature, adopting these methods in practice is often not straightforward. Thorough understanding of the methods and their artefacts is necessary to apply the methods in a proper manner, and likewise realize the expected goals of SPLE. Recently the Essence framework has been proposed to model the essential elements of a method and to support the modeling of a broad set of software development methods including plan-driven methods and agile methods. So far, the Essence framework has been applied to single system development methods and not yet for SPLE methods. To enhance the understanding of SPLE methods and support a vision for tailoring SPLE methods, we provide a mapping of an SPLE method to the Essence framework. We present experiences about modeling an SPLE method using the Essence framework within the industrial context of Havelsan.
        </div>
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://arxiv.org/abs/1805.08894">Are Computer Science and Engineering Graduates Ready for the
                Software Industry? Experiences from an Industrial Student Training Program </a>
            <br><i>Eray Tuzun, Hakan Erdogmus and Izzet Gokhan Ozbilgin</i>
            <br>International Conference in Software Engineering SEET 2018 (Acceptance rate <25%)
            <br><button data-toggle="collapse" data-target="#demo21">See Abstract</button><br>

            <div id="demo21" class="collapse">
            It has  been  50  years  since  the  term  “software  engineering”  was coined  in  1968  at  a  NATO  conference.  The  field  should  be relatively   mature   by   now,   with   most   established   universities coveringcore  software  engineering  topics  in  their  Computer Science   programs   and   others   offering   specialized   degrees. However,  still  many  practitioners  lament  a  lack  of  skills  in  new software   engineering   hires.   With   the   growing   demand   for software  engineers  from  the  industry,  this  apparent  gap  becomes more and more pronounced. One corporate strategy to address this gap   is   for   the   industry   to   develop   supplementary   training programs   before   the   hiring   process,   which   could   also   help companiesscreen  viable  candidates.In  this  paper,  we  report  on our  experiences  and  lessons  learned  in conducting  a  summer school  program  aimed  at  screening  new  graduates,  introducing them to core  skills relevant  to  the  organization  and industry,  and assessing  their  attitudes  toward  mastering  those  skills  before  the hiring   process   begins.   Our   experiencesuggests   that   such initiatives can be mutually beneficial for new hires and companiesalike.  We  support  this  insight  with  pre-and  post-training  data collected  from  the  participants  during  the  first  edition  of thesummer  school  and  a  follow-up  questionnaire  conducted  after  a year  with  the participants,  50%  of  whom werehired  by  the company shortly after the summer school.
        </div>
        </div>
            </li>
            <br>
            <li>
        <div style="text-align: justify">
            <a href="https://doi.org/10.1016/j.infsof.2014.12.007">Empirical evaluation of a decision support model for adopting software product line engineering </a>
            <br><i>Eray Tuzun, Bedir Tekinerdogan, Mert Emin Kalender, Semih Bilgen</i>
            <br>Information and Software Technology
            <br><button data-toggle="collapse" data-target="#demo50">See Abstract</button><br>

            <div id="demo50" class="collapse">
Context: The software product line engineering (SPLE) community has provided several different approaches for assessing the feasibility of SPLE adoption and selecting transition strategies. These approaches usually include many rules and guidelines which are very often implicit or scattered over different publications. Hence, for the practitioners it is not always easy to select and use these rules to support the decision making process. Even in case the rules are known, the lack of automated support for storing and executing the rules seriously impedes the decision making process. 
Objective: We aim to evaluate the impact of a decision support system (DSS) on decision-making in SPLE adoption. In alignment with this goal, we provide a decision support model (DSM) and the corresponding DSS.
Method: First, we apply a systematic literature review (SLR) on the existing primary studies that discuss and present approaches for analyzing the feasibility of SPLE adoption and transition strategies. Second, based on the data extraction and synthesis activities of the SLR, the required questions and rules are derived and implemented in the DSS. Third, for validation of the approach we conduct multiple case studies.
Results: In the course of the SLR, 31 primary studies were identified from which we could construct 25 aspects, 39 questions and 312 rules. We have developed the DSS tool Transit-PL that embodies these elements.
Conclusions: The multiple case study validation showed that the adoption of the developed DSS tool is justified to support the decision making process in SPLE adoption.
        </div>
        </div>
            </li>
            <br>
            <li>
        <div style="text-align: justify">
            <a href="https://doi.org/10.1016/j.infsof.2014.09.008">Analyzing impact of experience curve on ROI in the software product line adoption process </a>
            <br><i>Eray Tuzun, Bedir Tekinerdogan</i>
            <br>Information and Software Technology
            <br><button data-toggle="collapse" data-target="#demo51">See Abstract</button><br>

            <div id="demo51" class="collapse">
Context:
Experience curve is a well-known concept in management and education science, which explains the phenomenon of increased worker efficiency with repetitive production of a good or service.

Objective:
We aim to analyze the impact of the experience curve effect on the Return on Investment (ROI) in the software product line engineering (SPLE) process.

Method:
We first present the results of a systematic literature review (SLR) to explicitly depict the studies that have considered the impact of experience curve effect on software development in general. Subsequently, based on the results of the SLR, the experience curve effect models in the literature, and the SPLE cost models, we define an approach for extending the cost models with the experience curve effect. Finally, we discuss the application of the refined cost models in a real industrial context.

Results:
The SLR resulted in 15 primary studies which confirm the impact of experience curve effect on software development in general but the experience curve effect in the adoption of SPLE got less attention. The analytical discussion of the cost models and the application of the refined SPLE cost models in the industrial context showed a clear impact of the experience curve effect on the time-to-market, cost of development and ROI in the SPLE adoption process.

Conclusions:
The proposed analysis with the newly defined cost models for SPLE adoption provides a more precise analysis tool for the management, and as such helps to support a better decision making.
        </div>
        </div>
            </li>
            <br>
            <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/5291914">Using continuous integration and automated test techniques for a robust C4ISR system </a>
            <br><i>H. Mehmet Yuksel, Eray Tuzun, Erdogan Gelirli, Emrah Biyikli, Buyurman Baykal</i>
            <br>2009 24th International Symposium on Computer and Information Sciences
            <br><button data-toggle="collapse" data-target="#demo52">See Abstract</button><br>

            <div id="demo52" class="collapse">
Context:
We have used CI (Continuous Integration) and various software testing techniques to achieve a robust C4ISR (Command, Control, Communications, Computers, Intelligence, Surveillance, and Reconnaissance) multi-platform system. Because of rapid changes in the C4ISR domain and in the software technology, frequent critical design adjustments and in turn vast code modifications or additions become inevitable. Defect fixes might also incur code changes. These unavoidable code modifications may put a big risk in the reliability of a mission critical system. Also, in order to stay competitive in the C4ISR market, a company must make recurring releases without sacrificing quality.

Objective:
We have designed and implemented an XML driven automated test framework that enabled us developing numerous high quality tests rapidly.

Method:
While using CI with automated software test techniques, we have aimed at speeding up the delivery of high quality and robust software by decreasing integration procedure, which is one of the main bottleneck points in the industry. 

Conclusions:
This work describes how we have used CI and software test techniques in a large-scaled, multi-platform, multi-language, distributed C4ISR project and what the benefits of such a system are.
        </div>
        </div>
            </li>
            <br>
            </ul>
