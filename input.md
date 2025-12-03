> **Acknowledgement**
>
> I would like to deeply acknowledge my distinguished supervisors, Mr.
>
> Supervisor and Mr. Supervisor, for guiding and providing me with any
> kind of
>
> support needed through the various phases of the project.
>
> Mr. Supervisor's oversight has been essential in providing academic
>
> direction and guaranteeing the project satisfies all requirements.
> Similarly, Mr.
>
> Supervisor's supervision and skills, with the important industry
> insights and a
>
> wider viewpoint he provided have helped me improve my project idea a
> lot. My
>
> sincere appreciation goes out to both supervisors for their
> encouragement and
>
> assistance in exploring new research directions, as well as their
> continuous and

insightful feedback.

> Finally, I would like to express my profound appreciation to Islington
> College for providing me with an opportunity to explore, learn and
> work in my field of interest.

**Abstract**

> The increasing importance of computer networks has increased the need
> for

effective and user-friendly network monitoring and packet analysis
tools. Even though strong tools like Wireshark and Zeek are currently
available, individuals with limited technical knowledge may find them
challenging to utilize due to their complexity. In order toclosethis
gap, this project proposes developingtheNetwork Packet Visualizer Tool,
a web-based program that offers an easy-to-use interface for network
monitoring and packet analysis.

> The application uses Zeek-generated logs to extract useful information
> and

displays them in an easy-to-understand dashboardthat iseasyto use
forboth network experts and regular users. Real-time data visualization,
threat detection, warnings, and notifications for anomalous network
activity are some of the key features.

Using the Agile methodology's Scrum framework, the project focuses on
adaptability, transparency, and iterative development. By improving
network data accessibility and understanding, the end result aims to
improve user experience and overall network security. This report covers
the goals, objectives, methods, risk management techniques, milestones,
and expected outcomes of the project.

**Table** **of** **Contents**

1\.
Introduction.........................................................................................................1

> 1.1 Problem Scenario
> ........................................................................................2
>
> 1.2 Project as a
> Solution....................................................................................4

2\. Aim and
Objectives.............................................................................................5

> 2.1
> Aim...............................................................................................................5
>
> 2.2
> Objectives....................................................................................................5

3\. Expected Outcomes and
Deliverables................................................................6

> 3.1
> Deliverables......................................................................................................6

4\. Project Risks, Threats and Contingency Plans
...................................................7

> 4.1 Project Risks and
> Threats............................................................................7
>
> 4.1.1 Zeek’s Functionality in
> Windows...........................................................7
>
> 4.1.2 Complex User
> Interface........................................................................7
>
> 4.1.3 Security
> Vulnerabilities..........................................................................7
>
> 4.1.4 Performance
> Bottleneck........................................................................7
>
> 4.1.5 Inadequate
> Testing...............................................................................7
>
> 4.2 Contingency
> Plans.......................................................................................8
>
> 4.2.1 Zeek’s Functionality in
> Windows...........................................................8
>
> 4.2.2 Complex User
> Interface........................................................................8
>
> 4.2.3 Security
> Vulnerabilities..........................................................................8
>
> 4.2.4 Performance
> Bottleneck........................................................................8
>
> 4.2.5 Inadequate
> Testing...............................................................................8

5\.
Methodologies.....................................................................................................9

> 5.1 Considered Methodologies
> ........................................................................10
>
> 5.1.1 Agile
> Methodology..............................................................................10
>
> 5.1.2 RUP
> Methodology...............................................................................11
>
> 5.1.3 Prototype
> Model..................................................................................12
>
> 5.2 Selected Methodology
> ...............................................................................13
>
> 5.2.1 Agile Methodology- Scrum
> Framework...............................................13

6\. Resource Requirements
...................................................................................15

> 6.1 Hardware
> Requirements............................................................................15
>
> 6.2 Software Requirements
> .............................................................................15

7\. Work Breakdown
Structure...............................................................................17

8\.
Milestones.........................................................................................................18

9\. Project Gantt Chart
...........................................................................................20

> 9.1 Project Gantt Chart – List
> View..................................................................22

10\.
Conclusion.....................................................................................................25

11\.
References....................................................................................................26

12\. Appendix
.......................................................................................................28

