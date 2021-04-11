nodenvm{

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("798167/jenkins1image")

        /* Push the container to the custom Registry */
        customImage.push()
    }

}
