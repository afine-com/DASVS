# Desktop Application Security Verification Standard - DASVS

*This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License.](https://creativecommons.org/licenses/by-sa/4.0//)*

**Welcome to Version 1.0 of the DASVS!**

*The comprehensive security standard for desktop applications.*

## Introduction to DASVS

The primary aim of the Desktop Application Security Verification Standard (DASVS) Project is to provide an open application security standard for desktop applications across all platforms and architectures.

Created by the AFINE security research team, DASVS defines a comprehensive set of security requirements for designing, developing, and testing modern desktop applications on Windows, macOS, and Linux platforms.

DASVS fills a critical gap in application security standards, complementing [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/) (web applications) and [OWASP MASVS](https://mas.owasp.org/) (mobile applications) by addressing the unique security challenges of desktop software.

Version 1.0 represents the culmination of ten years of research, penetration testing, and security assessments performed by AFINE's team on enterprise desktop applications.

Please log issues if you find any bugs or if you have ideas. We may subsequently ask you to open a pull request based on the discussion in the issue. We are also actively looking for translations of the 1.0 branch.

## Project Team

DASVS was created by the AFINE Team.

## Latest Stable Version - 1.0.0

The latest stable version is version 1.0.0 (dated November 2025), which can be found:

- [Desktop Application Security Verification Standard 1.0.0 English (PDF)](https://github.com/afinepl/DASVS/raw/main/DASVS_v1.0.0_en.pdf)
- [Desktop Application Security Verification Standard 1.0.0 English (docx)](https://github.com/afinepl/DASVS/releases/download/v1.0.0/DASVS.v1.0.0.docx)
- [Desktop Application Security Verification Standard 1.0.0 (GitHub Branch)](https://github.com/afinepl/DASVS)

The master branch of this repository will always be the "bleeding edge version" which might have in-progress changes or other edits open. The next release target will be a minor update, version 1.1. For details on the DASVS release strategy, see the release strategy section of [CONTRIBUTING.md](./CONTRIBUTING.md).

## Scope and Coverage

DASVS provides security requirements for:

- Native Desktop Applications (Windows, macOS, Linux)
- Cross-Platform Desktop Applications (Electron, Qt, .NET MAUI, etc.)
- Client-Server Desktop Applications
- Standalone Desktop Software
- Desktop Application Updates and Installers
- Inter-Process Communication (IPC)
- Local Data Storage and Encryption
- Desktop Application Authentication
- Privilege Management and Separation

## Why did we create DASVS?

Desktop applications present unique security challenges that are not adequately covered by existing standards:

- **Local attack surface**: Direct access to file systems, memory, and OS APIs
- **Update mechanisms**: Secure delivery and installation of updates
- **Local data storage**: Protection of sensitive data at rest
- **Inter-process communication**: Secure IPC mechanisms
- **Privilege escalation**: Prevention of unauthorized privilege elevation
- **Binary protection**: Code signing, obfuscation, and anti-tampering
- **Platform-specific vulnerabilities**: OS-specific security requirements

DASVS addresses these challenges with comprehensive, actionable security requirements.

## Translations

DASVS is currently available in English. We welcome community contributions for translations into other languages.

If you would like to contribute a translation, please contact the AFINE team or submit a pull request following the translation guidelines. For more information on translating the DASVS, see the translations section of [CONTRIBUTING.md](./CONTRIBUTING.md).

## How To Reference DASVS Requirements

Each requirement has an identifier in the format `<chapter>.<section>.<requirement>`, where each element is a number. For example, 2.3.5.

- The `<chapter>` value corresponds to the chapter from which the requirement comes
- The `<section>` value corresponds to the section within that chapter where the requirement appears
- The `<requirement>` value identifies the specific requirement within the chapter and section

Since the identifiers may change between versions of the standard, it is preferable for other documents, reports, or tools to use the following format: `v<version>-<chapter>.<section>.<requirement>`, where 'version' is the DASVS version tag.

For example: `v1.0.0-2.3.5` would be understood to mean specifically the 5th requirement in section 3 of chapter 2 from version 1.0.0.

**Note**: The 'v' preceding the version number in the format should always be lowercase.

If identifiers are used without including the `v<version>` element, they should be assumed to refer to the latest Desktop Application Security Verification Standard content.

## Contributing

We welcome contributions from the security community! Please submit issues for:

- Bug reports
- New requirement suggestions
- Clarifications on existing requirements
- Documentation improvements

For substantial contributions, please open an issue first to discuss the proposed changes.

## Use Cases

DASVS can be used by:

- Security teams conducting desktop application security assessments
- Developers building secure desktop applications
- QA teams verifying security requirements
- Compliance teams establishing security baselines
- Procurement teams evaluating vendor security
- Security researchers analyzing desktop application security

## DASVS Verification Levels

DASVS defines three verification levels:

- **Level 1**: Basic security hygiene for all desktop applications
- **Level 2**: Standard security requirements for applications handling sensitive data
- **Level 3**: Advanced security for high-risk applications and critical infrastructure

## About AFINE

AFINE is a Poland-based cybersecurity company specializing in offensive security, penetration testing, and security research. With ten years of experience in desktop application security, AFINE works with major enterprise clients, including banks, financial institutions, and critical infrastructure providers.

Visit: [www.afine.com](https://www.afine.com)

## License

The entire project content is under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

## Contact

For questions, feedback, or business inquiries:

- **Email**: [afine@afine.com](mailto:afine@afine.com)
- **Website**: [www.afine.com](https://www.afine.com)
- **GitHub Issues**: [Submit an issue](https://github.com/afinepl/DASVS/issues)

---

**DASVS - Securing the desktop application landscape, one requirement at a time.**
