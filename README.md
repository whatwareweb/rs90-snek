# rs90-snek
Snake game in SDL for the RS-90

# build
 - get the latest toolchain from here: https://github.com/OpenDingux/buildroot/actions
 - `git clone` the repo
 - run `` /path/to/rs90-toolchain/bin/mipsel-rs90-linux-musl-gcc snake.c `/path/to/rs90-toolchain/mipsel-rs90-linux-musl/sysroot/usr/bin/sdl-config  --cflags --libs\` ``
