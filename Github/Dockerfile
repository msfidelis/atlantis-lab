FROM runatlantis/atlantis:latest

ENV AWS_ACCESS_KEY=
ENV AWS_SECRET_ACCESS_KEY=

ENV URL="https://ef53de31.ngrok.io"
ENV USERNAME="msfidelis"
ENV GITHUB_TOKEN=""
ENV WEBHOOK_SECRET="eaemainkkkk"
ENV REPO_WHITELIST="*"


ADD repos.yaml /tmp/repos.yaml

EXPOSE 4141

CMD ["server", "--repo-config", "/tmp/repos.yaml", "--atlantis-url", "\https://1373b517.ngrok.io\", "--gh-user", "", "--gh-token", "", "--gh-webhook-secret", "", "--repo-whitelist", "*"]