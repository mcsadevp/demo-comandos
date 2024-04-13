touch README.md
mkdir assets
cd assets
cd ..
mv style.css ./assets/css
git add .
git commit -m "Firts commit"
git checkout -b development
git add .
git commit -m "Corrección errores"
git remote add origin https://github.com/mcsadevp/demo-comandos.git
git push origin development
git checkout main
git pull
git push origin main.

 

