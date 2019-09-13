### Author Antony

Easy to use proxy server

scales well. It's not a blocking HTTP proxy, it's event driven and asynchronous, meaning hundreds of people can use simultaneously and it will work well.

### how to run it

```nodejs
    $ ./configure --prefix=/home/pkrumins/installs/nodejs-0.1.92
    $ make
    $ make install

    $ PATH=$PATH:/home/pkrumins/installs/nodejs-0.1.92/bin

    $ node proxy.js
```
### Add site to a blacklist
```nodejs
    $ echo 'example.com' >> blacklist
```