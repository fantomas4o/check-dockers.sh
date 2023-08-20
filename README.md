# check-dockers.sh

ABOUT TOOL :

This script is written in Bash and serves to check the status of Docker containers and notify via Telegram if there are containers that are not in the 'running' state

Attention!

It is essential to consider that for this script to work, the following steps need to be executed:

You must have a valid token for the Telegram bot and the chat ID where the bot will send messages.

The script should be executable, meaning it must have execution permissions (chmod +x script.sh).

It should be invoked with appropriate execution privileges, allowing it to interact with Docker and read/write files where the results are stored.
