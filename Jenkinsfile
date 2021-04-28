node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'nawelfh') {

        def customImage = docker.build("nawelfh/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
