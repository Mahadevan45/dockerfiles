ARG version
FROM almalinux:${version:-9}
# ENV course="Devops with AWS" \
#     duration="120 hrs"
ARG course="Devops with AWS" \
    duration="120 hrs"
ENV duration=$duration
RUN echo "Course: $course, Duration:$duration, Version: $version"
CMD ["sleep","100"]