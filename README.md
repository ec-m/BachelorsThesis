#### Mutation-based Validation of Temporal Logic Specifications with Guarantees

This repository contains my Bachelor's thesis. It was written in 2016/2017 as part of my undergraduate studies in Computer Science at the University of Tübingen, Germany and supervised by Prof. Dr. Thomas Kropf. The work demonstrated in this thesis resulted in the project [STLInspector](https://github.com/STLInspector/STLInspector).

#### Abstract

Trust in software relies on trust in the specification the software is based on.
In this bachelor's thesis we aim to support engineers to gain trust in
specifications written in Signal Temporal Logic (STL). We achieve this goal by
introducing a systematic approach for the validation of STL specifications. The
approach is realized in the tool [STLInspector](https://github.com/STLInspector/STLInspector) that computes validation tests
which can be checked against informal textual requirements of a software. We
discuss how validation tests are constructed by means of the coverage criteria
property mutation, unique first cause and property inactive clause. The use of
coverage criteria enables for certain guarantees about the correctness of the
specification.  The thesis further covers test generation algorithms that depend
on SMT solving.  Finally, we detail the implementation of [STLInspector](https://github.com/STLInspector/STLInspector) and apply
the tool to several STL formulae to show its effectiveness in finding faulty
specifications. By enabling validation of temporal logic specifications the
bachelor's thesis contributes to improve the application of formal
specifications in industry.
