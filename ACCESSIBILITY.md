# Accessibility

Fajrix aims to make this repository's documentation and community materials
readable, understandable and usable by people with disabilities, including
people using assistive technology.

This statement describes our accessibility priorities, contributor
expectations, current limitations and reporting process. Its scope is this
repository. Fajrix products, websites and other repositories require their
own accessibility assessments.

## Priorities

We use the Web Content Accessibility Guidelines (WCAG) 2.2 Level AA as a
reference for improving our content. This is an improvement target, not
a claim of verified conformance.

Our priorities include:

- Clear language and a logical heading structure.
- Descriptive links that explain their destination or purpose.
- Meaningful alternative text for informative images.
- Text explanations for information conveyed through diagrams and visuals.
- Tables with clear headings.
- Information that can be understood without relying on colour alone.
- Content that supports navigation and understanding with assistive technology.

## Contributor expectations

Contributors should consider accessibility when creating or changing content.

- Keep important information available as text rather than only in images.
- Use headings, lists and tables appropriately.
- Explain specialist terms where readers may need them.
- Provide captions or transcripts when contributing audio or video.
- Review the rendered content and describe relevant accessibility checks
  in the pull request.
- For changes affecting interaction, check keyboard operation and relevant
  assistive technology behaviour, and report any testing limitations.

Run the repository's documentation checks as described in
[the validation instructions](.github/ci/README.md).

These automated checks cover selected Markdown conventions, local links,
image paths and YAML syntax. They do not assess alternative text quality,
screen reader usability or overall accessibility conformance. Manual review
remains necessary.

## Reporting accessibility issues

If you encounter a barrier or need help accessing information, you can:

- Email [info@fajrix.com](mailto:info@fajrix.com).
- Open a correction issue in this repository using the
  **Correction or presentation issue** form.

Please describe the page or file, what you were trying to do, the barrier
encountered and the outcome you expected.

Where useful, include your browser, operating system, assistive technology
or input method. Screenshots and recordings are optional. You do not need
to disclose a disability or provide medical information.

GitHub issues are public. Do not include confidential or sensitive personal
information. If GitHub's reporting interface is itself a barrier, please
use email.

### How we respond

Repository maintainers review accessibility reports and may ask questions
to understand the affected task and its impact.

Where possible, we will suggest a workaround or an alternative way to access
the information while considering a correction. For reports tracked in
GitHub, we will use the issue to communicate progress and invite feedback
on proposed fixes.

Response and resolution times depend on the barrier's impact, complexity
and available capacity. We do not currently offer fixed response or
resolution deadlines.

## Ownership and maintenance

The repository maintainers are responsible for reviewing accessibility
reports, considering accessibility during changes and maintaining this
statement.

We review the statement when the repository's content, accessibility
practices, reporting routes or ownership materially change. When maintainer
responsibilities change, accessibility responsibilities should be included
in the handover.

## Supported environments

The documentation is intended to be read through GitHub's web interface
or a Markdown reader. Navigation and presentation depend partly on GitHub,
the reader's software and their configuration.

We have not established a verified support matrix across browsers,
operating systems, devices, input methods and assistive technologies.
Specific combinations should not be treated as tested or supported solely
because they can display this repository.

## Known limitations

We have not completed a comprehensive accessibility assessment or user
testing with people with disabilities. Accessibility barriers may remain
unidentified.

Our documentation checks do not evaluate keyboard navigation, screen reader
behaviour, colour contrast, zoom and reflow, or the accessibility of linked
external resources.

We control the repository's content but do not control GitHub's interface
or external websites. Please still report barriers that prevent you from
accessing our materials so we can consider content changes or alternative
ways to provide the information.

## Feedback and improvements

Suggestions to improve this statement or our accessibility practices are
welcome through an issue, a pull request or
[info@fajrix.com](mailto:info@fajrix.com).

For a barrier currently preventing you from completing a task, use the
reporting process above and explain its impact.

Last reviewed: 20 October 2026.
