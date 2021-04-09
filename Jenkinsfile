

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("798167/jenkinimage1")

        /* Push the container to the custom Registry */
        customImage.push()
    }

