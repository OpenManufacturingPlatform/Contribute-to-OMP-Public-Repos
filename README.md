# How to use this Repository
This repository is dedicated for participants to sign the IPR Agreement that protects OMP public repositories.

> Please note that signing this IPR Agreement doesn't imply [OMP Membership](https://open-manufacturing.org/get-involved/).

# Open Manufacturing Platform (OMP) Contribution Acknowledgement

Contributors to Open Manufacturing Platform (OMP) repositories must agree to the terms of the OMP IP policies.

OMP uses [EasyCLA](https://easycla.lfx.linuxfoundation.org/#/) to ensure that all contributors have signed the appropriate documents. This tool was created and is maintained by the Linux Foundation, and has a number of features designed to support our open source project communities:

* Once a contributor is authorized for one OMP project, the signature is recognized for any other OMP repos that use EasyCLA.
* Contributors may sign as individuals, or their company can sign on their behalf. *(as per company policy)*
* Companies who sign the CLA can authorize employee usernames individually, add an entire email domain, or specify a GitHub organization containing their employees as members.

There is no cost to signing the OMP CLA. Please note that this is different from [OMP Membership](https://open-manufacturing.org). If your organization relies upon our project, [please become a member](https://open-manufacturing.org/get-involved/). Membership dues are an essential source of funding, and we rely upon them to support the OMP ecosystem.

## How to use EasyCLA

### Who signs the documents?

You can sign the OMP CLA as an individual, or your company can sign and authorize you as a contributor. 

The individual workflow is for people who can make CLA commitments on their own behalf (e.g., hobbyists, students, sole proprietors, etc). This workflow is fast and easy, but may not be appropriate for people who are doing work-for-hire. The corporate workflow involves more steps, but allows a company to sign one document one time for all of their contributors.

At a high level, the signature process works like this:

1. Open a PR against a repo covered by EasyCLA (including this one).
1. A bot will check whether your GitHub user is covered by a signed CLA.
1. If you're already covered you will get a green checkmark, and your contribution can be merged.
1. If you're not covered, you'll be prompted through the signature process.

#### High-Level Diagram

The following is a high-level diagram, showing the different flows and roles that EasyCLA supports:

![image](https://user-images.githubusercontent.com/3258579/138139396-311ac7e9-5150-41b6-a520-1968ec9ffeb4.png)

> Note: Click [here](https://docs.linuxfoundation.org/lfx/easycla) to view EasyCLA Documentation.
### Initiating the signature process against a test repo

The easiest way to initiate the process is to open a PR against any covered repo, including this one.

If you simply want to sign the documents in preparation for future contributions, you can open a trivial PR against, e.g. a file in this repository and you will be prompted through the process. PRs against this repo will be closed periodically.

## Sign as an individual

If you are working on your own behalf and can make IP commitments about what you produce, you can sign as an individual contributor. 

1. Open a PR against this [file](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos/edit/main/Raise-a-PR-against-this-file.md) that uses EasyCLA.
1. When blocked by the bot, follow the prompts and choose *Individual*.
1. Fill in the details and sign the DocuSign form.
1. Wait a little while for the check to re-run.

That's all there is to it.

> Note: click in the link for further information on [Individual Contributor](https://docs.linuxfoundation.org/lfx/easycla/v2-current/contributors/individual-contributor)
## Sign as a Company

If you are doing work for someone else (e.g., it's your job), the company might need to sign for you. The advantage here is that they can authorize other employees with a single signature. If your company has already signed the document but you're still blocked, you may just need to request your username be added to the list of authorized contributors. Once this is complete you'll just have to confirm you work for them by clicking through the process one final time.

Here are the steps to have your company sign the CLA.

### If you contribute onbehalf of your company

1. Open a PR e.g., against this [file](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos/edit/main/Raise-a-PR-against-this-file.md) that uses EasyCLA.
1. When blocked by the bot, follow the prompts and choose *Corporate*.
1. Choose your company from the list. If it's not there, add it.
> --- if your company hasn't asigned a CLA Manager yet ---
4. Designate someone with signing authority (generally an officer or attorney, if in doubt ask your manager) to receive the DocuSign. This person is the *CLA Manager*.
5. Follow up with the CLA Manager and ask them to sign the DocuSign form.
6. The CLA Manager can now designate other CLA Managers who are allowed to manage your company's list of authorized contributors.
7. The CLA Manager needs to perform the tasks in the [next section](#when-your-company-has-finished-signing-the-agreement)
> --- end of CLA Manager envolvement ---
8. Once this is done, you'll need to click the *Details* link in the PR (again) and click a button that acknowledges you want to be covered by the company.
9. Wait a little while for the check to re-run.

At this point, your PRs will no longer be blocked by EasyCLA on any OMP repo.

> Note: click in the link for further information on [Corporate Contributor](https://docs.linuxfoundation.org/lfx/easycla/v2-current/contributors/corporate-contributor).

### When your company has finished signing the agreement

> These tasks are performed by the CLA Manager.

1. Once the agreement is signed, any CLA manager can [log into the EasyCLA site](https://easycla.lfx.linuxfoundation.org/#/) *(choose EasyCLA v2 if prompt it)* and either:
    * Add the contributor GitHub username individually to the list of authorized contributors, or
    * Add your corporate email domain, which authorizes anyone who has that email in their GitHub account, or
    * Add a corporate GitHub Organization, where any member of the org is covered by the CLA.

> Note: click in this link to see further information on [Corporate CLA Managers](https://docs.linuxfoundation.org/lfx/easycla/v2-current/corporate-cla-managers).

### Best practices

* Ask the CLA Manager to add the corporate email domain to the list of authorized contributors, or ask them to add your corporate GitHub organization. This is much easier than adding contributors individually.

## Getting help

If your company is in the system but you don't know who your CLA manager is, you can email [info@open-manufacturing.org](mailto:info@open-manufacturing.org).

If you run into issues, you can [open a ticket in JIRA](https://jira.linuxfoundation.org/plugins/servlet/theme/portal/4/create/143).

> Note: click in the link [training video](https://linuxfoundation.org/webinars/lfx-easycla-streamline-your-development-workflow/ ) to see how to use EasyCLA.


Here are the steps to add EasyCLA to your repository.

### 1. Prepare your core contributors

The single most valuable thing you can do prior to adding EasyCLA is to ensure your core contributors have already been authorized. This minimizes the potential for disruption, and can be accomplished by them simply opening a trivial PR against this [repo](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos) and [following the steps](#how-to-use-easycla). (Contributors who have already signed the OMP CLA in EasyCLA for another OMP project do not need to do this.)

You may also want to open an issue letting others know that this will be happening.

### 2. Prepare your GitHub repository

You will need to contact OMP staff member to setup EasyCLA for in your repository. Reach out to [Joaquin Prado](mailto:info@open-manufacturing.org) to coordinate on the details.

### 3. Add instructions to your project

We recommend adding something like the following to your main README and/or CONTRIBUTING files, so that new contributors are not surprised. You may also consider updating your PR template to point to the instructions.

Here is some suggested text you can use:

```
This repository is managed by EasyCLA. Project participants must sign the free [OMP CLA](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos) before making a contribution. You only need to do this one time, and it can be signed by [individual contributors](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos#sign-as-an-individual) or their [employers](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos#have-your-company-sign-for-you).

To initiate the signature process please open a PR against this repo [Contribute-to-OMP-Public-Repos](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos). The EasyCLA bot will block the merge if we still need a CLA from you.

You can find [detailed instructions here](https://github.com/OpenManufacturingPlatform/Contribute-to-OMP-Public-Repos). If you have issues, please email [info@open-manufacturing.org](mailto:info@open-manufacturing.org).

If your company benefits from this project and you would like to provide essential financial support for the systems and people that power our community, please also consider [membership in the Open Manufacturing Platform](https://open-manufacturing.org/get-involved/).
```

### 4. Request that EasyCLA be enabled

When the above steps are completed, please reach out to [Joaquin Prado](mailto:info@open-manufacturing.org) and EasyCLA will be enabled for your repos.

New line by me ...
