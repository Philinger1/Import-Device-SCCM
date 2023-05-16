# Import-Device-SCCM
Small GUI for importing new devices without using SCCM-Console:

![image](https://github.com/Philinger1/Import-Device-SCCM-/assets/96050818/722f87a1-c0a3-493f-9c05-b14d04cc5b87)

Um eine dynamische Installation mit unterschiedlichen Tasksequencen mit unterschiedlichen Collection-Variablen zu ermöglichen wird nicht nur der REchner-name und die MAC-Adresse abgefragt. Sonder auch der Type und die Domain.
Die unterschiedlichen Collection Variablen können dann in der Tasksequenz abgefragt werden und als Bedingung für weiter Installation etc verwendet werden.

Beispiel:

![image](https://github.com/Philinger1/Import-Device-SCCM-/assets/96050818/4f16f0d0-c3ca-4177-b099-bf90ddcdcb77)




Domain wird aus den Collections, die im Ordner "Domain" sind generiert:
![image](https://github.com/Philinger1/Import-Device-SCCM-/assets/96050818/5338eaae-f8ec-4c91-96ce-0ba460c93dcf)

"Type" wird aus dem Collection im Ordner "OSD" generiert:
![image](https://github.com/Philinger1/Import-Device-SCCM-/assets/96050818/762c1336-e2ac-439b-8fb5-0513fd521e4d)
