# dev branch with code
    push code to dev :
        -- create pre-release 
        -- then merge pre release to main :
                                            create docker image and tag it the release tag
                                            push to dockerhub


# argocd :
    install argocd image updater
    wich should detect changes in image from dockerhub
    then pull the latest version

    kubectl exec my-argocd-image-updater-598579b569-27zfd -n  argocd -- argocd-image-updater test mveyone/argocd-release:latest