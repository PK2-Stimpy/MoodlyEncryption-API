# MoodlyEncryption library
This used to be the MoodlyMod encryption lib made by me.

# Usage
````java
MoodlyEncryption moodlyEncryption = new MoodlyEncryption();
moodlyEncryption.init("KEY1234567890KEY"); /* Just in case you want to use custom key(must be 16 length) */

byte[] encryptedBytes = moodlyEncryption.encrypt("Test");
String encryptedString = new String(encryptedBytes);

String decryptedString = moodlyEncryption.decrypt(encryptedBytes);
````

# Credits
PK2_Stimpy#0001 -> Making the code.