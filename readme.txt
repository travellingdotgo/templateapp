

./gradlew clean build

templatecom
templateapp


template modify
- - - - - - - - - - - - - - -
Mac OS:
find . -type f -exec sed -i "" 's/templatecom/templatecomreplaced/g' {} \;
find . -type f -exec sed -i "" 's/templateapp/templateappreplaced/g' {} \;

git checkout gradle/
git checkout gradlew






