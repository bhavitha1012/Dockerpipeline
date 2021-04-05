node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', '798167') {

        def customImage = docker.build("bhavitha/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
