git clone https://mockii@github.com/mockii/mockii.git

mvn dependency:get -DrepoUrl=http://download.java.net/maven/2/
mvn dependency:tree

Add .idea folder to gitignore
git rm -r --cached .idea