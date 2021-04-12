nodenvm{

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("798167/jenkinsimage1")

        /* Push the container to the custom Registry */
        customImage.push()
    }

}
