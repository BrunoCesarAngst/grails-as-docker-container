# Grails as Docker Container

Para construir o guia, faça o seguinte:

    ./gradlew publishGuide

A documentação gerada deve estar em build/docs/index.html.

Para construir o guia, faça o seguinte:

    ./gradlew publishImage

Para construir o guia, faça o seguinte:

    docker run -p 8080:8080 grails-sample/complete:0.1
