Optional
often we use Optional to avoid NPE;

```
String str = "";
Optional.ofNullable(str).orElse("other value");
```
