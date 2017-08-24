FROM postgres:9.6.4-alpine

ADD posts_v2.sql /docker-entrypoint-initdb.d/posts_v2.sql

ENTRYPOINT ["docker-entrypoint.sh"]
EXPOSE 5432
CMD ["postgres"]
