# **1. Introduction:** {#introduction}

This specification defines a set of python coding standards, development flow, and tools to help to identify and fix deviations in written code. These standards, flow and tools to establish

*   Uniformity of style
*   Uniform conventions
*   To maintain consistency
*   To maintain extensibility
*   To improve readability
*   To improve maintainability, reusability

These rules apply to all code developed in Python for inclusion in the EDK II , and are intended as an enabling philosophy. All changes or additions from this point on shall conform to this specification. Pre-existing code does not need to be updated for the sole purpose of conforming to this specification. As conforming updates are made, the developer may update other content within the modified file to bring it within compliance with this specification. 

This specification addresses the chronic problem of providing accurate documentation of the code base by embedding the documentation within the code.

A document generation system, using inbuilt python module, then produce formatted documentation by extracting information from specially formatted comment blocks and the syntactic elements of the code