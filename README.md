# ✨ Dropwizard Dependency Challenge 🔮


### Setup

- Sign up for FOSSA.
- Review documentation at https://github.com/fossas/fossa-cli

### Integration

- Integrate the FOSSA CLI to your favorite pipeline.
- Run a scan on each of these projects listed in this topic; you may fork them.
  - https://github.com/topics/dropwizard-application
- Review results.
- _Bonus_ :tada:: Add all projects to a release group called "Dropwizard Release".


### Vulnerabilities

- Choose a project with some vulnerabilties.
  - If you need a place to start, `CVE-2019-14892` is raised in one of these projects. :wink:
- How would you resolve the transitive vulnerabilities?
- Run a scan again after resolving some vulnerabilities.

### Compliance Issues

- Choose a project with some compliance issues.
- How would you resolve the compliance issues?
- Run a scan again after resolving any compliance issue.

### Troubleshooting

- How do you list analysis targets?
- How do you get debug logs via the FOSSA CLI?
  - What does the dependency graph look like for one transitive dependency, based on your findings in the debug logs?

### Integration (Part 2)

- If you were to push a project to a specific team in FOSSA, how would you do that?
  - Feel free to copy the project and run another scan with the desired result.
- Vendor in a dependency in the project and scan it by providing a fossa-deps.json file. 
  - https://github.com/fossas/fossa-cli/blob/master/docs/references/files/fossa-deps.md#vendored-dependencies
- Dynamically convert vendored dependencies into a fossa-deps.json.
- Block a pull request if there’s at least one issue in the project.

### Compliance Issues (Part 2)

- Modify any of the existing policies. Explain what you denied, flagged, approved.
- Check the project to see if any of the dependencies were flagged as noncompliant based on the policy that was set for that project.

### Reporting

- Based on the vulnerability report, make a suggestion on how to resolve vulnerabilities going forward.

### API

- Provide a list of denied licenses of one of your policies.
- Write a script that provides the next safe version for any critical vulnerability.
  - https://app.swaggerhub.com/apis-docs/FOSSA1/App/0.3.7#/Vulns/revisionNextSafeVersion

### Improvements

- What parts of FOSSA do you think can be improved?
  - Come prepared with any questions or imrpovements.
    - Bonus points if you present this in a doc or presentation deck!