> 12.1 RUP
> Methodology......................................................................................28
>
> 12.1.1 Circumstances to use RUP Methodology
> ...........................................28
>
> 12.1.2 Advantages of RUP
> Methodology.......................................................29
>
> 12.1.3 Disadvantages of RUP
> Methodology..................................................29
>
> 12.2 Prototype
> Model.........................................................................................30
>
> 12.2.1 Circumstances to use Prototype Model
> ..............................................30
>
> 12.3 Agile Software Development
> Frameworks.................................................31
>
> 12.3.1 Scrum Framework
> ..............................................................................32
>
> 12.3.2 Reasons for Selecting Scrum
> Framework...........................................33
>
> 12.4 Work Breakdown
> Structure........................................................................34
>
> 12.5 Project Gantt
> Chart....................................................................................35

**Table** **of** **Figures**

Figure 1: Complexity of Wireshark.
............................................................................2

Figure 2:
Zeek............................................................................................................3
Figure 3: Software Development Life Cycle (Sandamal,
2020)..................................9 Figure 4: Agile Methodology
(nvsia learn,
2020)......................................................10 Figure 5:
RUP Methodology (Agile Lone Star, 2024).
..............................................11 Figure 6: Prototype
Model........................................................................................12
Figure 7: Three Pillars of
Scrum...............................................................................14
Figure 8: Work Breakdown Structure.
......................................................................17
Figure 9: Project Milestone
Map...............................................................................19
Figure 10: Project Gantt Chart.
................................................................................21
Figure 11: Phases of RUP
Methodology..................................................................28
Figure 12: Steps of Prototype
Model........................................................................30
Figure 13: Principles of Agile
Methodology..............................................................31
Figure 14: Scrum
Framework...................................................................................32

**Table** **of** **Tables**

Table 1: Software
Requirements..............................................................................16

Table 2: Project Milestone
Table..............................................................................19

CS6P05NI Final Year Project

**1.** **Introduction**

In today's interconnected world, computer networks are the backbone of
today's society, allowing for smooth communication, information
exchange, and collaboration. In the current state of information
technology development, security plays a significant role in computer
network applications (Zhang, 2024).

> Computer networks are particularly important today for communication
> and

information flow because they allow for the easy transfer of digital
data between interconnected computing devices. Computer networks are
essentially systems of nodes that are connected in a unique way. Recent
improvements in computer, software, and networking technology have led
to a significant increase in the amount of time people spend online (H,
et al., 2024).

The use of computer networks is now far more widespread than it has ever
been thanks to major advancements in the field and the internet's
technology, which has expanded at a remarkable pace. Similarly, with the
growth of networks, network security is growing more and more crucial as
the next most crucial component of a system. Monitoring network traffic
and analyzing it is a challenging task that is often handled by highly
skilled technical professionals such as network engineers and security
analysts (Zhang, 2024).

1 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./s3itxwen.png"
style="width:6.26805in;height:4.65556in" />

**1.1** **Problem** **Scenario**

While advanced network analysis can be obtained with existing tools such
as Wireshark,userswith limited knowledge of network protocols will not
be ableto benefit from them. To put it another way, understanding how a
network functions is essential to being able to use Wireshark correctly
(CompTIA, 2024).

> *Figure* *1:* *Complexity* *of* *Wireshark.*

Similarly, Zeek; an open-source network security monitoring tool, is an
advanced tool used for packet/ traffic analysis, it was primarily built
for the Unix-based systems and is CLI- based. It produces different
types of logs which only an experienced network professional can
understand. The logs produced by Zeek can be used to detect abnormal
activities in a network. Furthermore, it does not offer any kind of
visualization, which makes it difficult for even network professionals
to understand.

2 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./zpyclrvu.png"
style="width:6.26805in;height:3.27708in" />

> *Figure* *2:* *Zeek*

This leaves room wide open for general users to not be able to see if
their network is up, troubleshoot connectivity problems, or even
identify if they may have a security threat on their network.

3 LMU ID \| Student Name

CS6P05NI Final Year Project

**1.2** **Project** **as** **a** **Solution**

In order to bridge the gap, Network Packet Visualizer Tool offers a
straightforward web-based application for packet analysis and
visualization. The project's goal is to make data from network traffic
graphs readable to all consumers, regardless of technical expertise
using the logs extracted from network analysis tools such as Zeek.

> Network Packet Visualizer Tool will use the logs produced by Zeek to
> extract the

required information and visualize them in a web application which will
make packet analysis and network monitoring easier both for the general
users as well as network professionals.

> An easy-to-use dashboard providing instant access to information on
> network and

