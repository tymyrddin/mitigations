# Webserver mitigations

## Apache

* [Chroot Apache](https://tymyrddin.github.io/webserver-mitigations/docs/apache/Chroot-Apache.md)
* [Hide version and OS identity](https://tymyrddin.github.io/webserver-mitigations/docs/apache/Hide-version-and-OS-identity.md)
* [Disable directory listing](https://tymyrddin.github.io/webserver-mitigations/docs/apache/Disable-directory-listing.md)
* [Restrict file and directory access](https://tymyrddin.github.io/webserver-mitigations/docs/apache/Restrict-file-and-directory-access.md)
* [Install and use mod_security](https://tymyrddin.github.io/webserver-mitigations/docs/apache/mod_security.md)

## Nginx

* [Chroot Nginx](https://tymyrddin.github.io/webserver-mitigations/docs/nginx/Chroot-Nginx.md)
* [Hide version and OS identity](https://tymyrddin.github.io/webserver-mitigations/docs/nginx/Hide-version-and-OS-identity.md)
* [Disable directory listing](https://tymyrddin.github.io/webserver-mitigations/docs/nginx/Disable-SSI-and-CGI-execution.md)
* [Restrict file and directory access](https://tymyrddin.github.io/webserver-mitigations/docs/nginx/Restrict-file-and-directory-access.md)
* [Install and use mod_security](https://tymyrddin.github.io/webserver-mitigations/docs/nginx/mod_security.md)

## Notes

* Reduce information disclosure (OS, version, ServerTokens)
* Use a firewall.
* Disable unused services.
* Monitor web traffic for unusual activity.
* Conduct regular, remote security scans.
* Conduct regular, local security scans.
* Guard against application level DOS attacks by limiting field input length.
* Disable url fopen if possible.
* Enable safe mode, include directory and open base restrictions if possible.
* Disable dangerous PHP functions if possible.
* Be careful with naming files *.bak, *.txt or *.inc within the web document root.
* Be careful using version management tools on doc root.