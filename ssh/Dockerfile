FROM docker:latest

RUN apk --no-cache add openssh \
	&& mkdir -p ~/.ssh \
	&& echo -e "Host *\n\tStrictHostKeyChecking no\n\n" > ~/.ssh/config