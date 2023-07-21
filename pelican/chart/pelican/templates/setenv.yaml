apiVersion: v1
data:
  setenv.sh: |
    export CATALINA_OPTS="$CATALINA_OPTS -Xms8192m"
    export CATALINA_OPTS="$CATALINA_OPTS -Xmx16384m"
    export CATALINA_OPTS="$CATALINA_OPTS -XX:MaxPermSize=256m"

kind: ConfigMap
metadata:
  creationTimestamp: null
  name: {{ .Release.Name }}-setenv-config
