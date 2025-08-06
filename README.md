# Morgen Malinoski – Security Projects Portfolio

Welcome! This repo highlights select projects, PoCs, tools, and research I've developed or contributed to.

## Custom Exploits
### [sudo chroot PrivEsc PoC (CVE-2025-32463)](https://github.com/morgenm/sudo-chroot-CVE-2025-32463)
- Rust implementation of CVE-2025-32463.
- Spawns a root shell to escalate privileges.
- Custom payloads are supported.

### [DirtyPipe (CVE-2022-0847)](https://github.com/morgenm/dirtypipe)
- Wrote a Rust-based PoC for the Dirty Pipe vulnerability.
- Arbitray file overwrite.
- Supports overwriting SUID binaries to escalate privileges.

## Tools and Utilities
### [BasicGoPot](https://github.com/morgenm/basicgopot)
- Customizable HTTP honeypot.
- Imitates file upload site. Saves and logs all files that are uploaded.
- Supports customization of the site using HTML and CSS.
- Uploads files to VirusTotal by default.
- Supports custom WebHooks called on file uploads.
- Writeup covering customization on my [blog](https://morgenm.github.io/blog/2023/basicgopot-hybrid-analysis/).

### [NLP AI Phishing Detection](https://github.com/morgenm/nlp-ai-phishing)
- Python code for detecting phishing emails based on email body text.
- Binary classification of emails.
- Writeup of methods and findings on my [blog](https://morgenm.github.io/blog/2023/phishing-detection-ai/).

### [MLWL](https://github.com/morgenm/mlwl) (Machine Learning Wordlist Generation)
- Utilizes ML/NLP to generate wordlists for password cracking.
- Word2Vec used to generate a list of similar words/phrases based on an input wordlist.
- Easily generates large targeted wordlists based on user-defined keywords.

### [AutoWebscan](https://github.com/morgenm/auto_webscan)
- Alternative to AutoRecon that scans web services with HTTP proxies support.
- HTTP proxy support allows Burp/ZAP usage when performing discovery scans.
- Additionally allows automated scanning wherever proxies are required.

## Reverse Engineering
### [Defcon 32 Badge Hacks](https://github.com/morgenm/defcon32_badge_hacks)
- Custom firmware modifications for the Defcon 32 badge.
- Added functionality for running Rubber Ducky scripts over USB connection.

### [Malwarebytes 2017 Crackme](https://morgenm.github.io/blog/tag/malwarebytes-crackme/)
- Reverse engineered Malwarebytes 2017 Crackme challenge.
- Writeups of my process and findings on my blog.

## Additional Contributions
### [GoSec](https://github.com/securego/gosec/)
- Developed slice bound checking ([PR](https://github.com/securego/gosec/pull/973)).
- Improved hardoced secret scanning ([PR](https://github.com/securego/gosec/pull/971)).

## Contact
- [LinkedIn](https://www.linkedin.com/in/morgen-malinoski/)
- [Mastodon](https://infosec.exchange/@morgenm)
