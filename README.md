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