bandwidth usage, connected users, and their activities for ordinary
users will be provided. Network Packet Visualizer Tool provides
analytics features related to threat detection, and comprehensive
insight on actual packetsfor advanced users. It will also send alerts
and notifications to users upon detecting unusual network activity. By
transforming unprocessed network data into graphical insights, Network
Packet Visualizer Tool helps users visualize and monitor their network
environment; even for users who have limited knowledge of network.

4 LMU ID \| Student Name

CS6P05NI Final Year Project

**2.** **Aim** **and** **Objectives**

**2.1** **Aim**

The aim of Network Packet Visualizer Tool is to fill the gap of the
existing tools and develop a comprehensive and accessible packet
visualization tool that simplifies network monitoring and enhances
understanding for both general users and network professionals based on
the logs extracted from networking analysis tools like Zeek.

**2.2** **Objectives**

i\. To develop packet visualization tool that would make network
monitoring easier

> to be understood and to be used by people who are generally not
> familiar with networks or to the professionals.

ii\. To integrate features such as visual representation of parameters
like packet loss, current bandwidth and the number of connected devices.

iii\. To develop the backend of log parsing using Python.

iv\. To implement a system to send alerts and notifications to users
upon detecting unusual network activity.

v\. To complete all the milestones in the given time ensuring the
successful completion of the project.

5 LMU ID \| Student Name

CS6P05NI Final Year Project

**3.** **Expected** **Outcomes** **and** **Deliverables**

> The mainobjectiveofthis projectis to develop an all-inclusive tool;
> Network Packet

Visualizer Tool that is capable of packet analysis and visualization.
The expected outcome is a web application meant for making packet
analysis and network monitoring easier both for the general users as
well as network professionals. It is expected that it will have
real-time data visualization ability as well as threat detection and
advanced analysis features.

**3.1** **Deliverables**

> The features of Network Packet Visualizer Tool are listed below:

• Dashboard Interface:

> An easy-to-use dashboard providing instant access to information on
> network and bandwidth usage, connected users, and their activities for
> ordinary users.

• Tools for Data Visualization:

> Dynamic and interactive visual components, such as charts, and graphs,
> that present important information in an understandable way, such as
> device connections, bandwidth utilization, packet flow, and quality of
> the network.

• Advanced Network Analysis Features:

> Advanced features with real-time threat identification, traffic port
> analysis, IP reputation, and country flagging designed for network
> professionals.

• Notification and Alert System:

> Acomprehensive alert systemdesigned for users to promptly identify and
> deal with possible risks by providing real-time alerts and
> notifications of abnormal network activity.

6 LMU ID \| Student Name

CS6P05NI Final Year Project

**4.** **Project** **Risks,** **Threats** **and** **Contingency**
**Plans**

> Risks and threats may arise throughout project development, as all
> systems are

subject to them. In order minimize systemic defects, the following risks
and threats are addressed together with contingency plans.

**4.1** **Project** **Risks** **and** **Threats**

> Below mentioned are the risks and threats that may arise during the
> development

of the project:

**4.1.1** **Zeek’s** **Functionality** **in** **Windows**

> Zeek was originally designed for Unix. Zeek has an experimental
> version for

Windows, which is not fully reliable.

**4.1.2** **Complex** **User** **Interface**

> General users may find the interface overwhelming or difficult to
> navigate, leading

to poor adoption.

**4.1.3** **Security** **Vulnerabilities**

The application could be vulnerable to cyberattacks, leading to data
breaches or unauthorized access.

**4.1.4** **Performance** **Bottleneck**

Visualization tools struggle to display large amounts of data, also
delay in data processing which could prevent users from receiving alerts
in time.

**4.1.5** **Inadequate** **Testing**

Insufficient testing of the application’s features may lead to bugs or
usability issues, affecting the final product’s quality and user
experience.

7 LMU ID \| Student Name

CS6P05NI Final Year Project

**4.2** **Contingency** **Plans**

Below mentioned are the contingency plans addressed with respect to the
risks and threats mentioned above that may arise during the development
process:

**4.2.1** **Zeek’s** **Functionality** **in** **Windows**

Since Zeek in Windows is an experimental version, switch to Linux to
avoid experimenting on the experiment.

**4.2.2** **Complex** **User** **Interface**

> To mitigate the risk of user interface complexity, use general user
> testing to get

feedback during design to make navigating easier. Improve simplicity by
navigating the design in response to user feedback.

