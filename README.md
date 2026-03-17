##### build the project and publishing to Nexus

To build run `gradle build` which creates a jar under `build/libs/`.

To publish the build run `gradle publish`.

Publishing uses the maven-publish plugin which uses the artifact found under build/libs/my-app-$version"+".jar where the version is defined above in the build.gradle.

        To publish the artifacts you need to set the credentials in gradle.properties of the Nexus repo.(Nexus is running in DigitalOcean)
        

