FROM wordpress:latest

RUN echo "file_uploads = On\n" \
         "memory_limit = 512M\n" \
         "upload_max_filesize = 64M\n" \
         "post_max_size = 64M\n" \
         "max_execution_time = 60\n" \
         > /usr/local/etc/php/conf.d/uploads.ini
