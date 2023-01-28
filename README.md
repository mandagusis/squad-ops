# squad-ops
Hello,
someday I will translate it

## Tasks:
### Step 1:
- Sukurti raportai, kurie saugojami kažkaip duombazėje:
  - Sitrep
  - KonRep
  - SALUTE
  - Medevac 9liner
  - LogRep
- Raportai gali būti atvaizduojami atgal
- Raportai eiliuojami pagal laiką, pirmas -> naujausias
- Prisijungiant į programą, galima suvesti pseudonimą, ir tai atvaizduojama raporte
- Prisijungiant į programą, galima matyti (pasirinktinai) arba savo raportus, arba kitų raportus
- Prisijungiant į programą, tikrinama, ar prisijungė vadovas, ar paprastas reportininkas
  - Paprastas reportininkas mato tik savo
  - Vadovas mato visus raportus, gali rūšiuoti pagal pseudonimą raportus

### Step 2:
- Tik super-vadovas gali sukurti reportininko ar kito vadovo asmenį, su slaptažodžiu.
- Lygmenys: Super-vadovas -> vadovas -> reportininkas
  - Super-vadovas:
    - Gali kurti vadovus bei reportininkus. Gali matyti visus raportus (kaip Step 1 paprastas vadovas)
    - Gali priskirti reportininkus prie vadovų.
    - Gali ištrinti visus duomenis: Paskyras, informaciją, lenteles.
  - Vadovas:
    - Gali sukurti reportininkus, ir matyti tik savo reportininkų informaciją
    - Gali kurti savo raportus, kuriuos matys kiti vadovai ar super-vadovai
  - Reportininkai:
    - Gali kurti savo raportus, gali matyti tik savo raportus

### Step 3:
- Kažkaip prijungiamas Google API.
- Google API automatiškai pasiima GPS duomenis, ir sukuriant raportą, galima matyti, iš kurios vietos yra siųstas raportas
- Papildomai išplėtoti, kad įrašant vietą raportuose, API sugebėtų kažkaip tai ištransliuoti į normalią lokaciją, ir tai matytų
