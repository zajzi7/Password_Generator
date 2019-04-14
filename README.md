# Generator Haseł
#### Projekt stworzony pare lat temu w czasie studiów, nie korzystałem wtedy z Github'a i wrzucam tylko plik JAR. Dla dociekliwych kodu pozostaje jedynie dekompilacja(np. Winrar'em i otworzenie w IntelliJ).
#### Co do samego programu działa on w mojej opinii bez zarzutów i w zupełności wystarcza na podstawowe potrzeby.
#### Co do kodu to jestem świadomy z perspektywy czasu, iż nie jest on perfekcyjny i należałoby sporą część aplikacji przepisać na nowo, jednakże nie będę się tym teraz zajmował, gdyż piszę aplikację w Spring, może w przyszłości.
#### Użyto JavaFX, IntelliJ, SceneBuilder
###### W razie problemów z uruchomieniem na JDK11, należy uruchomić na JRE javy 8(lub JDK 12), zmiana w rejestrze na pewno pomoże.
###### HKEY_CLASSES_ROOT\jarfile\shell\open\command
###### "C:\Program Files\Java\jdk-11.0.1\bin\javaw.exe" -jar "%1" %*
###### Zamień na twoją wersję JRE
###### "C:\Program Files\Java\jre1.8.0_191\bin\javaw.exe" -jar "%1" %*
## Przykładowy zrzut ekranu z aplikacji:
![Generator_Hasel](https://user-images.githubusercontent.com/27241538/56096099-10dd3e00-5ee4-11e9-8b8f-db938a589206.png)
