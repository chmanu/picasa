# This docker provide picasa for linux distribution. It avoid to have 32bits libs on his system



# Example of this docker's usage
# Your photos can be linked in the picasaDATA subdirectoy and your database will be stored in picasaBD subdirectory
#
# unix socket is used for X server connection

run -ti --rm        -e DISPLAY=$DISPLAY   -v `pwd`/picasaDATA:/photos -v `pwd`/picasaBD:/home/developer/.wine   -v /tmp/.X11-unix:/tmp/.X11-unix  picasa:3
