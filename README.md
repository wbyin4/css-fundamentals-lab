# รวบรวมคําสั่ง git
git clone https://github.com/wbyin4/css-fundamentals-lab.git
git add .
git commit -m  "init project "
git push
git checkout -b feature/main
git add .
git add index.html
git commit -m "create main page"
git checkout -b feature/css
git add .
git commit -m "add basic CSS selectors"
git add .
git commit -m "add box model styles"
git add .
git commit -m "add flexbox layouts"
git checkout main
git merge feature/main
git merge feature/css
git push origin main