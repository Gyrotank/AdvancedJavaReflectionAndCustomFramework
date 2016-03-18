# AdvancedJavaReflectionAndCustomFramework

Code for upcoming Advanced Java: Reflection and Custom Framework tutorial video.

The project provides an example of custom Spring-like framework capable of parsing XML-configuration file and instantiating 
configured beans. It als provides an example of custom annotation (@Autowiring) used to annotate fields which must be instantiated
automatically with an instance of class implementing the needed interface or inheriting the needed class. It also demonstrates some
basic instruments of Java Reflection API.

This is a Maven project, so in order for it to be imported correctly and with all dependencies resolved, you should copy it unpacked into a folder you want (e.g. a workspace folder) and import it using Import > Maven > Existing Maven Projects, then choode the project's home folder (i.e. the one containing pom.xml).
