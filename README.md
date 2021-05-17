## Android Testing and Analysis

Recent paper related to Android testing and Analysis

### ASE

  + 2020
      + Seven Reasons Why: An In-Depth Study of the Limitations of Random Test Input Generation for Android
      + UI obfuscation and its effects on automated UI analysis for Android apps
      + Automated third-party library detection for Android applications: are we there yet?
      + Owl eyes: spotting UI display issues via visual understanding
      + Test automation in open-source android apps
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
  + A tale of two cities: how WebView induces bugs to Android applications
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

* 2020

  * Unblind your apps: predicting natural-language labels for mobile GUI components by deep learning
  * Translating video recordings of mobile app usages into replayable scenarios
  * Multiple-entry testing of Android applications by constructing activity launching contexts
  * How Android developers handle evolution-induced API compatibility issues: a large-scale study
  * ComboDroid: generating high-quality test inputs for Android apps via use case combinations
  * RoScript: a visual script driven truly non-intrusive robotic testing system for touch screen applications
  * Time-travel testing of Android apps
  * An empirical assessment of security risks of global Android banking apps
  * Accessibility issues in Android apps: state of affairs, sentiments, and ways forward
  * Collaborative bug finding for Android apps

* 2019
  * IconIntent: automatic identification of sensitive UI widgets based on icon classification for Android apps
  * Mimic: UI compatibility testing system for Android apps
  * Search-based energy testing of Android
  * Practical GUI testing of Android applications via model abstraction and refinement
  * Towards understanding and reasoning about Android interoperations
* 2018
  * Automated reporting of GUI design violations for mobile apps
  * Leveraging program analysis to reduce user-perceived latency in mobile applications
  * Software protection on the go: a large-scale empirical study on mobile app obfuscation
  * Repairing crashes in Android apps
  * DetReduce: minimizing Android GUI test suites for regression testing
  * Studying the dialogue between users and developers of free apps in the google play store
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

### Reproduce & Flaky 

* LIRAT: Layout and Image Recognition Driving Automated Mobile Testing of Cross-Platform (ASE'19)

* SARA: Self-Replay Augmented Record and Replay for Android in Industrial Cases (ISSTA '19)

* Record and replay for Android: are we there yet in industrial cases? （ESEC/FSE '17)

* RANDR: Record and Replay for Android Applications via Targeted Runtime Instrumentation (ASE'19)

* Translating video recordings of mobile app usages into replayable scenarios (ICSE'20)

* Versatile Yet Lightweight Record-and-replay for Android (OOPSLA'15)

* MobiPlay: A Remote Execution Based Record-and-replay Tool for Mobile Applications (ICSE'16)

* Mosaic: cross-platform user-interaction record and replay for the fragmented android ecosystem (ICSE'16)

* [A Large-Scale Longitudinal Study of Flaky Tests](http://taoxie.cs.illinois.edu/publications/oopsla20-flaky.pdf)(OOPSLA'20) 

* [An Empirical Analysis of UI-based Flaky Tests]( https://ui-flaky-test.github.io/ ) （ICSE'21)

* [Concurrency-related Flaky Test Detection in Android Apps](https://arxiv.org/pdf/2005.10762.pdf)
  
* iDFlakies: A framework for detecting and partially classifying flaky tests. (ICST'19)
  https://taoxie.cs.illinois.edu/publications/icst19-idflakies.pdf

* DeFlaker: Automatically detecting flaky tests (ICSE'18)
  http://mir.cs.illinois.edu/legunsen/pubs/BellETAL18DeFlaker.pdf

*  Making system user interactive tests repeatable: when and what should we control? (ICSE'15)

* Who broke the build?: Automatically identifying changes that induce test failures in continuous integration at Google scale (ICSE'2017)
  https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45794.pdf

*  Root causing flaky tests in a large-scale industrial setting. (ISSTA'2019)
  http://winglam2.web.engr.illinois.edu/publications/2019/LamETAL19RootFinder.pdf

*  A study on the lifecycle of flaky tests (ICSE'2020)
  http://mir.cs.illinois.edu/winglam/publications/2020/LamETAL20FaTB.pdf

*  What Causes My Test Alarm? Automatic Cause Analysis for Test Alarms in System and Integration Testing (ICSE'2017)
  https://arxiv.org/pdf/1703.00768.pdf

* Understanding flaky tests: The developer’s perspective.(ESEC/FSE'2019)
  https://arxiv.org/pdf/1907.01466.pdf

* The impact of failing, flaky, and high failure tests on the number of crash reports associated with Firefox builds. (ESEC/FSE'2018)
  http://users.encs.concordia.ca/~pcr/paper/Rahman2018FseIndustry.pdf

* Debugging the performance of Maven’s test isolation: Experience report.(ISSTA'2020)
  https://users.ece.utexas.edu/~gligoric/papers/NieETAL20ForkScript.pdf

* Reliable testing: Detecting state-polluting tests to prevent test dependency. (ISSTA'2015)
  http://mir.cs.illinois.edu/gyori/pubs/issta15pollution.pdf

*  Improving oracle quality by detecting brittle assertions and unused inputs in tests.(FSE'2014)
  https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1058.311&rep=rep1&type=pdf

*  Detecting assumptions on deterministic implementations of non-deterministic specifications.(ICST'2016)
  https://www.cs.cornell.edu/~legunsen/pubs/ShiETAL16NonDex.pdf

*  Empirically revisiting the test independence assumption(ISSTA'2014)
  http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.645.6632&rep=rep1&type=pdf

* Practical test dependency detection(ICST'2018)
  https://www.jonbell.net/icst18-pradet.pdf

* An empirical analysis of flaky tests(FSE'2014)
  http://mir.cs.illinois.edu/~eloussi2/publications/fse14.pdf

*  iFixFlakies: A framework for automatically fixing order-dependent flaky tests(ESEC/FSE'2019)
  https://par.nsf.gov/servlets/purl/10111143

  