nsnode {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("798167/jenkinimage")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
