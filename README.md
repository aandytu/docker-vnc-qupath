## Build QuPath in a ubuntu-based vnc desktop


Desktop from https://www.github.com/fcwu/docker-ubuntu-vnc-desktop

QuPath available at: https://github.com/qupath/qupath

Build with: docker build --rm -t qupath .

Run with: docker run -p 6080:80 qupath

Access it: http://127.0.0.1:6080

Taken from https://git.embl.de/heriche/docker-vnc-qupath/-/tree/master/


