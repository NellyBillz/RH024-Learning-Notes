# RH024: Red Hat Enterprise Linux Technical Overview

My study notes and small practice activities for the videos shown in my RH024 course list. These are original summaries by topic, not transcripts or official Red Hat course materials. The public RH024 overview describes a RHEL 10 introduction, while the video titles in my course view include newer subjects such as Bootc and Insights; this repository follows the titles visible in that view.

## How to use this repository

Read one lesson, try its **Practice** section on a Linux machine, and add your own observations under **My results**. Commands that inspect the system are generally safe; commands that change users, permissions, services, packages, or networking should be tried only on a disposable RHEL virtual machine. Do not paste passwords, tokens, private IP addresses, or personal information into commits.

On Windows, use a RHEL virtual machine or remote RHEL host for the RHEL-specific commands. WSL is useful for shell basics, but it does not reproduce every RHEL service and product.

| # | Video | Notes |
|---|---|---|
| 01 | Linux distributions | [Read](lessons/01-linux-distributions.md) |
| 02 | Introduction to the shell | [Read](lessons/02-introduction-to-the-shell.md) |
| 03 | Documentation | [Read](lessons/03-documentation.md) |
| 04 | Command line assistant | [Read](lessons/04-command-line-assistant.md) |
| 05 | Linux directories explained | [Read](lessons/05-linux-directories-explained.md) |
| 06 | Basic file management | [Read](lessons/06-basic-file-management.md) |
| 07 | Editing files with Vim | [Read](lessons/07-editing-files-with-vim.md) |
| 08 | Organizing local users and groups | [Read](lessons/08-organizing-local-users-and-groups.md) |
| 09 | File permissions | [Read](lessons/09-file-permissions.md) |
| 10 | Managing software and updates | [Read](lessons/10-managing-software-and-updates.md) |
| 11 | Managing networking | [Read](lessons/11-managing-networking.md) |
| 12 | Managing system startup services with Systemd | [Read](lessons/12-managing-system-startup-services-with-systemd.md) |
| 13 | Deploying an application runtime to host a simple application | [Read](lessons/13-deploying-an-application-runtime.md) |
| 14 | Using Image Mode with Bootc | [Read](lessons/14-using-image-mode-with-bootc.md) |
| 15 | Insights Image Builder | [Read](lessons/15-insights-image-builder.md) |
| 16 | Insights Vulnerability Management | [Read](lessons/16-insights-vulnerability-management.md) |
| 17 | Managing systems with the RHEL web console | [Read](lessons/17-rhel-web-console.md) |
| 18 | Next steps | [Read](lessons/18-next-steps.md) |

The screenshots show these 18 titles. If the scrollable course list contains additional videos outside those screenshots, add them after checking their exact titles.

## Optional system inspection

Run `bash scripts/inspect-system.sh` on Linux to display OS, shell, identity, network and service information without changing the machine. Review the output before sharing it publicly.

## Sources

- [RH024 course access](https://rhtapps.redhat.com/promo/course/rh024)
- [Red Hat RH024 overview](https://www.redhat.com/en/services/training/rh024-red-hat-linux-technical-overview)
- [RHEL 10 documentation](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/10)

Red Hat, RHEL, and related product names belong to Red Hat. This is a personal learning repository.
