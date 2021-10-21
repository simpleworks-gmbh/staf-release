# staf-release

This repository **hosts** the artifacts of the **Simpleworks Test Automation Framework** (STAF)

## pom.xml instructions
Add the following to your pom.xml, to get access to this repository

```
<repositories>
    <repository>
        <id>mvn-repo</id>
        <url>https://raw.githubusercontent.com/simpleworks-gmbh/staf-release/BRANCH</url>
        <releases>
            <enabled>true</enabled>
        </releases>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```

BRANCH is the name of the "branch" that contains the "version" one wants to use.