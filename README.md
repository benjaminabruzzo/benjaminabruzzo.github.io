# benjaminabruzzo.github.io

mkdir -p ~/webpages && cd ~/webpages

git clone git@github.com:benjaminabruzzo/benjaminabruzzo.github.io.git

cd benjaminabruzzo.github.io

git remote rm origin && git remote add gh git@github.com:benjaminabruzzo/benjaminabruzzo.github.io.git

echo "Hello World" > index.html && git add --all && git commit -m "Initial commit"

git push -u gh main
