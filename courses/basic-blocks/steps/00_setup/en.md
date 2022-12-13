# Set Up

## Introduction

Before getting your hands dirty and learning more about VTEX IO's Store Framework, you'll need to set up a few basic configurations, such as:

- Installing **Git**;
- Installing **VTEX IO's CLI**;
- **Logging into** a VTEX account;
- Creating a development **workspace**;
- **Linking** your local files to the platform.

Have a look at the step-by-step below for each of these configurations:

## Installing Git

Install Git on your computer by clicking on the link below and selecting your operating system (Windows, MAC or Linux):

[https://git-scm.com/downloads](https://git-scm.com/downloads)

## Installing VTEX IO's CLI

**VTEX IO CLI** is a **command line** tool. It allows you to perform any activity on the platform, such as creating a new development workspace, logging into a VTEX account, developing new apps, or managing already existing ones, etc.

Since it's the VTEX IO's CLI that establishes the communication between the developer and the platform, you'll need it in order to perform all the activities put forward during this and the other courses.

To install VTEX IO's CLI, you must follow the [Installing the VTEX IO CLI](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-install) guideline. 

Once successfully installed, your next step is to _log into_ a VTEX account.

## Logging in

1. Run `vtex login appliancetheme` in your terminal. During this training, we will work on this account.

2. After _logging in_, run `vtex whoami` to confirm the account and workspace in which you find currently are.

Workspaces are nothing other than what the namesake suggests. On VTEX IO, accounts have three main workspace types, namely [master](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-promoting-a-workspace-to-master), [production](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-creating-a-production-workspace), and development.

The next step is to create a development workspace, which will allow you to play with the configurations throughout the course without altering the store's final public version.

## Creating a development workspace

1. Run `vtex use workspace-name`, replacing `workspace-name` with the desired name. Use an unique name for your workspace. It is important that you choose wisely this name, in order to avoid conflicts of more than one developer working on the same workspace.

### Accessing your workspace

After creating the workspace, you'll be able to access it at this link: `https://{workspace}--{account}.myvtex.com`, replacing `{workspace}` and `{account}` with the name of the previously created workspace and account. For example, `https://devworkspace--appliancetheme.myvtex.com` Or you can simply run `vtex browse` which opens an endpoint in a browser window based on the current logged in account, workspace and environment data.

---

After setting up the basic configurations, you're ready to start the course!
