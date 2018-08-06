# Boxes

Collection of useful vagrants lessons for myself.

## Gabi Box

My Vagrant box to quickly instantiate a running local environment of my [Blog](http://amterano.net).
	
### Starting up the Vagrant machine

	vagrant up
	vagrant ssh

### Getting Blog sources and running Hugo

	cd /data &&	git clone https://github.com/leonardossz/blog.git
	hugo serve -b http://192.168.33.10 --bind 0.0.0.0

### Editing

The mounted path `/data` is available to be edited inside the box or from the host machine ready to be edited from your favorite
text editor. From the host machine access http://192.168.33.10:1313 to render the site.
