this is minis spring framework!
初始化github项目

* 本地初始化 maven项目
```

mvn archetype:generate -DgroupId=com.minis.spring -DartifactId=minis-spring -Dversion=1.0-SNAPSHOT -DarchetypeArtifactId=maven-archetype-quickstart --settings /Users/kejianwang/.m2/setting_ali.xml 
```

* 新建文件 README.md
```
echo "minis spring" >> README.md
```

* git init
* git add README.md
* git commit -m "first commit"
* git branch -M master
* git remote add git@github.com:EternalNight2020/minis-spring.git
* git push -u origin master