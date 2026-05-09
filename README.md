# NDC Directory

Pre-built SQLite snapshots of the [FDA National Drug Code
Directory](https://www.fda.gov/drugs/drug-approvals-and-databases/national-drug-code-directory)
— a US-government public-domain dataset of approved drug products and
packages.

Each release attaches a single asset, `ndc_directory.db.gz`, built from the
FDA's daily-updated tab-delimited source file
(`https://www.accessdata.fda.gov/cder/ndctext.zip`). The unzipped database
is plain SQLite 3.

The underlying data is US-government public domain. No license restrictions.
