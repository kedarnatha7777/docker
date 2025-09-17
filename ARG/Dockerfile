ARG version
FROM almalinux:${version:-9}
ARG course 
ARG trainer 
ARG Duration=600HRS 
ENV Duration=${Duration}
RUN echo "course is ${course}, trainer is ${trainer} & duratuion is ${Duration}"
CMD [ "sleep","300" ]

 # docker build -t  arg:1.1 . --build-arg trainer=kedarnath,course=devo,duration=400hrs