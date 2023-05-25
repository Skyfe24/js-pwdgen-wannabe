# GENERARE UNA PASSWORD ASSEMBLANDO RISPOSTE DATE DALL'UTENTE E AGGIUNGENDO " +21 ".
- <OL> CHIEDO ALL'USER 3 COSE attraverso PROMPT:
    <LI> Qual'è il tuo nome? </li>
    <LI> Qual'è il tuo cognome? </li>
    <LI>  Qual'è il tuo colore preferito? </li>
</OL>
-Ognuna di queste risposte diventa una CONST,
le chiamerò userName , userSurname , userFavoritecolor

-Dichiaro anche il numero 21 come CONST e lo chiamerò numberTwentyone

-Creo in HTML uno span id chiamato userPsw

-lo chiamo con document.getElementById('userPsw').innerText =
    e sommo le mie const; quindi userName + userSurname + userFavoritecolor + numberTwentyone

