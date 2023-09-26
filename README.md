## Android Testing and Analysis

Recent paper related to Android testing and Analysis

[ASE](#ase)

[ISSTA](#issta)

[ICSE](#icse)

[OOPSLA](#oopsla)

[ESEC/FSE](#esecfse)

[Reproduce Flaky](#reproduce-flaky)

[Test Event Reduction](#test-event-reduction)

[Non-crash bug](#non-crashing-bug)

### ASE
* 2023
  * Fine-Grained In-Context Permission Classification for Android Apps using Control-Flow Graph Embedding
  * ReuNify: A Step Towards Whole Program Analysis for React Native Android App
  * Scene-Driven Exploration and GUI Modeling for Android Apps
  * Vision-based Widget Mapping for Test Migration across Mobile Platforms: Are We There Yet?
  * Automated Fixing of Web UI Tests via Iterative Element Matching [[pdf]](https://gaoxiang9430.github.io/papers/ASE23_UITESTFIX.pdf)
* 2022
  * Accelerating OCR-Based Widget Localization for Test Automation of GUI Applications
  * A Comprehensive Evaluation of Android ICC Resolution Techniques
  * Automatically Detecting Visual Bugs in HTML5 <canvas> Games
  * Groundhog: An Automated Accessibility Crawler for Mobile Apps
  * The Metamorphosis: Automatic Detection of Scaling Issues for Mobile Apps
  * VITAS : Guided Model-based VUI Testing of VPA Apps
 
* 2021
  * Characterizing and Detecting Configuration Compatibility Issues in Android Apps
  * Finding the Missing Piece: Permission Specification Analysis for Android NDK
  * Automated Repair for Size-Based Inaccessibility Issues in Mobile Apps
  * Deep GUI: Black-box GUI Input Generation with Deep Learning
  * UI Test Migration Across Mobile Platforms

+ 2020
  + Seven Reasons Why: An In-Depth Study of the Limitations of Random Test Input Generation for Android
  + UI obfuscation and its effects on automated UI analysis for Android apps
  + Automated third-party library detection for Android applications: are we there yet?
  + [Owl eyes: spotting UI display issues via visual understanding](https://arxiv.org/ftp/arxiv/papers/2009/2009.01417.pdf)
  + Test automation in Open-Source Android Apps: A Large-Scale Empirical Study
  + [ER Catcher: A Static Analysis Framework for Accurate and Scalable Event-Race Detection in Android](http://seal.ics.uci.edu/publications/2020_ASE_ERCatcher.pdf)
  + Speeding up GUI Testing by On-Device Test Generation
+ 2019
  + Humanoid: a deep learning-based approach to automated black-box Android app testing
  + Test transfer across mobile apps through semantic mapping
  + Goal-driven exploration for Android applications
  + Randr: Record and replay for android applications via targeted runtime instrumentation
  + LIRAT: layout and image recognition driving automated mobile testing of cross-platform
  + DaPanda: detecting aggressive push notifications in Android apps
  + Test migration between mobile apps with similar functionality
  + MutAPK: source-codeless mutant generation for Android apps
  + Automating app review response generation
  + A qualitative analysis of Android taint-analysis results
  + OAuthLint: an empirical study on OAuth bugs in Android applications
  + Demystifying application performance management libraries for Android
  + Characterizing Android app signing issues
+ 2018
  + An empirical study of android test generation tools in industrial cases
  + Understanding and detecting evolution-induced compatibility issues in Android apps
  + Understanding and detecting callback compatibility issues for Android applications
  + Efficiently manifesting asynchronous programming errors in Android apps
  + On adopting linters to deal with performance concerns in Android apps
  + Self-protection of Android systems from inter-component communication attacks
  + [A tale of two cities: how WebView induces bugs to Android applications](http://sccpu2.cse.ust.hk/andrewust/files/ASE18-wDroid.pdf)
  + Characterizing and identifying misexposed activities in Android applications
  + Dual-force: understanding WebView malware via cross-language forced execution
+ 2017
  + SimplyDroid: efficient event sequence simplification for Android application
  + EHBDroid: beyond GUI testing for Android applications
  + Sketch-guided gui test generation for mobile applications
  + Systematically testing background services of mobile apps
  + UI driven Android application reduction
  + ANDROFLEET: testing WiFi peer-to-peer mobile apps in the large
  + Automated cross-platform inconsistency detection for mobile apps
  + Systematic reduction of GUI test sequences
  + EventFlowSlicer: a tool for generating realistic goal-driven GUI tests
  + Crowd intelligence enhances automated mobile testing
+ 2016
  + Automated model-based Android GUI testing using multi-level GUI comparison criteria
  + Reflection-aware static analysis of Android apps
  + Taming Android fragmentation: characterizing and detecting compatibility issues for Android apps
  + Relda2: an effective static analysis tool for resource leak detection in Android apps.

### ISSTA
* 2023
  * An Empirical Study of Functional Bugs in Android Apps [[pdf]](https://tingsu.github.io/files/ISSTA23-functional-bugs.pdf), [[repo]](https://github.com/Android-Functional-bugs-study/home)
  * Automatically Reproducing Android Bug Reports using Natural Language Processing and Reinforcement Learning [[pdf]](https://dennielzhang.github.io/files/issta2023-preprint.pdf), [[website]](https://sites.google.com/usc.edu/reprobot/home), [[tool]](https://github.com/USC-SQL/ReproBot-Artifact)
  * ConfFix: Repairing Configuration Compatibility Issues in Android Apps [[pdf]](https://chixu.netlify.app/files/ConfFix_huang.pdf), [[repo]](https://github.com/rudmannn/ConfFix)
  * DDLDroid: Efficiently Detecting Data Loss Issues in Android Apps [[artifact]](https://doi.org/10.5281/zenodo.7907006)
  * Guided Retraining to Enhance the Detection of Difficult Android Malware
  * Precise and Efficient Patch Presence Test for Android Applications against Code Obfuscation
  * ωTest: WebView-Oriented Testing for Android Applications [[pdf]](https://arxiv.org/abs/2306.03845), [[repo]](https://richardhooooo.github.io/wTest/)
* 2022
  * PermDroid: automatically testing permission-related behaviour of Android applications.
  * Detecting and fixing data loss issues in Android apps
  * Automatically detecting API-induced compatibility issues in Android apps: a comparative analysis (replicability study)
  * NCScope: hardware-assisted analyzer for native code in Android apps
  * Detecting resource utilization bugs induced by variant lifecycles in Android. 
* 2021

  * [An Infrastructure Approach to Improving Effectiveness of Android UI Testing Tools](https://wenyu.io/pub/issta21-toller.pdf)
  * [GUIDER: GUI Structure and Vision Co-Guided Test Script Repair for Android Apps](https://minxuepan.github.io/Pubs/guider.pdf)
  * [Semantic Matching of GUI Events for Test Reuse: Are We There Yet?](https://valerio-terragni.github.io/assets/pdf/mariani-issta-2021.pdf)
  * [Understanding and Finding System Setting-Related Defects in Android Apps](https://tingsu.github.io/files/issta21-Setdroid.pdf)
* 2020

  * Data loss detector: automatically revealing data loss bugs in Android apps
  * Automated classification of actions in bug reports of mobile apps
* 2019

  * SARA: self-replay augmented record and replay for Android in industrial cases
  * Improving random GUI testing with image-based widget detection
  * TestMig: migrating GUI test cases from iOS to Android
  * Mining Android crash fixes in the absence of issue- and change-tracking systems
  * LibID: reliable identification of obfuscated third-party Android libraries
  * QADroid: regression event selection for Android applications
  * Learning user interface element interactions
* 2018

  * Automatically translating bug reports into test cases for mobile apps
  * LAND: a user-friendly and customizable test generation tool for Android apps
  * CiD: automating the detection of API-related compatibility issues in Android apps
  * Test migration for efficient large-scale assessment of mobile app coding assignments
* 2017

  * Data flow oriented UI testing: exploiting data flows and UI elements to test Android applications
  * Semi-automated discovery of server-based information oversharing vulnerabilities in Android applications
* 2016

  * Monkey see, monkey do: effective generation of GUI tests with inferred macro events
  * Sapienz: multi-objective automated testing for Android applications
  * DroidRA: taming reflection to support whole-program analysis of Android apps
  * Energy-aware test-suite minimization for android apps
* 2015

  * Systematic execution of android test suites in adverse conditions

### ICSE
* 2023
  * COLUMBUS: Android App Testing Through Systematic Callback Exploration [[pdf]](https://dipanjan.in/papers/cbdroid-icse-2023.pdf)
  * Compatibility Issue Detection for Android Apps Based on Path-Sensitive Semantic Analysis [[pdf]](https://sen-chen.github.io/img_cs/pdf/icse2023-psdroid.pdf)
  * PTPDroid: Detecting Violated User Privacy Disclosures to Third-Parties of Android Apps 
  * AidUI: Toward Automated Recognition of Dark Patterns in User Interfaces [[pdf]](https://arxiv.org/pdf/2303.06782.pdf)
  * BADGE: Prioritizing UI Events with Hierarchical Multi-Armed Bandits for Automated UI Testing [[pdf]](https://wenyu.io/pub/icse23-badge.pdf)
  * Context-aware Bug Reproduction for Mobile Apps 
  * Demystifying Privacy Policy of Third-Party Libraries in Mobile Apps
  * Detecting Dialog-Related Keyboard Navigation Failures in Web Applications
  * Dependency Facade: The Coupling and Conflicts between Android Framework and Its Customization
  * Efficiency Matters: Speeding Up Automated Testing with GUI Rendering Inference [[pdf]](https://arxiv.org/pdf/2212.05203.pdf)
  * Ex pede Herculem: Augmenting Activity Transition Graph for Apps via Graph Convolution Network
  * Fill in the Blank: Context-aware Automated Text Input Generation for Mobile GUI Testing [[pdf]](https://arxiv.org/pdf/2212.04732.pdf)
  * Read It, Don't Watch It: Captioning Bug Recordings Automatically [[pdf]](https://arxiv.org/pdf/2302.00886.pdf)

* 2022
  * APER: Evolution-Aware Runtime Permission Misuse Detection for Android Apps. 
  * Demystifying Android Non-SDK APls: Measurement and Understanding
  * Difuzer: Uncovering Suspicious Hidden Sensitive Operations in Android Apps

  * GIFdroid: Automated Replay of Visual Bug Reports for Android Apps
  * JuCify: A Step Towards Android Code Unification for Enhanced Static Analysis
  * Large-scale Security Measurements on the Android Firmware Ecosystem
  * PROMAL: Precise Window Transition Graphs for Android via Synergy of Program Analysis and Machine Learning
  * Towards Automatically Repairing Compatibility Issues in Published Android Apps
  * Use of Test Doubles in Android Testing: An In-Depth Investigation
  * Analyzing User Perspectives on Mobile App Privacy at Scale
  * DescribeCtx: Context-Aware Description Synthesis for Sensitive Behaviors in Mobile
  * Domain-Specific Analysis of Mobile App Reviews Using Keyword-Assisted Topic Models
  * Fast and Precise Application Code Analysis using a Partial Library
  * Where is Your App Frustrating Users

* 2021

  * [ATVHunter: Reliable Version Detection of Third-Party Libraries for Vulnerability Identification in Android Apps](https://arxiv.org/pdf/2102.08172.pdf)
  * [An Empirical Analysis of UI-based Flaky Tests](https://arxiv.org/pdf/2103.02669.pdf)
  * [An Empirical Assessment of Global COVID-19 Contact Tracing Applications](https://arxiv.org/pdf/2006.10933.pdf)
  * [An Empirical Study on Deployment Faults of Deep Learning Based Mobile Applications](https://chenzhenpeng18.github.io/papers/ICSE21.pdf)
  * [App&#39;s Auto-Login Function Security Testing via Android OS-Level Virtualization](https://arxiv.org/pdf/2103.03511.pdf)
  * [Automatically Matching Bug Reports With Related App Reviews](https://arxiv.org/pdf/2102.07134.pdf)
  * [ Don&#39;t Do That! Hunting Down Visual Design Smells in Complex UIs against Design Guidelines](https://xin-xia.github.io/publication/icse213.pdf)
  * [Layout and Image Recognition Driving Cross-Platform Automated Mobile Testing](https://arxiv.org/pdf/2008.05182.pdf)
  * [It Takes Two to Tango: Combining Visual and Textual Information for Detecting Duplicate Video-Based Bug Reports](https://arxiv.org/pdf/2101.09194.pdf)
  * [Prioritize Crowdsourced Test Reports via Deep Screenshot Understanding](https://arxiv.org/pdf/2102.09747.pdf)
  * [RAICC: Revealing Atypical Inter-Component Communication in Android Apps](https://arxiv.org/pdf/2012.09916.pdf)
  * [IMGDroid: Detecting Image Loading Defects in Android Applications](https://o2lab.github.io/p/imgdroid.pdf)
* 2020

  * [LABLEDROID: Unblind your apps: predicting natural-language labels for mobile GUI components by deep learning](https://arxiv.org/pdf/2003.00380.pdf)
  * Translating video recordings of mobile app usages into replayable scenarios
  * Multiple-entry testing of Android applications by constructing activity launching contexts
  * How Android developers handle evolution-induced API compatibility issues: a large-scale study
  * ComboDroid: generating high-quality test inputs for Android apps via use case combinations
  * RoScript: a visual script driven truly non-intrusive robotic testing system for touch screen applications
  * [Time-travel testing of Android apps](https://mboehme.github.io/paper/ICSE20.TTT.pdf)
  * An empirical assessment of security risks of global Android banking apps
  * Accessibility issues in Android apps: state of affairs, sentiments, and ways forward
  * Collaborative bug finding for Android apps
* 2019

  * [IconIntent: automatic identification of sensitive UI widgets based on icon classification for Android apps](https://engineering.case.edu/groups/xusheng-xiao/sites/engineering.case.edu.groups.xusheng-xiao/files/docs/iconintent-icse2019.pdf)
  * [Mimic: UI compatibility testing system for Android apps](https://nsr.cse.buffalo.edu/wp-content/uploads/2019/06/mimic-icse2019.pdf)
  * Search-based energy testing of Android
  * Practical GUI testing of Android applications via model abstraction and refinement
  * Towards understanding and reasoning about Android interoperations
* 2018

  * Automated reporting of GUI design violations for mobile apps
  * Leveraging program analysis to reduce user-perceived latency in mobile applications
  * Software protection on the go: a large-scale empirical study on mobile app obfuscation
  * Repairing crashes in Android apps
  * DetReduce: minimizing Android GUI test suites for regression testing
  * [Augusto: exploiting popular functionalities for the generation of semantic GUI tests with Oracles](https://star.inf.usi.ch/media/papers/2018-icse-zuddas-augusto.pdf)
* 2017

  * Analysis and testing of notifications in Android wear applications
  * Adaptive unpacking of Android apps
  * Automatic text input generation for mobile testing
  * LibD: scalable and precise third-party library detection in android markets
* 2016

  * Reducing combinatorics in GUI testing of android applications
  * MobiPlay: a remote execution based record-and-replay tool for mobile applications
  * VDTest: an automated framework to support testing for virtual devices
  * PRADA: prioritizing android devices for apps by mining large-scale usage data

### OOPSLA

* 2021
  * [Fully Automated Functional Fuzzing of Android Apps for Detecting Non-Crashing Logic Bugs](https://tingsu.github.io/files/oopsla21-Genie.pdf)
* 2020
  * [A Large-Scale Longitudinal Study of Flaky Tests](https://www.jonbell.net/preprint/oopsla20flaky.pdf)
  * [LiveDroid: Identifying and Preserving Mobile App State in Volatile Runtime Environments](https://manu.sridharan.net/files/OOPSLA20LiveDroid.pdf)
* 2018
  * [Robust Relational Layouts Synthesis from Examples for Android](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/319644/3/oopsla18main-p215-p.pdf)
* 2016
  * [Finding Resume and Restart Errors in Android Applications](https://web.njit.edu/~ineamtiu/pubs/oopsla16shan.pdf)
* 2015
  * [Versatile Yet Lightweight Record-and-replay for Android](http://www.cs.ucr.edu/~neamtiu/pubs/oopsla15hu.pdf)
  * [Interactively Verifying Absence of Explicit Information Flows in Android Apps](https://theory.stanford.edu/~aiken/publications/papers/oopsla2015b.pdf)
  * [Scalable Race Detection for Android Applications](https://files.sri.inf.ethz.ch/website/papers/oopsla15-eventracer-android.pdf)

### ESEC/FSE
* 2023
  * Automata-based Trace Analysis for Aiding Diagnosing GUI Testing Tools for Android
  * Automated and Context-Aware Repair of Color-Related Accessibility Issues for Android Apps
  * Property-based Fuzzing for Finding Data Manipulation Errors in Android Apps
  * ViaLin: Path-Aware Dynamic Taint Analysis for Android

* 2022
  
  * AccessiText: Automated Detection of Text Accessibility Issues in Android Apps
  * Detecting Non-crashing Functional Bugs in Android Apps via Deep-State Differential Analysis
  * Cross-Device Record and Replay for Android Apps
  * Cross-Language Android Permission Specification
  * Toward Interactive Bug Reporting for (Android App) End-Users
  * Avgust: Automating Usage-Based Test Generation from Videos of App Executions
  
* 2021

  * [Benchmarking Automated GUI Testing for Android against Real-World Bugs](https://tingsu.github.io/files/fse21-themis.pdf)
  * [Checking Conformance of Applications against GUI Policies](https://www.cs.utexas.edu/~isil/venus.pdf)
  * [Data-Driven Accessibility Repair Revisited: On the Effectiveness of Generating Labels for Icons in Android Apps](https://github.com/XYIheng/AndroidTesting/blob/main/paper/ESECFSE/2021_3.pdf)
  * [An Empirical Study of GUI Widget Detection for Industrial Mobile Games  ](https://github.com/XYIheng/AndroidTesting/blob/main/paper/ESECFSE/2021_3.pdf)
* 2020

  * [All Your App Links Are Belong to Us: Understanding the Threats of Instant Apps Based Attacks](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2020_1.pdf)
  * [Automated Construction of Energy Test Oracles for Android](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2020_2.pdf)
  * [Object Detection for Graphical User Interface: Old Fashioned or Deep Learning or a Combination?](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2020_3.pdf)
  * [Static Asynchronous Component Misuse Detection for Android Applications](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2020_4.pdf)
* 2019

  * [Preference-Wise Testing for Android Applications](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2019_1.pdf)
  * [ServDroid: detecting service usage inefficiencies in Android applications](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2019_2.pdf)
  * [Together strong: cooperative Android app analysis](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2019_3.pdf)
* 2018

  * [AppFlow: Using Machine Learning to Synthesize Robust, Reusable UI Tests](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2018_1.pdf)
  * [Do Android Taint Analysis Tools Keep Their Promises?](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2018_2.pdf)
  * [FraudDroid: Automated Ad Fraud Detection for Android Apps](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2018_3.pdf)
  * [Neural-Augmented Static Analysis of Android Communication](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2018_4.pdf)
* 2017

  * [µDroid: An Energy-Aware Mutation Testing Framework for Android](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2017_1.pdf)
  * [PATDroid: permission-aware GUI testing of Android](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2017_2.pdf)
  * [Enabling Mutation Testing for Android Apps](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2017_3.pdf)
  * [Guided, Stochastic Model-Based GUI Testing of Android Apps](https://tingsu.github.io/files/fse17-stoat.pdf)
* 2016

  * [Understanding and detecting wake lock misuses for Android applications](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2016_1.pdf)
  * [DiagDroid: Android performance diagnosis via anatomizing asynchronous executions](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2016_2.pdf)
  * [Minimizing GUI event traces](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2016_3.pdf)
  * [What would users change in my app? summarizing app reviews for recommending software changes](https://github.com/mohui1999/AndroidTesting/blob/main/paper/ESECFSE/2016_4.pdf)

### Reproduce Flaky

* LIRAT: Layout and Image Recognition Driving Automated Mobile Testing of Cross-Platform (ASE '19)
* SARA: Self-Replay Augmented Record and Replay for Android in Industrial Cases (ISSTA '19)
* Record and replay for Android: are we there yet in industrial cases? （ESEC/FSE '17)
* RANDR: Record and Replay for Android Applications via Targeted Runtime Instrumentation (ASE '19)
* Translating video recordings of mobile app usages into replayable scenarios (ICSE '20)
* Versatile Yet Lightweight Record-and-replay for Android (OOPSLA '15)
* MobiPlay: A Remote Execution Based Record-and-replay Tool for Mobile Applications (ICSE '16)
* Mosaic: cross-platform user-interaction record and replay for the fragmented android ecosystem (ICSE '16)
* [A Large-Scale Longitudinal Study of Flaky Tests](http://taoxie.cs.illinois.edu/publications/oopsla20-flaky.pdf)(OOPSLA '20)
* [An Empirical Analysis of UI-based Flaky Tests](https://ui-flaky-test.github.io/) (ICSE '21)
* [Concurrency-related Flaky Test Detection in Android Apps](https://arxiv.org/pdf/2005.10762.pdf)
* [iDFlakies: A framework for detecting and partially classifying flaky tests](https://taoxie.cs.illinois.edu/publications/icst19-idflakies.pdf) (ICST '19)
* [DeFlaker: Automatically detecting flaky tests](http://mir.cs.illinois.edu/legunsen/pubs/BellETAL18DeFlaker.pdf) (ICSE '18)
* Making system user interactive tests repeatable: when and what should we control? (ICSE '15)
* [Who broke the build?: Automatically identifying changes that induce test failures in continuous integration at Google scale](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45794.pdf) (ICSE '2017)
* [Root causing flaky tests in a large-scale industrial setting](http://winglam2.web.engr.illinois.edu/publications/2019/LamETAL19RootFinder.pdf) (ISSTA '2019)
* [A study on the lifecycle of flaky tests](http://mir.cs.illinois.edu/winglam/publications/2020/LamETAL20FaTB.pdf) (ICSE '2020)
* [What Causes My Test Alarm? Automatic Cause Analysis for Test Alarms in System and Integration Testing](https://arxiv.org/pdf/1703.00768.pdf) (ICSE '2017)
* [Understanding flaky tests: The developers perspective](https://arxiv.org/pdf/1907.01466.pdf) (ESEC/FSE '2019)
* [The impact of failing, flaky, and high failure tests on the number of crash reports associated with Firefox builds](http://users.encs.concordia.ca/~pcr/paper/Rahman2018FseIndustry.pdf) (ESEC/FSE '2018)
* [Debugging the performance of Maven’s test isolation: Experience report](https://users.ece.utexas.edu/~gligoric/papers/NieETAL20ForkScript.pdf)(ISSTA '2020)
* [Reliable testing: Detecting state-polluting tests to prevent test dependency](http://mir.cs.illinois.edu/gyori/pubs/issta15pollution.pdf) (ISSTA '2015)
* [Improving oracle quality by detecting brittle assertions and unused inputs in tests](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1058.311&rep=rep1&type=pdf)(FSE '2014)
* [Detecting assumptions on deterministic implementations of non-deterministic specifications](https://www.cs.cornell.edu/~legunsen/pubs/ShiETAL16NonDex.pdf) (ICST'2016)
* [Empirically revisiting the test independence assumption](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.645.6632&rep=rep1&type=pdf) (ISSTA'2014)
* [Practical test dependency detection ](https://www.jonbell.net/icst18-pradet.pdf) (ICST'2018)
* [An empirical analysis of flaky tests](http://mir.cs.illinois.edu/~eloussi2/publications/fse14.pdf) (FSE'2014)
* [iFixFlakies: A framework for automatically fixing order-dependent flaky tests](https://par.nsf.gov/servlets/purl/10111143) (ESEC/FSE'2019)
* [An Empirical Study of Flaky Tests in Android Apps](https://people.cs.vt.edu/nm8247/publications/empirical-study-flaky-pdf.pdf) (ICSME'2018)

### Test Event Reduction

* [Efficient testing of GUI applications by event sequence reduction](https://www.researchgate.net/publication/343619960_Efficient_testing_of_GUI_applications_by_event_sequence_reduction)(Science of Computer Programming '2021)
* [Understanding Ineffective Events and Reducing Test Sequences for Android Applications](https://www.researchgate.net/profile/Jiwei-Yan/publication/337643189_Understanding_Ineffective_Events_and_Reducing_Test_Sequences_for_Android_Applications/links/5e4e240c92851c7f7f48befb/Understanding-Ineffective-Events-and-Reducing-Test-Sequences-for-Android-Applications.pdf) (TASE '2019)
* [Event trace reduction for effective bug replay of Android apps via differential GUI state analysis](https://opus.lib.uts.edu.au/bitstream/10453/137409/4/fse2019%20%281%29.pdf) (ESEC/FSE '2019)
* [Context-based event trace reduction in client-side JavaScript applications](http://www.tcse.cn/~wsdou/papers/2018-icst-evmin.pdf) (ICST '2018)
* [DetReduce: minimizing Android GUI test suites for regression testing](https://dl.acm.org/doi/pdf/10.1145/3180155.3180173) (ICSE '2018)
* [SimplyDroid: Efficient event sequence simplification for android application](http://jiangbo.buaa.edu.cn/ASE17.pdf) (ASE '2017)
* [Systematic reduction of GUI test sequences](https://cs.wmich.edu/~zijiang/pub/ase17preprint.pdf) (ASE '2017)
* [Constraint-based event trace reduction](http://www.tcse.cn/~wsdou/papers/2016-fse-src.pdf) (FSE '2016)
* [Minimizing GUI event traces](https://theory.stanford.edu/~aiken/publications/papers/fse16.pdf)  (FSE '2016)
* [On the use of delta debugging to reduce recordings and facilitate debugging of web applications](https://dl.acm.org/doi/abs/10.1145/2786805.2786846) (ESEC/FSE '2015)

### Non-crashing bug

* [Data Loss Detector: Automatically Revealing Data Loss Bugs in Android Apps](https://oliviero.gitlab.io/pub/RiganelliISSTA2020.pdf) (ISSTA '2020)
* [Understanding and finding system setting-related defects in Android apps](https://tingsu.github.io/files/issta21-Setdroid.pdf) (ISSTA '2021)
* [QUANTUM: Automated Generation of Oracles for Testing User-Interaction Features of Mobile Apps](https://www.researchgate.net/profile/Razieh-Nokhbeh-Zaeem/publication/269305033_Automated_Generation_of_Oracles_for_Testing_User-Interaction_Features_of_Mobile_Apps/links/60071458a6fdccdcb86880c6/Automated-Generation-of-Oracles-for-Testing-User-Interaction-Features-of-Mobile-Apps.pdf) (ICST '2014)
* Is this the lifecycle we really want?: an automated black-box testing approach for Android activities  (INTUITESTBEDS 2018)
* UI Test Migration Across Mobile Platforms （ASE '21)
* [Owl eyes: spotting UI display issues via visual understanding](https://arxiv.org/ftp/arxiv/papers/2009/2009.01417.pdf) (ASE '20)
* Test migration between mobile apps with similar functionality (ASE '19)
* Sketch-guided gui test generation for mobile applications (ASE '17)
* EventFlowSlicer: a tool for generating realistic goal-driven GUI tests (ASE '17)
* QADroid: regression event selection for Android applications (ISSTA '2019)
* Monkey see, monkey do: effective generation of GUI tests with inferred macro events (ISSTA '2016)
* An Empirical Study of i18n Collateral Changes and Bugs in GUIs of Android apps (ICSME 2020)

#### Find non-crashing bug

* [Fully Automated Functional Fuzzing of Android Apps for Detecting Non-Crashing Logic Bugs](https://tingsu.github.io/files/oopsla21-Genie.pdf) (OOPSLA '21)
* [Understanding and finding system setting-related defects in Android apps](https://tingsu.github.io/files/issta21-Setdroid.pdf) (ISSTA '21)
* [Data Loss Detector: Automatically Revealing Data Loss Bugs in Android Apps](https://oliviero.gitlab.io/pub/RiganelliISSTA2020.pdf) (ISSTA '20)
* [Owl eyes: spotting UI display issues via visual understanding](https://arxiv.org/ftp/arxiv/papers/2009/2009.01417.pdf) (ASE '20)
* [Mimic: UI compatibility testing system for Android apps](https://nsr.cse.buffalo.edu/wp-content/uploads/2019/06/mimic-icse2019.pdf) (ICSE '19)
* [A tale of two cities: how WebView induces bugs to Android applications](http://sccpu2.cse.ust.hk/andrewust/files/ASE18-wDroid.pdf) (ASE '18')
* [Finding Resume and Restart Errors in Android Applications](https://web.njit.edu/~ineamtiu/pubs/oopsla16shan.pdf) (OOPSLA '16)
* [THOR: Systematic Execution of Android Test Suites in Adverse Conditions](https://cs.au.dk/~amoeller/papers/thor/paper.pdf) (ISSTA '15)
* [QUANTUM: Automated Generation of Oracles for Testing User-Interaction Features of Mobile Apps](https://www.researchgate.net/profile/Razieh-Nokhbeh-Zaeem/publication/269305033_Automated_Generation_of_Oracles_for_Testing_User-Interaction_Features_of_Mobile_Apps/links/60071458a6fdccdcb86880c6/Automated-Generation-of-Oracles-for-Testing-User-Interaction-Features-of-Mobile-Apps.pdf) (ICST '14)
* [IMGDroid: Detecting Image Loading Defects in Android Applications](https://o2lab.github.io/p/imgdroid.pdf) (ICSE '21)
* [LiveDroid: Identifying and Preserving Mobile App State in Volatile Runtime Environments](https://manu.sridharan.net/files/OOPSLA20LiveDroid.pdf)

#### others related bug study

* [Runtime Permission Issues in Android Apps: Taxonomy, Practices, and Ways Forward](https://arxiv.org/pdf/2106.13012.pdf)
* [Actor Concurrency Bugs: A Comprehensive Study on Symptoms, Root Causes, API Usages, and Differences](https://mbagherz.bitbucket.io/lab-correct-software/papers/akka-actor-bugs.pdf) (OOPSLA '2020)
* [A Large-Scale Longitudinal Study of Flaky Tests](https://www.jonbell.net/preprint/oopsla20flaky.pdf) (OOPSLA '2020)

#### Human-provided oracles to find non-crashing bugs

* [THOR: Systematic Execution of Android Test Suites in Adverse Conditions](https://cs.au.dk/~amoeller/papers/thor/paper.pdf) (ISSTA '2015)
* ChimpCheck: property-based randomized test generation for interactive apps
* AppFlow: using machine learning to synthesize robust, reusable UI tests (ESEC/FSE '2018)
* Automation of Android applications functional testing using machine learning activities classification (MOBILESofT '2018)
* Test Migration Between Mobile Apps with Similar Functionality (ASE '2019)
* Test Transfer Across Mobile Apps Through Semantic Mapping (ASE '2019)
* Reinforcement Learning-Driven Test Generation for Android GUI Applications using Formal Specifications (ARXIV '2019)
* Augusto: exploiting popular functionalities for the generation of semantic GUI tests with Oracles (ICSE '2018)
* Automated test oracles for GUIs (FSE '2000)
* What Test Oracle Should I Use for Effective GUI Testing? (ASE '2003)
* Designing and comparing automated test oracles for GUI-based software applications (ACM Trans. Softw. Eng. Methodol '2007)
* ReNaLART: Automating test oracles from restricted natural language agile requirements (Expert Syst. J. Knowl. Eng '2021)

#### Uses differential testing to overcome the oracle problem

* SPAG-C: On the Accuracy, Efficiency, and Reusability of Automated Test Oracles for Android Devices (IEEE Trans. Software Eng)
* DIFFDROID: Automated cross-platform inconsistency detection for mobile apps (ASE '2017)

#### Generates automated oracles for a specific class of user interactions

* [QUANTUM: Automated Generation of Oracles for Testing User-Interaction Features of Mobile Apps](https://www.researchgate.net/profile/Razieh-Nokhbeh-Zaeem/publication/269305033_Automated_Generation_of_Oracles_for_Testing_User-Interaction_Features_of_Mobile_Apps/links/60071458a6fdccdcb86880c6/Automated-Generation-of-Oracles-for-Testing-User-Interaction-Features-of-Mobile-Apps.pdf) (ICST '2014)
* [THOR: Systematic Execution of Android Test Suites in Adverse Conditions](https://cs.au.dk/~amoeller/papers/thor/paper.pdf) (ISSTA '2015)
* [ACETON: Automated construction of energy test oracles for Android](https://reyhaneh.cs.illinois.edu/pdfs/2020_FSE_Automated.pdf) (ESEC/FSE '2020)
