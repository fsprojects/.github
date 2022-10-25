# An F# Community Project Incubation Space

An F# Community Space for incubating open community projects.

The intention of "fsprojects" is to facilitate a co-operative neutral space where open community projects are born, live, thrive and grow to maturity.

This is an incubation space, and so is slightly anarchic: the idea is to "let many flowers bloom" and take a creative attitude to incubation, co-operation, experimentation and maturation. We understand that creativity is also Darwinian: we are equally happy whether a project matures and is used by thousands, or if a project ends up archived.

No copyright is transferred and no rights to code are granted beyond those in the project license. Our expectation is that you are seeking collaboration and co-operation, and that you wish to facilitate other people to contribute to your project. It's more like a joint working space, with some loose shared goals, and if you abandon the project the backup maintainers have some rights to do things to the github project itself.

Current "fsprojects" backup admins are Sergey Tihon and Don Syme.  "fsprojects" is not a part of the F# Software Foundation, however we think of it as as "FSSF-compatible" - we align with the FSSF goals for education and community enablement by running the project space.

## Requesting transfer

To request a project to be added or removed from this F# Community Incubation space, [please add an issue to this repository](https://github.com/fsprojects/FsProjectsAdmin/issues/new).

## Onboarding process 

If you are a member of the "fsprojects" organization you can create repos here and transfer repos in.

After transfer GitHub implicitly redirects accesses to your repo (though not to the old URL of the gh-pages of your repo).  Issues and/or wiki are transferred.

After transfer you will be assigned GitHub “admin” rights on the project and are expected to continue to respond to issues and make new releases.  

Your project will automatically get listed on http://fsprojects.github.io.

Your project *might* be a bit more visible, so you may get more feedback or contributions. Historically this has happened for many projects.

## Policies

* **❤️ Incubation** - The intention of "fsprojects" is to facilitate a co-operative neutral space where projects exist. The expectation is that you are seeking collaboration and co-operation and that you wish to facilitate other people to contribute to your project. This is a happy, creative space. Please help keep it that way. Projects transferred to fsprojects should normally initially be at "incubation" stage. This is not precisely defined, and projects may grow to maturity in this space over many years.

* **❤️ Two maintainers** - Your project should ideally have two people with “maintainer” or “admin” status (besides the backup admins). 

* **❤️ CI** - There's an expectation that projects will have continuous integration support enabled. You may get help with continuous integration and/or cross-platform builds for the repo. This will be via pull requests to your project from backup admins or other people.

* **❤️ Testing, Docs** - There's an expectation that projects will have testing, documentation, getting-started and contributing instructions. If you don't have testing or documentation, don't be surprised if backup admins create issues such as "please add testing" or "please add documentation".

* **A helping hand** - By moving a project into "fsprojects" you give Github "administrator" rights to "fsproject backup admins". The backup admins are not responsible for your project - you remain responsible - their role is to help facilitate a co-operative neutral space where projects exists, including giving the possibility that your project might continue should you abandon it. The backup admins reserve the right to make maintenance and policy commits to your projects, including, but not exclusively, to adjusting license and copyright messages for consistency and accuracy, applying a code of conduct, making adjustments to continuous integration, clarifying build, contribution and release instructions, clarifying documentation, pulling pull requests, unlisting packages, or addressing known security vulnerabilities. The intent in these things is always to be helpful and will where possible be done via PRs. It is strongly preferred that project maintainers look after these things.

* **💔** - If you are the person who initiated the inward transfer of the project, and still have "administrator" rights, you may move the project out of “fsprojects” at any time.

* **🤔 Forking** - Sometimes open source projects developed elsewhere get widely used, and then stagnate, and the original developer no longer maintains the project or even replies. In this situation it's sometimes proposed to fork the project into fsprojects, and copy across all issues, and continue development, perhaps under a different name. This can be done if really, really necessary, but requires there to have been a real effort to engage with the original developer, and there must be a new maintainer to do the transfer and maintain the new repository. The license must permit this kind of derived work, and should not be modified. Any copyright notices must be respected and a copyright notice added to all files. A polite recognition of the origins should be added to the README, and if the original developer desires to re-engage this should be respected and a positive resolution found.

* **Packages** - You may also receive a request to make the [fsprojects](https://www.nuget.org/profiles/fsprojects) nuget account a co-owner on any nuget packages associated with the repo. This is primarily to ensure the project can has the possibility of living on should you abandon it or not longer be able to publish nuget packages.

* **OSS Licences** - Projects in fsprojects should have a recognised [Open Source License](https://opensource.org/licenses#:~:text=Open%20source%20licenses%20are%20licenses,Source%20Initiative's%20license%20review%20process.) 

* **Neutral space** - Projects may support commercial activity outside "fsprojects" (within the project license), but should not be a direct source of revenue nor represent an exclusive commercial advantage.

* **Copyright** - No copyright is transferred, it remains with the relevant contributors. Your project is requested to have accurate copyright notices kept up-to-date.

* **README** - Projects are requested to include a section in the README.md like [this one](https://github.com/fsprojects/FSharp.Compatibility#maintainers). This may get added by backup admins, or please add it yourself.

* **CoC** - Projects should have a Code of Conduct and it is the resposibility of project admins to enforce this. The backup admins reserve the right to apply the [FSSF Code of Conduct](https://foundation.fsharp.org/code_of_conduct) if no Code of Conduct is present and may in the future apply this Code of Conduct to the organization as a whole.

* **2FA** - You must have 2FA enabled to be a member of this organization.

* **Abandoned projects** - Should a project be "abandoned", the backup admins may take certain actions. "Abandoning" means not answering question issues or commenting/pulling/approving pull requests within 30 days, or not answering a contact request from the backup admins via a github issue within 14 days. For abandoned projects, the backup admins may try to recruit a new maintainer, granting Github "Maintainer" rights, normally by asking an issue on the repository, though there is no guarantee they will do this (it is preferable you do it yourself before abandonment!). They may also give permissions to publish nuget packages or other assets, make direct commits to the project, or decide to rename, archive or delete the project.

* **Archiving projects** - The backup admins may decide to archive abandoned projects after 1 year of primary admin absence (no activity in issues and/or commits). When archived, a project is renamed (prefixed by `zzarchive-`) or moved to the "fsprojects-archive" organization, and marked as read-only on GitHub.

* **Eviction** - The backup admins reserve the right to remove a project from "fsprojects" without giving a reason (though this has never happened historically). In this case, an issue will be added to the repository and an outward transfer facilitated should a current maintainer wish that. If the project has not been transferred out within 14 days the project may be archived or deleted.

* **Policy adjustment** - These policies may be adjusted by fsprojects backup admins at any time. Notice will be given via a pull request to this file.

