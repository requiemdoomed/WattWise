# Citing WattWise

Author: **Swayam Shakya** ([requiemdoomed](https://github.com/requiemdoomed)).

Repository: https://github.com/requiemdoomed/WattWise

## IEEE reference

For the current WattWise manuscript, add this entry after reference [9]:

> [10] S. Shakya, “WattWise: A Regression-based Household Appliance Energy Consumption Prediction, with a test on Temporal Generalization”, GitHub repository, 2026. Accessed: Nov. 10, 2026. [Online]. Available: https://github.com/requiemdoomed/WattWise

The reference number applies to the existing manuscript. In another paper, assign the number according to first appearance and use the date on which you actually accessed the repository.

## In-text citation for the manuscript

Place this sentence in **DATA AND CODE AVAILABILITY**, immediately before **REFERENCES**:

> The WattWise source code, Jupyter notebook, and experimental results are available in the project’s GitHub repository [10].

Retain the existing citations to the original dataset and its authors. WattWise does not replace the dataset citation. Do not claim that the November manuscript or its fresh audit files are hosted in the repository unless those files have also been uploaded.

## BibTeX

The accompanying `WattWise.bib` uses `@misc` for compatibility with conventional BibTeX and IEEEtran. Cite it in LaTeX with `\cite{shakya2026wattwise}`.

```bibtex
@misc{shakya2026wattwise,
  author       = {Shakya, Swayam},
  title        = {{WattWise}: Household Appliance Energy Estimation and Forecasting},
  year         = {2026},
  howpublished = {GitHub repository, version 2.0.0},
  url          = {https://github.com/requiemdoomed/WattWise},
  note         = {Accessed: Nov. 10, 2026}
}
```

## Adding these files to GitHub

1. Replace the existing `CITATION.cff` in the repository root with the supplied file.
2. Add `CITATION.md` and `WattWise.bib` in the same directory as `README.md`.
3. Commit the files to the default branch, `main`.
4. GitHub uses `CITATION.cff` to provide **Cite this repository** with APA and BibTeX citations. The IEEE-formatted reference is provided here separately.

Optional README section:

```markdown
## Citation

If you use WattWise in your work, please cite the software using
[CITATION.cff](CITATION.cff). See [CITATION.md](CITATION.md) for an IEEE
reference and [WattWise.bib](WattWise.bib) for BibTeX.
Please also cite the original dataset and research used in your analysis.
```

## Metadata and reproducibility notes

- The repository was inspected on November 10, 2026. Its existing `CITATION.cff` declares version **2.0.0**, dated **2026-10-27**; these values are preserved. The GitHub API returned no tags or releases at inspection, so this is a declared software version, not a verified GitHub release tag.
- The supplied title aligns the citation metadata with the current WattWise manuscript. The previous citation title was “WattWise: Temporal Generalization in Household Appliance Energy Regression.”
- The inspected `main` commit was `1d6707cab05c636fcb12b79822d642676918e737`. Its permanent source URL is https://github.com/requiemdoomed/WattWise/tree/1d6707cab05c636fcb12b79822d642676918e737. This identifies the inspected repository snapshot; it has not been established as the exact source snapshot for the November manuscript audit. Cite the actual experiment commit when that correspondence is verified.
- No DOI, publication venue, acceptance status, ORCID, or affiliation is asserted. The CFF describes software rather than a published IEEE article.
- The existing README and citation file claim MIT licensing, but the current `LICENSE` file states that no open-source license has been granted. The replacement citation file omits the optional license field to avoid repeating that contradiction. Resolve the repository’s licensing separately; citation metadata does not grant permission to reuse the software.

## Format documentation

- [GitHub: About CITATION files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files)
- [Citation File Format 1.2.0 schema guide](https://github.com/citation-file-format/citation-file-format/blob/1.2.0/schema-guide.md)
- [IEEE Reference Guide](https://journals.ieeeauthorcenter.ieee.org/wp-content/uploads/sites/7/IEEE_Reference_Guide.pdf)
