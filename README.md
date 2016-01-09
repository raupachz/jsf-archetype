# jsf-archetype
A Maven archetype for creating JSF projects for Apache Tomcat. This archetype
uses latest versions of JSF.

* Apache Tomcat 8 (Servlet API)
* Mojarra 2.2.12 (JSF)
* Weld 2.3 (CDI)

## Installation
This archetype is *not* available in Maven Central. You first need to clone this
Github repository and install the archetype in your local Maven respository.

```
> git clone https://github.com/raupachz/jsf-archetype.git
> cd jsf-edge-archetype.git
> mvn install
```

After installation you can safely remove the `jsf-archetype` directory.
You will no longer need it.

## Usage
To create a project with this archetype, open a Terminal and execute the
[Maven Archetype Plugin](https://maven.apache.org/archetype/maven-archetype-plugin/).

```
> mvn archetype:generate                                \
  -DarchetypeGroupId=me.raupach.maven.archetypes        \
  -DarchetypeArtifactId=jsf-archetype                   \
  -DarchetypeVersion=1                                  \
```
