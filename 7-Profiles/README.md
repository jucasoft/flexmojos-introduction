#7. Profiles
This project adds to the SWF and SWC project with additional build parameters.

To run the various profiles.

* A release build 

		mvn clean install -P release

* Target specific Flex SDK

		mvn clean install -P flex4.1

* Skip coverage

    	mvn clean install -P no-coverage

* Enable multiple profiles

		mvn clean install -P flex4.1, no-coverage

	
* Alternative flashplayer location for unit tests (automatically enabled whenever that location is valid)	


	

