#Hello
echo "# test" >> README.md     #fájl létrehozása, az első alkalommal
git init
git add README.md     #staarting changes azaz a változtatások mentése
git commit -m "first commit"     #változtatások jóváhagyása
git branch -M main     #fejlesztési ág átnevezése
git remote add origin https://github.com/kovacszalan/test.git
git push -u origin main     #a fejlesztési ág feltöltése első alkalommal
git remote add origin https://github.com/kovacszalan/test.git
git branch -M main
git push -u origin main     #feltölti az origin nevű távoli repo-ba a commitokat


További terminál parancsok:
git origin main     #a friss repo letöltése
git remote     #aktuális távoli repo hozzáadása
git remote -v     #change, stage commit állatotának létrehozása
git config --global--list     #globális beállítások listázása
cd     #change directory
cd..     #egy mappával feljebb lép
mkdir <directory name>     #make directory
mkdir <directory name>     #remove directory
ls #list     könyvtár listázása
  
