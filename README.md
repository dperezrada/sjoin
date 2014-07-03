# sjoin
(unix join wrapper) To also sort before join

## Example
	sjoin -1 2 -2 2 -t$'\t' -o'1.1,2.1,1.2,2.2'  ./example/a ./example/b

## Install
	git clone git@github.com:dperezrada/sjoin.git
	#create symbolic link
	ln -s <ABPATH>/sjoin /usr/local/bin
	#or copy
	copy sjoin /usr/local/bin

Make sure you have the PATH un your profile

	PATH=$PATH:/usr/local/bin

## TODO:
support -- params

* --check-order
* --nocheck-order
* --header