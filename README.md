# Research related information


## Useful Links

- [Crossref](https://www.crossref.org/) - open metadata
- [Research Organization Registry](https://ror.org/) - open metadata

## Publishers

- [Sage](https://in.sagepub.com/en-in/sas)

## Directory Structure for the research project

### Citation
- [Citation File Format Schema](https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md)

    A typical CITATION.cff file may look like for research software:

```yaml
cff-version: 1.2.0
message: If you use this software, please cite it using these metadata.
title: My Research Software
abstract: This is my awesome research software. It does many things.
authors:
  - family-names: Druskat
    given-names: Stephan
    orcid: "https://orcid.org/1234-5678-9101-1121"
  - name: "The Research Software project"
version: 0.11.2
date-released: "2021-07-18"
identifiers:
  - description: This is the collection of archived snapshots of all versions of My Research Software
    type: doi
    value: "10.5281/zenodo.123456"
  - description: This is the archived snapshot of version 0.11.2 of My Research Software
    type: doi
    value: "10.5281/zenodo.123457"
license: Apache-2.0
repository-code: "https://github.com/citation-file-format/my-research-software"
```
