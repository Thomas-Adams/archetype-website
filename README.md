# Simple Maven archetype for static website #

## 1. Clone this repository to your local machine ##
## 2. Import as exisiting Maven project into Eclipse ##
## 3. Run `mvn package` from the command line ##
## 4. Afterwards install the archetype into your Maven repository, by executing: ##
<pre>
`mvn install:install-file              	\
   -Dfile=archetype-website-1.0.0.jar 	\
   -DgroupId=cn.interone                \
   -DartifactId=archetype-website       \
   -Dversion=1.0.0                      \
   -Dpackaging=jar                      \
   -DgeneratePom=true`

</pre>

## 5. Now you can use the Maven type also in Spring now.##
