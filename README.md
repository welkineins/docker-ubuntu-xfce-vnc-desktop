docker-ubuntu-xfce-vnc-desktop
=========================

### From Docker Repository

``
$ docker pull welkineins/ubuntu-xfce-vnc-desktop
``

### Build yourself

``
$ git clone https://github.com/welkineins/docker-ubuntu-xfce-vnc-desktop.git
$ docker build --rm -t welkineins/ubuntu-xfce-vnc-desktop docker-ubuntu-xfce-vnc-desktop
``

### Run

``
$ docker run -i -t -p 5900:5900 welkineins/ubuntu-xfce-vnc-desktop
``

Use vnc viewer to <YOUR IP>:5900


Trobleshooting
==================
You can find logs under /var/log/ in container.

