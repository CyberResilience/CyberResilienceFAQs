# Cyber Resilience Frequently Asked Questions

## Section 1
Editors Note:
Eventually the FAQs will be organized into sections by topic.
But for now they are just random

Editors Note:
should we anchor/bookmark questions?
Can template do it? or do we need to put html inline -
see first faq for how ugly it looks.


### <a id="whatIsCyberResilience">What is Cyber Resilience?</a>

Cyber Resilience is achieved by making it costly and difficult for intruders to break into our environment and maintain presence in the systems, as well as strengthening the system-of-system’s ability to recover business functions after adversity. One of the first steps to kick-start a Cyber Resilience program is by identifying critical data, processes and systems that are high value assets and develop plans to address gaps in resiliency. Once identified, those key assets can be designed, implemented and maintained appropriately by leveraging existing cyber resilience best practices. This perspective is particularly relevant to address Advanced Persistent Threats (APT) which may execute a coordinated, destructive long-lasting attack towards an organization. APT actors aim to compromise not only the most vulnerable or less protected assets in order to carry out their mission. In fact, they may specifically decide to attack assets that can provide them maximum gain towards the achievement of their objectives. These assets are referred to as High Value Targets.

The ultimate definition of Cyber Resilience:

Business world - Cyber Resilience is an outcome of Cyber Security and Operational Resilience and is defined as “the ability of an organization to transcend any stresses, failures, hazards and threats to its cyber resources within the organization and its ecosystem, such that the organization can confidently pursue its mission, enable its culture and maintain its desired way of operating” (WEF, 2022).

Technical world - Cyber Resilience is an extension of Cyber Security and is defined as “the ability to anticipate, withstand, recover from, and adapt to adverse conditions, stresses, attacks, or compromises on systems that use or are enabled by cyber resources. Cyber resiliency is intended to enable mission or business objectives that depend on cyber resources to be achieved in a contested cyber environment.” (NIST 800-160 v2 r1). Cyber Resilience is grounded on NIST 800-160 v2 r1 and MITRE CREF (the most authoritative industry resources known nowadays).


put answer here

"the ability to continuously deliver the intended outcome despite adverse events"
reference "Cyber Resilience - fundamentals for a definition" Bjorck et al,
https://www.researchgate.net/publication/283102782_Cyber_Resilience_-_Fundamentals_for_a_Definition

"the ability to prepare and plan for, to absorb, recover from, and more
successfully adapt to adverse events"
reference NAS via hausken
https://www.researchgate.net/publication/283102782_Cyber_Resilience_-_Fundamentals_for_a_Definition

"the ability of a system, person, or organization to recover from, defy
or resist from any shock, insult, or disturbance"
ref kishor via hausken

"Cyber resilience is the ability of an actor to resist, respond, and recover
from cyber incidents to ensure the actor's operational continuity"
ref Hausken

"assuming two equally performing systems A and B subjected
to an impact (resulting from a cyber-attack) that left both
systems with an equal performance degradation, the
resiliency of system A is greater if after a given period T
it recovers to a higher level of performance than that of
system B."
ref linkov

"The ability to anticipate, withstand, recover from, and
adapt to adverse conditions, stresses, attacks, or
compromises on systems that use or are enabled by cyber
resources."
Source(s):
NIST SP 800-172

"The ability to anticipate, withstand, recover from, and
adapt to adverse conditions, stresses, attacks, or
compromises on systems that use or are enabled by cyber
resources.
Cyber resiliency is intended to enable mission or
business objectives that depend on cyber resources to be
achieved in a contested cyber environment."
Source(s):
NIST SP 800-160 Vol. 2 Rev. 1
NIST SP 800-172A from NIST SP 800-160 Vol. 2 Rev. 1

"Cyber resilience is the ability of an organization to
transcend any stresses, failures, hazards and threats to its
cyber resources within the organization and its ecosystem,
such that the organization can confidently pursue its
mission, enable its culture and maintain its desired way of
operating."
https://www3.weforum.org/docs/WEF_Cyber_Resilience_Index_2022.pdf

“Cyber resilience refers to the ability to protect
electronic data and systems from cyberattacks, as well as to
resume business operations quickly in case of a successful
attack.”
https://www.ecb.europa.eu/paym/cyber-resilience/html/index.en.html

“‘Cyber resilience’ is the ability for organisations to
prepare for, respond to and recover from cyber attacks and
security breaches.”
https://www.gov.uk/government/collections/cyber-resilience

