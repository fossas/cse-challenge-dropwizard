# ✨ Dropwizard Dependency Challenge 🔮


### Setup

- Sign up for FOSSA.
- Ask your FOSSA point of contact to upgrade your account.
- Review documentation at https://github.com/fossas/fossa-cli

### Integration (Part I)

- Run a scan on each of these projects listed in this [topic](https://github.com/topics/dropwizard-application); you may fork them.
  - Choose your favorite pipeline for integration. Here are some: 
    - Jenkins
    - GitHub Actions
    - Azure DevOps
  - If you run into CLI issues, try to troubleshoot it. :muscle:
  - _Bonus_ :tada:: If you were able to resolve integration issues, document it somewhere.
- Review results.
- _Bonus_ :tada:: Add all projects to a release group called "Dropwizard Release".

### Choose either vulnerability exercises or the compliance exercises of this challenge.

<details>
<summary>Compliance </summary>

#### Compliance

- Choose a project with some compliance issues.
- How would you resolve the compliance issues?
- Run a scan again after resolving any compliance issue.
</details>

<details>
<summary>Vulnerabilities </summary>

#### Vulnerabilities

- Choose a project with some vulnerabilties.
  - If you need a place to start, `CVE-2019-14892` is raised in one of these projects. :wink:
- How would you resolve the transitive vulnerabilities?
- Run a scan again after resolving some vulnerabilities.
</details>


### Troubleshooting

- How do you list analysis targets?
- How do you get debug logs via the FOSSA CLI?
  - What does the dependency graph look like for one transitive dependency, based on your findings in the debug logs?


### Integration (Part II)

- If you were to push a project to a specific team in FOSSA, how would you do that?
  - Feel free to copy the project and run another scan with the desired result.
- Vendor in a dependency in the project and scan it by providing a fossa-deps.json file. 
  - https://github.com/fossas/fossa-cli/blob/master/docs/references/files/fossa-deps.md#vendored-dependencies
- Write a script that dynamically converts vendored dependencies into a fossa-deps.json.
- Block a pull request if there’s at least one issue in the project.

### Reporting/Issue Triaging

<details>
<summary>Compliance </summary>

#### Compliance

- Modify any of the existing policies. Explain what you denied, flagged, approved.
- Check the project to see if any of the dependencies were flagged as noncompliant based on the policy that was set for that project.

</details>

<details>
<summary>Vulnerabilities </summary>

#### Vulnerabilities
- Based on the vulnerability report, make a suggestion on how to resolve vulnerabilities going forward.
</details>

### API

<details>
<summary>Compliance </summary>

#### Compliance
- Provide a list of denied licenses of one of your policies. Click [here](https://app.swaggerhub.com/apis-docs/FOSSA1/App/0.3.7#/) for API docs.

</details>

<details>
<summary>Vulnerabilities </summary>

#### Vulnerabilities
- Write a script that provides the next safe version for any critical vulnerability.
  - https://app.swaggerhub.com/apis-docs/FOSSA1/App/0.3.7#/Vulns/revisionNextSafeVersion

</details>


### Improvements

- What parts of FOSSA do you think can be improved?
  - Come prepared with any questions or improvements.
    - Bonus points if you present this in a doc or presentation deck!
