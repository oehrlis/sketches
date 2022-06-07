# Author and Release Guide
<!-- markdownlint-configure-file { "MD013": { "tables": false } } -->
## Document Structure

### Folders

This repository contains a number of folders for sketches on various topics.
The directories are only a loosely summarized list for different topics. In some
cases, the sketches cannot always be explicitly assigned to a topic.

- [backup](./backup/README.md) Sketches all around the topic of backup & recovery.
  Mainly backup & recovery for Oracle databases.
- [libraries](./libraries/README.md) A couple of *Excalidraw* libraries which
  have not be officially published in the public *Excalidraw* library repository.
- [misc](./misc/README.md) Miscellaneous Sketches about different topic.
  Basically all sketches that are not or not yet stored somewhere else.
- [oci](./oci/README.md) Sketches all around the topic of *Oracle Cloud Infrastructure
  (OCI*) including LAB setup, Terraform and more.
- [security](./security/README.md) Sketches all around the topic of
  *Oracle Database Security*.

The following Markdown files are generic files describing the repository,
authoring, contributing etc.

- [AUTHOR_GUIDE](AUTHOR_GUIDE.md) General author's and contribution guide to
  *OraDBA Sketches*.
- [CHANGELOG.md](./CHANGELOG.md) Change log for the *OraDBA Sketches*.
- [LICENSE](./LICENSE) License documentation.

### Excalidraw Files

to be documented

## Releases and Versions

### Release and Version Numbering

You find all official releases and release information on the Azure DevOps
project release page. As well documented in the [CHANGELOG](CHANGELOG.md).

The versioning and release tags follow the
[semantic versioning](https://semver.org/). A version number is specified by
*MAJOR.MINOR.PATCH*, increase the:

- *MAJOR* version when you make incompatible API changes,
- *MINOR* version when you add functionality in a backwards compatible manner,
  AND
- *PATCH* version when you make backwards compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions
to the MAJOR.MINOR.PATCH format.

### Create a Release

New releases currently have to be build via GitHub release. Each release require
a short release note. Procedure:

- Update / Commit changes
- Update the [CHANGELOG](CHANGELOG.md) add the latest change information
- Create an new release
- Add release information based on changes e.g.
  `git log --pretty=format:%s v0.1.0...HEAD`

## Contribution

to be documented

## Further Topics

There a couple of additional topics which are not yet implemented or documented.
This includes among other the following points.

- Automatic Release Workflow
- Generate additional formates like Word (.docx), eBooks (.epub), Power Point
  (.pptx), man pages, etc.
- Generate HTML version / Webpage
