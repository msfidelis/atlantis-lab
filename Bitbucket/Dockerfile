FROM runatlantis/atlantis:latest

ENV AWS_ACCESS_KEY=
ENV AWS_SECRET_ACCESS_KEY=

ENV URL="http://386882c3.ngrok.io"
ENV USERNAME=msfidelis_
ENV TOKEN=
ENV REPO_WHITELIST=*

ADD repos.yaml /tmp/repos.yaml

EXPOSE 4141

CMD ["server", "--atlantis-url", "$URL", "--bitbucket-user", "$USERNAME", "--bitbucket-token", "$TOKEN"]