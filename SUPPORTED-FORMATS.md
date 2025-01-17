<!--- DO NOT EDIT - Generated by ToolsLister at 2022-04-15T08:58:46.101518-->
# Supported Report Formats

Jenkins' Warnings Next Generation Plugin supports the following report formats. 
If your tool is supported, but has no custom icon yet, please file a pull request for the
[Warnings Next Generation Plugin](https://github.com/jenkinsci/warnings-ng-plugin/pulls).

If your tool is not yet supported you can
1. define a new Groovy based parser in the user interface
2. export the issues of your tool to the native XML format (or any other format)
3. provide a parser within a new small plugin. 

If the parser is useful for 
other teams as well please share it and provide pull requests for the 
[Warnings Next Generation Plug-in](https://github.com/jenkinsci/warnings-ng-plugin/pulls) and 
the [Analysis Parsers Library](https://github.com/jenkinsci/analysis-model/). 

| Number | ID | Symbol | Icons | Name | Default Pattern |
| --- | --- | --- | --- | --- | --- |
| 0 | acu-cobol | acuCobol() | ![AcuCobol](plugin/src/main/webapp/icons/analysis.svg) ![AcuCobol](plugin/src/main/webapp/icons/analysis.svg) | AcuCobol |  |
| 1 | gnat | gnat() | ![Ada Compiler (gnat)](plugin/src/main/webapp/icons/analysis.svg) ![Ada Compiler (gnat)](plugin/src/main/webapp/icons/analysis.svg) | Ada Compiler (gnat) |  |
| 2 | android-lint | androidLintParser() | ![Android Lint](plugin/src/main/webapp/icons/android-lint-24x24.png) ![Android Lint](plugin/src/main/webapp/icons/android-lint-48x48.png) | Android Lint |  |
| 3 | ansiblelint | ansibleLint() | ![Ansible Lint](plugin/src/main/webapp/icons/analysis.svg) ![Ansible Lint](plugin/src/main/webapp/icons/analysis.svg) | Ansible Lint |  |
| 4 | scannercli | aquaScanner() | ![Aqua Scanner](plugin/src/main/webapp/icons/analysis.svg) ![Aqua Scanner](plugin/src/main/webapp/icons/analysis.svg) | Aqua Scanner |  |
| 5 | trivy | trivy() | ![Aquasec Trivy](plugin/src/main/webapp/icons/analysis.svg) ![Aquasec Trivy](plugin/src/main/webapp/icons/analysis.svg) | [Aquasec Trivy](https://github.com/aquasecurity/trivy) |  |
| 6 | armcc | armCc() | ![Armcc Compiler](plugin/src/main/webapp/icons/analysis.svg) ![Armcc Compiler](plugin/src/main/webapp/icons/analysis.svg) | Armcc Compiler |  |
| 7 | aspectj | ajc() | ![AspectJ](plugin/src/main/webapp/icons/analysis.svg) ![AspectJ](plugin/src/main/webapp/icons/analysis.svg) | AspectJ |  |
| 8 | axivion-suite | axivionSuite() | ![Axivion Suite](plugin/src/main/webapp/icons/axivion-24x24.png) ![Axivion Suite](plugin/src/main/webapp/icons/axivion-48x48.png) | Axivion Suite | - |
| 9 | brakeman | brakeman() | ![Brakeman](plugin/src/main/webapp/icons/brakeman-24x24.png) ![Brakeman](plugin/src/main/webapp/icons/brakeman-48x48.png) | [Brakeman](https://brakemanscanner.org) | **/brakeman-output.json |
| 10 | buckminster | buckminster() | ![Buckminster](plugin/src/main/webapp/icons/analysis.svg) ![Buckminster](plugin/src/main/webapp/icons/analysis.svg) | Buckminster |  |
| 11 | cadence | cadence() | ![Cadence Incisive](plugin/src/main/webapp/icons/analysis.svg) ![Cadence Incisive](plugin/src/main/webapp/icons/analysis.svg) | Cadence Incisive |  |
| 12 | cargo | cargo() | ![Cargo Check](plugin/src/main/webapp/icons/analysis.svg) ![Cargo Check](plugin/src/main/webapp/icons/analysis.svg) | Cargo Check |  |
| 13 | ccm | ccm() | ![CCM](plugin/src/main/webapp/icons/analysis.svg) ![CCM](plugin/src/main/webapp/icons/analysis.svg) | CCM |  |
| 14 | checkstyle | checkStyle() | ![CheckStyle](plugin/src/main/webapp/icons/checkstyle-24x24.png) ![CheckStyle](plugin/src/main/webapp/icons/checkstyle-48x48.png) | [CheckStyle](https://checkstyle.org) | **/checkstyle-result.xml |
| 15 | clair | clair() | ![Clair Scanner](plugin/src/main/webapp/icons/analysis.svg) ![Clair Scanner](plugin/src/main/webapp/icons/analysis.svg) | [Clair Scanner](https://github.com/arminc/clair-scanner) |  |
| 16 | clang | clang() | ![Clang](plugin/src/main/webapp/icons/analysis.svg) ![Clang](plugin/src/main/webapp/icons/analysis.svg) | Clang |  |
| 17 | clang-analyzer | clangAnalyzer() | ![Clang Analyzer](plugin/src/main/webapp/icons/analysis.svg) ![Clang Analyzer](plugin/src/main/webapp/icons/analysis.svg) | [Clang Analyzer](https://clang-analyzer.llvm.org) |  |
| 18 | clang-tidy | clangTidy() | ![Clang-Tidy](plugin/src/main/webapp/icons/analysis.svg) ![Clang-Tidy](plugin/src/main/webapp/icons/analysis.svg) | Clang-Tidy |  |
| 19 | cmake | cmake() | ![CMake](plugin/src/main/webapp/icons/analysis.svg) ![CMake](plugin/src/main/webapp/icons/analysis.svg) | CMake |  |
| 20 | code-analysis | codeAnalysis() | ![Code Analysis](plugin/src/main/webapp/icons/analysis.svg) ![Code Analysis](plugin/src/main/webapp/icons/analysis.svg) | Code Analysis |  |
| 21 | code-checker | codeChecker() | ![CodeChecker](plugin/src/main/webapp/icons/analysis.svg) ![CodeChecker](plugin/src/main/webapp/icons/analysis.svg) | CodeChecker |  |
| 22 | codenarc | codeNarc() | ![CodeNarc](plugin/src/main/webapp/icons/analysis.svg) ![CodeNarc](plugin/src/main/webapp/icons/analysis.svg) | CodeNarc |  |
| 23 | coolflux | coolflux() | ![Coolflux DSP Compiler](plugin/src/main/webapp/icons/analysis.svg) ![Coolflux DSP Compiler](plugin/src/main/webapp/icons/analysis.svg) | Coolflux DSP Compiler |  |
| 24 | cpd | cpd() | ![CPD](plugin/src/main/webapp/icons/dry.svg) ![CPD](plugin/src/main/webapp/icons/dry.svg) | [CPD](https://pmd.github.io/latest/pmd_userdocs_cpd.html) | **/cpd.xml |
| 25 | cppcheck | cppCheck() | ![CPPCheck](plugin/src/main/webapp/icons/analysis.svg) ![CPPCheck](plugin/src/main/webapp/icons/analysis.svg) | CPPCheck |  |
| 26 | cpplint | cppLint() | ![Cpplint](plugin/src/main/webapp/icons/analysis.svg) ![Cpplint](plugin/src/main/webapp/icons/analysis.svg) | Cpplint |  |
| 27 | csslint | cssLint() | ![CSS-Lint](plugin/src/main/webapp/icons/analysis.svg) ![CSS-Lint](plugin/src/main/webapp/icons/analysis.svg) | CSS-Lint |  |
| 28 | dart | dart() | ![Dart Analyze](plugin/src/main/webapp/icons/analysis.svg) ![Dart Analyze](plugin/src/main/webapp/icons/analysis.svg) | [Dart Analyze](https://dart.dev/) |  |
| 29 | detekt | detekt() | ![Detekt](plugin/src/main/webapp/icons/analysis.svg) ![Detekt](plugin/src/main/webapp/icons/analysis.svg) | [Detekt](https://detekt.github.io/detekt) |  |
| 30 | docfx | docFx() | ![DocFX](plugin/src/main/webapp/icons/analysis.svg) ![DocFX](plugin/src/main/webapp/icons/analysis.svg) | DocFX |  |
| 31 | dockerlint | dockerLint() | ![Dockerfile Lint](plugin/src/main/webapp/icons/analysis.svg) ![Dockerfile Lint](plugin/src/main/webapp/icons/analysis.svg) | [Dockerfile Lint](https://github.com/projectatomic/dockerfile_lint) |  |
| 32 | doxygen | doxygen() | ![Doxygen](plugin/src/main/webapp/icons/analysis.svg) ![Doxygen](plugin/src/main/webapp/icons/analysis.svg) | Doxygen |  |
| 33 | dr-memory | drMemory() | ![Dr. Memory](plugin/src/main/webapp/icons/analysis.svg) ![Dr. Memory](plugin/src/main/webapp/icons/analysis.svg) | Dr. Memory |  |
| 34 | dscanner | dscanner() | ![DScanner](plugin/src/main/webapp/icons/analysis.svg) ![DScanner](plugin/src/main/webapp/icons/analysis.svg) | [DScanner](https://github.com/dlang-community/D-Scanner) | **/dscanner-report.json |
| 35 | eclipse | eclipse() | ![Eclipse ECJ](plugin/src/main/webapp/icons/analysis.svg) ![Eclipse ECJ](plugin/src/main/webapp/icons/analysis.svg) | Eclipse ECJ |  |
| 36 | erlc | erlc() | ![Erlang Compiler (erlc)](plugin/src/main/webapp/icons/analysis.svg) ![Erlang Compiler (erlc)](plugin/src/main/webapp/icons/analysis.svg) | Erlang Compiler (erlc) |  |
| 37 | error-prone | errorProne() | ![Error Prone](plugin/src/main/webapp/icons/bug.svg) ![Error Prone](plugin/src/main/webapp/icons/bug.svg) | [Error Prone](https://errorprone.info) |  |
| 38 | eslint | esLint() | ![ESlint](plugin/src/main/webapp/icons/eslint-24x24.png) ![ESlint](plugin/src/main/webapp/icons/eslint-48x48.png) | [ESlint](https://eslint.org) |  |
| 39 | findbugs | findBugs() | ![FindBugs](plugin/src/main/webapp/icons/findbugs-24x24.png) ![FindBugs](plugin/src/main/webapp/icons/findbugs-48x48.png) | FindBugs | **/findbugsXml.xml |
| 40 | flake8 | flake8() | ![Flake8](plugin/src/main/webapp/icons/analysis.svg) ![Flake8](plugin/src/main/webapp/icons/analysis.svg) | [Flake8](https://flake8.pycqa.org/) |  |
| 41 | flawfinder | flawfinder() | ![FlawFinder](plugin/src/main/webapp/icons/analysis.svg) ![FlawFinder](plugin/src/main/webapp/icons/analysis.svg) | [FlawFinder](https://dwheeler.com/flawfinder/) |  |
| 42 | flex | flexSdk() | ![Flex SDK Compiler](plugin/src/main/webapp/icons/analysis.svg) ![Flex SDK Compiler](plugin/src/main/webapp/icons/analysis.svg) | Flex SDK Compiler |  |
| 43 | fxcop | fxcop() | ![FxCop](plugin/src/main/webapp/icons/analysis.svg) ![FxCop](plugin/src/main/webapp/icons/analysis.svg) | FxCop |  |
| 44 | gendarme | gendarme() | ![Gendarme](plugin/src/main/webapp/icons/analysis.svg) ![Gendarme](plugin/src/main/webapp/icons/analysis.svg) | Gendarme |  |
| 45 | ghs-multi | ghsMulti() | ![GHS Multi Compiler](plugin/src/main/webapp/icons/analysis.svg) ![GHS Multi Compiler](plugin/src/main/webapp/icons/analysis.svg) | GHS Multi Compiler |  |
| 46 | gcc | gcc() | ![GNU C Compiler (gcc)](plugin/src/main/webapp/icons/analysis.svg) ![GNU C Compiler (gcc)](plugin/src/main/webapp/icons/analysis.svg) | GNU C Compiler (gcc) |  |
| 47 | gcc3 | gcc3() | ![GNU C Compiler 3 (gcc)](plugin/src/main/webapp/icons/analysis.svg) ![GNU C Compiler 3 (gcc)](plugin/src/main/webapp/icons/analysis.svg) | GNU C Compiler 3 (gcc) |  |
| 48 | fortran | gnuFortran() | ![GNU Fortran Compiler](plugin/src/main/webapp/icons/analysis.svg) ![GNU Fortran Compiler](plugin/src/main/webapp/icons/analysis.svg) | GNU Fortran Compiler |  |
| 49 | golint | goLint() | ![Go Lint](plugin/src/main/webapp/icons/golint-24x24.png) ![Go Lint](plugin/src/main/webapp/icons/golint-48x48.png) | Go Lint |  |
| 50 | go-vet | goVet() | ![Go Vet](plugin/src/main/webapp/icons/analysis.svg) ![Go Vet](plugin/src/main/webapp/icons/analysis.svg) | Go Vet |  |
| 51 | groovy | groovyScript() | ![Groovy Parser](plugin/src/main/webapp/icons/analysis.svg) ![Groovy Parser](plugin/src/main/webapp/icons/analysis.svg) | Groovy Parser | - |
| 52 | hadolint | hadoLint() | ![HadoLint](plugin/src/main/webapp/icons/hadolint-24x24.png) ![HadoLint](plugin/src/main/webapp/icons/hadolint-48x48.png) | [HadoLint](https://github.com/hadolint/hadolint) |  |
| 53 | iar-cstat | iarCstat() | ![IAR C-STAT](plugin/src/main/webapp/icons/analysis.svg) ![IAR C-STAT](plugin/src/main/webapp/icons/analysis.svg) | IAR C-STAT |  |
| 54 | iar | iar() | ![IAR Compiler (C/C++)](plugin/src/main/webapp/icons/analysis.svg) ![IAR Compiler (C/C++)](plugin/src/main/webapp/icons/analysis.svg) | IAR Compiler (C/C++) |  |
| 55 | iblinter | ibLinter() | ![IbLinter](plugin/src/main/webapp/icons/analysis.svg) ![IbLinter](plugin/src/main/webapp/icons/analysis.svg) | [IbLinter](https://github.com/IBDecodable/IBLinter) |  |
| 56 | xlc | xlc() | ![IBM XLC Compiler](plugin/src/main/webapp/icons/analysis.svg) ![IBM XLC Compiler](plugin/src/main/webapp/icons/analysis.svg) | IBM XLC Compiler |  |
| 57 | infer | infer() | ![Infer](plugin/src/main/webapp/icons/analysis.svg) ![Infer](plugin/src/main/webapp/icons/analysis.svg) | [Infer](https://fbinfer.com) |  |
| 58 | intel | intel() | ![Intel Compiler (C, Fortran)](plugin/src/main/webapp/icons/analysis.svg) ![Intel Compiler (C, Fortran)](plugin/src/main/webapp/icons/analysis.svg) | Intel Compiler (C, Fortran) |  |
| 59 | idea | ideaInspection() | ![IntelliJ IDEA Inspections](plugin/src/main/webapp/icons/idea-24x24.png) ![IntelliJ IDEA Inspections](plugin/src/main/webapp/icons/idea-48x48.png) | [IntelliJ IDEA Inspections](https://www.jetbrains.com/help/idea/code-inspection.html) |  |
| 60 | java | java() | ![Java Compiler](plugin/src/main/webapp/icons/java-24x24.png) ![Java Compiler](plugin/src/main/webapp/icons/java-48x48.png) | Java Compiler |  |
| 61 | javadoc-warnings | javaDoc() | ![JavaDoc](plugin/src/main/webapp/icons/java-24x24.png) ![JavaDoc](plugin/src/main/webapp/icons/java-48x48.png) | JavaDoc |  |
| 62 | jc-report | jcReport() | ![JCReport](plugin/src/main/webapp/icons/analysis.svg) ![JCReport](plugin/src/main/webapp/icons/analysis.svg) | JCReport |  |
| 63 | js-hint | jsHint() | ![JsHint](plugin/src/main/webapp/icons/analysis.svg) ![JsHint](plugin/src/main/webapp/icons/analysis.svg) | JsHint |  |
| 64 | jslint | jsLint() | ![JSLint](plugin/src/main/webapp/icons/analysis.svg) ![JSLint](plugin/src/main/webapp/icons/analysis.svg) | [JSLint](https://www.jslint.com) |  |
| 65 | junit | junitParser() | ![JUnit](plugin/src/main/webapp/icons/junit-24x24.png) ![JUnit](plugin/src/main/webapp/icons/junit-48x48.png) | [JUnit](https://junit.org) |  |
| 66 | klocwork | klocWork() | ![Klocwork](plugin/src/main/webapp/icons/analysis.svg) ![Klocwork](plugin/src/main/webapp/icons/analysis.svg) | Klocwork |  |
| 67 | kotlin | kotlin() | ![Kotlin](plugin/src/main/webapp/icons/kotlin-24x24.png) ![Kotlin](plugin/src/main/webapp/icons/kotlin-48x48.png) | Kotlin |  |
| 68 | ktlint | ktLint() | ![KtLint](plugin/src/main/webapp/icons/ktlint-24x24.png) ![KtLint](plugin/src/main/webapp/icons/ktlint-48x48.png) | [KtLint](https://ktlint.github.io) |  |
| 69 | maven-warnings | mavenConsole() | ![Maven](plugin/src/main/webapp/icons/analysis.svg) ![Maven](plugin/src/main/webapp/icons/analysis.svg) | Maven |  |
| 70 | taglist | tagList() | ![Maven Taglist Plugin](plugin/src/main/webapp/icons/analysis.svg) ![Maven Taglist Plugin](plugin/src/main/webapp/icons/analysis.svg) | [Maven Taglist Plugin](https://www.mojohaus.org/taglist-maven-plugin) | **/taglist.xml |
| 71 | modelsim | modelsim() | ![Mentor Graphics Modelsim/Questa Simulators](plugin/src/main/webapp/icons/analysis.svg) ![Mentor Graphics Modelsim/Questa Simulators](plugin/src/main/webapp/icons/analysis.svg) | Mentor Graphics Modelsim/Questa Simulators |  |
| 72 | metrowerks | metrowerksCodeWarrior() | ![Metrowerks CodeWarrior Compiler](plugin/src/main/webapp/icons/analysis.svg) ![Metrowerks CodeWarrior Compiler](plugin/src/main/webapp/icons/analysis.svg) | Metrowerks CodeWarrior Compiler |  |
| 73 | msbuild | msBuild() | ![MSBuild](plugin/src/main/webapp/icons/analysis.svg) ![MSBuild](plugin/src/main/webapp/icons/analysis.svg) | MSBuild |  |
| 74 | mypy | myPy() | ![MyPy](plugin/src/main/webapp/icons/analysis.svg) ![MyPy](plugin/src/main/webapp/icons/analysis.svg) | MyPy |  |
| 75 | nag-fortran | nagFortran() | ![NAG Fortran Compiler](plugin/src/main/webapp/icons/analysis.svg) ![NAG Fortran Compiler](plugin/src/main/webapp/icons/analysis.svg) | NAG Fortran Compiler |  |
| 76 | issues | issues() | ![Native Analysis Model Format](plugin/src/main/webapp/icons/analysis.svg) ![Native Analysis Model Format](plugin/src/main/webapp/icons/analysis.svg) | [Native Analysis Model Format](https://github.com/jenkinsci/warnings-ng-plugin/blob/master/doc/Documentation.md#export-your-issues-into-a-supported-format) |  |
| 77 | oelint-adv | oelintAdv() | ![oelint-adv](plugin/src/main/webapp/icons/analysis.svg) ![oelint-adv](plugin/src/main/webapp/icons/analysis.svg) | [oelint-adv](https://github.com/priv-kweihmann/oelint-adv) |  |
| 78 | open-tasks | taskScanner() | ![Open Tasks Scanner](plugin/src/main/webapp/icons/open-tasks.svg) ![Open Tasks Scanner](plugin/src/main/webapp/icons/open-tasks.svg) | Open Tasks Scanner | - |
| 79 | invalids | invalids() | ![Oracle Invalids](plugin/src/main/webapp/icons/analysis.svg) ![Oracle Invalids](plugin/src/main/webapp/icons/analysis.svg) | Oracle Invalids |  |
| 80 | ot-docker-linter | otDockerLint() | ![OT Docker Linter](plugin/src/main/webapp/icons/ot-docker-linter-24x24.png) ![OT Docker Linter](plugin/src/main/webapp/icons/ot-docker-linter-48x48.png) | [OT Docker Linter](https://github.com/opstree/OT-Dockerlinter) |  |
| 81 | owasp-dependency-check | owaspDependencyCheck() | ![OWASP Dependency Check](plugin/src/main/webapp/icons/analysis.svg) ![OWASP Dependency Check](plugin/src/main/webapp/icons/analysis.svg) | OWASP Dependency Check | **/dependency-check-report.json |
| 82 | pclint | pcLint() | ![PC-Lint Tool](plugin/src/main/webapp/icons/analysis.svg) ![PC-Lint Tool](plugin/src/main/webapp/icons/analysis.svg) | PC-Lint Tool |  |
| 83 | pep8 | pep8() | ![PEP8](plugin/src/main/webapp/icons/analysis.svg) ![PEP8](plugin/src/main/webapp/icons/analysis.svg) | PEP8 |  |
| 84 | perforce | perforce() | ![Perforce Compiler](plugin/src/main/webapp/icons/analysis.svg) ![Perforce Compiler](plugin/src/main/webapp/icons/analysis.svg) | Perforce Compiler |  |
| 85 | perl-critic | perlCritic() | ![Perl::Critic](plugin/src/main/webapp/icons/analysis.svg) ![Perl::Critic](plugin/src/main/webapp/icons/analysis.svg) | Perl::Critic |  |
| 86 | php | php() | ![PHP Runtime](plugin/src/main/webapp/icons/analysis.svg) ![PHP Runtime](plugin/src/main/webapp/icons/analysis.svg) | PHP Runtime |  |
| 87 | php-code-sniffer | phpCodeSniffer() | ![PHP_CodeSniffer](plugin/src/main/webapp/icons/analysis.svg) ![PHP_CodeSniffer](plugin/src/main/webapp/icons/analysis.svg) | [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) |  |
| 88 | phpstan | phpStan() | ![PHPStan](plugin/src/main/webapp/icons/phpstan-24x24.png) ![PHPStan](plugin/src/main/webapp/icons/phpstan-48x48.png) | [PHPStan](https://github.com/phpstan/phpstan) |  |
| 89 | pit | pit() | ![PIT](plugin/src/main/webapp/icons/pit-24x24.png) ![PIT](plugin/src/main/webapp/icons/pit-48x48.png) | [PIT](https://pitest.org) | **/mutations.xml |
| 90 | pmd | pmdParser() | ![PMD](plugin/src/main/webapp/icons/pmd-24x24.png) ![PMD](plugin/src/main/webapp/icons/pmd-48x48.png) | [PMD](https://pmd.github.io) | **/pmd.xml |
| 91 | prefast | prefast() | ![PREfast](plugin/src/main/webapp/icons/analysis.svg) ![PREfast](plugin/src/main/webapp/icons/analysis.svg) | PREfast |  |
| 92 | protolint | protoLint() | ![ProtoLint](plugin/src/main/webapp/icons/analysis.svg) ![ProtoLint](plugin/src/main/webapp/icons/analysis.svg) | [ProtoLint](https://github.com/yoheimuta/protolint) |  |
| 93 | puppetlint | puppetLint() | ![Puppet Lint](plugin/src/main/webapp/icons/analysis.svg) ![Puppet Lint](plugin/src/main/webapp/icons/analysis.svg) | Puppet Lint |  |
| 94 | pvs-studio | PVSStudio() | ![PVS-Studio](plugin/src/main/webapp/icons/pvs-24x24.png) ![PVS-Studio](plugin/src/main/webapp/icons/pvs-48x48.png) | [PVS-Studio](https://pvs-studio.com/en/pvs-studio/) | **/*.plog |
| 95 | pydocstyle | pyDocStyle() | ![PyDocStyle](plugin/src/main/webapp/icons/analysis.svg) ![PyDocStyle](plugin/src/main/webapp/icons/analysis.svg) | PyDocStyle |  |
| 96 | pylint | pyLint() | ![Pylint](plugin/src/main/webapp/icons/pylint-24x24.png) ![Pylint](plugin/src/main/webapp/icons/pylint-48x48.png) | Pylint |  |
| 97 | qac | qacSourceCodeAnalyser() | ![QA-C Sourcecode Analyser](plugin/src/main/webapp/icons/analysis.svg) ![QA-C Sourcecode Analyser](plugin/src/main/webapp/icons/analysis.svg) | QA-C Sourcecode Analyser |  |
| 98 | qt-translation | qtTranslation() | ![Qt translations](plugin/src/main/webapp/icons/qt-24x24.png) ![Qt translations](plugin/src/main/webapp/icons/qt-48x48.png) | [Qt translations](https://www.qt.io) |  |
| 99 | analysis-model | analysisParser() | ![RegisteredParser](plugin/src/main/webapp/icons/analysis.svg) ![RegisteredParser](plugin/src/main/webapp/icons/analysis.svg) | RegisteredParser | - |
| 100 | dupfinder | dupFinder() | ![Resharper DupFinder](plugin/src/main/webapp/icons/dry.svg) ![Resharper DupFinder](plugin/src/main/webapp/icons/dry.svg) | Resharper DupFinder |  |
| 101 | resharper | resharperInspectCode() | ![Resharper Inspections](plugin/src/main/webapp/icons/resharper-24x24.png) ![Resharper Inspections](plugin/src/main/webapp/icons/resharper-48x48.png) | Resharper Inspections |  |
| 102 | robocopy | robocopy() | ![Robocopy](plugin/src/main/webapp/icons/analysis.svg) ![Robocopy](plugin/src/main/webapp/icons/analysis.svg) | Robocopy |  |
| 103 | rflint | rfLint() | ![Robot Framework Lint](plugin/src/main/webapp/icons/robot-framework-24x24.png) ![Robot Framework Lint](plugin/src/main/webapp/icons/robot-framework-48x48.png) | Robot Framework Lint |  |
| 104 | rubocop | ruboCop() | ![Rubocop](plugin/src/main/webapp/icons/rubocop-24x24.png) ![Rubocop](plugin/src/main/webapp/icons/rubocop-48x48.png) | Rubocop |  |
| 105 | sarif | sarif() | ![SARIF](plugin/src/main/webapp/icons/analysis.svg) ![SARIF](plugin/src/main/webapp/icons/analysis.svg) | [SARIF](https://github.com/oasis-tcs/sarif-spec) |  |
| 106 | scala | scala() | ![Scala Compiler](plugin/src/main/webapp/icons/scala-24x24.png) ![Scala Compiler](plugin/src/main/webapp/icons/scala-48x48.png) | Scala Compiler |  |
| 107 | simian | simian() | ![Simian](plugin/src/main/webapp/icons/dry.svg) ![Simian](plugin/src/main/webapp/icons/dry.svg) | Simian |  |
| 108 | sonar | sonarQube() | ![SonarQube Issues](plugin/src/main/webapp/icons/sonar-24x24.png) ![SonarQube Issues](plugin/src/main/webapp/icons/sonar-48x48.png) | SonarQube Issues | **/sonar-report.json |
| 109 | sphinx | sphinxBuild() | ![Sphinx Build](plugin/src/main/webapp/icons/analysis.svg) ![Sphinx Build](plugin/src/main/webapp/icons/analysis.svg) | Sphinx Build |  |
| 110 | spotbugs | spotBugs() | ![SpotBugs](plugin/src/main/webapp/icons/spotbugs-24x24.png) ![SpotBugs](plugin/src/main/webapp/icons/spotbugs-48x48.png) | [SpotBugs](https://spotbugs.github.io) | **/spotbugsXml.xml |
| 111 | stylecop | styleCop() | ![StyleCop](plugin/src/main/webapp/icons/analysis.svg) ![StyleCop](plugin/src/main/webapp/icons/analysis.svg) | StyleCop |  |
| 112 | sunc | sunC() | ![SUN C++ Compiler](plugin/src/main/webapp/icons/analysis.svg) ![SUN C++ Compiler](plugin/src/main/webapp/icons/analysis.svg) | SUN C++ Compiler |  |
| 113 | swiftlint | swiftLint() | ![SwiftLint](plugin/src/main/webapp/icons/analysis.svg) ![SwiftLint](plugin/src/main/webapp/icons/analysis.svg) | [SwiftLint](https://github.com/realm/SwiftLint) |  |
| 114 | tasking-vx | taskingVx() | ![TASKING VX Compiler](plugin/src/main/webapp/icons/analysis.svg) ![TASKING VX Compiler](plugin/src/main/webapp/icons/analysis.svg) | TASKING VX Compiler |  |
| 115 | code-composer | tiCss() | ![Texas Instruments Code Composer Studio](plugin/src/main/webapp/icons/analysis.svg) ![Texas Instruments Code Composer Studio](plugin/src/main/webapp/icons/analysis.svg) | Texas Instruments Code Composer Studio |  |
| 116 | tnsdl | tnsdl() | ![TNSDL Translator](plugin/src/main/webapp/icons/analysis.svg) ![TNSDL Translator](plugin/src/main/webapp/icons/analysis.svg) | TNSDL Translator |  |
| 117 | tslint | tsLint() | ![TSLint  ](plugin/src/main/webapp/icons/analysis.svg) ![TSLint  ](plugin/src/main/webapp/icons/analysis.svg) | [TSLint  ](https://palantir.github.io/tslint/) |  |
| 118 | diabc | diabC() | ![Wind River Diab Compiler (C/C++)](plugin/src/main/webapp/icons/analysis.svg) ![Wind River Diab Compiler (C/C++)](plugin/src/main/webapp/icons/analysis.svg) | Wind River Diab Compiler (C/C++) |  |
| 119 | xmllint | xmlLint() | ![XML-Lint](plugin/src/main/webapp/icons/analysis.svg) ![XML-Lint](plugin/src/main/webapp/icons/analysis.svg) | XML-Lint |  |
| 120 | yamllint | yamlLint() | ![YamlLint](plugin/src/main/webapp/icons/analysis.svg) ![YamlLint](plugin/src/main/webapp/icons/analysis.svg) | [YamlLint](https://yamllint.readthedocs.io/) |  |
| 121 | yui | yuiCompressor() | ![YUI Compressor](plugin/src/main/webapp/icons/analysis.svg) ![YUI Compressor](plugin/src/main/webapp/icons/analysis.svg) | YUI Compressor |  |
| 122 | zptlint | zptLint() | ![ZPT-Lint](plugin/src/main/webapp/icons/analysis.svg) ![ZPT-Lint](plugin/src/main/webapp/icons/analysis.svg) | ZPT-Lint |  |
