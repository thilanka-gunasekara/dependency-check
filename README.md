# Maven Dependency Check
Maven Dependency Check is very simple stand along java project can automatically detect the project dependencies, query the NVD and give the vulnerability analysis report. For this we need Maven 3.1 or higher.

To execute the OWASP dependency check, just run

```sh
mvn clean install org.owasp:dependency-check-maven:check
```

A report containing a CVE is generated to `target/dependency-check-report.html`

For more: 
[dependency checks for vulnerabilities](https://www.triology.de/en/blog-entries/automatic-checks-for-vulnerabilities-in-java-project-dependencies).
