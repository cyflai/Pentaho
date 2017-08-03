

…or create a new repository on the command line
echo "# Pentaho" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/cyflai/Pentaho.git
git push -u origin master


…or push an existing repository from the command line
git remote add origin https://github.com/cyflai/Pentaho.git
git push -u origin master

wget http://gitlab.hds-cloudconnect.com:8008/pentaho-business-analytics-7.1.0.0-12-x64.bin
