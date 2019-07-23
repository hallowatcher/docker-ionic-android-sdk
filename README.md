# Build android apps with docker
docker run --rm -v $(pwd):/ionicapp -p 8100:8100 --network="host" build-ionic ionic cordova build android