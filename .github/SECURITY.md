# Security Policy

Thank you for your interest in the security of PayStub-Generator-Java-CLI-Tool. We take security very seriously and are committed to providing a secure and reliable tool.

## Reporting a Vulnerability

We encourage responsible disclosure of security vulnerabilities. If you discover a vulnerability, please report it to us following these steps:

1.  **DO NOT** use public channels (like GitHub Issues or Pull Requests) to report security vulnerabilities. This could expose the vulnerability to malicious actors.
2.  **DO NOT** exploit the vulnerability in any way, including data exfiltration, denial of service, or other unauthorized actions.
3.  **DO** send an email to `chirag127.security@example.com` detailing the vulnerability. Please include:
    *   A clear and concise description of the vulnerability.
    *   The affected version(s) of the software.
    *   Steps to reproduce the vulnerability, including any necessary code snippets or configuration.
    *   Information about the environment where the vulnerability was found.
    *   Any potential impact of the vulnerability.
    *   Your contact information so we can follow up.
4.  We will acknowledge receipt of your report within **48 hours** and will work diligently to assess and address the vulnerability.
5.  We will provide updates on the progress of the fix and will notify you when a patch or updated version is available.
6.  We will give credit to the discoverer of valid vulnerabilities upon public disclosure, provided this aligns with responsible disclosure practices.

## Supported Versions

We are committed to providing security updates for the actively maintained versions of PayStub-Generator-Java-CLI-Tool. As of December 2025, the actively maintained versions are those released within the last **12 months**. Older versions may still contain vulnerabilities but are no longer actively maintained or patched.

For detailed information on specific versions, please refer to the project's release notes and the `main` branch.

## Security Best Practices

While we strive to make PayStub-Generator-Java-CLI-Tool secure, users should also follow general security best practices when using the tool:

*   **Dependency Management:** Regularly update dependencies to their latest versions using `mvn clean install` to incorporate security patches. Consult the `pom.xml` for dependency details.
*   **Input Validation:** Always validate external inputs before processing them, even when using this tool, to prevent injection attacks or unexpected behavior.
*   **Secure Execution Environment:** Run the CLI tool in a secure and trusted environment. Avoid running it with excessive privileges unless absolutely necessary.
*   **Code Review:** If you fork or modify the source code, conduct thorough security reviews of your changes.

## Scope

This security policy applies to vulnerabilities found within the official PayStub-Generator-Java-CLI-Tool repository located at `https://github.com/chirag127/PayStub-Generator-Java-CLI-Tool` and its associated official releases.

## Acknowledgements

We are grateful to the security community for their ongoing efforts to improve the security of open-source software. We will acknowledge valid security disclosures in our release notes.

---

*This policy was last updated in December 2025.*