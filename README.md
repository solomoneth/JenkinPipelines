### Installing Node and NPM on code server

```bash
# add the NodeSource yum repository to your system:
curl -sL https://rpm.nodesource.com/setup_12.x | sudo bash -

# install node.js 12.x and npm
sudo yum install -y nodejs

# check version of node and npm
node --version
npm --version

# setup a new package
npm init




# initialize git repo
git init

# add remote origin
git remote add origin https://github.com/<your github username>/<repo name>.git

# set global configs
git config --global user.email "email@example.com"
git config --global user.name "myusername"

# add tracked files
git add .

# commit changes
git commit -m "initial commit"

# push to master
# click cancel on code server
git push origin master

Rebase Dev
