# mvn-repo

To use this repositoty, add this to your pom.xml file:

```
<repositories>
  <repository>
    <id>janzhou-github-mvn-repo</id>
    <url>https://raw.githubusercontent.com/janzhou/mvn-repo/master</url>
  </repository>

  <repository>
    <id>janzhou-bitbucket-mvn-repo</id>
    <url>https://bitbucket.org/janzhou/mvn-repo/raw/master</url>
  </repository>
</repositories>
```

Or, add this to your ``build.sbt``:

```
resolvers += "janzhou-github-mvn-repo" at "https://raw.githubusercontent.com/janzhou/mvn-repo/master"
resolvers += "janzhou-bitbucket-mvn-repo" at "https://bitbucket.org/janzhou/mvn-repo/raw/master"
```
