# Codec
Librairie pour coder et décoder des informations (pas des codecs vidéos !).

# Comment l'utiliser ?
Utiliser la classe :
```java
import com.phenix.codec.Base64;
```

Exemple :
```java
import com.phenix.codec.Base64;

void main(String[] args) {
    String data = "...";
    // Décoder du base 64.
    Base64.decode(data, Base64.GZIP);
    // ...
}
```
