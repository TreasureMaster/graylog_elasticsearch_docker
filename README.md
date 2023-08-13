### Установка пароля GRAYLOG_ROOT_PASSWORD_SHA2

Сейчас сделан для admin:pswd1111
`echo -n "Enter Password: " && head -1 </dev/stdin | tr -d '\n' | sha256sum | cut -d" " -f1`
