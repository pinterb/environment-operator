FROM alpine:3.5
RUN apk update && apk add --no-cache openssl openssh curl bash git libgit2 openssh libcurl
RUN adduser -u 1000 -S oper
ADD _output/bin/environment-operator /environment-operator
CMD ["/environment-operator"]
