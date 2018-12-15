# sjoin
(unix join wrapper) To also sort before join

## Example
	sjoin -1 2 -2 2 -t$'\t' -o'1.1,2.1,1.2,2.2'  ./example/a ./example/b

## Install
	cd /tmp
	git clone git@github.com:dperezrada/sjoin.git
	cd sjoin
	sudo cp sjoin /usr/local/bin
	sudo chmod +x /usr/local/bin/sjoin

Make sure you have the PATH un your profile

	PATH=$PATH:/usr/local/bin

## TODO:
support -- params

* --check-order
* --nocheck-order
* --header
