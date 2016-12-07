# Google Maps med Kotlin
Projektet er lavet ud fra Google Maps Activity templaten.<br>
Husk at få API key fra console.developers.google.com<br>
eller følg det der står i google_maps_api.xml.<br>
---
Hvis man skal finde brugerens lokation, som der er gjort i dette projekt, skal man have permission fra brugeren, som man kan requeste på denne måde:
```kotlin
ActivityCompat.requestPermissions(this,
                arrayOf(android.Manifest.permission.ACCESS_FINE_LOCATION, android.Manifest.permission.ACCESS_COARSE_LOCATION),
                MY_PERMISSIONS_REQUEST)
```
