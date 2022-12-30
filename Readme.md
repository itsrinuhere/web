PS D:\GITHUB WEB APP\Site> git add .
warning: in the working copy of 'mvnw', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'mvnw.cmd', LF will be replaced by CRLF the next time Git touches it
PS D:\GITHUB WEB APP\Site> git add --chmod=+x --      
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
PS D:\GITHUB WEB APP\Site> git add --chmod=+x -- .
PS D:\GITHUB WEB APP\Site> git commit -m "e"      
[main 5ed554a] e
 28 files changed, 13 insertions(+), 181 deletions(-)
 mode change 100644 => 100755 .classpath
 mode change 100644 => 100755 .gitattributes
 mode change 100644 => 100755 .gitignore
 mode change 100644 => 100755 .mvn/wrapper/MavenWrapperDownloader.java
 mode change 100644 => 100755 .mvn/wrapper/maven-wrapper.jar
 mode change 100644 => 100755 .mvn/wrapper/maven-wrapper.properties
 mode change 100644 => 100755 .project
 delete mode 100644 .settings/.jsdtscope
 delete mode 100644 .settings/org.eclipse.core.resources.prefs
 delete mode 100644 .settings/org.eclipse.jdt.apt.core.prefs
 delete mode 100644 .settings/org.eclipse.jdt.core.prefs
 delete mode 100644 .settings/org.eclipse.m2e.core.prefs
 delete mode 100644 .settings/org.eclipse.wst.common.component
 delete mode 100644 .settings/org.eclipse.wst.common.project.facet.core.xml
 delete mode 100644 .settings/org.eclipse.wst.jsdt.ui.superType.container
 delete mode 100644 .settings/org.eclipse.wst.jsdt.ui.superType.name
 delete mode 100644 .settings/org.eclipse.wst.validation.prefs
 mode change 100644 => 100755 mvnw
 mode change 100644 => 100755 netlify.toml
 mode change 100644 => 100755 pom.xml
 mode change 100644 => 100755 settings.xml
 mode change 100644 => 100755 src/main/webapp/WEB-INF/web.xml
 mode change 100644 => 100755 src/main/webapp/index.jsp
 mode change 100644 => 100755 target/Site.war
 mode change 100644 => 100755 target/Site/WEB-INF/web.xml
 mode change 100644 => 100755 target/Site/index.jsp
 mode change 100644 => 100755 target/maven-archiver/pom.properties
PS D:\GITHUB WEB APP\Site> git push -u origin main
Enumerating objects: 25, done.
Counting objects: 100% (25/25), done.
Delta compression using up to 16 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (13/13), 1.43 KiB | 486.00 KiB/s, done.
Total 13 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To https://github.com/itsrinuhere/web.git
   00722f7..5ed554a  main -> main
branch 'main' set up to track 'origin/main'.
PS D:\GITHUB WEB APP\Site> 