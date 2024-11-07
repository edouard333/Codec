# Codec
Librairie qui code et décode des informations (pas des codecs vidéos !).

# Comment l'utiliser ?
Utiliser la seule classe [`com.phenix.codec.Base64`](src/main/java/com/phenix/codec/Base64.java).
```java
String data = "...";
// Décoder du base 64.
Base64.decode(data, Base64.GZIP);
...
```

Pour plus d'information, consulter la **[JavaDoc du projet](target/site/apidocs/index.html)**.
