FROM mcr.microsoft.com/devcontainers/javascript-node:20

ARG DEBIAN_FRONTEND=noninteractive
# ARG USERNAME=vscode
# ARG USER_UID=1001
# ARG USER_GID=$USER_UID

# Create the user
# RUN groupadd --gid $USER_GID $USERNAME \
#     && useradd --uid $USER_UID --gid $USER_GID -m $USERNAME \
#     #
#     # [Optional] Add sudo support. Omit if you don't need to install software after connecting.
#     && apt-get update \
#     && apt-get install -y sudo \
#     && echo $USERNAME ALL=\(root\) NOPASSWD:ALL > /etc/sudoers.d/$USERNAME \
#     && chmod 0440 /etc/sudoers.d/$USERNAME 

RUN git config --global user.name "Louis DeRienzo"
RUN git config --global user.email "DeRienzo_louis@yahoo.com"

# ENV HOME /home/${USERNAME}
ENV SHELL /bin/bash