**4.2.3** **Security** **Vulnerabilities**

Conduct regular security audits. Use up-to-date security software,
conduct vulnerability assessments, and have a response plan in place.

**4.2.4** **Performance** **Bottleneck**

Design the architecturefor horizontal scaling and optimizebackend
processing for efficiency. Use light visualization libraries.

**4.2.5** **Inadequate** **Testing**

Adopt a test first approach, where write unit tests for the backend
functionality and perform usability testing for frontend features.

8 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./g3m4sthe.png"
style="width:5.73333in;height:5.73333in" />

**5.** **Methodologies**

> The software development process must follow precise, well-considered

procedures in a reliable plan in order to meet the needs necessary for
any project to be successful. Software development life cycle (SDLC)
methodologies have provided several models that comply with the needs of
the various proposed projects. These methodologies offer a range of
situations that can be used when developing systems to increase their
effectiveness and predictability (ALazzawi, et al., 2023).

> *Figure* *3:* *Software* *Development* *Life* *Cycle* *(Sandamal,*
> *2020).*

9 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./lwi3dj0h.png"
style="width:6.26805in;height:3.58958in" />

**5.1** **Considered** **Methodologies**

Prior to initiating the project, a variety of methodologies were studied
and taken into consideration, with their individual benefits being
weighed and matched to the objectives of the project.

**5.1.1** **Agile** **Methodology**

> Agile methodology is a series of incremental and iterative techniques
> that puts

adaptability and customer engagement first. Agile projects are broken up
into brief iterations known as sprints rather than following a straight
line (Hossain, 2024).

> *Figure* *4:* *Agile* *Methodology* *(nvsia* *learn,* *2020).*

For more information on Agile Methodology, visit <u>Appendix 12.3</u>.

10 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./yyp0oajo.png"
style="width:6.26805in;height:4.03056in" />

**5.1.2** **RUP** **Methodology**

> A Rational Unified Process is a software engineering approach for
> distributing

tasks and responsibilities inside the software development organization.
Its main goal is to make it possible to produce high-quality software
that meets end users' needs on a predictable budget and schedule
(Kanjilal, 2022).

> *Figure* *5:* *RUP* *Methodology* *(Agile* *Lone* *Star,* *2024).*

For more information on RUP Methodology, visit <u>Appendix 12.1</u>.

11 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./4iuwehml.png"
style="width:6.26805in;height:3.92292in" />

**5.1.3** **Prototype** **Model**

> The Prototyping Model is a software development process model that
> focuses

on quickly building a functioning model or prototype of software in
order to receive user feedback and improve requirements prior to
developing the final product (Hossain, 2024).

> *Figure* *6:* *Prototype* *Model.*

For more information on Prototype Model, visit <u>Appendix 12.2</u>.

12 LMU ID \| Student Name

CS6P05NI Final Year Project

**5.2** **Selected** **Methodology**

Among the different methodologies that were taken into consideration,
the Scrum Framework of Agile Methodology was chosen for the project.

**5.2.1** **Agile** **Methodology-** **Scrum** **Framework**

The Scrum Framework was chosen given that it can provide an organized
yet flexible approach to developing the packet analysis tool; Network
Packet Visualizer Tool, facilitating effective advancement through its
three pillars: Transparency, Inspection, and Adaptation.

The primary reasons for choosing Scrum Framework with respect to the
three pillars are outlined below:

• **Transparency:**

> Scrum places a strong emphasis on transparency through its various
> artifacts, including the Increment, Product Backlog, and Sprint
> Backlog. Through transparency, it will be easier to keep track of how
> the project is progressing. (Schwaber & Sutherland, 2020).

• **Inspection:**

> Through its five events (Sprint Planning, Daily Scrum, Sprint Review,
> Sprint Retrospective, and the Sprint itself), Scrum offers frequent
> inspection opportunities. This enables us to monitor the progress of
> the project on a regular basis, identify problems early, and make the
> required corrections (Schwaber & Sutherland, 2020).

• **Adaptation:**

> The flexibility of Scrum enables us to quickly modify the procedure or
> final product if any aspect of the project deviates from the
> anticipated result. It guarantees that we can quickly handle any
> alterations and maintain the project's progress to provide a
> high-quality product (Schwaber & Sutherland, 2020).

For more information on the reasons behind choosing Scrum Framework,
visit <u>Appendix 12.3.2.</u>

13 22066999 \| Student Name

