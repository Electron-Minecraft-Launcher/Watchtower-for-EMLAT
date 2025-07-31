# Watchtower for EML AdminTool

Watchtower is a process for automating Docker container base image updates.

This repository contains the configuration for Watchtower to monitor and update the EML AdminTool Docker container. It embeds Watchtower into a Alpine Linux image, which is lightweight and efficient. It allows to run an entrypoint script before the Watchtower process starts, enabling custom initialization tasks.

Please refer to the [Watchtower documentation](https://containrrr.dev/watchtower/) for more information on how to use and configure Watchtower.