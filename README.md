# Maven Repository Testing

## Configuration for Maven:

```xml
<repositories>
  <repository>
    <id>Jian Zhou Testing</id>
    <url>https://raw.githubusercontent.com/janzhou/mvn-repo/testing</url>
  </repository>
</repositories>
```
## Configuration for SBT:

```scala
resolvers += "Jian Zhou Testing" at "https://raw.githubusercontent.com/janzhou/mvn-repo/testing"
```
