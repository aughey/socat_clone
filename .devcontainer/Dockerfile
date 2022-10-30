FROM mcr.microsoft.com/devcontainers/dotnet:0-6.0-bullseye

RUN cd /tmp && curl https://download.visualstudio.microsoft.com/download/pr/f5c74056-330b-452b-915e-d98fda75024e/18076ca3b89cd362162bbd0cbf9b2ca5/dotnet-sdk-7.0.100-rc.2.22477.23-linux-x64.tar.gz > dotnet.tar.gz && mkdir -p /root/dotnet && tar zxf dotnet.tar.gz -C /root/dotnet && rm -rf dotnet.tar.gz
RUN echo 'export DOTNET_ROOT=/root/dotnet' >> /root/.bashrc && echo 'export PATH=/root/dotnet:$PATH' >> /root/.bashrc