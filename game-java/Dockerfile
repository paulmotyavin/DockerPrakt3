FROM openjdk:11

LABEL name="praktGameLastBuild"

COPY . /usr/src/game

WORKDIR /usr/src/game

RUN javac game.java
CMD ["java", "game"]
