# sphinx-contrib GitHub Administration

This repository is used for managing the sphinx-contrib GitHub organization, including requesting importing new repositories or granting permissions.

## How do I add a new repo to sphinx-contrib?

1. Create the repository elsewhere, such as under your personal account.
2. File a ticket [here](https://github.com/sphinx-contrib/github-administration/issues) asking to join the organization, including a link to the repository being added.
3. Accept the invitation to join the organization.
4. Use the GitHub UI to move the repository into the organization (you will need administrator/owner rights on the repository to do this). See [the GitHub documentation on repository transfer](https://help.github.com/en/github/administering-a-repository/transferring-a-repository) for details.
5. After it is moved, rename the repository to remove prefixes like `sphinx`, `sphinx-contrib`, and `sphinxcontrib`. Don't forget to update the documentation in the repository, too!

## How do I add a project to the sphinx-contrib PyPI organization?

In addition to adding the project on the `sphinx-contrib` GitHub organization, you may also wish to add it to the [`sphinx-contrib` PyPI organization](https://pypi.org/org/sphinx-contrib/).
This is optional, and the main advantage is that it allows for the appointment of new maintainers should you no longer wish to be involved in the project/not be available.

> [!NOTE]
> We will not add new maintainers to a project without attempting to reach out to the original maintainers via all available methods.

1. Ask to be invited to the organization, either when transferring project(s) or by opening a new issue.
2. Add the `sphinx-contrib` *user* to the project(s) in question. This is a meta account managed by @stephenfin that allows us to actually add a project, in the absence of a transfer request mechanism.

Once these steps are done, you will be added as a member to the `sphinx-contrib` *organization*, and project will be moved to this organization.