“The ability to anticipate, withstand, recover from, and
adapt to adverse conditions, stresses, attacks, or
compromises on systems that use or are enabled by cyber
resources.”
https://csrc.nist.gov/glossary/term/cyber_resiliency

“‘Cyber resiliency (also referred to as cyber resilience) is
the ability to anticipate, withstand, recover from, and
adapt to adverse conditions, stresses, attacks, or
compromises on cyber resources.”
https://www.mitre.org/sites/default/files/PR_17-1434.pdf

This is from Francesco – collated from various sources (mainly MITRE and ISF).
"The science of anticipation defined mission assurance. Mission assurance defines engineering practices to secure enterprises from advanced threats. Cyber resilience is part of mission assurance, focused on advanced cyber threats."


### What is the relationship between Cyber Resilience and Cyber Security?

Cyber Resilience is an overlay and extension of Cyber Security.
There are four key differences between Cyber Resilience and Cyber Security (source: www.highvaluetarget.org):

Difference #1: Cybersecurity encompasses a wide set of controls from NIST 800-53 r5 (by definition, a set of security baseline controls), roughly 1100 controls. Cyber resilience aims to extend the depth at which a small set of controls are designed and then perform (this set of controls is outlined in NIST 800-53 but NIST 800-160 and 800-172 expand these), roughly 200 controls.

Difference #2: Cybersecurity focuses on protecting all assets, with special focus on high value assets (business view). Cyber resilience focuses on protecting primarily high value targets (adversary view).

Difference #3: Cybersecurity focuses on “severe but plausible” threat scenarios against adversaries who go after the less protected and the most vulnerable – NIST 800-53 controls allow to provide adequate protection against these. Cyber resilience focuses on “extreme but plausible” threat scenarios against adversaries who may pivot from primary organizational impacts to secondary impacts potentially causing unknown harm to the organization as a whole – NIST 800-160 and NIST 800-172 provide the needed techniques and approaches which have corresponding controls in NIST 800-53 r5 however at a deeper level of detail.

Difference #4: Cybersecurity focuses on reducing likelihood of occurrence as well as reducing likelihood of impact through the application of security frameworks such as the NIST CSF. Security is about keeping adversary from doing harm. Cyber resilience focuses on reducing magnitude of impact which can be achieved by specific security architecture and engineering practices such as MITRE CREF. Resiliency recognizes harm may occur and how to maximize mission achievement despite that.


### What is the relationship between Cyber Resilience and Business Resilience?
Business Resilience is the ability for a business or organization to continue to move foward with it's business prupose while reacting and recovering to unknown challanges.  It is generally a key driver for any risk program.  Business Resilience, and the policies and tollerances that are agreed upon by the risk office should be the drivers for a Cyber Resilience program.  In other words, a Cyber Resilience program should fufill the goals of a Business Resiliance plan or program, where technology is conserned.


