main:
	rm -rf build && mkdir build
	iced --runtime inline --no-header --output build -c src
	parcel build -d ./build -o module.min.js --no-source-maps ./build/module.js
	iced scripts/build-index.iced

	#git add build/* -f

