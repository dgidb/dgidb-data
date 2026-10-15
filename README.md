# DGIdb Data Releases

This repository houses data releases for the [Drug-Gene Interaction Database](https://dgidb.org/). 

New releases consist of the following artifacts:

* A SQL dump generated from the database itself
* `interactions.tsv`: A list of all known interaction claims, their constituent drug and gene claims, and metrics (drug and gene specificity, evidence score) that can be used to rank interactions (see the [documentation](https://dgidb.org/about/overview/interaction-score) for more information)
* `drugs.tsv`: A list of all known drug claims and supporting metadata (including source and source version)
* `genes.tsv`: A list of all known gene claims and supporting metadata (including source and source version)
* `categories.tsv`: A listing of all known gene categorization claims (including source and source version)

All TSVs include metadata, declared with leading `"#"` characters, naming the version of the data release and the version of DGIdb used to generate the data.

The [Releases](https://github.com/dgidb/dgidb-data/releases) page, linked on the right-hand side of the repository landing page, lists all releases. The address [https://github.com/dgidb/dgidb-data/releases](https://github.com/dgidb/dgidb-data/releases) can always be used to access the latest available release. For programmatic access to releases, see the [GitHub API documentation](https://docs.github.com/en/rest/releases/releases).

# Data Licensing

DGIdb software is available under the [MIT License](../LICENSE). DGIdb data are aggregated from independently maintained biomedical resources, and the claims contributed by each source remain subject to that source’s applicable license, terms of use, attribution requirements, and redistribution restrictions. DGIdb does not apply additional licensing terms to imported source content.

Each data release is accompanied by a source-level licensing manifest that identifies the contributing sources, source versions, data-availability locations, and the primary license or terms-of-use reference for each resource. Where explicit licensing terms could not be identified during review, the manifest records this status and users should consult the original source before redistributing or reusing those data.

Users are responsible for reviewing and complying with the terms applicable to each source included in a DGIdb release. In particular, a source’s public availability does not necessarily imply unrestricted redistribution or commercial reuse.

Individual Source licensing is tracked in the [License excel document](https://github.com/dgidb/dgidb-data/blob/main/dgidb_source_licensing.xlsx).
