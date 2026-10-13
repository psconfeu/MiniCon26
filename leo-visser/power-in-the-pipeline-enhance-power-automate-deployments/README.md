# Power in the Pipeline: Enhance Power Automate deployments

**Speaker(s):** Leo Visser — session on the [MiniCon26](https://synedgy.com/psconfeu-minicon/) agenda.

## Abstract

Are you tired of people not following best practices when creating Power Automate flows? These low-code solutions are treated like code because they are versioned, reviewed, and deployed across environments, so let’s treat them like code in our pipelines with quality checks, tests, and automated documentation.

A pull request after a change triggers an Azure DevOps pipeline that validates the flow’s quality using PowerShell. The pipeline checks common issues like unclear naming, unsafe handling of sensitive values, performance bottlenecks, and unexpected premium connector usage. It then generates a concise solution description plus an AI-assisted changelog as part of the release.

If you want Power Automate flows that stay maintainable, secure, and predictable at scale, join this session and leave with a practical pattern you can apply to your own deployments. Basic familiarity with Power Automate solutions and pipelines helps.

## Resources

Check out these resources for more infomation

- [Repository showing the CI/CD](https://github.com/autosysops/PowerPlatformCICD)
- [Respository showing the module](https://github.com/autosysops/PowerShell_PowerPlatformChecker)