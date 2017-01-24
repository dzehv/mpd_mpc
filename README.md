apt-get install mpd mpc ncmpcpp
mkdir ~/.ncmpcpp && cp config ~/.ncmpcpp

cp mpd.conf /etc

Uncomment/comment needed audio_output config

# For PulseAudio
cp default.pa /etc/pulse/default.pa
