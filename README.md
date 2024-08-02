# lib-parent-project
This project was generated with Java JDK 21 and Spring Boot 3. Configure plugins for sonarqube, jacoco unit test anilizer.

# Project Structure
	- Implementation of common depencences
	- Profile definition
		- generate_jpa_metamodel -> Generate JPA model based on entities defined in the main project
		- default               -> Default profile, which takes properties defined in the resource path and loads the main class defined in the `prop.main.class` property in the properties file
		- dev                   -> Development profile, which takes properties defined in `resources/config_properties/dev/` path and loads the main class defined in the `prop.main.class` property in the properties file
		- prod                  -> Production profile, which takes properties defined in `resources/config_properties/prod/` path and loads the main class defined in the `prop.main.class` property in the properties file