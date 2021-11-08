# Modelling, Reverse Engineering, and Learning Software Variability (HDR, Mathieu Acher)

[Habilitation à diriger des recherches](https://fr.wikipedia.org/wiki/Habilitation_%C3%A0_diriger_des_recherches) (aka HDR) is a diploma that "sanctions the recognition of the candidate's high scientific level, the originality of his or her approach in a field of science, his or her ability to master a research strategy in a sufficiently broad scientific or technological field and his or her capacity to supervise young researchers". 

HDR is a good excuse to share research works, present them in an original, integrated way, and also provide long-term perspectives. 
I've tried my best to synthesize my research results since 2008, in collaboration with many Masters' students, PhD students, interns, post-docs, engineers, professors, colleagues and friends.  
The manuscript is entitled "Modelling, Reverse Engineering, and Learning Software Variability", 190 pages long. It will be available after the defense.

The defense will take place in the room Métivier at IRISA/Inria Rennes, France. 
The jury will remotely attend. It will be broacasted live through Zoom and Youtube (links are coming, stay tuned!). 

## Abstract

> Society expects software to deliver the right functionality, in a
> short amount of time and with fewer resources, in every possible
> circumstance whatever are the hardware, the operating systems, the
> compilers, or the data fed as input. For fitting such a diversity of
> needs, it is common that software comes in many variants and is highly
> configurable through configuration options, runtime parameters,
> conditional compilation directives, menu preferences, configuration
> files, plugins, etc. As there is no one-size-fits-all solution,
> software variability ("the ability of a software system or artifact to
> be efficiently extended, changed, customized or configured for use in
> a particular context") has been studied the last two decades and is a
> discipline of its own. Though highly desirable, software variability
> also introduces an enormous complexity due to the combinatorial
> explosion of possible variants. For example, the Linux kernel has
> 15000+ options and most of them can have 3 values: "yes", "no", or
> "module". Variability is challenging for maintaining, verifying, and
> configuring software systems (Web applications, Web browsers, video
> tools, etc.). It is also a source of opportunities to better
> understand a domain, create reusable artefacts, deploy
> performance-wise optimal systems, or find specialized solutions to
> many kinds of problems. In many scenarios, a model of variability is
> either beneficial or mandatory to explore, observe, and reason about
> the space of possible variants. For instance, without a variability
> model, it is impossible to establish a sampling strategy that would
> satisfy the constraints among options and meet coverage or testing
> criteria. I address a central question in this HDR manuscript: How to
> model software variability? I detail several contributions related to
> modelling, reverse engineering, and learning software variability. 
> 
> I first contribute to support the persons in charge of manually
> specifying feature models, the de facto standard for modeling
> variability. I develop an algebra together with a language for
> supporting the composition, decomposition, diff, refactoring, and
> reasoning of feature models. I further establish the syntactic and
> semantic relationships between feature models and product comparison
> matrices, a large class of tabular data. I then empirically
> investigate how these feature models can be used to test in the large
> configurable systems with different sampling strategies. Along with this
> effort, I report on the attempts and lessons learned when defining the
> "right" variability language. From a reverse engineering perspective,
> I contribute to synthesize variability information into models and
> from various kinds of artefacts. I develop foundations and methods for
> reverse engineering feature models from satisfiability formulae,
> product comparison matrices, dependencies files and architectural
> information, and from Web configurators. I also report on the degree
> of automation and show that the involvement of developers and domain
> experts is beneficial to obtain high-quality models. Thirdly, I
> contribute to learning constraints and non-functional properties
> (performance) of a variability-intensive system. I describe a
> systematic process "sampling, measuring, learning" that aims to
> enforce or augment a variability model, capturing variability
> knowledge that domain experts can hardly express. I show that
> supervised, statistical machine learning can be used to synthesize
> rules or build prediction models in an accurate and interpretable way.
> This process can even be applied to huge configuration space, such as
> the Linux kernel one. 
> 
> Despite wide applicability and observed benefits, I show that each
> individual line of contributions has limitations. I defend the
> following answer: a supervised, iterative process (1) based on the
> combination of reverse engineering, modelling, and learning
> techniques; (2) capable of integrating multiple variability
> information (eg expert knowledge, legacy artefacts, dynamic
> observations). 
> 
> Finally, this work opens different perspectives related to so-called
> deep software variability, security, smart build of configurations,
> and (threats to) science.

## Committee

 * Krzysztof Czarnecki (University of Waterloo, Canada), reviewer
 * Ina Schaefer (Technische Universität Braunschweig, Germany), reviewer
 * Romain Rouvoy (University of Lille, IUF, France), reviewer
 * Julia Lawall (Inria, France), examiner
 * Christian Kästner (CMU, USA), examiner
 * Jean-Marc Jézéquel (University of Rennes 1, France), examiner 




