HCLS SindiceTech
================

Queries developed as examples for the HCLS sparql endpoint.

Adverse Events Queries
======================
 
Adverse events queries are those related to identifying the outcome of drug exposure.
These queries use the SIDER, drugbank, and chembl database to lookup synonyms and brand
names their related side effect.


Example 1 - /examples/adverse-events/side_effect_by_name.txt
------------------------------------------------------------

Retrieve all side effects for a chemical based on its name. Brand names and
synonyms will be used as well to look up side effects. The example provided
looks for all side effects of aspirin.

Pharmacology Queries
=====================

Example 1 - /examples/pharmacology/chembl_compound.info.txt
-----------------------------------------------------------

This query pulls in all pharmacology information from ChEMBL and available
information from DrugBank.
