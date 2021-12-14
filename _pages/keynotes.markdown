---
layout: page
title: Keynote Speakers
permalink: /keynotes/
order: 3
---
<div id="secondary" class="widget-area sidey" role="complementary">

      <ul class="xoxo">

          <li id="custom_html-3" class="widget_text widget-container widget_custom_html"><div class="textwidget custom-html-widget"><a class="twitter-timeline" data-width="300" data-height="600" data-theme="light" href="https://twitter.com/sefm_conf?ref_src=twsrc%5Etfw">Tweets by sefm2021</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> </div></li>	</ul>
</div>

<h2><a href="https://www-users.cs.york.ac.uk/~alcc/">Ana Cavalcanti</a>, University of York, UK</h2>

<p><img src="{{ '/assets/ana.jpg' | relative_url }}" class="imageSpeaker" align="left"/></p>

<p><strong>Title:</strong> RoboWorld: where can my robot work?</p>

<p><a href="https://www.youtube.com/watch?v=AaGYZjSBO5c&ab_channel=FormalMethodsEurope">Watch the keynote session on YouTube</a></p>

<p><strong>Abstract:</strong> The behaviour of a robot affects and is affected by its environment.  So, many of the expected and desirable properties of a robotic system depend on properties of its environment. While a complete model of that environment is very difficult, if not impossible, to construct, we can realistically capture assumptions about the environment.  In this talk, we present RoboWorld, a controlled natural language with a process-algebraic semantics that can be used to define (a) the operational requirements of a robot, and (b) how the
robot interacts with its environment.  RoboWorld is part of the RoboStar framework of domain-specific languages that support proof, simulation, and testing of robotic systems. RoboWorld plays a central role in all these forms of verification.</p>

<p><strong>Biography:</strong> Ana Cavalcanti (University of York) is Professor of Software Verification and Royal Academy of Engineering Chair in Emerging Technologies working on Software Engineering for Robotics: modelling, validation, simulation, and testing. She currently leads the RoboStar research group at the University of York. She held a Royal Society-Wolfson Research Merit Award and a Royal Society Industry Fellowship to work with QinetiQ in avionics. She has chaired the Programme Committee of various well-established international conferences, is on the editorial board of four international journals, and is Chair of the board of the Formal Methods Europe Association. Her current research is on theory and practice of verification and
testing for robotics.</p>

<br>

<h2><a href="http://www.cs.toronto.edu/~chechik/">Marsha Chechik</a>, University of Toronto, Canada</h2>

<p>
<img src="{{ '/assets/chechik.png' | relative_url }}" class="imageSpeaker" align="left"/>
</p>

<p><strong>Title:</strong> On Safety, Assurance and Reliability:  A Software Engineering Perspective</p>

<p><a href="https://www.youtube.com/watch?v=zBg515ZvmYc&ab_channel=FormalMethodsEurope">Watch the keynote session on YouTube</a></p>

