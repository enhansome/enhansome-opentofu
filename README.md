# Awesome OpenTofu with stars

> A curated and collaborative list of awesome OpenTofu resources and tools.

[OpenTofu](https://opentofu.org/) allows you to declaratively manage your infrastructure. It's an open-source, community-driven alternative to Terraform.

## Contents <!-- omit in toc -->

* [Official](#official)
* [Community](#community)
* [Features](#features)
* [Tools](#tools)
  * [Environment managers](#environment-managers)
  * [Wrappers](#wrappers)
  * [CI](#ci)
  * [Tests](#tests)
  * [State](#state)
  * [Providers](#providers)
  * [Platforms](#platforms)
  * [Registry](#registry)
  * [Helpers](#helpers)
* [Learning](#learning)
* [Media](#media)
* [Podcasts](#podcasts)

## Official

* [OpenTofu repository](https://github.com/opentofu/opentofu) ⭐ 29,836 | 🐛 325 | 🌐 Go | 📅 2026-08-19 🎉
* [Weekly updates](https://github.com/opentofu/opentofu/discussions/categories/weekly-updates) ⭐ 29,836 | 🐛 325 | 🌐 Go | 📅 2026-08-19
* [Registry](https://github.com/opentofu/registry) ⭐ 406 | 🐛 9 | 🌐 Go | 📅 2026-08-19
* [Registry MCP Server](https://github.com/opentofu/opentofu-mcp-server#opentofu-mcp-server) ⭐ 107 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-15
* [Technical Steering Committee updates](https://github.com/opentofu/org/tree/main/TSC) ⭐ 4 | 🐛 10 | 📅 2026-08-04
* [Fork announcement](https://opentofu.org/announcement)
* [Office hours](https://www.youtube.com/watch?v=aEoMzUza6Ok\&list=PLnVotLM2QsyhCc1_8PA7fbVF-ixt4_XAY)

## Community

*Communication channels, meetups, newsletters, and forums.*

* [OpenTofu GitHub Discussion](https://github.com/orgs/opentofu/discussions)
* [OpenTofu LinkedIn](https://www.linkedin.com/company/opentofuorg/)
* [OpenTofu Slack](https://opentofu.org/slack)
* [OpenTofu Twitter](https://twitter.com/opentofuorg)

## Features

<!--lint disable double-link-->

* [1.10 - Enhanced moved and removed blocks](https://opentofu.org/docs/v1.10/intro/whats-new/#enhanced-moved-and-removed-blocks)
* [1.10 - External key providers](https://opentofu.org/docs/v1.10/intro/whats-new/#external-key-providers)
* [1.10 - OCI registry support](https://opentofu.org/docs/cli/oci_registries/)
* [1.10 - S3 native state locking](https://opentofu.org/docs/v1.10/intro/whats-new/#native-s3-state-locking)
* [1.10 - Target and exclude files](https://opentofu.org/docs/v1.10/intro/whats-new/#target-and-exclude-files)
* [1.9 - Provider iteration with for\_each](https://opentofu.org/docs/v1.9/intro/whats-new/#provider-iteration-for_each)
* [1.9 - The -exclude flag](https://opentofu.org/docs/v1.9/intro/whats-new/#the--exclude-flag)
* [1.8 - Early variable and locals evaluation](https://opentofu.org/docs/v1.8/intro/whats-new/#early-variablelocals-evaluation)
* [1.8 - Override files for OpenTofu (.tofu)](https://opentofu.org/docs/v1.8/intro/whats-new/#override-files-for-opentofu-keeping-compatibility)
* [1.7 - End-to-end encryption for state files](https://opentofu.org/docs/v1.7/intro/whats-new/#state-encryption)
* [1.7 - Loopable import blocks](https://opentofu.org/docs/v1.7/intro/whats-new/#loopable-import-blocks)
* [1.7 - Provider-defined functions](https://opentofu.org/docs/v1.7/intro/whats-new/#provider-defined-functions)
* [1.7 - Removed block](https://opentofu.org/docs/v1.7/intro/whats-new/#removed-block)
* [CanI.TF - Feature parity between Terraform and OpenTofu](https://cani.tf/)

<!--lint enable double-link-->

## Tools

### Environment managers

* [arkade](https://github.com/alexellis/arkade) ⭐ 4,607 | 🐛 18 | 🌐 Go | 📅 2026-08-16 - CLI and Kubernetes app installer.
* [tenv](https://github.com/tofuutils/tenv) ⭐ 1,430 | 🐛 46 | 🌐 Go | 📅 2026-08-18 - Terraform and OpenTofu version manager written in Go.
* [tofuenv](https://github.com/tofuutils/tofuenv) ⭐ 235 | 🐛 21 | 🌐 Shell | 📅 2026-02-10 - OpenTofu version manager inspired by tfenv.
* [asdf-opentofu](https://github.com/virtualroot/asdf-opentofu) ⭐ 31 | 🐛 3 | 🌐 Shell | 📅 2026-06-23 - OpenTofu plugin for asdf version manager.
* [tfswitcher](https://github.com/ASleepyCat/tfswitcher) ⭐ 4 | 🐛 5 | 🌐 Rust | 📅 2025-05-26 - Terraform and OpenTofu version switcher written in Rust.

### Wrappers

*Simplify your OpenTofu workflows with a thin wrapper.*

* [Terragrunt](https://github.com/gruntwork-io/terragrunt) ⭐ 9,785 | 🐛 217 | 🌐 Go | 📅 2026-08-19 - Keep your configurations DRY, work with multiple modules, and manage remote state.
* [Terramate](https://github.com/terramate-io/terramate) ⭐ 3,623 | 🐛 104 | 🌐 Go | 📅 2026-08-18 - Automation, orchestration, and code generation for OpenTofu, Terraform, Kubernetes, and others.
* [Atmos](https://github.com/cloudposse/atmos) ⭐ 1,355 | 🐛 293 | 🌐 Go | 📅 2026-08-19 - Orchestration tool that keeps environment configuration DRY.
* [pug](https://github.com/leg100/pug) ⭐ 693 | 🐛 21 | 🌐 Go | 📅 2026-01-02 - A terminal user interface for power users.
* [tfwrapper](https://github.com/claranet/tfwrapper) ⭐ 155 | 🐛 9 | 🌐 Python | 📅 2026-08-16 - Python wrapper that simplifies OpenTofu usage and enforces best practices.
* [tf](https://github.com/dex4er/tf) ⭐ 89 | 🐛 9 | 🌐 Go | 📅 2026-08-19 - Less verbose and more friendly command outputs.
* [easy\_infra](https://github.com/SeisoLLC/easy_infra) ⭐ 78 | 🐛 6 | 🌐 Python | 📅 2026-08-17 - Docker container to simplify and secure the use of infrastructure as code.
* [tfam](https://github.com/Ant0wan/tfam) ⭐ 25 | 🐛 0 | 🌐 Rust | 📅 2025-03-06 - Rust-powered wrapper for concurrent Terraform/OpenTofu apply, enabling multi-deployment support.
* [tfexe](https://github.com/Ant0wan/tfexe) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-11-03 - Rust-powered wrapper for seamless execution of tfswitch and Terraform/OpenTofu with version control.

### CI

* [tofu-controller](https://github.com/flux-iac/tofu-controller) ⭐ 1,684 | 🐛 154 | 🌐 Go | 📅 2026-08-17 - GitOps OpenTofu and Terraform controller for Flux.
* [terraform-github-actions](https://github.com/dflook/terraform-github-actions) ⭐ 980 | 🐛 27 | 🌐 Python | 📅 2026-07-19 - GitHub Actions for OpenTofu.
* [TF-via-PR](https://github.com/OP5dev/TF-via-PR) ⭐ 336 | 🐛 16 | 🌐 TypeScript | 📅 2026-08-13 - GitHub Action to init, plan and apply Terraform/OpenTofu via PR automation.
* [setup-opentofu](https://github.com/opentofu/setup-opentofu) ⭐ 169 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-04 - Set up OpenTofu CLI in your GitHub Actions workflow.
* [pre-commit-opentofu](https://github.com/tofuutils/pre-commit-opentofu) ⭐ 100 | 🐛 4 | 🌐 Shell | 📅 2026-08-02 - Git pre-commit hooks plugin.
* [drifthound](https://github.com/treezio/drifthound) ⭐ 70 | 🐛 16 | 🌐 Ruby | 📅 2026-04-23 - Continuous infrastructure drift detection with historical tracking and notifications.
* [tofUI](https://github.com/65156/tofUI) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - Easily export OpenTofu and Terraform plans in HTML for better readability.
* [Atlantis](https://www.runatlantis.io/) - Automating workflows via pull requests.
* [Burrito](https://docs.burrito.tf/latest/overview/) - A TACoS (Terraform Automation and Collaboration Software) that works inside Kubernetes.

### Tests

* [Terratest](https://github.com/gruntwork-io/terratest) ⭐ 7,942 | 🐛 2 | 🌐 Go | 📅 2026-08-13 - Go library that makes writing automated tests for your infrastructure code easier.

### State

*Analyze and manipulate OpenTofu's state.*

* [tfmigrate](https://github.com/minamijoyo/tfmigrate) ⭐ 1,278 | 🐛 23 | 🌐 Go | 📅 2026-05-04 - State migration tool.
* [tfimport](https://github.com/coolapso/tfimport) ⭐ 50 | 🐛 0 | 🌐 Go | 📅 2026-06-02 - Tool to automate state imports.

### Providers

*Inspect and interact with OpenTofu providers.*

* [tfschema](https://github.com/minamijoyo/tfschema) ⭐ 314 | 🐛 4 | 🌐 Go | 📅 2026-05-04 - Schema inspector for providers.

### Platforms

*Alternatives to Terraform Cloud.*

* [digger](https://github.com/diggerhq/digger) ⭐ 5,023 | 🐛 478 | 🌐 Go | 📅 2026-08-11 - Open-source IaC orchestration tool. Digger allows you to run IaC in your existing CI pipeline.
* [Terrateam](https://github.com/terrateamio/terrateam) ⭐ 1,263 | 🐛 145 | 🌐 OCaml | 📅 2026-08-19 - Open-source alternative to Terraform Cloud/Enterprise. GitOps-first and built for scale, security, and reliability across modern VCS providers.
* [terrakube](https://github.com/AzBuilder/terrakube) ⭐ 946 | 🐛 113 | 🌐 Java | 📅 2026-08-19 - Open-source platform with a private registry, remote state, custom flows, scheduled workspaces, and visual states.
* [tofutf](https://github.com/tofutf/tofutf) ⭐ 84 | 🐛 37 | 🌐 Go | 📅 2024-12-13 - Open-source alternative to Terraform Enterprise with SSO, team management, agents, etc.
* [Stategraph](https://stategraph.com) - State backend that eliminates the state file bottleneck. Teams plan in parallel with resource-level locking, and state is queryable via SQL.
* [Terramantle](https://terramantle.dev) - Free hosted module, state backend and private registry that maps module and provider dependencies and surfaces security, drift, and usage insights across your workspaces.

### Registry

* [citizen](https://github.com/outsideris/citizen) ⭐ 654 | 🐛 44 | 🌐 JavaScript | 📅 2024-10-12 - Private registry for modules and providers with support for multiple databases and storages.
* [terralist](https://github.com/terralist/terralist) ⭐ 513 | 🐛 22 | 🌐 Go | 📅 2026-08-16 - Private registry for providers and modules.
* [terrareg](https://github.com/MatthewJohn/terrareg) ⭐ 347 | 🐛 20 | 🌐 Go | 📅 2026-05-11 - Open-source modules registry with UI, optional Git integration and deep analysis.
* [boring-registry](https://github.com/boring-registry/boring-registry) ⭐ 290 | 🐛 27 | 🌐 Go | 📅 2026-08-14 - An open-source module and provider registry compatible with OpenTofu.
* [tapir](https://github.com/PacoVK/tapir) ⭐ 238 | 🐛 33 | 🌐 Java | 📅 2026-08-14 - Private registry for modules and providers with a UI.
* [terraform-registry](https://github.com/nrkno/terraform-registry) ⭐ 118 | 🐛 17 | 🌐 Go | 📅 2026-08-17 - Modules registry with authentication and support for multiple backends.
* [terustry](https://github.com/veepee-oss/terustry) ⭐ 73 | 🐛 0 | 🌐 Rust | 📅 2024-08-13 - Proxy registry for providers.
* [hermitcrab](https://github.com/seal-io/hermitcrab) ⭐ 50 | 🐛 5 | 🌐 Go | 📅 2025-11-20 - Registry network mirroring service compatible with OpenTofu.
* [petra](https://github.com/devoteamgcloud/petra) ⭐ 44 | 🐛 10 | 🌐 Go | 📅 2024-06-06 - Private registry manager using Google Cloud Storage.
* [terrac](https://github.com/haoliangyu/terrac) ⭐ 34 | 🐛 7 | 🌐 TypeScript | 📅 2026-01-30 - Minimal private module registry compatible with OpenTofu.
* [tofuref](https://github.com/djetelina/tofuref) ⭐ 27 | 🐛 2 | 🌐 Python | 📅 2026-07-23 - TUI for OpenTofu provider registry.
* [library.tf](https://library.tf/) - An indexer of registries for providers and modules with insights and documentation.
* [GitLab Module Registry](https://docs.gitlab.com/ee/user/packages/terraform_module_registry/) - Use GitLab projects as a private registry for Terraform modules.

### Helpers

* [terratag](https://github.com/env0/terratag) ⭐ 1,054 | 🐛 7 | 🌐 Go | 📅 2026-07-03 - CLI tool allowing for tags or labels to be applied across an entire set of OpenTofu/Terraform files.
* [tfupdate](https://github.com/minamijoyo/tfupdate) ⭐ 657 | 🐛 15 | 🌐 Go | 📅 2026-07-15 - Update version constraints in your Terraform / OpenTofu configurations.
* [OpenTofu Language Server](https://github.com/opentofu/tofu-ls) ⭐ 183 | 🐛 13 | 🌐 Go | 📅 2026-07-08 - The OpenTofu Language Server.
* [zed Extension](https://github.com/ashpool37/zed-extension-opentofu) ⭐ 8 | 🐛 3 | 🌐 Tree-sitter Query | 📅 2025-06-27 - Extension for the Zed Editor.
* [VS Code Extension](https://open-vsx.org/extension/OpenTofu/vscode-opentofu) - Extension for Visual Studio Code with the OpenTofu Language Server adds editing features for OpenTofu files such as syntax highlighting, IntelliSense, code navigation, code formatting, module explorer.

## Learning

* [OpenTofu Course](https://killercoda.com/quincycheng/course/course_opentofu) - Interactive tutorials.
* [Terraform in Depth](https://www.manning.com/books/terraform-in-depth) - Book with OpenTofu sections.
* [Infrastructure automation with OpenTofu](https://www.udemy.com/course/infrastructure-automation-with-opentofu-hands-on-devops/?couponCode=1D97F4D8FFE62E296BE1) - Learn infrastructure provisioning with lectures, quizzes, hands-on demos and coding exercises.
* [Migrating From Terraform To OpenTofu](https://www.youtube.com/watch?v=v9rJgtHzxUk) - Introduction to OpenTofu history and how to migrate.
* [Terraform Academy OpenTofu Practitioner Path](https://www.terraformacademy.app/max/labs/opentofu-basics.html) - Interactive browser-based lab covering native state and plan encryption with PBKDF2 and AES-GCM, plus a full practitioner readiness path that reuses HCL fundamentals applicable to OpenTofu 1.6 and later.

## Media

* [OSS EU 2023 - Announcement](https://www.youtube.com/watch?v=Ha77rpusEDM\&t=1190s)
* [OSS EU 2023 - Project Overview](https://www.youtube.com/watch?v=-8sOE9-icmY\&t=15116s)
* [Code To Cloud - Getting Started With OpenTofu](https://www.youtube.com/watch?v=HeUz6TMg82U)
* [CNCF - OpenTofu Day Europe 2024](https://www.youtube.com/playlist?list=PLnVotLM2Qsyiw_6Pd_9WxRRLdrUAs3c1c)
* [CNCF - OpenTofu Day North America 2024](https://www.youtube.com/playlist?list=PLnVotLM2QsyhhCO5TgEUsAip601j3NUlm)
* [CNCF - OpenTofu Day Europe 2025](https://www.youtube.com/playlist?list=PLj6h78yzYM2P1WUOx9Ny6Q3JJxiAs1A3M)
* [CNCF - OpenTofu Day North America 2025](https://www.youtube.com/playlist?list=PLj6h78yzYM2MATqCH0Tux6phUq9o4-lnG)

## Podcasts

<!-- DESC, from most recent to oldest. -->

* [SE Radio: Christian Mesh on OpenTofu](https://se-radio.net/2025/01/se-radio-652-christian-mesh-on-opentofu/)
* [Kubernetes Podcast - OpenTofu, with Ohad Maislish](https://kubernetespodcast.com/episode/232-opentofu/)
* [TheIaCPodcast - Expert Panel on OpenTofu GA Release, Licensing, and OSS Future](https://www.theiacpodcast.com/episode/expert-panel-on-opentofu-ga-release-licensing-and-oss-future)
* [Contributor - Community-Driven IaC](https://www.contributor.fyi/opentofu)
* [Ned in the Cloud - IaC Live Stream](https://www.youtube.com/watch?v=p0vDydkUWB4)
* [Arrested DevOps - What's Up With Open Terraform?](https://www.arresteddevops.com/open-tofu/)
* [OpenObservability - Terraform is no longer open source. Is OpenTF the successor?](https://www.youtube.com/watch?v=5QdUs9VKq5g)
* [TheCloudGambit - The Future of OpenTF](https://www.thecloudgambit.com/2236725/13576531-the-future-of-opentf-with-ohad-maislish)
* [Oxide and Friends - Fork in the road for Terraform?](https://www.youtube.com/watch?v=QaU94LY891M)
* [Changelog -  OpenTF for an open Terraform](https://changelog.com/podcast/556)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
