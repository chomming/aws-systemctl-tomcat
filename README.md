# service 파일 등록하기
[test.service](https://github.com/chomming/aws-systemctl-tomcat/blob/main/test.service)

# systemctl 등록하기
$ sudo systemctl daemon-reload
</br>
$ sudo systemctl enable /usr/lib/systemd/system/test.service
</br>
$ sudo systemctl start test