<p>
<strong>Abstract:</strong> From financial services platforms to social networks to vehicle control, software has come to mediate many activities of daily life. Governing bodies and standards organizations have responded to this trend by creating regulations and standards to address issues such as safety, security and privacy. In this environment, the compliance of software development to standards and regulations has emerged as a key requirement. Compliance claims and arguments are often captured in assurance cases, with linked evidence of compliance. Evidence can come from testcases, verification proofs, human judgement, or a combination of these. That is, we try to build (safety-critical) systems carefully according to well justified methods and articulate these justifications in an assurance case that is ultimately judged by a human.
Building safety arguments for traditional software systems is difficult ­­ they are lengthy and expensive to maintain, especially as software undergoes change. Safety is also notoriously non­compositional ­­ each subsystem might be safe but together they may create unsafe behaviors. It is also easy to miss cases, which in the simplest case would mean developing an argument for when a condition is true but missing arguing for a false condition. Furthermore, many ML­based systems are becoming safety­critical.  For example, recent Tesla self­driving cars misclassified emergency vehicles and caused multiple crashes. ML­based systems typically do not have precisely specified and machine­verifiable requirements. While some safety requirements can be stated clearly: "the system should detect all pedestrians at a crossing", these requirements are for the entire system, making them too high­level for safety analysis of individual components. Thus, systems with ML components (MLCs) add a significant layer of complexity for safety assurance.
I argue that safety assurance should be an integral part of building safe and reliable software systems, but this process needs support from advanced software engineering and software analysis. In this talk, I outline a few approaches for development of principled, tool-supported methodologies for creating and managing assurance arguments. I then describe recent work on specifying and verifying reliability requirements for machine-learned components in safety-critical domains.
</p><p>
<strong>Biography:</strong> Marsha Chechik is Professor and Chair in the Department of Computer Science at the University of Toronto. She received her Ph.D. from the University of Maryland in 1996. Prof. Chechik’s research interests are in the application of formal methods to improve the quality of software. She has authored over 200 papers in formal methods, software specification and verification, computer safety and security and requirements engineering.  Marsha Chechik has been Program Committee Co-Chair of the 2021 International Conference on Foundations of Software Engineering (ESEC/FSE’21), 2018 International Conference in Software Engineering (ICSE’18), 2016 International Conference on Tools and Algorithms for the Construction and Analysis of Systems (TACAS'16), the 2016 Working Conference on Verified Software: Theories, Tools, and Experiments (VSTTE16), the 2014 International Conference on Automated Software Engineering (ASE'14), the 2008 International Conference on Concurrency Theory (CONCUR'08), the 2008 International Conference on Computer Science and Software Engineering (CASCON'08), and the 2009 International Conference on Formal Aspects of Software Engineering (FASE'09). She is a Distinguished Member of ACM and Vice Chair of ACM SIGSOFT.
</p>

<br>

<h2><a href="https://lafhis.dc.uba.ar/~suchitel">Sebastian Uchitel</a>, University of Buenos Aires, Argentina; and Imperial College London, UK</h2>

<p>
<img src="{{ '/assets/Sebas.jpeg' | relative_url }}" class="imageSpeaker" align="left"/>
</p><p>
<strong>Title:</strong> Controller synthesis for Adaptive Mobile Robots. Abstractions, all change!?</p>

<p><a href="https://www.youtube.com/watch?v=uE8KNSU1MYE&ab_channel=FormalMethodsEurope">Watch the keynote session on YouTube</a></p>

<p>
<strong>Abstract:</strong> Discrete event controller synthesis promises correct-by-construction strategies for controlling reactive systems to ensure user specified goals. Runtime synthesis takes this one step further, enabling correct runtime adaptation when a reactive system's goals, capabilities, or environment change. The need for synthesis in mobile robotic systems is particularly telling. Despite the wide availability of general purpose mobile robots (particularly Unmanned Aerial Vehicles - UAVs), the ability of end-users (individuals and organisations) to exploit them to their full potential is limited. Either complex and error prone programming is required or graphical mission planning interfaces are used to model simple, non-reactive missions.  The use of synthesis and runtime synthesis for mobile robots has many challenges ahead. In this talk I will discuss how we addressed some of them by revisiting both (1) the abstractions used to specify and synthesise discrete event controllers and (2) the architectural abstractions needed to successfully deploy synthesis technology on both fixed wing and multi-rotor systems.</p>
<p>
<strong>Biography:</strong> Sebastian Uchitel is a Professor at University of Buenos Aires, Principal Investigator at CONICET, and holds a Readership at Imperial College London. He received his undergraduate Computer Science degree from University of Buenos Aires and his Phd in Computing from Imperial College London. His research interests are in behaviour modelling, analysis and synthesis applied to requirements engineering, software architecture and system design, and in particular the use of synthesis at runtime to support system adaptation. He is associate editor in chief of Transactions on Software Engineering and has held editorial responsibilities in Communications of the ACM, the Requirements Engineering Journal and the Science of Computer Programming Journal. He was program co-chair of ASE’06 and ICSE’10, and General Chair of ICSE’17. He has served on the board of directors of the Argentine national oil company, YPF, and been an advisor to the chief cabinet officer of the Province of Buenos Aires. Sebastian Uchitel has been distinguished with the Philip Leverhulme Prize, the Konex Foundation Prize and the Houssay Prize. He is a member of the Argentine National Academy of Exact, Physical and Natural Sciences.
</p>
