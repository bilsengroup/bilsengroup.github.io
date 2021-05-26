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
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/publication/343712903_Identifying_Key_Developers_using_Artifact_Traceability_Graphs"> Identifying Key Developers using Artifact Traceability Graphs</a> 
            <br><i>H.Alperen Çetin, Eray Tüzün</i>
            <br>16th International Conference on Predictive Modeling in Software Engineering (PROMISE 2020)
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/9206173">Creation of a Serious Game For Teaching Code Review: An Experience Report</a>
            <br><i>Barış Ardıç, İrem Yurdakul, Eray Tüzün</i>
            <br>32nd IEEE International Conference on Software Engineering Education & Training (CSEE&T 2020)
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://dl.acm.org/doi/abs/10.1145/3360497">Understanding the knowledge gaps of software engineers: An empirical analysis based on SWEBOK </a> 
            <br><i>Vahid Garouisi,  Görkem Giray, Eray Tüzün</i>
            <br>ACM Transactions on Computing Education, 2019
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/8870190">Investigating the Validity of Ground Truth in Code Reviewer Recommendation Studies </a> (Best Emerging Results and Vision Paper Award)
            <br><i>Emre Doğan,  Eray Tüzün,  K. Ayberk Tecimer  and  H. Altay Güvenir</i>
            <br>13th ACM/IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM 2019)
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://dl.acm.org/doi/10.1145/3345629.3345637">Reviewer Recommendation Using Software Artifact Traceability Graphs </a>
            <br><i>Emre Sülün, Eray Tüzün, Uğur Doğrusöz</i>
            <br>15th International Conference on Predictive Models and Data Analytics in Software Engineering - PROMISE '19, 2019
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
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.sciencedirect.com/science/article/pii/S0164121219301347?dgcid=author">Aligning software
                engineering education with industrial needs: a meta-analysis </a>
            <br><i>Vahid Garousi, Görkem Giray, Eray Tüzün, Cagatay Catal, Michael Felderer</i>
            <br>Journal of Systems and Software,2019
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
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.sciencedirect.com/science/article/pii/S0164121218302565">Adopting Integrated
                Application Lifecycle Management within a Large-Scale Software Company: An Action Research Approach </a>
            <br><i>Eray Tuzun, Bedir Tekinerdogan, Yagup Macit, Kursat Ince</i>
            <br>Journal of Systems and Software, 2018 
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://ieeexplore.ieee.org/document/8861461">An Auction-Based Serious Game for Bug Tracking</a>
            <br><i>Cagdas Usfekes, Eray Tuzun, Murat Yılmaz, Yagup Macit, Paul Clarke</i>
            <br>IET Software, 2019
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://arxiv.org/abs/1812.01954">Closing the gap between software engineering education and
                industrial needs </a>
            <br><i>Vahid Garousi, Görkem Giray, Eray Tüzün, Cagatay Catal, Michael Felderer</i>
            <br>IEEE Software
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://link.springer.com/chapter/10.1007/978-3-319-97925-0_16">Adopting Augmented Reality for the
                Purpose of Software Development Process Training and Improvement: An Exploration </a>
            <br><i>İpek Ohri, İrem Öge, Bora Orkun, Murat Yılmaz, Eray Tüzün, Paul Clarke, RV O’Connor</i>
            <br>European Conference on Software Process Improvement, 195-206
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://www.researchgate.net/publication/320596390_IoT_System_Development_Methods">IoT System
                Development Methods </a>
            <br><i>Görkem Giray, Bedir Tekinerdogan, Eray Tüzün</i>
            <br>Internet of Things: Challenges, Advances and Applications, CRC Press, 2018 (Book Chapter)
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
        </div>
    </li>
    <br>
    <li>
        <div style="text-align: justify">
            <a href="https://arxiv.org/abs/1805.08894">Are Computer Science and Engineering Graduates Ready for the
                Software Industry? Experiences from an Industrial Student Training Program </a>
            <br><i>Eray Tuzun, Hakan Erdogmus and Izzet Gokhan Ozbilgin</i>
            <br>International Conference in Software Engineering SEET 2018 (Acceptance rate <25%) </div> </li> </ul>
