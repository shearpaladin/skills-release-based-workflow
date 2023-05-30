<header>

<!--
    The step and endstep markers will cause this
    introduction content to be hidden once the
    repository is created off the template
-->

# Create a release based workflow

_Create a release based workflow that is built on the foundations of the GitHub flow._

</header>

<!--Step 5-->

## Step 5: Finalize the release

_Awesome work on the release notes :+1:_

### Finalizing releases

It's important to be aware of the information what will be visible in that release. In the pre-release, the version and commit messages are visible.

![image](https://user-images.githubusercontent.com/13326548/47883578-bdba7780-ddea-11e8-84b8-563e12f02ca6.png)

### Semantic versioning

Semantic versioning is a formal convention for specifying compatibility. It uses a three-part version number: **major version**; **minor version**; and **patch**. Version numbers convey meaning about the underlying code and what has been modified. For example, versioning could be handled as follows:

| Code status                     | Stage         | Rule                                                                   | Example version |
| ------------------------------- | ------------- | ---------------------------------------------------------------------- | --------------- |
| First release                   | New product   | Start with 1.0.0                                                       | 1.0.0           |
| Backward compatible fix         | Patch release | Increment the third digit                                              | 1.0.1           |
| Backward compatible new feature | Minor release | Increment the middle digit and reset the last digit to zero            | 1.1.0           |
| Breaking updates                | Major release | Increment the first digit and reset the middle and last digits to zero | 2.0.0           |

Check out this article on [Semantic versioning](https://semver.org/) to learn more.

### Finalize the release

Now let's change our recently automated release from _draft_ to _latest release_.

### :keyboard: Activity: Finalize release

1. In a separate tab, go to the **Releases** page for this repository.
   - _Tip: To reach this page, click the **Code** tab at the top of your repository. Then, find the navigation bar below the repository description, and click the **Releases** heading link._
1. Click the **Edit** button next to your draft release.
1. Ensure the _Target_ branch is set to `main`.
1. Click **Publish release**.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) • [Review the GitHub status page](https://www.githubstatus.com/)

© 2022 GitHub • [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) • [MIT License](https://gh.io/mit)

</footer>
