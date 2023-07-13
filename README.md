# AndroidLibXrayLite

## Build requirements
* JDK
* Android SDK
* Go
* gomobile

## Build instructions
1. `git clone [repo] && cd AndroidLibXrayLite`
2. `gomobile init`
3. `go mod tidy -v`
4. `gomobile bind -v -androidapi 19 -ldflags='-s -w' ./`



# iOS LibXrayLite

1. `git clone [repo] && cd AndroidLibXrayLite`
2. `gomobile init`  // exec once
3. `go mod tidy -v` 
2. `gomobile bind -a -ldflags "-s -w" -tags ios -target=ios -o libv2ray.xcframework ./`
