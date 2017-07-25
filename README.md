
# MPD + MPC configuration

## Install packages
apt-get install mpd mpc ncmpcpp

## Copy config files

mkdir ~/.ncmpcpp && cp config ~/.ncmpcpp

cp mpd.conf /etc

## Uncomment/comment needed audio_output config in /etc/mpd.conf

## To use with PulseAudio
cp default.pa /etc/pulse/default.pa
