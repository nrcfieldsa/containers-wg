# containers-wg proposal
containers-wg proposal prepared for SC23 and NIST 2nd International Workshop on FAIR Containerized Computational Software 2023

KEYWORDS: "container specification", "standard", OCI, labelling, metadata, annotation, "container image", compatibility, attestation, security

OBJECTIVE: Proposal for container metadata standardization, enumerate common fields and build a usage case.

GOALS
--
 1. Outline usage case for metadata with containers at NRC
 2. Propose a common set of fields for inclusion in standard
 3. Propose mechanism for handling domain-specific metadata field-sets

IMPLEMENTATION TARGETS
--
 - At this phase no implementation targets have been planned by NRC. This is exploratory work only.
 - The first step of this excercise is to outline a light-weight proposal for standards discussion.
 - It would then be possible to use a very basic stub OCI annotation handler, extended to test proposed new metadata fields and external schema (namespace and plugin) support. To include expamples of how to get an set the annotations and display a summary using demo OCI image.
 - Otherwise, if other code bases are implementing already - check if this guidance in workable using existing those implementations.
 - External schema references should be cached on first build, or upon container update with the schema version number listed.

AUTHOR: NRCFieldsA o/b/o Research Platform Support, National Research Council, Government of Canada (NRC-CNRC) - http://www.nrc.ca

LICENSE: GPL

SENSITIVITY: Unclassified for public release in working draft form.

