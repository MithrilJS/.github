# Security

The Mithril developers deeply value the security of our projects. We encourage all who discover exploits and security vulnerabilities to responsibly disclose them to us upon discovery.

If you discover a security vulnerability, please feel free to reach out privately at <contact@isiahmeadows.com>. We ask that you do not publicly disclose any vulnerability until we release a patch or if 90 days have passed since we received the initial report, whichever comes first. At the time of writing, we do not offer bug bounties, nor are we aware of anyone who offers bug bounties for vulnerabilities in this project.

### Targets

The following projects are considered in-scope:

- https://github.com/MithrilJS/mithril.js/

The following areas are considered in-scope:

- Handling of untrusted user data, such as `input` attributes, text vnodes, keys in keyed fragments, or the URL read by `m.route`

### Excluded submissions

The following submissions are considered out-of-scope, as they are dangerous to assess and/or provide minimal security benefit to the project:

- Findings exploiting a browser vulnerability, operating system vulnerability, hardware vulnerability, or similar. This includes native code execution, browser crashes, and so on
- Findings that only reproduce on platforms other than those we support
- Findings that rely on existing global values to be set or overwritten first
- Findings that rely on physical testing, network manipulation, and/or human manipulation, such as tailgating, distributed denial of service, and social engineering
- Findings in projects and areas not listed above as in-scope in "Targets"
- Global access to internal component data
- Functional, UI, or UX bugs and spelling mistakes outside of executable code
