FROM hadilotfy/jenkins-ubuntu-slave:v1

#install helm3
RUN curl -fsSL https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 -o get_helm.sh  \    
    && chmod 700 get_helm.sh \    
    && ./get_helm.sh

ENTRYPOINT ["bash"]
CMD ["-c"," service ssh start  ; tail -f /dev/null"]
