# Security Policy

## Repository Nature

This repository contains **theoretical research materials only**:

- LaTeX manuscripts
- BibTeX bibliography files
- TikZ figure source code
- Documentation (Markdown files)

This repository is **not** an implementation of the harmonic field model or any AI system; it is documentation and LaTeX source only. The repository contains only LaTeX/TikZ source for the paper *"A Harmonic Field Model of Consciousness in the Human Brain"* (Bridge Paper I) and associated documentation.

**There is no executable code implementing AI systems, simulators, cryptographic systems, or any computational functionality.** All files are document sources intended for compilation with standard LaTeX distributions.

## Vulnerability Scope

### Not Applicable

Traditional software security vulnerabilities (buffer overflows, SQL injection, XSS, etc.) are **not applicable** to this repository because:

1. No executable code is present
2. No web applications or APIs exist
3. No database interactions occur
4. No user input processing takes place

### Relevant Concerns

The following concerns may be relevant:

- **LaTeX compilation**: Malicious LaTeX code could theoretically execute shell commands during compilation. All LaTeX in this repository uses standard packages and does not invoke shell escape or external commands.
- **Bibliography integrity**: BibTeX entries should reference legitimate academic sources.
- **Link validity**: External URLs should point to legitimate websites.

## Reporting

If you identify any of the following, please report it:

1. **Malicious LaTeX code** — Any code that could harm a user's system during compilation
2. **Fraudulent citations** — Bibliography entries referencing non-existent or misrepresented sources
3. **Malicious links** — URLs pointing to harmful or fraudulent websites
4. **Sensitive information** — Any inadvertently included private data

### How to Report

**Email**: contact@vibrationalfielddynamics.org

Please include:
- Description of the concern
- File path and line numbers (if applicable)
- Potential impact assessment

### Response Timeline

- **Acknowledgment**: Within 48 hours
- **Initial assessment**: Within 1 week
- **Resolution**: Dependent on nature and severity

## Safe Compilation

To safely compile the LaTeX documents in this repository:

1. Use a standard LaTeX distribution (TeX Live, MiKTeX)
2. Do not enable shell escape unless required
3. Compile in a sandboxed environment if concerned
4. Review the preamble of `main.tex` before compilation

## No Bounty Program

This is an academic research repository. We do not offer financial rewards for security reports, but we will acknowledge reporters in our documentation if desired.

## Contact

**Vibrational Field Dynamics Institute**

- **Email**: contact@vibrationalfielddynamics.org
- **Website**: https://vibrationalfielddynamics.org
- **X/Twitter**: @vfd_org
- **Institute**: Vibrational Field Dynamics Institute
