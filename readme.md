## Hapat për Ekzekutim

1. **Siguroni Python**:
   - Sigurohuni që keni të instaluar Python në kompjuterin tuaj.
   - Për të kontrolluar nëse Python është instaluar, përdorni komandën `python --version` ose `python3 --version` në terminal ose konsolë.

2. **Shkarkoni Projektin**:
   - Klononi repositorin ose shkarkoni dosjen që përmban kodin Python.
   - Përdorni komandën e mëposhtme për të klonuar repositorin:

     ```bash
     git clone <URL>
     ```

     Zëvendësoni `<URL>` me adresën e saktë të repositorit GitHub.

3. **Hapni Terminalin dhe Navigoni në Dosje**:
   - Hapni një terminal ose konsolë.
   - Navigoni në dosjen ku është klonuar ose shkarkuar projekti, duke përdorur komandat si `cd <emri_i_dosjes>`.

4. **Ekzekutoni Programin**:
   - Ekzekutoni skedarin Python që përmban kodin e algoritmit me komandën e mëposhtme:

     ```bash
     python <emri_i_skedarit>.py
     ```

     Zëvendësoni `<emri_i_skedarit>` me emrin e saktë të skedarit Python që përmban kodin tuaj.

5. **Futni Çelësin dhe Mesazhin**:
   - Pasi të ekzekutohet programi, ju do të kërkohet të futni çelësin e permutacionit (një sekuencë numrash) dhe tekstin e thjeshtë që dëshironi të enkriptoni.
   - Shtypni çelësin dhe mesazhin në terminal kur të kërkohet.

6. **Shikoni Rezultatet**:
   - Programi do të shfaqë tekstin e enkriptuar në terminal.
   - Për të dekriptuar tekstin e enkriptuar, përdorni të njëjtin çelës dhe programi do të kthejë tekstin e dekriptuar.

## Problemet dhe Përmirësimet

Nëse hasni probleme gjatë ekzekutimit, kontrolloni nëse Python është instaluar saktë dhe nëse komandat janë të shkruara siç duhet. Për sugjerime dhe përmirësime, ju lutemi kontaktoni në [email ose kanal tjetër kontakti].


# Permutation Cipher

Permutation Cipher është një lloj i algoritmit të enkriptimit që përdor një permutacion të shkronjave ose simboleve për të transformuar tekstin e shkrimit të thjeshtë në tekst të koduar. Ky lloj i enkriptimit bazohet në përzierjen ose riorganizimin e karaktereve në një mënyrë të caktuar.

## Si funksionon

1. **Çelësi i Permutacionit**: Në këtë algoritëm, një çelës përdoret për të krijuar një permutacion të karaktereve. Ky çelës është një sekuencë që përcakton mënyrën se si karakteret do të riorganizohen.

2. **Enkriptimi**:
   - Teksti i thjeshtë ndahet në blloqe ose në nivel karakteri.
   - Për secilin bllok ose karakter, zbatohet permutacioni sipas çelësit për të krijuar tekstin e koduar.

3. **Dekriptimi**:
   - Për të deshifruar tekstin e koduar, përdoret permutacioni invers i çelësit.
   - Kjo rikthen blloqet ose karakteret në pozicionet e tyre origjinale për të marrë tekstin e thjeshtë.

