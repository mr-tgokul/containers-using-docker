FROM alpine
ARG app_dir
RUN echo $(app_dir)
COPY configurationfile.txt ${app_dir}/copiedfile.txt
WORKDIR /
CMD ["sh"]
