# Example of concepts extraction

From statement: 
```
"the reason was because Google had been moving towards the Kotlin as the official language"
```

we extracted the concept `Google Promoted`.

From: 
```
"I moved on from Java to Kotlin because I liked the features that are present in Kotlin and C++, but not in Java, [...] also because of extension functions"
```

we extract `Like features from C++`, and `Like new feature extension functions`.


From: 
```
"even with the Android Studio auto conversion we have to go in and manually fix any errors"
```

we extract `Used auto-converted` and  `problems with conversion`. 


From 
```
"automated conversion is only good for a starting point, you have to do it by hand afterwards to get idiomatic kotlin."
```
we extracted `Used auto-converted` and  `converted code not idiomatic`.

From 
```
"Other reasons are access to modern syntax and language features [...] all of which are still unavailable on some platforms due to constraints with JVM/JDK level supported on the platform."
``` 

we extracted `Avoid Limitation of JVM/JDK`, `Kotlin modern syntax`, and `Kotlin modern features`.