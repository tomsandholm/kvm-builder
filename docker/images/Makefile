builder:

.PHONY:	amd64 arm64v8 jendock i386 arm32v7

amd64:
	cd amd64 && docker build -t builder-amd64 .

i386:
	cd i386 && docker build -t builder-i386 .

arm64v8:
	cd arm64v8 && docker build -t builder-arm64v8 .

arm32v7:
	cd arm32v7 && docker build -t builder-arm32v7 .

jendock:
	cd jendock && docker build -t custom-jenkins-docker .