CS6P05NI Final Year Project<img src="./v3us0myd.png"
style="width:6.26805in;height:3.31111in" />

> *Figure* *7:* *Three* *Pillars* *of* *Scrum.*

For more information on the Scrum Framework, visit <u>Appendix
12.3.1</u>.

14 LMU ID \| Student Name

CS6P05NI Final Year Project

**6.** **Resource** **Requirements**

> Below are the hardware and software components that will be utilized
> to launch the

project and develop the project.

**6.1** **Hardware** **Requirements**

The hardware requirements are mentioned below:

a\) Development Machine:

> Personal device will be used as a development machine.

**6.2** **Software** **Requirements**

The software requirements are mentioned below:

||
||
||
||
||
||
||
||
||
||
||

15 LMU ID \| Student Name

CS6P05NI Final Year Project

||
||
||
||
||
||

> *Table* *1:* *Software* *Requirements*

16 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./fevmuzfq.png"
style="width:6.26805in;height:2.6875in" />

**7.** **Work** **Breakdown** **Structure**

> *Figure* *8:* *Work* *Breakdown* *Structure.*

For the enlarged and clear view of WBS, visit <u>Appendix 12.4</u>.

17 LMU ID \| Student Name

CS6P05NI Final Year Project

**8.** **Milestones**

||
||
||
||
||
||
||
||
||

18 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./utyhezeu.png"
style="width:6.26805in;height:4.70139in" />

||
||
||
||

> *Table* *2:* *Project* *Milestone* *Table.*
>
> *Figure* *9:* *Project* *Milestone* *Map.*

19 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./x1tx5zol.png"
style="width:6.30486in;height:9.04292in" />

**9.** **Project** **Gantt** **Chart**

20 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./1shfn4a3.png"
style="width:6.00889in;height:3.49097in" />

> *Figure* *10:* *Project* *Gantt* *Chart.*

For the clear view of Project Gantt Chart, visit <u>Appendix 12.5</u>.

21 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./uhf2byu5.png"
style="width:6.40528in;height:2.85139in" /><img src="./dynpi5to.png"
style="width:6.35778in;height:3.0993in" /><img src="./mh0er2vc.png"
style="width:6.26805in;height:1.11736in" /><img src="./5zhrif1y.png"
style="width:6.26805in;height:1.36458in" />

**9.1** **Project** **Gantt** **Chart** **–** **List** **View**

22 LMU ID \| Student Name

CS6P05NI<img src="./u1uhwxxg.png"
style="width:6.4243in;height:0.82564in" /><img src="./mcnhhi2d.png"
style="width:6.57292in;height:3.06653in" /><img src="./pmk4pnfo.png"
style="width:6.56944in;height:2.50806in" /><img src="./yxgydxhr.png"
style="width:6.49792in;height:2.23319in" />

LMU ID \| Student Name

Final Year Project

> 23

CS6P05NI<img src="./xizf1j3e.png"
style="width:6.31806in;height:1.29987in" /><img src="./j3egehjc.png"
style="width:6.26805in;height:2.47361in" />

LMU ID \| Student Name

Final Year Project

> 24

CS6P05NI Final Year Project

**10.** **Conclusion**

> The mainobjectiveofthis projectis to develop an all-inclusive tool;
> Network Packet

Visualizer Tool that is capable of packet analysis and visualization.
This will be accomplished by using scrum framework of agile methodology
that tackles development and delivery in iterations, allowing for a high
degree of flexibility for user needs to be prioritized.

> There are some advanced network analysis tools such as Wireshark and
> Zeek,

which are used by network professionals; but that leaves room for
general users to not be able to see if their network is up, troubleshoot
connectivity problems, or even identify if they may have a security
threat on their network.

The expected outcome is a web application meant for making packet
analysis and network monitoring easier both for the general users as
well as network professionals. It provides an opportunity to fill the
gap in the existing network analysis tool and at the same time learn
about network and network security, and software development among
others.

25 LMU ID \| Student Name

CS6P05NI Final Year Project

**11.** **References**

Agile Lone Star, 2024. *agilelonestar.* \[Online\]

Available at:
<u>https://www.agilelonestar.com/knowledge-base/rational-unified-process</u>
\[Accessed 17 September 2024\].

ALazzawi, A., M.Yas, Q. & Rahmatullah, B., 2023. A Comprehensive Review
of

