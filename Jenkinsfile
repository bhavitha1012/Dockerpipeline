node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("798167/dockerimage")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
