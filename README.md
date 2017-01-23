# Maven Repository maintained by Jian Zhou

## Release Channel

### Configure Release Channel for Maven:

```xml
<repositories>
  <repository>
    <id>Jian Zhou Release</id>
    <url>https://raw.githubusercontent.com/janzhou/mvn-repo/release</url>
  </repository>
</repositories>
```

### Configure Release Channel for SBT:

```scala
resolvers += "Jian Zhou Release" at "https://raw.githubusercontent.com/janzhou/mvn-repo/release"
```

## Testing Channel

### Configure Testing Channel for Maven:

```xml
<repositories>
  <repository>
    <id>Jian Zhou Testing</id>
    <url>https://raw.githubusercontent.com/janzhou/mvn-repo/testing</url>
  </repository>
</repositories>
```

### Configure Testing Channel for SBT:

```scala
resolvers += "Jian Zhou Testing" at "https://raw.githubusercontent.com/janzhou/mvn-repo/testing"
```