Software Development Life Cycle methodologies: Pros, Cons, and Future
Directions. *Iraqi* *Journal* *for* *Computer* *Science* *and*
*Mathematics,* 4(4), pp. 173-190.

CompTIA, 2024. *CompTIA.* \[Online\]

Available at:
<u>https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-it</u>

\[Accessed 15 September 2024\].

Hammad, M., 2024. *GeeksforGeeks.* \[Online\]

Available at:
<u>https://www.geeksforgeeks.org/rup-and-its-phases/#what-is-rational-unified-process-rup</u>

\[Accessed 18 September 2024\].

H, L. et al., 2024. A Review of Modern Computer Networking Technologies.
*IJARIIE,* 10(4), pp. 1844-1851.

Hossain, M. I., 2024. Software Development Life Cycle (SDLC)
Methodologies for

Information Systems Project Management. *International* *Journal* *for*
*Multidisciplinary* *Research* *(IJFMR),* 5(5), pp. 1-36.

Kanjilal, J., 2022. *developer.com.* \[Online\]

Available at:
<u>https://www.developer.com/project-management/rational-unified-process-rup/</u>

\[Accessed 16 September 2024\].

Khan, D. R. A. H. et al., 2024. The Waterfall Model-Software
Engineering.

*International* *Journal* *of* *Research* *Publication* *and* *Reviews,*
5(4), pp. 7825-7830.

Khan, S. M., 2023. *Waterfall* *Model* *Used* *in* *Software*
*Development* *Reference:* *Software* *Requirements* *Engineering*
*Waterfall* *Model.* s.l.:s.n.

26 LMU ID \| Student Name

CS6P05NI Final Year Project

Mugwadi, I., 2024. *Medium.* \[Online\]

Available at:
<u>https://medium.com/@mugwadiinnocent/system-development-life-cycle-sdlc-afce857b91fc</u>

\[Accessed 18 September 2024\].

nvsia learn, 2020. *nvisia.* \[Online\]

Available at: <u>https://www.nvisia.com/insights/agile-methodology</u>
\[Accessed 17 September 2024\].

Sandamal, H., 2020. *Medium.* \[Online\]

Available at:
<u>https://hansasandamal.medium.com/software-development-life-cycle-methods-7ccd25d6e198</u>

\[Accessed 17 September 2024\].

Schwaber, K. & Sutherland, J., 2020. *The* *Scrum* *Guide.* s.l.:2020
Ken Schwaber and

Jeff Sutherland.

Zhang, S., 2024. The Importance of Computer Network Applications and
Security. *Journal* *of* *Computing* *and* *Electronic* *Information*
*Management,* 12(3), pp. 55-58.

27 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./4cgbx4xp.png"
style="width:6.26805in;height:3.52569in" />

**12.** **Appendix**

**12.1** **RUP** **Methodology**

Rational Unified Process (RUP) is a software development methodology for
object-oriented models. It goes by the name Unified Process Model as
well. UML (Unified Modeling Language) is used in its design and
documentation, and it was produced by Rational Corporation. The IBM
Rational Method Composer (RMC) software includes this procedure.
Customization, design, and personalization of the unified process are
made possible by IBM (International Business Machine Corporation)
(Hammad, 2024).

Since its creation by Rational Software in the 1990s, the RUP has grown
to be one of the most popular approaches for software development
(Kanjilal, 2022).

> *Figure* *11:* *Phases* *of* *RUP* *Methodology.*

**12.1.1Circumstances** **to** **use** **RUP** **Methodology**

The RUP methodology works best for building high-quality software within
a time and

budget limit (Hammad, 2024).

28 LMU ID \| Student Name

CS6P05NI Final Year Project

**12.1.2Advantages** **of** **RUP** **Methodology**

The benefits of the Rational Unified Process (RUP) are as follows:

• Good documentation is provided by RUP, which also completes the
procedure. • RUP offers assistance with risk management.

• Because RUP reuses the components, the overall time is reduced.

• Tutorials and training are accessible online to provide effective
assistance.

**12.1.3Disadvantages** **of** **RUP** **Methodology**

The following are RUP's (Rational Unified Process) drawbacks:

• Because the process is complex, a team of qualified professionals is
needed. • A complex and poorly structured procedure.

•     An increased reliance on risk mitigation. •     Challenging to
continuously incorporate.

29 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./2ib3jguv.png"
style="width:6.26805in;height:1.54444in" />

**12.2** **Prototype** **Model**

