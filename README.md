```bash
NEW_PROJECT_NAME=new_project_name
git clone https://github.com/gustavogp11/ionic-quickstart.git $NEW_PROJECT_NAME
cd $NEW_PROJECT_NAME
rm -rf .git
sed -i "s/ionic-quickstart/${NEW_PROJECT_NAME}/g" $(find . -type f)
```
