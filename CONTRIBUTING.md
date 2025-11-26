# Contributing

**Last Update**: This document has been updated as of the v1.0.0 release in November 2025.

## Introduction

### What is AFINE?

AFINE is a Poland based cybersecurity company specializing in offensive security, penetration testing, and security research.

### What is the DASVS?

The Desktop Application Security Verification Standard (DASVS) Project provides a basis for testing desktop application technical security controls and also provides developers with a list of requirements for secure development.

The primary aim of the DASVS Project is to normalize the range in the coverage and level of rigor available in the market when it comes to performing desktop application security verification using a commercially-workable open standard.

### What is the Current Status of DASVS development?

The DASVS project released v1.0.0 during November 2025 which represents the first comprehensive security standard specifically designed for desktop applications.

You can see the static version of this release on the [v1.0.0 branch](https://github.com/AFINE-Company/DASVS/tree/v1.0.0) within the 1.0 folder. The master branch continues to be the "bleeding edge" and will contain any incremental changes made following the v1.0.0 release.

## Release Strategy

DASVS releases follow the pattern "Major.Minor.Patch" and the numbers provide information on what has changed within the release. In a major release, the first number will change, in a minor release, the second number will change, and in a patch release, the third number will change.

- **Major release** - Full reorganization, almost everything may have changed, including requirement numbers. Reevaluation for compliance will be necessary (for example, 1.0.0 -> 2.0.0).
- **Minor release** - Requirements may be added or removed, but overall numbering will stay the same. Reevaluation for compliance will be necessary, but should be easier (for example, 1.0.0 -> 1.1.0).
- **Patch release** - Requirements may be removed (for example, if they are duplicates or outdated) or made less stringent, but an application that complied with the previous release will comply with the patch release as well (for example, 1.0.0 -> 1.0.1).

The above specifically relates to the requirements in the DASVS. Changes to surrounding text and other content such as the appendices will not be considered to be a breaking change.

## How can I help?

We would be glad to receive feedback to help us to further enhance the DASVS.

At this stage, we are accepting the following types of changes:

- Changes to surrounding text and other content such as the appendices which is not be considered to be a breaking change for release purposes.
- Changes which are considered "non-breaking" for a DASVS "patch" release. This means that requirements may be removed (for example, if they are duplicates or outdated) or made less stringent, but an application that complied with the previous release will comply with the patch release as well.

If you feel there are other important changes but they would be considered breaking for a patch release, you are welcome to open an issue but please note that the issue may not be progressed until we are considering a new minor or major release, for which there is currently no fixed timeline.

## Additional Details for Helping

### Before you open a Pull Request

Please do not open a pull request without first opening an associated issue. Please do not open an issue until you have used the search functionality to ensure that the issue has not previously been discussed and that there are no currently open issues relating to it.

If you are comfortable that your query has not been previously discussed, you can open an issue. Please try and include the DASVS requirement number and text you are talking about in the issue to save having to jump back and forth and please carry out all discussion in the associated issue and not in a PR discussion.

## Translations

We are keen to receive translations for v1.0.0 of DASVS!

**Note** that we are ONLY accepting translations based on markdown and not preformatted translations in Word or PDF format to make tracking and maintenance easier.

If you are interested in creating a translation, here are some pointers for how you can help us:

1. Please first of all search the repository to see if there is already a translation for your proposed language.
2. If the language you are interested in appears, it would be great if you could reach out to the translator to see if you can help them.
   - Often there is work to do in creating markdown files or updating the translation to keep it up to date with latest changes.
3. We would request that you base your translation on the `1.0/en` folder in the [v1.0.0 branch](https://github.com/AFINE-Company/DASVS/tree/v1.0.0) as this is now static at the 1.0.0 version.
4. In order to start a translation, please start by forking the DASVS repository.
5. Take a copy of the `/en` folder and rename it to the 2 character language code which will be used for the translation.
6. You can then edit the markdown files to include your translation rather than the original English.
7. When you have completed the translation, please open a Pull Request against the v1.0.0 DASVS branch and one of the maintainers will look at integrating it.
8. The maintainer will also use the relevant scripts to create the documents from the raw markdown (or you can if you want to save us some trouble).
9. Finally, the maintainer will back port the translation into the branch containing the DASVS version which was targeted (at this point, presumably v1.0.0).

**Thank you for your help!!**
