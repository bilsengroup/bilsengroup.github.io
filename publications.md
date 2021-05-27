---
layout: post
title: Publications
image: /img/logo.png
---

<ul>
     <li>
        <div style="text-align: justify">
            <a href="">Characterizing Duplicate Bugs: An Empirical Analysis</a>
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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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

			<div id="demo12" class="collapse">
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

		</div>			
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/8861461">An Auction-Based Serious Game for Bug Tracking</a>
            <br><i>Cagdas Usfekes, Eray Tuzun, Murat Yılmaz, Yagup Macit, Paul Clarke</i>
            <br>IET Software, 2019
			<br><button data-toggle="collapse" data-target="#demo15">See Abstract</button><br>

			<div id="demo15" class="collapse">
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

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
			Bug  handling  is  an  essential  part  of  the  softwaredevelopment process. Ideally, in a bug tracking system, bugs arereported,  fixed,  verified,  and  closed.  In  some  cases,  bugs  haveto  be  reopened  mostly  due  to  an  incorrect  fix.  However,  insteadof  reopening  the  existing  bug  report,  users  may  submit  a  newreport on a previously reported bug, which causes duplicate bugreports.  Additionally,  users  might  report  duplicate  bugs  if  theyare unable to reopen the previously reported bugs due to the bugbeing unresolved (i.e., in progress) and when they miss previouslyreported bug reports. These duplicate bug reports may cost extramaintenance  efforts  in  triaging  and  fixing  bugs.There  have  been  several  studies  on  characterizing  reopenedbugs  and  duplicate  bug  reports,  however,  to  the  best  of  ourknowledge,  there  has  been  no  prior  work  on  understanding  thedynamics of their intersection, which ismissed reopenbugs. Ourstudy  is  based  on  analyzing  the  differences  between  duplicateand non-duplicate bugs, and further categorizing the duplicatedbugs.  In  this  regard,  we  categorize  duplicate  bugs  accordingto  their  creation  time  with  respect  to  their  master’s  resolutionstatus  as  Master-Unresolved  bugs  and  Master-Resolved  (MissedReopen  bugs)  to  distinguish  their  properties.  We  compare  thesetwo  different  types  of  bugs  in  terms  of  various  aspects  such  astheir  relationships  to  their  master  bugs,  bug  surface  time,  bugfix  time,  bug’s  severity,  and  the  number  of  users  involved.  Weperform case studies using the Eclipse and Mozilla projects’ bugrepositories  that  include  more  than  165,500  and  394,000  bugreports  respectively. 

		</div>			
			</div> 
			</li> 
			</ul>
			
