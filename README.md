```
[INFO] Scanning for projects...
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] Building japicmp-bug-20170302 0.1.0
[INFO] ------------------------------------------------------------------------
[INFO]
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ japicmp-bug-20170302 ---
[INFO] Deleting /home/someone/git/com.github/io7m/japicmp-bug-20170302/target
[INFO]
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ japicmp-bug-20170302 ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/japicmp-bug-20170302/src/main/resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ japicmp-bug-20170302 ---
[INFO] No sources to compile
[INFO]
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ japicmp-bug-20170302 ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/japicmp-bug-20170302/src/test/resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ japicmp-bug-20170302 ---
[INFO] No sources to compile
[INFO]
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ japicmp-bug-20170302 ---
[INFO] No tests to run.
[INFO]
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ japicmp-bug-20170302 ---
[WARNING] JAR will be empty - no content was marked for inclusion!
[INFO] Building jar: /home/someone/git/com.github/io7m/japicmp-bug-20170302/target/japicmp-bug-20170302-0.1.0.jar
[INFO]
[INFO] --- japicmp-maven-plugin:0.9.4:cmp (default) @ japicmp-bug-20170302 ---
[INFO] Written file '/home/someone/git/com.github/io7m/japicmp-bug-20170302/target/japicmp/japicmp.diff'.
[INFO] Written file '/home/someone/git/com.github/io7m/japicmp-bug-20170302/target/japicmp/japicmp.xml'.
[INFO] Written file '/home/someone/git/com.github/io7m/japicmp-bug-20170302/target/japicmp/japicmp.html'.
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 2.773 s
[INFO] Finished at: 2017-03-02T15:51:30+00:00
[INFO] Final Memory: 14M/194M
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal com.github.siom79.japicmp:japicmp-maven-plugin:0.9.4:cmp (default) on project japicmp-bug-20170302: Versions of archives indicate no API changes but found API changes. -> [Help 1]
[ERROR]
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR]
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoFailureException
```
