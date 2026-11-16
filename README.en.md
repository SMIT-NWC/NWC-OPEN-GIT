
# NWC

### SMIT Web Component Framework

**A Component-Based Framework and Developer Resources for Web UI Development**

NWC is SMIT's web component-based development environment, designed to support consistent user interface development and efficient UI implementation.

![JavaScript](https://img.shields.io/badge/JavaScript-Framework-F7DF1E?logo=javascript&logoColor=black)
![Web Components](https://img.shields.io/badge/Web-Components-2563EB)
![License](https://img.shields.io/badge/License-NWC%20Public%20Source-64748B)

[Usage Guide](#-usage-guide) · [Key Features](#-key-features) · [Getting Started](#-getting-started) · [Main Components](#-main-components) · [Documentation and Examples](#-documentation-and-examples)

---

## ✨ Introduction to NWC

**NWC** is a web component-based framework that provides UI components and development patterns for web application development. It helps maintain a consistent user experience across projects and makes UI structures easier to maintain.

This repository is the **Public repository** for NWC source code, development documentation, and samples released by SMIT. The publicly available materials can be accessed and used by anyone, including individual developers and organizations.

## 📋 Usage Guide

NWC public source code may be freely used by individuals and organizations. Downloading, using, and modifying the source code do not require prior approval or a separate application.

| Category | Permission | Description |
|---|---|---|
| Source Code Access and Download | Permitted | Freely accessible to everyone |
| Clone and GitHub Fork | Permitted | Forking within GitHub is allowed |
| Source Code Modification and Feature Extensions | Permitted | Available to individuals and organizations |
| Personal Learning, Research, and Testing | Permitted | Free to use for these purposes |
| Corporate Internal Systems | Permitted | Development and operation of internal business systems |
| Commercial Project Use | Permitted | Customer projects and service development |
| Project Deliverable Distribution | Permitted | May be provided to the extent necessary for project development, operation, and maintenance |
| Resale of Original or Modified Source Code | Prohibited | Cannot be sold or offered as an independent product |
| Unauthorized Independent Redistribution | Prohibited | Distribution as a separate repository, website, or software product is restricted |
| Removal or Modification of Copyright Notices | Prohibited | Existing copyright, attribution, and license notices must be retained |

**Important Notes**

- Developing and operating commercial services using NWC is permitted.
- Selling the original NWC source code or modified versions as independent products, or redistributing them without authorization, is prohibited.
- GitHub Fork is permitted, but it does not grant independent resale or redistribution rights outside GitHub.
- Project deliverables containing NWC configuration files may be provided to customers or operators to the extent necessary for project development, operation, and maintenance. Copyright and license notices must be retained, and the recipient does not acquire independent rights to resell or redistribute NWC itself.
- Third-party libraries, fonts, images, and packages included in NWC are subject to their respective owners' licenses.

**Ordinary downloading, use, and modification of publicly available NWC source code do not require separate approval or inquiries.**

For detailed rights and obligations, please refer to [LICENSE](./LICENSE).

## 🚀 Key Features

| Area | Description |
|---|---|
| **UI Components** | UI components used in web application development, including inputs, buttons, and grids |
| **Layout & Navigation** | Components supporting screen composition and navigation, including layouts, tabs, MDI, and menus |
| **Data & Input** | Components for user input, selection, data retrieval, and editing |
| **Sample** | Examples demonstrating component usage and business screen implementation patterns |
| **Docs** | Component-specific usage instructions, properties, events, and development references |
| **FAQ** | Frequently asked questions and troubleshooting information |

## ⚡ Getting Started

If you are new to NWC, start by downloading the public source repository and running the provided samples in your project environment.

### 1. Clone or Download the Repository

If you use Git, clone the repository with the following command:

```bash
git clone https://github.com/SMIT-NWC/NWC-OPEN-GIT.git
```

If you do not use Git, you can download the repository by selecting **Code → Download ZIP** on the GitHub repository page.

### 2. Check the Project and Execution Environment

Review the documentation and samples in the downloaded repository, and prepare your project environment according to the instructions provided for each example.

- Check the required files and dependencies for each sample.
- Review the NWC loading and initialization settings in the project.
- Check the supported browsers and execution environment.
- Run the screen according to the execution instructions provided with each sample.

> Required settings and dependencies may vary depending on the project configuration and execution environment. Do not assume or apply package installation or execution commands that are not documented. Always refer to the instructions provided with each sample and its documentation.

### 3. Explore Basic Components

NWC web components can be used in a project environment where NWC has been properly loaded.

```html
<nc-input label="Search"></nc-input>
<nc-button>Search</nc-button>
```

The code above demonstrates a basic component usage pattern. To run it independently, NWC must be loaded, the components must be registered, and the project-specific initialization settings must be configured.

### 4. Next Steps

Explore the documentation and samples in the repository to learn how to use individual components and implement actual application screens.

## 🧩 Main Components

NWC provides various components that can be used to build user interfaces and implement business functionality.

| Category | Component Examples | Main Purpose |
|---|---|---|
| Input & Actions | `nc-input`, `nc-textarea`, `nc-checkbox`, `nc-radio`, `nc-select`, `nc-button` | Data input, selection, and user interactions |
| Data Display | `nc-grid` | List and data presentation |
| Screen Composition | `nc-layout`, `nc-panel`, `nc-card`, `nc-accordion` | Screen areas and content organization |
| Navigation | `nc-tab`, `nc-mdi`, `nc-menu`, `nc-treeview` | Tabs, multiple screens, menus, and tree structures |
| Feedback & Overlay | `nc-dialog`, `nc-tooltip`, `nc-progress`, `nc-gauge` | Notifications, dialogs, and status indicators |

The list above contains examples of major components and is not exhaustive. For detailed properties, events, and usage instructions, please refer to the publicly available development documentation.

## 📚 Documentation and Examples

| Resource | Description |
|---|---|
| **Docs** | Component usage, properties, events, and development guides |
| **Sample** | Examples of screen implementations, including search, forms, calendars, and dashboards |
| **FAQ** | Frequently asked questions and troubleshooting references |
| **Release / Changelog** | Public versions and change history, where available |

The development documentation and samples can help you understand how to use the publicly available NWC source code and apply it to actual projects.

## 🛠️ Development and Improvement Suggestions

If you discover an issue in the public source code or have suggestions for improvement, you may report them through the GitHub repository's Issues feature, if it is enabled.

- When reporting an issue, include reproduction steps, expected behavior, actual behavior, and relevant environment information.
- When suggesting an improvement, clearly describe the reason for the suggestion and the expected behavior.
- Do not include information that should not be made public, such as account details, authentication keys, customer data, or internal source code, in Issues or Pull Requests.
- Submitting a Pull Request does not guarantee acceptance or integration. Review and implementation decisions are made according to the project's management policies.

## 📄 License and Copyright

Copyright (c) [Year] [Copyright-Holding Legal Entity]. All rights reserved.

This repository is subject to the **NWC PUBLIC SOURCE LICENSE**. The license permits the use and modification of NWC public source code while restricting the resale of the source code itself and unauthorized independent redistribution.

This license is not an OSI-approved open source license, such as the MIT License or Apache License.

For detailed terms and conditions, please refer to [LICENSE](./LICENSE). The English version is available at [LICENSE_EN.md](./LICENSE_EN.md).

---

## 💬 Inquiries About Additional Features and Development Tools

If you require additional features, extension modules, separate development tools, or technical support beyond what is provided in the NWC public source, please contact SMIT through its official contact channels.

The following topics are available for inquiries:

- **Additional Components and Feature Extensions:** Inquiries about UI components or features not included in the public source.
- **Development and Management Tools:** Inquiries about separate tools that support screen development, source code management, or development workflows.
- **Corporate Environment Integration and Technical Support:** Inquiries about corporate system integration, implementation environment reviews, and technical support.
- **Custom Development:** Inquiries about feature enhancements or custom development based on business environments and project requirements.

The availability and terms of additional features and tools will be provided separately depending on the inquiry.

**Downloading, using, and modifying publicly available NWC source code do not require separate approval or inquiries.**

Official contact information and detailed inquiry procedures will be provided once confirmed.

<div align="center">

**NWC · Build consistent web experiences**

<sub>Copyright (c) [Year] [Copyright-Holding Legal Entity]. All rights reserved.</sub>

</div>
