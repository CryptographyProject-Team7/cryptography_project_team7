# cryptography_project_team7
 Voice assistants are a very convenient feature increasingly being found on most smartphones and other home appliances. But as the companies behind voice assistants admit that our voice commands are being recorded for quality assurance purposes, the personal data of millions of consumers is at risk.  This leaves the possibility of hackers breaking into companies' databases and stealing our personal information, preferences and the structure of our voices which can be forged to sound like us.  Thus to mitigate the potential damage posed by this intrusion, we propose a system which converts the speech commands into text, encrypted using double key RSA, and hashed and salted to be stored anonymously so that the most hackers can get would be random texts of customer preferences. This model can also help to send secure voice messages from one device to another.  Using the speech to text function and the secured encryption and authentication system, voice messages can be used for convenience or for the visually impaired. To implement this model, we use socket connection and the Google Speech to Text API to emulate the voice assistants.  It is then encrypted by a modified RSA encryption system for encrypting the text and the key to decrypt the text. The ciphertext is then hashed with a salt to prevent easy decryption.
