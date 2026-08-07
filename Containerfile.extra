# Pre-install Flatpaks system-wide into the container filesystem
RUN flatpak remote-add --system --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo && \
    flatpak install --system -y flathub \
      com.valvesoftware.Steam \
      io.gitlab.librewolf-community \
      org.onlyoffice.desktopeditors \
      com.github.tchx84.Flatseal \
      org.videolan.VLC \
      ca.littlesvr.asunder \
      com.mattjakeman.ExtensionManager