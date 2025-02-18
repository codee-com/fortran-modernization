# Top 10 Recommendations for Fortran Modernization

Modernizing Fortran codebases is a crucial step toward improving code quality
and ensuring maintainability. It helps developers uncover hidden bugs and
reduces the risk of introducing new errors during development. Additionally,
these efforts support modern compilers and tools in generating optimized code
and identifying potential issues early. Ultimately, modernization boosts
developer productivity and enhances code robustness.

## Context and motivation

This project is inspired by the [OWASP](https://owasp.org/) community-led
initiative, which regularly publishes the most relevant Top 10 Secure Coding
Recommendations. These are widely adopted by the industry to help developers
avoid common security vulnerabilities. The OWASP initiative thrives on
collaboration and knowledge sharing through platforms like their [GitHub
repository](https://github.com/OWASP/Top10).

Beyond OWASP, various open catalogs provide comprehensive collections of checks
(rules) to help ensure secure coding practices. Each check describes specific
scenarios and necessary actions, offering extensive documentation, example
codes, automated code analysis tools, and references to other resources.
Notable examples include [SEI CERT
C](https://wiki.sei.cmu.edu/confluence/display/c) and
[CWE](https://cwe.mitre.org/).

Building on these foundations, this project aims to start a similar
community-driven initiative focused on modern Fortran software development.
Leveraging the existing [Open Catalog of Coding Guidelines for Correctness,
Modernization, Security, and
Optimization](https://github.com/codee-com/open-catalog/), we seek to establish
a dedicated set of Top 10 Recommendations and related checks to address the
specific challenges of Fortran Modernization.

Modernizing Fortran code encompasses updating and maintaining legacy Fortran
codes (e.g., F77, F90) with extensive development histories. It also involves
refactoring existing Fortran codes to leverage the features of the latest
Fortran standards (e.g., transitioning from F90 to F23).

## Methodology

To develop the Top 10 Recommendations for Fortran Modernization, we adopted a
comprehensive and community-focused approach. First, we conducted an extensive
review of existing resources on the topic to identify an initial draft of the
most recurrent recommendations. These were later discussed with the Fortran
development community to collect insights and feedback (e.g., in Fortran
Discourse
[[12](https://fortran-lang.discourse.group/t/our-initiative-to-publish-the-fortran-lang-top-10-recommendation-for-fortran-modernization-is-it-really-new-or-even-feasible/7774)]),
which were crucial for shaping the final proposal.

The presented Top 10 Recommendations are prioritized to guide developers
through a progression of modernization efforts. Each recommendation is detailed
with specific checks that describe actionable steps, including examples of
before and after code snippets, the rationale behind the changes, and links to
further reading.

To ensure the recommendations remain relevant and comprehensive, we plan to
continuously review community input and update the guidelines as the Fortran
standards evolve and new best practices emerge.

## Top 10 Recommendations

1. [Strict compliance with modern Fortran
   standards](Recommendations/R1_ModernStandardCompliance.md).

2. [Declare procedures in modules](Recommendations/R2_ProceduresInModules.md).

3. [Restrict data visibility with
   modules](Recommendations/R3_RestrictDataVisibility.md).

4. [Improve dummy arguments
   semantics](Recommendations/R4_ImproveDummyArguments.md).

5. [Improve data type consistency and
   management](Recommendations/R5_ImproveDataTypes.md).

6. [Avoid legacy control-flow
   constructs](Recommendations/R6_AvoidLegacyControlFlow.md).

7. [Enhance source code semantics](Recommendations/R7_EnhanceCodeSemantics.md).

8. [Adhere to code conventions](Recommendations/R8_CodeConventions.md).

9. [Adopt modern development
   practices](Recommendations/R9_ModernDevelopmentPractices.md).

10. [Proper C/C++ interoperability](Recommendations/R10_CInteroperability.md).

## Contributing

We welcome and encourage contributions to the Top 10 Recommendations! Here's
how you can get involved:

1. **Join the discussion:**

    Got ideas, questions, or suggestions? Head over to our [GitHub
    Discussions](https://github.com/codee-com/fortran-modernization/discussions).
    It's the perfect place for open-ended conversations and brainstorming!

2. **Report issues:**

    Found inacuracies, unclear explanations, or other problems? Please open an
    [**Issue**](https://github.com/codee-com/fortran-modernization/issues).
    Detailed reports help us quickly improve the quality of the project!

3. **Submit pull requests:**

    Interested in solving any issues? Feel free to fork the repository, make
    your changes, and submit a [Pull
    Request](https://github.com/codee-com/fortran-modernization/pulls). We'd
    love to see your contributions!

## References

- [1] Fortran Community. "Fortran Best Practices". Accessed: Jun. 06, 2024.
  [Online] Available: https://fortran-lang.org/en/learn/best_practices/

- [2] Fortran Wiki Contributors. "Modernizing Old Fortran". Accessed: Jun. 06,
  2024. [Online] Available:
  https://fortranwiki.org/fortran/show/Modernizing+Old+Fortran

- [3] Fortran Discourse Community. "Fortran Discourse". Accessed: Jun. 06,
  2024. [Online] Available: https://fortran-lang.discourse.group

- [4] Reinhold Bader. "Fortran code modernization". Accessed: Jun. 06, 2024.
  [Online] Available:
  https://www.ugent.be/hpc/en/training/2018/modern_fortran_materials/modernfortran2018.pdf

- [5] The Numerical Algorithms Group. "Fortran Modernisation Workshop".
  Accessed: Jun. 06, 2024. [Online] Available:
  https://blog.rwth-aachen.de/hpc_import_20210107/attachments/39157901/39420371.pdf

- [6] The Carpentries. "Best Practices in Modern Fortran". Accessed: Jun. 06,
  2024. [Online] Available:
  https://wvuhpc.github.io/Modern-Fortran/11-Best-Practices/index.html

- [7] Norman S. Clerman, Walter Spector. "Modern Fortran: Style and Usage". 1st
  Edition, 2011.

- [8] Michael Metcalf, John Reid, Malcolm Cohen, Reinhold Bader. "Modern
  Fortran Explained". 6th Edition, 2023.

- [9] Fortran Users of NERSC (FUN). "FUN Training July 2023: Modern Fortran
  Basics". Accessed: Jun. 06, 2024. [Online] Available:
  https://www.nersc.gov/users/training/past-training-events/2023/fun-training-july-2023-modern-fortran-basics/

- [10] Jack Carlson, Olaf David. "Fortran 90/95 Coding Conventions - Fortran
  Features that are obsolescent and/or discouraged". Accessed: Jun. 06, 2024.
  [Online] Available:
  https://alm.engr.colostate.edu/cb/wiki/16983#section-Fortran+Features+that+are+obsolescent+and_2For+discouraged

- [11] GitHub Collaborators. "Best practices and styles guidelines of Fortran
  FOSS Programmers". Accessed: Jun. 06, 2024. [Online] Available:
  https://github.com/Fortran-FOSS-Programmers/Best_Practices

- [12] Fortran Discourse Community. "Our initiative to publish the
  'Fortran-lang Top 10 Recommendation for Fortran modernization', is it really
  new or even feasible?". Accessed: Jun. 06, 2024. [Online] Available:
  https://fortran-lang.discourse.group/t/our-initiative-to-publish-the-fortran-lang-top-10-recommendation-for-fortran-modernization-is-it-really-new-or-even-feasible/7774

- [13] GitHub Collaborators. "Open Catalog of Coding Guidelines for
  Correctness, Modernization, Security, and Optimization". Accessed: Feb. 18,
  2025. [Online] Available: https://github.com/codee-com/open-catalog
