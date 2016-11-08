docker-gerrit
=============

A Docker container for the Gerrit code review system.

    $ docker pull nikolas/gerrit
    $ docker run -P -d -t nikolas/gerrit

Or, if you've cloned this repository, you can build it with `./build`, and
run it with `./run`. For an externally accessible instance, do:

    $ docker run -p 0.0.0.0:8080:8080 -p 127.0.0.1:29418:29418 nikolas/gerrit