Prototype Model is a software development process that mainly focuses on
creating a working model of the software quickly and then gathers user
feedback to develop the final product. The key goal is to guarantee that
the software closely matches user needs and expectations. It entails
iteratively improving the prototype in response to user feedback until
the intended functionality and design are realized. The Prototyping
Model is especially useful when needs are ambiguous or subject to
change, as well as when early user interaction and validation is
required (Hossain, 2024).

> *Figure* *12:* *Steps* *of* *Prototype* *Model.*

**12.2.1Circumstances** **to** **use** **Prototype** **Model**

The Prototype Model works best when early user participation and
validation are required, and when requirements are susceptible to
change. It is a useful strategy for enhancing communication between
development teams and stakeholders, which eventually results in the
creation of a more effective and approachable end product (Hossain,
2024).

30 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./tuh3l1vb.png"
style="width:6.26805in;height:3.13403in" />

**12.3** **Agile** **Software** **Development** **Frameworks**

Agile places a strong emphasis on close coordination between customers,
testers, and developers at every stage of the project. This methodology
allows teams to adapt well to changing priorities and is especially
well-suited for projects whose requirements are dynamic or change often.
The Agile development methodology provides a conceptual framework for
managing a variety of software development projects. The Agile
development methodology runs in sprint. Usually lasting one to four
weeks, these sprints produce a software increment that may be prepared
for eventual deployment (Hossain, 2024).

> There are a few different software development methodologies that fall
> under

the overall framework of Agile; the most well-known ones are Extreme
Programming (XP), Crystal methods, Scrum, and Feature Driven Development
(Hossain, 2024).

> *Figure* *13:* *Principles* *of* *Agile* *Methodology.*

31 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./llccn01g.png"
style="width:6.26805in;height:3.43333in" />

**12.3.1Scrum** **Framework**

> Within the Agile technique, the Scrum Framework adds further structure
> in the

form of roles, ceremonies, and artifacts. Scrum uses a framework that
consists of sprint planning, daily stand-up meetings, sprint reviews,
retrospectives, and product backlogs. Scrum's primary characteristic is
its focus on brief, time-boxed iterations known as sprints, which
usually run for two to four weeks. Scrum encourages transparency,
review, and adaptability through every phase of the project (Hossain,
2024).

> *Figure* *14:* *Scrum* *Framework*

32 LMU ID \| Student Name

CS6P05NI Final Year Project

**12.3.2Reasons** **for** **Selecting** **Scrum** **Framework**

**Transparency:**

Scrum places a strong emphasis on transparency through its various
artifacts, including the Increment, Product Backlog, and Sprint Backlog.
Through transparency, it will be easier to keep track of how the project
is progressing. This transparency facilitates decision-making, lowers
risks, and guarantees that all parties involved are aware of and
comprehend each phase of the project (Schwaber & Sutherland, 2020).

**Inspection:**

Through its five events (Sprint Planning, Daily Scrum, Sprint Review,
Sprint Retrospective, and the Sprint itself), Scrum offers frequent
inspection opportunities. This enables us to monitor the progress of the
project on a regular basis, identify problems early, and make the
required corrections (Schwaber & Sutherland, 2020). These inspections
will aid in the early detection of possible issues with different
features.

**Adaptation:**

The flexibility of Scrum enables us to quickly modify the procedure or
final product if any aspect of the project deviates from the anticipated
result. It guarantees that we can quickly handle any alterations and
maintain the project's progress to provide a high-quality product
(Schwaber & Sutherland, 2020). This adaptability is essential when
creating sophisticated systems, such as network analysis tools, whose
specifications may alter in response to user input or technical
limitations.

33 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./zqdlxqqy.png"
style="width:4.21736in;height:8.96597in" />

**12.4** **Work** **Breakdown** **Structure**

34 LMU ID \| Student Name

CS6P05NI Final Year Project<img src="./omwnv34n.png"
style="width:6.26805in;height:3.82431in" /><img src="./r0wa4uqg.png"
style="width:6.435in;height:1.95417in" /><img src="./mut21qwc.png"
style="width:6.48028in;height:1.69653in" />

**12.5** **Project** **Gantt** **Chart**

35 LMU ID \| Student Name

CS6P05NI<img src="./biuaxbvv.png"
style="width:6.33958in;height:2.58472in" /><img src="./42ztecem.png"
style="width:6.55069in;height:3.845in" />

LMU ID \| Student Name

Final Year Project

> 36
