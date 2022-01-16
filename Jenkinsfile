node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'chaminda90') {

        def customImage = docker.build("chaminda90/node-web-app")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
