FROM mattermost/mattermost-team-edition:9.11.3

COPY config/config.json /mattermost/config/config.json

RUN mkdir -p /mattermost/data && chown -R mattermost:mattermost /mattermost

WORKDIR /mattermost

EXPOSE 8065

USER mattermost

CMD ["mattermost"]