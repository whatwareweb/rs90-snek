# rs90-snek
Snake game in SDL for the RS-90

Forked from https://gist.github.com/cellularmitosis/6e54ea6d0965bff16ac947c19bc06d3c

# build
 - get the latest toolchain from here: https://github.com/OpenDingux/buildroot/actions
 - `git clone` the repo
 - run `` /path/to/rs90-toolchain/bin/mipsel-rs90-linux-musl-gcc snake.c `/path/to/rs90-toolchain/mipsel-rs90-linux-musl/sysroot/usr/bin/sdl-config  --cflags --libs\` ``

# controls
 - D-pad: move the snake
 - A/Start: start new game
 - Select: exit
