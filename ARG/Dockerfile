ARG VERSION
FROM almalinux:${VERSION:-9}

ARG Course="docker" \
    Trainer="sivakumar" \
    Author="info@joindevops.com" \
    Duration="120"
ENV Course=${Course}
RUN echo "Course: ${Course}, Trainer: ${Trainer}, Author: ${Trainer} Duration: ${Duration}"    
CMD ["sleep", "1000"]