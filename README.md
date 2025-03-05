
# Awesome Self-Hosted UX Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome **free as in freedom** (libre/open source) and **self-hosted** software for **User Experience (UX)** professionals and teams.

> **"Free as in freedom"** means the software respects the user's freedom, as defined by the Free Software Foundation.  This generally implies the software is licensed under an OSI-approved license like GPL, MIT, Apache, etc.
>
> **"Self-hosted"** means you can install and run the software on your own servers or infrastructure, giving you control over your data, workflows, and user insights.
>
> **"User Experience (UX)"** encompasses all aspects of the end-user's interaction with a company, its services, and its products. This list focuses on software tools that aid in the UX design process, research, testing, and optimization.

This list aims to provide UX designers, researchers, and teams with a collection of powerful, open-source, and self-hosted tools to enhance their workflows and create better user experiences. It covers various stages of the UX process, from prototyping and user testing to analytics and design systems.

**Table of Contents**

- [Prototyping & Wireframing](#prototyping--wireframing)
- [User Testing & Feedback Platforms](#user-testing--feedback-platforms)
- [Usability Testing Tools (Supporting Aspects)](#usability-testing-tools-supporting-aspects)
- [Design Systems & Component Libraries (Self-Hosted Elements)](#design-systems--component-libraries-self-hosted-elements)
- [UX-Focused Analytics](#ux-focused-analytics)
- [Collaboration & Design Workflow](#collaboration--design-workflow)
- [Form Builders & Survey Tools (for User Research)](#form-builders--survey-tools-for-user-research)
- [A/B Testing & Experimentation Frameworks](#ab-testing--experimentation-frameworks)
- [Accessibility Testing Tools (Self-Hosted Components)](#accessibility-testing-tools-self-hosted-components)
- [User Session Recording & Heatmaps](#user-session-recording--heatmaps)
- [Important Considerations](#important-considerations)
- [Contributing](#contributing)
- [License](#license)

---

## Prototyping & Wireframing

* **Penpot** - A web-based, open-source design and prototyping platform for teams. Offers collaborative design features, vector editing, prototyping capabilities, and is focused on open web standards (SVG).
    * **License:** [MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/)
    * **Website:** [https://penpot.app/](https://penpot.app/)
    * **Source Code:** [GitHub](https://github.com/penpot/penpot)
    * **Notes:**  A strong, actively developed, and feature-rich open-source alternative to Figma and similar design tools. Excellent for UX prototyping and collaborative design.
* **WireframeSketcher (Source Available - Requires License for Full Use)** - While WireframeSketcher itself is not fully "free as in freedom" in its fully compiled form, the source code is available, and it is a desktop application focused on rapid wireframing and prototyping.  Included as a *source-available* option in the UX prototyping space. *License required for compiled versions for continued use beyond trial.*
    * **License:** Source-available, Commercial License for Compiled Version
    * **Website:** [https://wireframesketcher.com/](https://wireframesketcher.com/)
    * **Source Code:** [Available upon request (check website)](https://wireframesketcher.com/source-code-access.html)
    * **Notes:**  Desktop-based tool focused on wireframing.  *License is not fully FOSS, be aware of the licensing terms.*

## User Testing & Feedback Platforms

*(Note: Truly comprehensive, fully self-hosted, open-source platforms that replicate all features of commercial user testing platforms are currently rare.  This section focuses on tools that support aspects of user testing or provide feedback mechanisms.)*

* **LimeSurvey** - Powerful open-source survey tool. Excellent for creating detailed user surveys, questionnaires, and gathering quantitative and qualitative user feedback on designs and prototypes.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [https://www.limesurvey.org/](https://www.limesurvey.org/)
    * **Source Code:** [GitHub](https://github.com/LimeSurvey/LimeSurvey)
    * **Notes:**  Versatile for various types of user research surveys. Can be used for usability testing questionnaires, post-test surveys, and general user feedback collection.
* **Fider** - Open-source customer feedback platform for feature requests and ideas. Allows users to submit and vote, providing insights into user needs and priorities, which is valuable for UX research.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://fider.io/](https://fider.io/)
    * **Source Code:** [GitHub](https://github.com/getfider/fider)
    * **Notes:**  Good for gathering user-driven feedback and understanding user priorities for product development and UX improvements.
* **OhMyForm** - Open-source form builder. Simple and easy to use for creating quick feedback forms, user feedback submission forms, and embedding forms within prototypes or websites for user input.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://ohmyform.com/](https://ohmyform.com/)
    * **Source Code:** [GitHub](https://github.com/ohmyform/ohmyform)
    * **Notes:** Lightweight and convenient for embedding feedback mechanisms directly into UX deliverables.
* **Nextcloud Forms** (Nextcloud App) - Forms app for Nextcloud. If using Nextcloud, provides a way to create and manage user feedback forms and surveys within your existing platform.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website & Source Code:** [Nextcloud App Store](https://apps.nextcloud.com/apps/forms) (Source code within the Nextcloud ecosystem)
    * **Notes:**  Integrates well with Nextcloud for teams already using the platform for collaboration and data management.

## Usability Testing Tools (Supporting Aspects)

*(This section lists tools that can support aspects of usability testing, but may not be full-fledged usability testing platforms.  Full self-hosted platforms are very rare in FOSS.)*

* **Open Broadcaster Software (OBS Studio)** - Open-source software for video recording and live streaming. Can be used to record usability testing sessions (screen recording, webcam, audio) for analysis and documentation.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [https://obsproject.com/](https://obsproject.com/)
    * **Source Code:** [GitHub](https://github.com/obsproject/obs-studio)
    * **Notes:**  Excellent for recording user interactions during usability tests. Requires manual setup and analysis of recordings.
* **Jitsi Meet** - Open-source video conferencing platform. Can be self-hosted to conduct remote usability testing sessions, allowing for screen sharing and observation of users interacting with designs.
    * **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
    * **Website:** [https://jitsi.org/meet/](https://jitsi.org/meet/)
    * **Source Code:** [GitHub](https://github.com/jitsi/jitsi-meet)
    * **Notes:**  Enables remote usability testing. Requires setup of a Jitsi Meet instance.

## Design Systems & Component Libraries (Self-Hosted Elements)

*(While design systems are often broader than software, these tools help manage and document design system components and can be self-hosted.)*

* **Storybook** - Open-source tool for developing UI components in isolation. Allows you to create, document, and showcase UI components (buttons, forms, etc.) for a design system, enhancing consistency and reusability in UX design.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://storybook.js.org/](https://storybook.js.org/)
    * **Source Code:** [GitHub](https://github.com/storybookjs/storybook)
    * **Notes:**  Essential for building and maintaining component libraries for design systems. Self-hosting ensures control over documentation and component showcase.
* **Styleguidist** - Isolated React component development environment with living style guide documentation. Similar to Storybook, but specifically for React components.
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [https://react-styleguidist.js.org/](https://react-styleguidist.js.org/)
    * **Source Code:** [GitHub](https://github.com/styleguidist/react-styleguidist)
    * **Notes:**  React-focused alternative to Storybook for design system component documentation.
* **Zeroheight (Self-Hosted Styleguide - License Required)** - While Zeroheight is primarily a commercial design system documentation platform, they offer a self-hosted styleguide option. *Not fully "free as in freedom," but included as a self-hosted option for design system documentation.* *License required, verify terms.*
    * **License:** Commercial (Self-Hosted Styleguide Available)
    * **Website:** [https://zeroheight.com/](https://zeroheight.com/)
    * **Notes:**  Commercial design system platform with a self-hosted styleguide option. *License is not FOSS, included for self-hosting consideration.* *Verify licensing details.*

## UX-Focused Analytics

* **Matomo (formerly Piwik)** - Leading open-source web analytics platform. Provides detailed website and user behavior analytics, including heatmaps, session recording (plugin), and user flow analysis, which are valuable for understanding user experience.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
    * **Website:** [https://matomo.org/](https://matomo.org/)
    * **Source Code:** [GitHub](https://github.com/matomo-org/matomo)
    * **Notes:**  Highly recommended for privacy-conscious UX analysis. Feature-rich and extensible with plugins for UX-specific analytics.
* **Plausible Analytics** - Lightweight and privacy-focused web analytics. Simpler than Matomo, but provides essential UX metrics like bounce rate, time on page, and user demographics, with a focus on ease of use and privacy.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://plausible.io/](https://plausible.io/)
    * **Source Code:** [GitHub](https://github.com/plausible/analytics)
    * **Notes:**  Good for simple, privacy-friendly UX analytics without the complexity of larger platforms.
* **GoAccess** - Real-time web log analyzer. Provides detailed server log analysis, which can be used for technical UX insights, such as page load times, server errors impacting user experience, and user agent analysis.
    * **License:** [GPLv2](https://www.gnu.org/licenses/gpl-2.0.en.html)
    * **Website:** [http://goaccess.io/](http://goaccess.io/)
    * **Source Code:** [GitHub](https://github.com/allinurl/goaccess)
    * **Notes:**  More technical but provides valuable performance insights that directly affect UX.

## Collaboration & Design Workflow

* **Nextcloud** - Open-source collaboration platform. Can be used for file sharing, project management (with apps), calendar, contacts, and more, supporting collaborative UX design workflows and team communication.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://nextcloud.com/](https://nextcloud.com/)
    * **Source Code:** [GitHub](https://github.com/nextcloud/server)
    * **Notes:**  Versatile platform for UX team collaboration, file management, and workflow organization.
* **Taiga** - Open-source project management platform with a focus on Agile methodologies. Can be used to manage UX design projects, sprints, user stories, and track progress within UX teams.
    * **License:** [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.en.html)
    * **Website:** [https://www.taiga.io/](https://www.taiga.io/)
    * **Source Code:** [GitHub](https://github.com/taigaio/taiga-back)
    * **Notes:**  Good for UX teams using Agile or Scrum methodologies. Provides project tracking, task management, and collaboration features.
* **GitLab (Self-Hosted)** -  Comprehensive platform for software development lifecycle, including version control (Git), issue tracking, project management, and CI/CD. UX designers can use Git for version controlling design files, collaborating on projects, and integrating with development workflows. *Community Edition is open-source.*
    * **License:** [MIT License](https://opensource.org/licenses/MIT) (for Community Edition)
    * **Website:** [https://about.gitlab.com/](https://about.gitlab.com/)
    * **Source Code:** [GitLab Repository](https://gitlab.com/gitlab-org/gitlab)
    * **Notes:**  Powerful platform for design version control, collaboration, and integration into development processes. *Use the Community Edition for open-source self-hosting.*

## Form Builders & Survey Tools (for User Research)

*(These are re-listed from the "User Testing & Feedback" section as they are specifically valuable for user research within UX.)*

* **LimeSurvey** - (See description in User Testing & Feedback Platforms)
* **OhMyForm** - (See description in User Testing & Feedback Platforms)
* **Nextcloud Forms** (Nextcloud App) - (See description in User Testing & Feedback Platforms)

## A/B Testing & Experimentation Frameworks

*(These tools provide frameworks for implementing A/B testing, but require integration into your website or application code.)*

* **GrowthBook (License: Apache 2.0 - Source Available, Self-Hostable)** - Feature flagging and A/B testing platform.  Offers self-hosting and source availability, allowing you to implement A/B tests to optimize UX and measure the impact of design changes. *License needs verification for strict "FOSS" definition.*
    * **License:** [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) (Source Available)
    * **Website:** [https://www.growthbook.io/](https://www.growthbook.io/)
    * **Source Code:** [GitHub](https://github.com/growthbook/growthbook)
    * **Notes:**  Self-hostable A/B testing and feature flag platform. *License needs verification for strict "free as in freedom" definition.*
* **Flagsmith (License: BSD 3-Clause, Self-Hostable)** - Feature flags platform that can also be used for A/B testing. Open-source and self-hostable, allowing you to control feature rollouts and run experiments to optimize UX.
    * **License:** [BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)
    * **Website:** [https://flagsmith.com/](https://flagsmith.com/)
    * **Source Code:** [GitHub](https://github.com/Flagsmith/flagsmith)
    * **Notes:** Open-source feature flag and A/B testing platform. Self-hosting provides control over experimentation data.

## Accessibility Testing Tools (Self-Hosted Components)

*(Fully self-hosted, comprehensive accessibility testing platforms are rare. This section includes components and tools that can be integrated into UX workflows for accessibility testing.)*

* **Axe-core (JavaScript Library - Integrate into Testing)** -  Popular open-source accessibility testing engine for web.  While not a standalone application, Axe-core can be integrated into browser-based testing tools, CI/CD pipelines, and custom UX testing setups to automate accessibility checks.
    * **License:** [MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/)
    * **Website:** [https://www.deque.com/axe/core/](https://www.deque.com/axe/core/)
    * **Source Code:** [GitHub](https://github.com/dequelabs/axe-core)
    * **Notes:**  Fundamental library for automated accessibility testing. Requires integration into testing workflows or custom tools.
* **Pa11y Dashboard (Self-Hosted Dashboard for Pa11y CI)** - Pa11y is a command-line accessibility testing tool. Pa11y Dashboard provides a self-hosted web dashboard to visualize and manage accessibility test results from Pa11y CI (continuous integration).
    * **License:** [MIT License](https://opensource.org/licenses/MIT)
    * **Website:** [http://pa11y.org/dashboard/](http://pa11y.org/dashboard/)
    * **Source Code:** [GitHub](https://github.com/pa11y/pa11y-dashboard)
    * **Notes:**  Provides a visual dashboard for managing accessibility testing results from Pa11y CI. Requires using Pa11y CI for testing.

## User Session Recording & Heatmaps

* **Matomo (formerly Piwik - Session Recording Plugin)** - Matomo's Session Recording plugin (available in Matomo Marketplace) allows you to record user sessions and generate heatmaps of user interactions on your website, providing direct visual insights into user behavior and UX issues.
    * **License:** [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) (Plugin inherits Matomo's license)
    * **Website:** [https://matomo.org/](https://matomo.org/) (Plugin in Matomo Marketplace)
    * **Source Code:** [GitHub (Matomo core - plugin code within Matomo)](https://github.com/matomo-org/matomo)
    * **Notes:**  Integrated session recording and heatmaps within a privacy-focused analytics platform. Requires installing the Session Recording plugin in Matomo.

---

## Important Considerations

When choosing and using self-hosted UX software, consider these points:

* **Define Your UX Tool Needs:** Clearly identify the specific UX processes and workflows you want to support with software.
* **Technical Skills & Setup:** Self-hosting requires technical expertise to install, configure, and maintain software. Assess your team's technical capabilities.
* **Integration with Existing Workflows:** Ensure the chosen tools integrate well with your existing design, development, and research workflows.
* **Data Privacy & Security:**  Self-hosting gives you control over data, but also responsibility for data privacy and security. Implement appropriate security measures.
* **Community Support & Documentation:**  Active communities and good documentation are essential for self-hosted open-source software, especially for troubleshooting and learning.
* **Realism for Advanced UX Tools:**  Fully featured, self-hosted, open-source alternatives to *all* commercial UX tools may not exist. Be realistic about the capabilities and focus on tools that address your core needs.

## Contributing

Contributions are welcome! If you know of other awesome free/open-source self-hosted software that is valuable for User Experience (UX) and should be on this list, please submit a pull request.

**To contribute:**

1. Fork this repository.
2. Add your software to the appropriate category in the `README.md` file, following the existing format. Please ensure:
    * The software is truly **free as in freedom** (open-source with an OSI-approved license).
    * The software is designed for **self-hosting**.
    * The software is relevant to **User Experience (UX)** practices.
    * Provide a concise and informative description, highlighting its UX benefits.
    * Include links to the official website and source code repository (if applicable).
3. Submit a pull request with your changes.

Please ensure your submissions are relevant, high-quality, and properly formatted. Duplicate entries or software that doesn't meet the criteria may be rejected.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, jaimepaezv has waived all copyright and related or neighboring rights to this work.

---
*This list is a community effort and is provided for informational purposes only. We are not endorsing or guaranteeing the suitability, quality, or security of any of the listed software. Always do your own research and testing before implementing any of these tools for your user experience (UX) activities.*
