1.) Ellenőrizd a telepített NodeJS verziószámát!
`node -v`

2.) Ellenőrizd a telepített npm verziószámát!
`npm -v`

3.) Listázd ki a projekted függőségeit! Csak az első szint kell, a telepített csomagok függőségei nem!
`npm ls --depth=0`

4.) Írasd ki a konzolra az eslint csomag adatait!
`npm view eslint`

5.) Kérdezd le az projekted elavult csomagjait, és ha van találat, frissítsd őket!
`npm outdated` (elavult)
`npm update` (frissítés)
