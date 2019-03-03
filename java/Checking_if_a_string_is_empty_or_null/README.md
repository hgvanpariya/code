# Checking if a string is empty or null


## Required import Statement
```java
import org.apache.commons.lang.StringUtils;
```

## Code to Check Empty String
```java
/* Validating the String if it is empty or not. */
String validateEmptyString = "YOUR STRING";

if(StringUtils.isEmpty(validateEmptyString)){
    System.out.println("String is Empty");
}else{
    System.out.println("String is not Empty");
}
```

## Required Maven Pom Dependency

```xml
<dependency>
    <groupId>commons-lang</groupId>
    <artifactId>commons-lang</artifactId>
    <version>2.6</version>
</dependency>
```


### Example output 
```java
StringUtils.isEmpty(null)      = true
StringUtils.isEmpty("")        = true
StringUtils.isEmpty(" ")       = false
StringUtils.isEmpty("bob")     = false
StringUtils.isEmpty("  bob  ") = false
```
