# antrepo
1. Clone the repo
2. Create one file call "build.gradle", it should in the base directory(where the build.xml preset)
3. Content of build.gradle is ant.importBuild 'build.xml'
4. run the the command(gradle war) gradle default task name which is present build.xml(in this case task name is war)
5. In our case the default task is dist and the command should be "gradle dist"
