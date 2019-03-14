FROM alpine:3.9

# Set timezone to Asia/Chongqing
RUN apk --update add tzdata \
	&& cp /usr/share/zoneinfo/Asia/Chongqing /etc/localtime \
	&& echo "Asia/Chongqing" > /etc/timezone \
	&& apk del tzdata
