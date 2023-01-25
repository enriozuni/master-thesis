# Master Thesis
This repository contains my Master Thesis from Paderborn University with title "Extending FluentTQL: Specifying taint flows through a DSL". The thesis was submitted on 21st October 2021.

## Abstract
Domain-specific languages (DSLs) have become helpful in describing
malicious taint flows and serve as a starting point for taint analyses. FluentTQL is one
of these languages and is utilized to specify taint queries related to vulnerabilities such
as SQL Injection or Cross-site Scripting. It comes together with a taint analysis tool
such as SecuCheck, which analyzes a program to find the specified malicious flows. Our
work includes enhancements to both the syntax of the language and the taint analysis
implementation in the tool. Two of them have to do with easily specifying overloaded
versions of methods that are part of a taint query and a second alternative of writing
such method specifications. Another improvement is the ability to specify other types
of vulnerabilities in FluentTQL, such as NULL Pointer Dereference or Hard-coded
Credentials. The last enhancement is shortening the overall runtime of the analysis by
manually specifying entry points in the language for given taint queries. Results show
a clear improvement in the usability of the DSL and better performance of the static
taint analysis.