### Where can I find out more about Cyber Resilience?
- Blogs
- Videos
  - [RSA 2021 - Cyber Resilience: Say What?](https://www.youtube.com/watch?v=XamYaMUkop4)
  - [Valiant Technology - Cybersecurity Resilience Frameworks](https://www.youtube.com/watch?v=9xZ6dYky5JQ)
- Intro Material

### How are NIST publications relevant to cyber resilience?
<<Renita>>

### How is NIST SP800-160 relevant for cyber resilience?
The NIST SP 800-160 (Vol. 2 Revision 1, 2021) is focused on the development of cyber resilient systems. In the current landscape of still-evolving cyber resilience frameworks, the NIST SP 800-16 Vol. 2 is one of the major frameworks that comprehensively addresses cyber resilience. Some other frameworks for cyber-resilience that have been developed include those put forth in whitepapers by the MITRE and World Economic Forum. Adopting a systems-engineering foundation, this SP incorporate principles from systems engineering, security, resilience, and risk management. (Note: NIST SP 800-160- Vol.1 first published in 2016, is focused on the development of multidisciplinary approaches for engineering secure and trustworthy systems.)

Cyber resiliency is the ability to anticipate, withstand, recover from, and adapt to adverse conditions, stresses, attacks, or compromises on systems that use or are enabled by cyber resources.Consequently, cyber resilience engineering is defined as follows:

Engineering that intends to architect, design, develop, implement, maintain, and sustain the trustworthiness of systems with the capability to anticipate, withstand, recover from, and adapt to adverse conditions, stresses, attacks, or compromises that use or are enabled by cyber resources.

The NIST-SP 800-160 defines cyber resilience and offers a set of four goals (anticipate, withstand, recover, adapt) and eight objectives (prevent/avoid, prepare, continue, constrain, reconstitute, understand, transform, re-architect). In addition, this framework offers a set of fourteen techniques and approaches, strategic and structural design principles, and clarifies the relationship between various cyber resiliency constructs. 

Notably, this SP emphasizes that cyber resiliency differs with the life cycle of a system and calls for the need for customized goals and objectives that benefit stakeholders at every stage of the system’s life cycle. Additionally, the document provides guidance for adapting cyber resiliency to different kinds of environments such as enterprise systems, cyber physical systems, and critical infrastructure systems, among others.

The interested reader is referred to the document here: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-160v2r1.pdf



### What standards and official publications exist?
- [NIST SP800-160](https://csrc.nist.gov/publications/detail/sp/800-160/vol-2/final)
- [MITRE Cyber Resilience Analysis (SCRAM)](https://www.mitre.org/publications/technical-papers/structured-cyber-resiliency-analysis-methodology)
- [CERT Resilience Management Model (RMM)](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=9881)
- [MITRE Cyber Resiliency Design Principles](https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf)
- [Cyber ResilienceReview (CRR) tool](www.us-cert.gov/ccubedvp/assessments)


Cyber resilience in aviation

1. Lykou, G., Anagnostopoulou, A., & Gritzalis, D. (2018, June). Implementing cyber-security measures in airports to improve cyber-resilience. In 2018 Global Internet of Things Summit (GIoTS) (pp. 1-6). IEEE.
2. Lykou, G., Anagnostopoulou, A., & Gritzalis, D. (2018). Smart airport cybersecurity: Threat mitigation and cyber resilience controls. Sensors, 19(1), 19.
3. Lykou, G., Iakovakis, G., & Gritzalis, D. (2019). Aviation cybersecurity and cyber-resilience: assessing risk in air traffic management. In Critical Infrastructure Security and Resilience (pp. 245-260). Springer, Cham.

Cyber resilience metrics

1. Graubart, R., & Bodeau, D. (2016). Cyber resilience metrics: Key observations. MITRE CORP MCLEAN VA.
2. Vugrin, E. D., & Turgeon, J. (2014). Advancing cyber resilience analysis with performance-based metrics from infrastructure assessments. In Cyber Behavior: Concepts, Methodologies, Tools, and Applications (pp. 2033-2055). IGI Global.
3. Ford, R., Cavalho, M., Mayron, L., & Bishop, M. (2012). Toward metrics for cyber resilience. In 21st EICAR (European Institute for Computer Anti-Virus Research) annual conference proceedings.

Organizational perspectives for cyber resilience

1.Ferdinand, J. (2015). Building organisational cyber resilience: A strategic knowledge-based view of cyber security management. Journal of business continuity & emergency planning, 9(2), 185-195.
2. Llansó, T., & McNeil, M. (2021, January). Towards an organizationally-relevant quantification of cyber resilience. In Proceedings of the 54th Hawaii International Conference on System Sciences (p. 7065).
3. Kott, A., Blakely, B., Henshel, D., Wehner, G., Rowell, J., Evans, N., ... & Møller, A. (2018). Approaches to enhancing cyber resilience: report of the North Atlantic Treaty Organization (NATO) workshop IST-153. arXiv preprint arXiv:1804.07651.
4. Hausken, K. (2020). Cyber resilience in firms, organizations and societies. Internet of Things, 11, 100204.

Others

1. Groenendaal, J., & Helsloot, I. (2021). Cyber resilience during the COVID‐19 pandemic crisis: A case study. Journal of Contingencies and Crisis Management, 29(4), 439-444.
2. Galinec, D., & Steingartner, W. (2017, November). Combining cybersecurity and cyber defense to achieve cyber resilience. In 2017 IEEE 14th International Scientific Conference on Informatics (pp. 87-93). IEEE.
3. Peter, A. S. (2017). Cyber resilience preparedness of Africa’s top-12 emerging economies. International Journal of Critical Infrastructure Protection, 17, 49-59.
4. Brennan, G., Joiner, K., & Sitnikova, E. (2019). Architectural choices for cyber resilience. Australian Journal of Multi-Disciplinary Engineering, 15(1), 68-74.
5. Carayannis, E. G., Grigoroudis, E., Rehman, S. S., & Samarakoon, N. (2019). Ambidextrous cybersecurity: The seven pillars (7Ps) of cyber resilience. IEEE Transactions on Engineering Management, 68(1), 223-234.
6. Kott, A., & Theron, P. (2020). Doers, not watchers: Intelligent autonomous agents are a path to cyber resilience. IEEE Security & Privacy, 18(3), 62-66.
7. Tran, H., Campos-Nanez, E., Fomin, P., & Wasek, J. (2016). Cyber resilience recovery model to combat zero-day malware attacks. computers & security, 61, 19-31.
8. Bellini, E., & Marrone, S. (2020, October). Towards a novel conceptualization of Cyber Resilience. In 2020 IEEE World Congress on Services (SERVICES) (pp. 189-196). IEEE.
9. Choudhury, S., Rodriguez, L., Curtis, D., Oler, K., Nordquist, P., Chen, P. Y., & Ray, I. (2015, October). Action recommendation for cyber resilience. In Proceedings of the 2015 Workshop on Automated Decision Making for Active Cyber Defense (pp. 3-8).
10. Abraham, C., & Sims, R. R. (2021). A comprehensive approach to cyber resilience. MIT Sloan Management Review.
11. Conklin, W. A., Shoemaker, D., & Kohnke, A. (2017, March). Cyber resilience: Rethinking cybersecurity strategy to build a cyber resilient architecture. In ICMLG2017 5th International Conference on Management Leadership and Governance (p. 105).
12. Alexeev, A., Henshel, D. S., Levitt, K., McDaniel, P., Rivera, B., Templeton, S., & Weisman, M. (2017, October). Constructing a science of cyber-resilience for military systems. In NATO IST-153 Workshop on Cyber Resilience (pp. 23-25).
13. Fink, G. A., Griswold, R. L., & Beech, Z. W. (2014, August). Quantifying cyber-resilience against resource-exhaustion attacks. In 2014 7th International Symposium on Resilient Control Systems (ISRCS) (pp. 1-8). IEEE.
14. Dickson, F., & Goodwin, P. (2019). Five key technologies for enabling a Cyber-resilience framework. US45455119, IBM.
15. Zou, B., Choobchian, P., & Rozenberg, J. (2020). Cyber Resilience of Autonomous Mobility Systems: Cyber Attacks and Resilience-Enhancing Strategies. World Bank Policy Research Working Paper, (9135).
16. Kleij, R. V. D., & Leukfeldt, R. (2019, July). Cyber resilient behavior: Integrating human behavioral models and resilience engineering capabilities into cyber security. In International conference on applied human factors and ergonomics (pp. 16-27). Springer, Cham.
17. Hammer, A. E., Miller, T. H., & Uribe, E. (2020). Cyber Resilience as a Deterrence Strategy (No. SAND-2020-9589; SAND-2020-5016). Sandia National Lab.(SNL-CA), Livermore, CA (United States); Sandia National Laboratories, Minneapolis, MN.
18. Škanata, D. (2020). Improving Cyber Security with Resilience. Annals of Disaster Risk Sciences: ADRS, 3(1), 0-0.


### What is MITRE Cyber Resilience Analysis (SCRAM)?
put answer here
 <<Calin>>

For more information see
[MITRE Cyber Resilience Analysis (SCRAM)](https://www.mitre.org/publications/technical-papers/structured-cyber-resiliency-analysis-methodology)
  
### What is the CERT Resilience Management Model?
put answer here
<<Josh>>
  
For more information see
[CERT Resilience Management Model (RMM)](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=9881)

### What are the MITRE Cyber Resiliency Design Principles?
put answer here
<<Josh>>
  
For more information see
[MITRE Cyber Resiliency Design Principles] (https://www.mitre.org/sites/default/files/publications/PR%2017-0103%20Cyber%20Resiliency%20Design%20Principles%20MTR17001.pdf)

### What is the Cyber Resilience Review (CRR) tool?
put answer here
<<Josh>>
  
For more information see
[Cyber ResilienceReview (CRR) tool](www.us-cert.gov/ccubedvp/assessments)

### How does Cyber Resilience relate to Enterprise Risk Management (ERM)?
put answer here
<<Christina & Walter>>

### How does Cyber Resilience fit with Mitre ATT&CK?
put answer here
<<Francesco>>

### How is DIE (distributed, immutable, ephemeral) relevant to Cyber Resilience?
put answer here

### What is the business justification for increasing Cyber Resilience?
Similar to cybersecurity spend, cyber-resilience spend
can be justified using quantitative risk analysis such as in
[_How to Measure Anything in Cybersecurity Risk_](https://www.barnesandnoble.com/w/how-to-measure-anything-in-cybersecurity-risk-douglas-w-hubbard/1122610668).
