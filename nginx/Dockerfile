FROM nginx:1.14-alpine

LABEL maintainer="Andy <andy@qq.com>"

USER root

ENV NGX_DOC_ROOT="/usr/share/nginx/html"

ADD index.html ${NGX_DOC_ROOT}

ADD entrypoint.sh /bin/

CMD ["/usr/sbin/nginx","-g","daemon off;"]

ENTRYPOINT ["/bin/entrypoint.sh"]
