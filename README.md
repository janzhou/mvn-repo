# Maven Repository by janzhou

## For MAVEN

To use this repositoty, add this to your pom.xml file:

    <repositories>
      <repository>
        <id>janzhou-github-mvn-repo</id>
        <url>https://raw.githubusercontent.com/janzhou/mvn-repo/master</url>
      </repository>
    </repositories>

## For SBT

Or, add this to your ``build.sbt``:

    resolvers += "janzhou-github-mvn-repo" at "https://raw.githubusercontent.com/janzhou/mvn-repo/master"
