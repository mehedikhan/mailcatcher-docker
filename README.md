# mailcatcher docker image

Dockerfile for [mailcatcher][mailcatcher].

It is a very small image available on [docker hub][dockerhubpage] based on [Alpine Linux][alpinehubpage].

## Usage

Get it:

    docker pull mehedikhan/mailcatcher

Run it:

    docker run -d -p 1080:1080 --name mehedikhan/mailcatcher
    
Then you can send emails from your app and check out the web interface: http://\<your docker host\>:1080/.



  [mailcatcher]: http://mailcatcher.me/ "MailCatcher fake SMTP server with web interface" 
  [dockerhubpage]: https://hub.docker.com/r/tophfr/mailcatcher/ "Mailcatcher docker hub page"
  [alpinehubpage]: https://hub.docker.com/_/alpine/ "A minimal Docker image based on Alpine Linux with a complete package index and only 5 MB in size!"