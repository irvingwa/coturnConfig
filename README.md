# coturnConfig (https://github.com/coturn/coturn)

turnserver -v --fingerprint --user=irving:test --lt-cred-mech --realm=irving.com --external-ip=IP1 --simple-log

turnadmin -k -u irving -p test -r irving.com


# jitsi meet (https://github.com/jitsi/docker-jitsi-meet)
In .env file

JVB_STUN_SERVERS=IP1:3478

