# To-Be-Secure-or-Not-to-Be-
To Be Secure or Not to Be? 
To Be Secure or Not to Be?
You probably know about computer hackers and computer viruses. Unless your computer has been targeted by
one, you may not know how they could affect an individual or an organization. If a computer is attacked by a
hacker or virus, it could lose important personal information and software.
The creation of a new university campus is being considered. Your requirement is to model the risk
assessment of information technology (IT) security for this proposed university. The narrative below
provides some background to help develop a framework to examine IT security. Specific tasks are
provided at the end of this narrative.
Computer systems are protected from malicious activity through multiple layers of defenses. These defenses,
including both policies and technologies (Figure 1), have varying effects on the organization’s risk categories
(Figure 2).
Figure 1 – Preventative Defensive Measures
Management and usage policies address how users interact with the organization’s computers and networks and
how people (system administrators) maintain the network. Policies may include password requirements, formal
security audits, usage tracking, wireless device usage, removable media concerns, personal use limitations, and
user training. An example password policy would include requirements for the length and characters used in the
password, how frequently they must be changed, and the number of failed login attempts allowed. Each policy
solution has direct costs associated with its implementation and factors that impact productivity and security. In
Figure 1, only the topmost branch is fully detailed. The structure is replicated for each branch.
The second aspect of a security posture is the set of technological solutions employed to detect, mitigate, and
defeat unauthorized activity from both internal and external users. Technology solutions cover both software 
and hardware and include intrusion detection systems (IDS), firewalls, anti-virus systems, vulnerability
scanners, and redundancy. As an example, IDS monitors and records significant events on a specific computer
or from the network examining data and providing an “after the fact” forensic ability to identify suspect activity.
SNORT (www.snort.org) is a popular IDS solution. Figure 1 provides a sample of key defensive measures
(management/usage policies and technology solutions). As with a policy, a technology solution also has direct
costs, as well as factors that impact productivity and security.
Sources of risk to information security include, but are not limited to, people or hardware within or outside the
organization (Figure 2). Different preventive defensive measures (Figure 1) may be more effective against an
insider threat than a threat from a computer hacker. Additionally, an external threat may vary in motivation,
which could also indicate different security measures. For example, an intruder who is trying to retrieve
proprietary data or customer databases probably should be combated much differently from an intruder who is
trying to shut down a network.
Potential costs due to information security that an organization may face (Figure 2) include opportunity cost,
people, and the cost of preventative defensive measures. Significant opportunity costs include: litigation
damages, loss of proprietary data, consumer confidence, loss of direct revenue, reconstruction of data, and
reconstruction of services. Each cost varies based on the profile of the organization. For example, a health care
component of the university might have a greater potential for loss due to litigation or availability of patient
medical records than with reconstruction of services.
Figure 2 - Economic Risk schematic for IT systems
An organization can evaluate potential opportunity costs through a risk analysis. Risks can be broken down into
three risk categories; confidentiality, integrity, and availability. Combined, these categories define the
organization’s security posture. Each of the categories has different impacts on cost depending on the mission
and requirements of the organization. Confidentiality refers to the protection of data from release to sources that
are not authorized with access. A health care organization could face significant litigation if health care records
were inadvertently released or stolen. The integrity of the data refers to the unaltered state of the data. If an
intruder modifies pricing information for certain products or deletes entire data sets, an organization would face
costs associated with correcting transactions affected by the erroneous data, the costs associated with
reconstructing the correct values, and possible loss of consumer confidence and revenue. Finally, availability
refers to resources being available to an authorized user, including both data and services. This risk can
manifest itself financially in a similar manner as confidentiality and integrity
Each measure implemented to increase the security posture of an organization will impact each of the three risk
categories (either positively or negatively). As each new defensive security measure is implemented, it will
change the current security posture and subsequently the potential opportunity costs. A complicated problem
faced by organizations is how to balance their potential opportunity costs against the expense of securing their
IT infrastructure (preventative defensive measures).
Task 1: You have been tasked by the Rite-On Consulting Firm to develop a model that can be
used to determine an appropriate policy and the technology enhancements for the proper level
of IT security within a new university campus. The immediate need is to determine an optimal
mix of preventive defensive measures that minimizes the potential opportunity costs along
with the procurement, maintenance, and system administrator training costs as they apply
to the opening of a new private university. Rite-On contracted technicians to collect technical
specifications on current technologies used to support IT security programs. Detailed technical
data sheets that catalog some possible defensive measures are contained in Enclosures A and B.
The technician who prepared the data sheets noted that as you combine defensive measures, the
cumulative effects within and between the categories confidentiality, integrity, and availability
cannot just be added.
The proposed university system has 10 academic departments, a department of intercollegiate
athletics, an admissions office, a bookstore, a registrar’s office (grade and academic status
management), and a dormitory complex capable of housing 15,000 students. The university
expects to have 600 staff and faculty (non IT support) supporting the daily mission. The
academic departments will maintain 21 computer labs with 30 computers per lab, and 600 staff
and faculty computers (one per employee). Each dorm room is equipped with two (2) high
speed connections to the university network. It is anticipated that each student will have a
computer. The total computer requirements for the remaining department/agencies cannot be
anticipated at this time. It is known that the bookstore will have a Web site and the ability to
sell books online. The Registrar’s office will maintain a Web site where students can check the
status of payments and grades. The admissions office, student health center, and the athletic
department will maintain Web sites.
The average administrative employee earns $38,000 per year and the average faculty employee
earns $77,000 per year. Current industry practice employs three to four system administrators
(sys admin) per sub-network and there is typically one (1) sys admin (help desk support)
employee per 300 computers. Additionally, each separate system of computers (for web
hosting or data management) is typically managed by one (1) sys admin person.
The current opportunity cost projection (due to IT) with no defensive measures is shown in
Table 1. The contribution of various risk categories (Confidentiality Integrity, and Availability)
to a given cost is also shown in Table 1.
Table 1: Current Opportunity costs and Risk Category contributions
Opportunity Cost (due to IT) Amount Risk Category Contribution
Litigation $3,800,000 C (55%), I (45%)
Proprietary Data loss $1,500,000 C (70%), I (30%)
Consumer confidence $2,900,000 C (40%), I (30%), A (30%)
Data Reconstruction $400,000 I (100%)
Service Reconstruction $80,000 I (100%)
Direct Revenue Loss $250,000 I (30%), A (70%) 
Task 2: We know that technical specifications will change rapidly over time. However, the
relations and interplay among costs, risk categories, and sources of risk will tend to change
more slowly. Create a model for the problem in Task 1 that is flexible enough to adapt to
changing technological capabilities and can be applied to different organizations.
Carefully describe the assumptions that you make in designing the model. In addition, provide
an example of how the university will be able to use your model to initially determine and then
periodically update their IT security system.
Task 3: Prepare a three page position paper to the university President that describes the
strengths, weakness, and flexibility of your model in Task 2. In addition, explain what can be
inferred and what should not be inferred from your model.
Task 4: Explain the differences that may exist in the initial Risk Category Contributions
(Table 1) if you model IT security for a commercial company that provides a search engine for
the World Wide Web (such as Google, Yahoo, AltaVista, … ). Will your model work for this
type of organization?
Task 5: Honeynets are designed to gather extensive information on IT security threats. Write
a two-page memo to your supervisor advising whether a university or a search engine company
should consider using a honeynet.
Task 6: To become a leader in IT security consulting, Rite-On Consulting must also take an
active role in anticipating the future direction of information technology and advising
companies on how to respond to future security risks. After performing your analysis, write a
two-page memo to the President of Rite-On to inform him of the future of IT security. In
addition, describe how your model can be used to anticipate and respond to the uncertain future. 
Technology -
Preventive
Defensive
Measure Enclosure A
Low Mean High Variability
Host-based
Firewall
Intelli-Scan Direct Costs
Procurement/computer n/a 45.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -2.00% -1.00% 0.00% Low
Confidentiality 9.00% 28.00% 38.00% High
Integrity 9.00% 28.00% 38.00% High
Availability 9.00% 18.00% 28.00% Med
Shield Direct Costs
Procurement/computer n/a 50.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -5.00% -2.00% 0.00% Low
Confidentiality 10.00% 20.00% 25.00% Low
Integrity 8.00% 15.00% 18.00% Low
Availability 7.00% 10.00% 20.00% Low
Lava Direct Costs
Procurement/computer n/a 35.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -3.00% -2.00% 0.00% Low
Confidentiality 3.00% 28.00% 35.00% High
Integrity 4.00% 28.00% 40.00% High
Availability 2.00% 18.00% 30.00% High
ProtectIT Direct Costs
Procurement/computer n/a 40.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -6.00% -3.00% 0.00% Low
Confidentiality 9.00% 20.00% 25.00% Med
Integrity 9.00% 20.00% 25.00% Med
Availability 9.00% 20.00% 25.00% Med
Blockade Direct Costs
Procurement/computer n/a 30.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -5.00% -3.00% 0.00% Low
Confidentiality 9.00% 20.00% 25.00% Med
Integrity 9.00% 20.00% 25.00% Med
Availability 9.00% 20.00% 25.00% Med
Quantitiative Values
How to read this table: The Qualitative Values are a judgment based on the assessment from industry experts on the tools'
effectiveness. Each defensive measure has several instances that vary in costs and effectiveness. The Low, Mean, and High values
represent a characterization of reviews found in different consumer review periodicals as they relate to user productivity,
confidentiality, integrity, and availability. The variability indicates the concentration of the data about the mean. The Low and High are
the minimum and maximum possible values, respectively. Costs are in U.S. dollars. A factor value of 5.00% indicates an
improvement of 5%. A value of -5.00% indicates that the factor is degraded by 5%. These values are modifiers to the existing levels.
For example from a base Confidentiality level of .8 a factor value of -25% would result in a new Confidentiality factor of 0.8 - (0.8*0.25)
= 0.6. A positive value results in a positive change in the factor. 
Blocker Direct Costs
Procurement/computer n/a 15.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -10.00% -5.00% 0.00% Low
Confidentiality 2.00% 10.00% 30.00% High
Integrity 1.00% 10.00% 25.00% Med
Availability 1.00% 5.00% 17.00% Med
Watertight Direct Costs
Procurement/computer n/a 10.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -5.00% -3.00% 0.00% Low
Confidentiality 9.00% 20.00% 25.00% Med
Integrity 9.00% 20.00% 25.00% Med
Availability 9.00% 20.00% 25.00% Med
Barrior Direct Costs
Procurement/computer n/a 10.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -4.00% -3.00% -2.00% Low
Confidentiality 9.00% 21.00% 20.00% Low
Integrity 10.00% 19.00% 23.00% Low
Availability 7.00% 20.00% 27.00% Med
Network-based
Firewall
Enterprise Solution Direct Costs
Procurement n/a 15,000.00 $ n/a
Maintenance/year/computer n/a 2,000.00 $ n/a
Training/year/sys admin n/a 4,000.00 $ n/a
Factors
User Productivity -15.00% -5.00% 0.00% Med
Confidentiality 10.00% 30.00% 40.00% High
Integrity 10.00% 30.00% 40.00% High
Availability 10.00% 20.00% 30.00% Med
Network defense Direct Costs
Procurement n/a 17,500.00 $ n/a
Maintenance/year/computer n/a 1,500.00 $ n/a
Training/year/sys admin n/a 4,000.00 $ n/a
Factors
User Productivity -10.00% -4.00% 0.00% Low
Confidentiality 15.00% 30.00% 40.00% Med
Integrity 19.00% 30.00% 50.00% High
Availability 9.00% 20.00% 30.00% Med
System Inoc Direct Costs
Procurement n/a 10,000.00 $ n/a
Maintenance/year/computer n/a 1,000.00 $ n/a
Training/year/sys admin n/a 4,000.00 $ n/a
Factors
User Productivity -15.00% -5.00% 0.00% Med
Confidentiality 5.00% 20.00% 40.00% High
Integrity 2.00% 15.00% 40.00% High
Availability 18.00% 20.00% 30.00% High
Protection Direct Costs
Procurement n/a 10,000.00 $ n/a
Maintenance/year/computer n/a 1,500.00 $ n/a
Training/year/sys admin n/a 2,000.00 $ n/a
Factors
User Productivity -0.11 -0.05 0 Low
Confidentiality 0.1 0.25 0.3 Low
Integrity 0.1 0.25 0.3 Low
Availability 0.1 0.13 0.2 Low
Acera Direct Costs
Procurement n/a 15,000.00 $ n/a
Maintenance/year/computer n/a 3,000.00 $ n/a
Training/year/sys admin n/a 2,500.00 $ n/a
Factors
User Productivity -70.00% -5.00% 0.00% High
Confidentiality 10.00% 25.00% 30.00% Med
Integrity 10.00% 25.00% 30.00% Med
Availability 10.00% 13.00% 20.00% Low
Plunger Direct Costs
Procurement n/a 12,500.00 $ n/a
Maintenance/year/computer n/a 1,500.00 $ n/a
Training/year/sys admin n/a 2,000.00 $ n/a
Factors
User Productivity -0.11 -0.05 0 Low
Confidentiality 0.1 0.25 0.3 Low
Integrity 0.1 0.25 0.3 Low
Availability 0.1 0.13 0.2 Low
Firebase Direct Costs
Procurement n/a 5,000.00 $ n/a
Maintenance/year/computer n/a 1,000.00 $ n/a
Training/year/sys admin n/a 2,500.00 $ n/a
Factors
User Productivity -9.00% -5.00% 0.00% Med
Confidentiality 5.00% 10.00% 20.00% Med
Integrity 5.00% 10.00% 20.00% Med
Availability 1.00% 5.00% 13.00% Med
Enterprise Lava Direct Costs
Procurement n/a 2,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 3,500.00 $ n/a
Factors
User Productivity -11.00% -7.00% 0.00% Med
Confidentiality 2.00% 10.00% 20.00% Med
Integrity 3.00% 10.00% 20.00% Med
Availability 1.00% 5.00% 13.00% Med
Draco Direct Costs
Procurement n/a 3,000.00 $ n/a
Maintenance/year/computer n/a 500.00 $ n/a
Training/year/sys admin n/a 2,500.00 $ n/a
Factors
User Productivity -11.00% -7.00% 0.00% Med
Confidentiality 2.00% 18.00% 20.00% Med
Integrity 3.00% 17.00% 20.00% Med
Availability 1.00% 10.00% 13.00% Low
Host-based AntiVirus
Bug Killer Direct Costs
Procurement/computer n/a 20.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -5.00% -2.00% 0.00% Low
Confidentiality 9.00% 28.00% 38.00% High
Integrity 9.00% 28.00% 38.00% High
Availability 9.00% 18.00% 28.00% Med
Anti-V Direct Costs
Procurement/computer n/a 12.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -3.00% -1.00% 0.00% Low
Confidentiality 10.00% 29.00% 32.00% Med
Integrity 12.00% 25.00% 40.00% High
Availability 9.00% 18.00% 24.00% Med
Insecticide Direct Costs
Procurement/computer n/a 8.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -6.00% -3.00% 0.00% Low
Confidentiality 9.00% 20.00% 25.00% Med
Integrity 9.00% 20.00% 25.00% Med
Availability 9.00% 20.00% 25.00% Med
Smasher Direct Costs
Procurement/computer n/a 10.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -8.00% -3.00% 0.00% Low
Confidentiality 5.00% 20.00% 23.00% Med
Integrity 2.00% 10.00% 20.00% Med
Availability 9.00% 18.00% 25.00% Med
Stomper Direct Costs
Procurement/computer n/a 5.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -9.00% -5.00% 0.00% Med
Confidentiality 5.00% 10.00% 20.00% Med
Integrity 5.00% 10.00% 20.00% Med
Availability 1.00% 5.00% 13.00% Low
The Swatter Direct Costs
Procurement/computer n/a 8.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -9.00% -5.00% 0.00% Med
Confidentiality 15.00% 19.00% 20.00% Med
Integrity 15.00% 18.00% 19.00% Low
Availability 1.00% 5.00% 13.00% Med
McKiller Direct Costs
Procurement/computer n/a 8.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -11.00% -5.00% 0.00% Med
Confidentiality 15.00% 19.00% 23.00% Med
Integrity 15.00% 16.00% 18.00% Med
Availability 1.00% 6.00% 10.00% Med
Fogger Direct Costs
Procurement/computer n/a 3.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -11.00% -5.00% 0.00% Med
Confidentiality 15.00% 19.00% 23.00% Low
Integrity 15.00% 16.00% 18.00% Low
Availability 1.00% 6.00% 10.00% Med
Innoculator Direct Costs
Procurement/computer n/a 5.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -11.00% -5.00% 0.00% Med
Confidentiality 10.00% 16.00% 22.00% Med
Integrity 5.00% 10.00% 11.00% Low
Availability 1.00% 6.00% 10.00% Med
Network-based
Anti-Virus
Enterprise Stopper Direct Costs
Procurement n/a 4,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 3,000.00 $ n/a
Factors
User Productivity -15.00% -5.00% 0.00% Med
Confidentiality 10.00% 30.00% 40.00% High
Integrity 10.00% 30.00% 40.00% High
Availability 10.00% 20.00% 30.00% Med
System Splatter Direct Costs
Procurement n/a 1,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 2,500.00 $ n/a
Factors
User Productivity -8.00% -5.00% 0.00% Low
Confidentiality 10.00% 30.00% 35.00% Med
Integrity 12.00% 30.00% 41.00% Med
Availability 9.00% 20.00% 28.00% Med
Enterprise Inoculation Direct Costs
Procurement n/a 600.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 3,000.00 $ n/a
Factors
User Productivity -15.00% -5.00% 0.00% Med
Confidentiality 10.00% 30.00% 36.00% Med
Integrity 12.00% 30.00% 35.00% Med
Availability 9.00% 20.00% 21.00% Med
Global Protect Direct Costs
Procurement n/a 400.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 4,000.00 $ n/a
Factors
User Productivity -11.00% -5.00% 0.00% Med
Confidentiality 10.00% 25.00% 30.00% Med
Integrity 10.00% 25.00% 30.00% Med
Availability 10.00% 13.00% 20.00% Low
Bug Zapper Direct Costs
Procurement n/a 600.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -11.00% -8.00% 0.00% Med
Confidentiality 5.00% 25.00% 30.00% Med
Integrity 7.00% 25.00% 31.00% Med
Availability 11.00% 13.00% 20.00% Med
Enterprise Stomper Direct Costs
Procurement n/a 300.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -9.00% -4.00% 0.00% Med
Confidentiality 20.00% 25.00% 30.00% Med
Integrity 9.00% 20.00% 28.00% Med
Availability 11.00% 13.00% 19.00% Low
Enterprise Fogger Direct Costs
Procurement n/a 400.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 3,000.00 $ n/a
Factors
User Productivity -11.00% -8.00% 0.00% Med
Confidentiality 5.00% 25.00% 30.00% Med
Integrity 7.00% 25.00% 31.00% Med
Availability 11.00% 13.00% 20.00% Med
System fixer Direct Costs
Procurement n/a 250.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 750.00 $ n/a
Factors
User Productivity -11.00% -5.00% 0.00% Med
Confidentiality 2.00% 10.00% 20.00% Med
Integrity 5.00% 9.00% 21.00% Med
Availability 2.00% 3.00% 11.00% Low
System Doctor Direct Costs
Procurement n/a 300.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,500.00 $ n/a
Factors
User Productivity -6.00% -2.00% 0.00% Low
Confidentiality 4.00% 10.00% 15.00% Low
Integrity 5.00% 7.00% 15.00% Low
Availability 1.00% 5.00% 13.00% Low
Blue Sky Direct Costs
Procurement n/a 400.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 2,000.00 $ n/a
Factors
User Productivity -5.00% -2.00% -1.00% Low
Confidentiality 3.00% 10.00% 14.00% Low
Integrity 1.00% 2.00% 9.00% Low
Availability 1.00% 12.00% 13.00% Low
Acer Security Direct Costs
Procurement n/a 300.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -9.00% -5.00% 0.00% Med
Confidentiality 5.00% 10.00% 20.00% Med
Integrity 5.00% 10.00% 20.00% Med
Availability 1.00% 5.00% 13.00% Low
Protection Direct Costs
Procurement n/a 250.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -11.00% -9.00% 0.00% Med
Confidentiality 4.00% 10.00% 20.00% Med
Integrity 2.00% 10.00% 19.00% Med
Availability 0.00% 5.00% 15.00% Med
Network-based
Intrusion
Detection
System
Data Watcher Direct Costs
Procurement n/a 19,000.00 $ n/a
Maintenance/year/computer/ass n/a 50.00 $ n/a
Training/year/sys admin n/a 5,000.00 $ n/a
Factors
User Productivity -10.00% -5.00% 0.00% Low
Confidentiality 10.00% 20.00% 30.00% Med
Integrity 18.00% 20.00% 30.00% Low
Availability 10.00% 20.00% 30.00% Med
Data Inc Direct Costs
Procurement n/a 20,000.00 $ n/a
Maintenance/year/computer/ass n/a 100.00 $ n/a
Training/year/sys admin n/a 7,000.00 $ n/a
Factors
User Productivity -11.00% -9.00% -2.00% Med
Confidentiality 10.00% 20.00% 40.00% High
Integrity 10.00% 20.00% 35.00% High
Availability 19.00% 20.00% 38.00% Med
Correlation Inc Direct Costs
Procurement n/a 15,000.00 $ n/a
Maintenance/year/computer/ass n/a - $ n/a
Training/year/sys admin n/a 6,000.00 $ n/a
Factors
User Productivity -10.00% -5.00% 0.00% Med
Confidentiality 3.00% 9.00% 42.00% High
Integrity 4.00% 11.00% 41.00% High
Availability 0.00% 13.00% 39.00% High
Detect IT Direct Costs
Procurement n/a 8,000.00 $ n/a
Maintenance/year/computer/ass n/a 50.00 $ n/a
Training/year/sys admin n/a 5,000.00 $ n/a
Factors
User Productivity -15.00% -10.00% 0.00% Med
Confidentiality 5.00% 15.00% 25.00% Med
Integrity 5.00% 15.00% 25.00% Med
Availability 5.00% 15.00% 25.00% Med
Security Associates Direct Costs
Procurement n/a 9,000.00 $ n/a
Maintenance/year/computer/ass n/a - $ n/a
Training/year/sys admin n/a 4,000.00 $ n/a
Factors
User Productivity -12.00% -8.00% 0.00% Med
Confidentiality 5.00% 15.00% 20.00% Med
Integrity 5.00% 15.00% 18.00% Low
Availability 5.00% 15.00% 17.00% Low
Network Traffic ID Direct Costs
Procurement n/a 9,000.00 $ n/a
Maintenance/year/computer/ass n/a 75.00 $ n/a
Training/year/sys admin n/a 5,000.00 $ n/a
Factors
User Productivity -15.00% -10.00% 0.00% Med
Confidentiality 5.00% 16.00% 30.00% Med
Integrity 5.00% 18.00% 28.00% Med
Availability 5.00% 20.00% 26.00% Med
Unitec Direct Costs
Procurement n/a 5,000.00 $ n/a
Maintenance/year/computer/ass n/a 20.00 $ n/a
Training/year/sys admin n/a 7,000.00 $ n/a
Factors
User Productivity -30.00% -20.00% -2.00% Med
Confidentiality 5.00% 18.00% 20.00% Med
Integrity 7.00% 17.00% 20.00% Med
Availability 10.00% 17.00% 20.00% Low
Network Eye Direct Costs
Procurement n/a 4,000.00 $ n/a
Maintenance/year/computer/ass n/a 35.00 $ n/a
Training/year/sys admin n/a 2,000.00 $ n/a
Factors
User Productivity -30.00% -10.00% 0.00% Med
Confidentiality 5.00% 20.00% 25.00% Med
Integrity 7.00% 21.00% 25.00% Med
Availability 10.00% 22.00% 25.00% Med
Watcher Direct Costs
Procurement n/a 3,000.00 $ n/a
Maintenance/year/computer/ass n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -30.00% -10.00% 0.00% Med
Confidentiality 5.00% 20.00% 22.00% Med
Integrity 7.00% 19.00% 22.00% Med
Availability 10.00% 21.00% 23.00% Low
Network-based
SPAM Filter
Spam Stoper Direct Costs
Procurement n/a 45,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -0.10% -0.10% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability 15.00% 15.00% 15.00% Low
Mail Control Direct Costs
Procurement n/a 30,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,500.00 $ n/a
Factors
User Productivity -0.10% -0.10% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability -5.00% 2.00% 15.00% Med
Postman Direct Costs
Procurement n/a 3,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 2,000.00 $ n/a
Factors
User Productivity -5.00% -1.00% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability -8.00% 1.00% 7.00% Med
Mail Scrubber Direct Costs
Procurement n/a 5,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -0.30% -0.20% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability 0.00% 1.00% 5.00% Low
Spam Meiseter Direct Costs
Procurement n/a 1,500.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 800.00 $ n/a
Factors
User Productivity -5.00% -1.00% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability -10.00% -3.00% 10.00% Med
Email Valve Direct Costs
Procurement n/a 10,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 500.00 $ n/a
Factors
User Productivity -0.20% -0.25% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability 0.00% 3.00% 5.00% Med
Email Filter Direct Costs
Procurement n/a 5,000.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -0.30% -0.25% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability -1.00% 3.00% 5.00% Med
Acer INC Direct Costs
Procurement n/a 100.00 $ n/a
Maintenance/year/computer n/a - $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity -0.20% -0.25% -0.10% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 0.00% 0.00% Low
Availability -15.00% -5.00% 5.00% Med
Network-based
Vulnerability
Scanning
Hole Plugger Direct Costs
Procurement n/a 75,000.00 $ n/a
Maintenance/year n/a 25,000.00 $ n/a
Training/year/sys admin n/a 10,000.00 $ n/a
Factors
User Productivity -1.00% -0.50% 0.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity -1.00% 0.00% 10.00% Med
Availability -1.00% 0.00% 10.00% Med
Scanner Direct Costs
Procurement n/a 60,000.00 $ n/a
Maintenance/year n/a 20,000.00 $ n/a
Training/year/sys admin n/a 5,000.00 $ n/a
Factors
User Productivity -1.00% -0.50% 0.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity -10.00% -70.00% 15.00% Med
Availability -10.00% -70.00% 15.00% Med
Health Check Direct Costs
Procurement n/a 90,000.00 $ n/a
Maintenance/year n/a 25,000.00 $ n/a
Training/year/sys admin n/a 9,000.00 $ n/a
Factors
User Productivity -1.00% -0.50% 0.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity -0.50% 0.00% 5.00% Low
Availability -0.50% 0.00% 5.00% Low
Net Assesment Direct Costs
Procurement n/a 50,000.00 $ n/a
Maintenance/year n/a 20,000.00 $ n/a
Training/year/sys admin n/a 7,000.00 $ n/a
Factors
User Productivity -0.90% -0.50% 0.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity -15.00% -9.00% 10.00% Med
Availability -19.00% -10.00% 10.00% Med
SCT scanner Direct Costs
Procurement n/a 30,000.00 $ n/a
Maintenance/year n/a 10,000.00 $ n/a
Training/year/sys admin n/a 5,000.00 $ n/a
Factors
User Productivity -5.00% -3.00% 0.00% Med
Confidentiality 0.00% 0.00% 0.00% Low
Integrity -20.00% -9.00% 15.00% Med
Availability -20.00% -10.00% 15.00% High
NetStat Direct Costs
Procurement n/a 20,000.00 $ n/a
Maintenance/year n/a 6,000.00 $ n/a
Training/year/sys admin n/a 3,000.00 $ n/a
Factors
User Productivity -1.20% -0.50% 0.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity -20.00% -10.00% 1.00% Med
Availability -20.00% -10.00% 1.00% Med
VulnerScan Direct Costs
Procurement n/a 15,000.00 $ n/a
Maintenance/year n/a 5,000.00 $ n/a
Training/year/sys admin n/a 3,000.00 $ n/a
Factors
User Productivity -1.20% -0.50% 0.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity -30.00% -20.00% 9.00% High
Availability -30.00% -20.00% 9.00% High
Data
Redundancy
Sonic Data Direct Costs
Procurement n/a 800,000.00 $ n/a
Maintenance/year/computer n/a 8,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 10.00% Med
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 10.00% 20.00% 40.00% Med
Availability 10.00% 20.00% 40.00% Med
Data Soutions Direct Costs
Procurement n/a 500,000.00 $ n/a
Maintenance/year/computer n/a 5,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 20.00% Med
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 10.00% 60.00% High
Availability 0.00% 10.00% 60.00% High
Data R Us Direct Costs
Procurement n/a 300,000.00 $ n/a
Maintenance/year/computer n/a 4,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 5.00% Med
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 10.00% 30.00% Med
Availability 0.00% 10.00% 30.00% Med
Bytes Direct Costs
Procurement n/a 250,000.00 $ n/a
Maintenance/year/computer n/a 3,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 5.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 20.00% 22.00% Med
Availability 0.00% 20.00% 22.00% Med
Digital Solutions Direct Costs
Procurement n/a 150,000.00 $ n/a
Maintenance/year/computer n/a 3,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 3.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 10.00% 15.00% Med
Availability 0.00% 10.00% 15.00% Med
Data Direct Costs
Procurement n/a 100,000.00 $ n/a
Maintenance/year/computer n/a 10,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 3.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 15.00% 17.00% Med
Availability 0.00% 15.00% 17.00% Med
Service
Redundancy
Web King Direct Costs
Procurement n/a 50,000.00 $ n/a
Maintenance/year/computer n/a 10,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 10.00% Med
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 10.00% 20.00% 40.00% High
Availability 10.00% 20.00% 40.00% High
Redundant Servies Direct Costs
Procurement n/a 30,000.00 $ n/a
Maintenance/year/computer n/a 10,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 20.00% Med
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 10.00% 60.00% High
Availability 0.00% 10.00% 60.00% High
ServU Direct Costs
Procurement n/a 15,000.00 $ n/a
Maintenance/year/computer n/a 10,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 5.00% Med
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 10.00% 30.00% High
Availability 0.00% 10.00% 30.00% High
Robust Solutions Direct Costs Med
Procurement n/a 10,000.00 $ n/a
Maintenance/year/computer n/a 10,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 5.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 20.00% 22.00% Med
Availability 0.00% 20.00% 22.00% Med
Duplicity Direct Costs
Procurement n/a 10,000.00 $ n/a
Maintenance/year/computer n/a 10,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 3.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 10.00% 15.00% Med
Availability 0.00% 10.00% 15.00% Med
Dito Direct Costs
Procurement n/a 6,000.00 $ n/a
Maintenance/year/computer n/a 10,000.00 $ n/a
Training/year/sys admin n/a 1,000.00 $ n/a
Factors
User Productivity 0.00% 1.00% 3.00% Low
Confidentiality 0.00% 0.00% 0.00% Low
Integrity 0.00% 15.00% 17.00% Med
Availability 0.00% 15.00% 17.00% Med
Policy -
Preventive
Defensive
Measure Enclosure B
Quantitiative
Values
Low Mean High Variability
Strong
Passwords
Costs
Policy Implementation n/a $45,000 n/a Low
Training/year per Sys Admin $8,000 $12,000 $15,000 Med
Training/year per user $3 $5 $12 Med
Maintenance Costs $10,000 $12,000 $20,000 Med
Factors
User Productivity 9.00% 28.00% 38.00% Med
Confidentiality 9.00% 28.00% 38.00% Low
Integrity 9.00% 28.00% 38.00% Low
Availability 9.00% 18.00% 28.00% Low
No Password
Policy
Costs
Policy Implementation n/a n/a n/a n/a
Training/year per Sys Admin n/a n/a n/a n/a
Training/year per user n/a n/a n/a n/a
Maintenance Costs n/a n/a n/a n/a
Factors
User Productivity 0.00% 0.00% 0.00% Low
Confidentiality -75.00% -50.00% 0.00% High
Integrity -75.00% -50.00% 0.00% High
Availability -75.00% -50.00% 0.00% High
Formal Security
Audits
Costs
Policy Implementation n/a $45,000 n/a Low
Training/year per Sys Admin $10,000 $12,000 $20,000 Med
Maintenance Costs $10,000 $12,000 $20,000 Med
Factors
User Productivity -10.00% 0.00% 0.00% Low
Confidentiality -5.00% 20.00% 40.00% High
Integrity -5.00% 20.00% 40.00% High
Availability -5.00% 20.00% 40.00% High
Disallow
Wireless
Costs
Policy Implementation n/a $20,000 n/a Low
Training/year per User $5 $10 $30 Med
Maintenance Costs $10,000 $12,000 $20,000 Med
Factors
User Productivity -10.00% -5.00% 0.00% Low
Confidentiality 0.00% 5.00% 10.00% Low
Integrity 0.00% 5.00% 10.00% Low
Availability 0.00% 5.00% 10.00% Low
Allow Wireless
Costs
Policy Implementation n/a $45,000 n/a Low
Training/year per Sys Admin $20,000 $30,000 $40,000 Med
Training/year per User $5 $10 $30 Med
Maintenance Costs $10,000 $12,000 $20,000 Med
Factors
User Productivity 40.00% 60.00% 70.00% Med
Confidentiality -60.00% -30.00% 0.00% High
Integrity -60.00% -30.00% 0.00% High
Availability -60.00% -30.00% 0.00% High
How to read this table: The Qualitative Values are a judgment based on the assessment from industry experts on the tools' effectiveness.
Each defensive measure has several instances that vary in costs and effectiveness. The Low, Mean, and High values represent a
characterization of reviews found in different consumer review periodicals as they relate to user productivity, confidentiality, integrity, and
availability. The variability indicates the concentration of the data about the mean. The Low and High are the minimum and maximum possible
values, respectively. Costs are in U.S. dollars. A factor value of 5.00% indicates an improvement of 5%. A value of -5.00% indicates that the
factor is degraded by 5%. These values are modifiers to the existing levels. For example from a base Confidentiality level of .8 a factor value of -
25% would result in a new Confidentiality factor of 0.8 - (0.8*0.25) = 0.6. A positive value results in a positive change in the factor. 
Restrict
Removable
Media
Costs
Policy Implementation n/a $20,000 n/a Low
Training/year per Sys Admin $10,000 $12,000 $20,000 Med
Training/year per User $5 $10 $30 Med
Maintenance Costs $10,000 $12,000 $20,000 Med
Factors
User Productivity -50.00% -40.00% -30.00% Low
Confidentiality 0.00% 5.00% 10.00% Low
Integrity 0.00% 5.00% 10.00% Low
Availability 0.00% 5.00% 10.00% Low
Unmonitored
Personal Use
Costs
Policy Implementation n/a $20,000 n/a Low
Training/year per Sys Admin $0 $0 $0 Med
Training/year per User $0 $0 $0 Med
Maintenance Costs $0 $0 $0 Med
Factors
User Productivity -20.00% -10.00% 10.00% High
Confidentiality -20.00% -10.00% 10.00% High
Integrity -19.00% -10.00% 10.00% High
Availability -19.00% -10.00% 10.00% High
Restricted
Personal Use/
Detailed User
Tracking
Costs
Policy Implementation n/a $45,000 n/a Low
Training/year per Sys Admin $20,000 $30,000 $40,000 Med
Training/year per User $3 $5 $10 Med
Maintenance Costs $10,000 $12,000 $20,000 Med
Factors
User Productivity -40.00% 0.00% 25.00% High
Confidentiality -10.00% 28.00% 38.00% High
Integrity 9.00% 28.00% 38.00% Med
Availability 9.00% 18.00% 28.00% Low
User Training
Required
Costs
Policy Implementation n/a $45,000 n/a Low
Training/year per User $5 $10 $13 Med
Maintenance Costs $10,000 $12,000 $20,000 Med
Factors
User Productivity 2.00% 15.00% 30.00% Med
Confidentiality 10.00% 30.00% 50.00% High
Integrity 10.00% 30.00% 50.00% High
Availability 10.00% 30.00% 50.00% High
Sys Admin
Training
Required
Costs
Policy Implementation n/a $45,000 n/a Low
Training/year per Sys Admin $20,000 $30,000 $40,000 Med
Maintenance Costs $10,000 $18,000 $20,000 Med
Factors
User Productivity 20.00% 40.00% 60.00% Med
Confidentiality 10.00% 30.00% 50.00% Med
Integrity 10.00% 30.00% 50.00% Med
Availability 10.00% 30.00% 50.00% Med
